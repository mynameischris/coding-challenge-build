# coding-challenge-build
a web application (angular/asp.net) which retrieves activities from boredapi.com, stores them in an ef in-memory database, and displays them in a table

# How to start
## 1. api instructions
The api is stored in the api folder. It was developed in ASP.NET (.NET 5.0). It was published for a win-x64 runtime. Run the executable (WebApplication2.exe) and the server should start at the specified server address (e.g. localhost:5000).

## 2. spa instructions
The spa is stored in the spa folder. It was developed in Angular 11. To view it, you need to be running a server. The easiest way is via Node.js and the http-server package. If you do not have the http-server package, install it via npm.
```
npm install --global http-server
```
To start the server from the command line, navigate to the ui folder and enter
```
http-server
```
The output of the command will tell you the server address/port (e.g. localhost:8080).

# How to use
Please start the api server before starting the spa server, otherwise the spa will not work.

To view the spa, visit the address/port specified by the http-server command. The activities table will be empty to start with as the in-memory database of the api server will be empty.

Click the add button to retrieve an activity from boredapi.com, it should then be displayed in the table. You should be able to add an infinite number of activities.

Click the delete all button to delete all of the activities from the in-memory database of the api server.

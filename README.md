# coding-challenge-build
a web application (angular/asp.net) which retrieves activities from boredapi.com, stores them in an ef in-memory database, and displays them in a table

# spa instructions
The spa is stored in the spa folder. It was developed in Angular 11. To view it, you need to be running a server. The easiest way is via Node.js and the http-server package. If you do not have the http-server package, install it via npm.
```
npm install --global http-server
```
To start the server from the command line, navigate to the ui folder and enter
```
http-server
```
The output of the command will tell you the server address/port (e.g. localhost:8080).

# api instructions
The api is stored in the api folder. It was developed in ASP.NET (.NET 5.0). It was published for a win-x64 runtime. Run the executable (WebApplication2.exe) and the server should start at the specified server address (e.g. localhost:5000).

# Getting Started with Aurelia and ASP.NET Core
Aurelia Core Template

### Setting Up Your Machine

The following steps must be performed once on the target machine:

* Install the .NET SDK from https://www.microsoft.com/net/download/windows
* Install Node.js from https://nodejs.org
* Install Visual Studio Code from https://code.visualstudio.com/ 

###  Restoring The Project Dependencies

Since this demo combines both .NET and Aurelia, you will need to install the dependencies for both the backend and the frontend. Here are the commands you need to run on the console:

* `dotnet restore` - This restores the .NET packages for the ASP.NET part of the application.
* `npm install` - This restores the JavaScript packages that comprise Aurelia along with the related frontend build and development tooling, such as Webpack and TypeScript.

### Starting Up The Application

To run the application, simply execute `dotnet run` on the command line. This will build both the backend and frontend and then start a web server up at `http://localhost:5000` (by default). Simply visit this address using your favorite web browser to see the application running.

## Running This Project Using Visual Studio 2017

If you are on Windows, you have the option to use Visual Studio 2017 for your ASP.NET development. Simply use VS to open the .csproj file provided in this repository. Once you've done that, the IDE will take care of restoring the .NET and NPM dependencies for you.

When your dependencies have finished restoring, press Ctrl+F5 to launch the application in a browser.

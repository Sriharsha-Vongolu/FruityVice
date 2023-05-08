# FruityVice
This project is a Web API application built using .NET Core 6.0 and XUnit with clean architecture.

#Getting Started
To get started with this project, follow these steps:

Clone the repository to your local machine.
Open the solution file in Visual Studio or your preferred IDE.
Build the solution to restore NuGet packages and build the application.
Run the project using your preferred debugging method (e.g. IIS Express, Kestrel).
Use a tool like Postman or Swagger to test the API endpoints.
Project Structure
This project follows the clean architecture principles to keep the application organized and maintainable. The solution is divided into several projects:

Application: This project is the entry point for the application and contains the API controllers. It depends on the Application and Infrastructure projects.
Domain: This project contains the domain entities and interfaces. It is the core of the application and has no dependencies.
Infrastructure: This project contains the implementation of the interfaces defined in the Application project. It depends on the Application and Domain projects.

#Testing
This project uses XUnit as the testing framework. Tests are located in the WebAPI.Tests project, which is a separate project from the application code. The tests cover both the application logic and the API endpoints.

To run the tests, follow these steps:
Open the solution file in Visual Studio or your preferred IDE.
Build the solution to restore NuGet packages and build the application.
Open the Test Explorer window.
Click the "Run All" button to run all the tests.

# Book_store
Bookstore is a demo application for Rhetos development platform. This project can be used as a prototype for new Rhetos apps, regarding its project structure and content.

For the most part, this application is developed by following tutorial articles from official Rhetos Wiki.

The Bookstore application in this demo is a business service (Bookstore.Service) that implements business features and database.

It does not contain front-end implementation. This is typically a part of the N-tier enterprise system where a front-end is developed as a separate application (for example, an Angular web app).
It exposes all business features through REST API. Other web protocols can be included with additional Rhetos plugins packages, or by implementing custom controllers.
Note that this application uses Rhetos v5. For demo application on Rhetos v4, use branch rhetos-4.

Build and initial setup

Initial database setup:

Create an empty test database and enter the database connection string in the machine-specific configuration file src\Bookstore.Service\rhetos-app.local.settings.json. You can find the template for that file in tools\Configs\Templates.
To build the application from source, run .\Build.ps1 and .\Test.ps1 in PowerShell console.

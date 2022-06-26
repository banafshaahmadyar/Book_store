# Book_store
Bookstore is a demo application for Rhetos development platform. This project can be used as a prototype for new Rhetos apps, regarding its project structure and content.

For the most part, this application is developed by following tutorial articles from official Rhetos Wiki.

The Bookstore application in this demo is a business service (Bookstore.Service) that implements business features and database.

It does not contain front-end implementation. This is typically a part of the N-tier enterprise system where a front-end is developed as a separate application (for example, an Angular web app).
It exposes all business features through REST API. Other web protocols can be included with additional Rhetos plugins packages, or by implementing custom controllers.
Note that this application uses Rhetos v5. For demo application on Rhetos v4, use branch rhetos-4.

# Library Management API
    
    Task Description
    
    Your task is to build a Library Management backend API. This API will be utilized by library administrators (Admins) to manage books and by library members (Members) to browse and borrow these books.
    
    The Library Management API will be used by Admins to:
    
    -   Add, update, and delete books.
    -   View which books are borrowed and by whom.
    
    Members will use the API to:
    
    -   Browse available books.
    -   Borrow and return books.
    
    Technical Details
    
    Your backend should serve all kinds of clients (which you do not have to implement) - using a RESTful API.
    
    The following technical requirements are placed on your implementation:
    
    -   Use .NET Core with ASP.NET Core framework.
    -   HTTP responses should follow best practices.
    -   API should communicate with their clients using JSON data structures.
    -   Implement authentication using JSON Web Tokens (JWT).
    -   Resource Permissions:
        -   Admins are not authorized to borrow books.
        -   Members are not authorized to add or remove books.
    -   Data Storage: All data should be stored in a relational database. You can use SQL Server.
    -   Users:
        -   Registrations should be done with email and password.
        -   There should be user roles distinguishing Admins and Members.
    
    You should implement the following functionality:
    
    -   User Registration (Members only).
    -   User Login.
    -   Book data: Books must have a title, author, genre, and availability status. Add, update, delete operations should be performed by the Admins.
    -   Borrow and Return: Members can borrow and return books.
    
    Bonus Tasks:
    
    -   Implement search for books by title, author, or genre.
    -   Send emails to the Member once the borrowed book is near the due date (You can use SendGrid for this).
    -   Add a feature to mark books as "Recommended" and they appear prominently to Members.
    -   Implement a simple client using a frontend framework of your choice that consumes your API.
    -   Implement CI using Azure DevOps and use Coverlet for code coverage and insert their badges into your readme file.
    
    Review Process:
    
    Similar to the previous tasks, we will be looking for code quality, security, testability, API structure and usability, validations and error handling, development and deployment, documentation, and version control.
    
    Please submit your code as a GitHub repository with a README file explaining how to run the app and any additional notes you want to include.
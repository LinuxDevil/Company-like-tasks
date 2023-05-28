#  Recipe Management API
    
    Task Description
    
    You are tasked to build a Recipe Management backend API. This API will be utilized by Users (Cooks) to share and manage their recipes and by other Users (Food Lovers) to browse, rate, and save these recipes.
    
    The Recipe Management API will be used by Cooks to:
    
    -   Create, update, and delete recipes.
    -   View ratings and comments for their recipes.
    
    Food Lovers will use the API to:
    
    -   View available recipes.
    -   Rate and comment on recipes.
    -   Save favorite recipes.
    
    Technical Details
    
    Your backend should serve all kinds of clients (which you do not have to implement) - using a RESTful API.
    
    The following technical requirements are placed on your implementation:
    
    -   Use .NET Core with ASP.NET Core framework.
    -   HTTP responses should follow best practices.
    -   API should communicate with their clients using JSON data structures.
    -   Implement authentication using JSON Web Tokens (JWT).
    -   Resource Permissions:
        -   Cooks are not authorized to delete ratings or comments.
        -   Food Lovers are not authorized to manage recipes.
    -   Data Storage: All data should be stored in a relational database. You can use SQL Server.
    -   Users:
        -   Registrations should be done with email and password.
        -   There should be user roles distinguishing Cooks and Food Lovers.
    
    You should implement the following functionality:
    
    -   User Registration.
    -   User Login.
    -   Recipe data: Recipes must have a title, ingredients, and instructions. Create, update, delete operations should be performed by the Cooks.
    -   Ratings and Comments: Food Lovers can rate and comment on recipes.
    
    Bonus Tasks:
    
    -   Allow Cooks to upload images of their dishes to be stored on Azure Blob Storage.
    -   Send emails to the Cook once the recipe receives a rating or comment (You can use SendGrid for this).
    -   Implement search for recipes by title, ingredients, or Cook.
    -   Add a feature to mark recipes as "Featured" and they appear prominently to Food Lovers.
    -   Implement a simple client using a frontend framework of your choice that consumes your API.
    -   Implement CI using Azure DevOps and use Coverlet for code coverage and insert their badges into your readme file.
    
    Review Process:
    
    Similar to the previous task, we will be looking for code quality, security, testability, API structure and usability, validations and error handling, development and deployment, documentation, and version control.
    
    Please submit your code as a GitHub repository with a README file explaining how to run the app and any additional notes you want to include.
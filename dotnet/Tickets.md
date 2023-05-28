#  Ticket Booking API
    
    Task Description
    
    You are tasked to create a Ticket Booking backend API. This API will be used by event organizers (Admins) to manage events and ticket bookings, and by users (Customers) to book tickets for these events.
    
    The Ticket Booking API will be used by your Admins to:
    
    -   Create, update, and delete events.
    -   View all ticket bookings for their events.
    
    Customers will use the API to:
    
    -   Browse available events.
    -   Book tickets for an event.
    -   View their own ticket bookings.
    
    Technical Details
    
    Your backend should serve all kinds of clients (which you do not have to implement) - using a RESTful API.
    
    The following technical requirements are placed on your implementation:
    
    -   Use .NET Core with ASP.NET Core framework.
    -   HTTP responses should follow best practices.
    -   API should communicate with their clients using JSON data structures.
    -   Implement authentication using JSON Web Tokens (JWT).
    -   Resource Permissions:
        -   Admins are not authorized to book tickets.
        -   Customers are not authorized to manage events.
    -   Data Storage: All data should be stored in a relational database. You can use SQL Server.
    -   Users:
        -   Registrations should be done with email and password.
        -   There should be user roles distinguishing Admins and Customers.
    
    You should implement the following functionality:
    
    -   User Registration (Customers only).
    -   User Login.
    -   Event data: Events must have a title, description, date, and available tickets. Add, update, delete operations should be performed by the Admins.
    -   Ticket Booking: Customers can book tickets for an event.
    
    Bonus Tasks:
    
    -   Implement search for events by title, date, or genre.
    -   Send emails to the Customer once the ticket is booked or event date is near (You can use SendGrid for this).
    -   Add a feature to mark events as "Featured" and they appear prominently to Customers.
    -   Implement a simple client using a frontend framework of your choice that consumes your API.
    -   Implement CI using Azure DevOps and use Coverlet for code coverage and insert their badges into your readme file.
    
    Review Process:
    
    Similar to the previous tasks, we will be looking for code quality, security, testability, API structure and usability, validations and error handling, development and deployment, documentation, and version control.
    
    Please submit your code as a GitHub repository with a README file explaining how to run the app and any additional notes you want to include.
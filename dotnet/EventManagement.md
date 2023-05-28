
# Event Management API
    
    Task Description
    
    Your task is to implement a simple Event Management backend API. This API will be used by event organizers (Admin Users) to manage events and by users (Attendees) to view and register for these events.
    
    The Event Management API will be used by your Admin Users to perform the following tasks:
    
    -   Create, update, delete events.
    -   List all registered attendees for an event.
    -   Change the status of events (Active, Cancelled).
    
    Attendees will use the API to perform the following tasks:
    
    -   View active events.
    -   Register for an event.
    -   View their own registrations with their current status (Confirmed, Cancelled).
    
    Technical Details
    
    Your backend should serve all kinds of clients (which you do not have to implement) - using a RESTful API.
    
    The following technical requirements are placed on your implementation:
    
    -   Use .NET Core with ASP.NET Core framework.
    -   HTTP responses should follow best practices.
    -   API should communicate with their clients using JSON data structures.
    -   Implement authentication using JSON Web Tokens (JWT).
    -   Resource Permissions:
        -   Attendees are not authorized to manage events.
        -   Admin Users are not authorized to cancel registrations.
    -   Data Storage: All data should be stored in a relational database. You can use SQL Server.
    -   Users:
        -   Registrations should be done with email and password (Attendees).
        -   There should be one Admin account, which will manage events.
    
    You should implement the following functionality:
    
    -   User Registration (Attendees only)
    -   User Login
    -   Event data: Events must have a title, description, date, and status. Create, update, delete operations should be performed by the Admin.
    -   Attendee registrations: Attendees can register for an event. Admin can view all registrations.
    
    Bonus Tasks:
    
    -   Implement search for events by title or date.
    -   Add an expiry date to events, so they won't appear to attendees after a specific date.
    -   Use Elasticsearch to search for keywords in the event description.
    -   Implement a simple client using a frontend framework of your choice that consumes your API.
    -   Implement CI using Azure DevOps and use Coverlet for code coverage and insert their badges into your readme file.
    
    Review Process:
    
    We will be looking for the following in your project:
    
    -   Code quality: Is your code well-structured? Do you keep your coding style consistent across your codebase?
    -   Security: How do you store your customers' passwords? What about the security of your customers' data and the API endpoints?
    -   Testability: Is your code tested? How do you approach testing?
    -   API structure and usability: How do you structure API endpoints? Do you follow REST principles? Do you make use of proper response codes and HTTP headers where it makes sense?
    -   Validations and error handling: How do you handle required fields, and errors that might appear due to invalid data? How do you handle responses and exceptions?
    -   Development and deployment: How hard is it to run your project locally? And how hard is it to deploy it?
    -   Documentation: Is your API documented? Is your documentation auto-generated from the code base? Does it cover all your endpoints?
    
    Please submit your code as a GitHub repository with a README file explaining how to run the app and any additional notes you want to include.
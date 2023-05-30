
**Asynchronous Email Notification System**

Project Description

You are tasked with creating an asynchronous email notification system. When an event occurs (like user registration), an email should be sent to the user. Use RabbitMQ as a message broker to make the email sending process asynchronous.

Functional Requirements:

1.  User Registration: When a user registers, they should receive a welcome email.
    
2.  Send Email: The email sending process should be asynchronous.
    

Technical Requirements:

-   Use Spring Boot to implement the backend.
-   Use RabbitMQ as a message broker.
-   Use an SMTP server or a service like SendGrid for sending emails.
-   The application should follow the REST architecture.
-   Write unit tests for your code using JUnit and Mockito.
-   Use MySQL or PostgreSQL for your database.
-   Use Git for version control and make sure to commit your changes regularly.

Bonus:

-   Implement user authentication using JWT.
-   Deploy your application to a platform like Heroku.
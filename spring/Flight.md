
**Flight Booking System Backend**

Project Description

You are tasked with creating a simple backend for a flight booking system. The system should allow users to search for flights, book flights, and view their flight bookings.

Functional Requirements:

1.  User Authentication: Implement a user registration and login system. Users should be able to register with an email and password and then login to access the other API endpoints. Use JWT for authentication.
    
2.  Search Flights: Users should be able to search for available flights by departure and arrival locations, and departure date. The API should return a list of flights that match the search criteria.
    
3.  Book Flight: Users should be able to book a flight by providing the necessary details such as their full name, passport number, and the flight id.
    
4.  View Bookings: Users should be able to view all their flight bookings.
    

Technical Requirements:

-   Use Spring Boot to implement the backend.
-   Use Spring Security for implementing user authentication.
-   Use Spring Data JPA for database operations.
-   The application should follow the REST architecture.
-   Write unit tests for your code using JUnit and Mockito.
-   Use MySQL or PostgreSQL for your database.
-   Use Git for version control and make sure to commit your changes regularly.

Bonus:

-   Implement user roles (Admin, User). Admins should be able to add, update and delete flights. Use Spring Security to manage the permissions.
-   Implement pagination for the flight search and view bookings API endpoints.
-   Deploy your application to a platform like Heroku.

**Real-time Order Processing System**

Project Description

You are tasked with creating a real-time order processing system. When a new order is placed, it should be processed in real-time using Kafka as a message broker.

Functional Requirements:

1.  Create Order: Users should be able to place a new order. An order should have details such as product id, quantity, and user id.
    
2.  Process Order: When a new order is placed, a Kafka producer should send the order details to a Kafka topic. A Kafka consumer should then consume the order from the Kafka topic and process it.
    

Technical Requirements:

-   Use Spring Boot to implement the backend.
-   Use Apache Kafka for real-time order processing.
-   Use MySQL or PostgreSQL for your database.
-   The application should follow the REST architecture.
-   Write unit tests for your code using JUnit and Mockito.
-   Use Git for version control and make sure to commit your changes regularly.

Bonus:

-   Implement user authentication using JWT.
-   Deploy your application to a platform like Heroku.
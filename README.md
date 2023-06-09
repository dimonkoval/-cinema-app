# cinema-app: Ticket Booking Application
The Cinema-App is a robust ticket booking application designed to facilitate seamless ticket purchases for cinema-goers. It offers user authentication and securely stores the history of their purchases. The application leverages a range of technologies and frameworks, including Spring, Hibernate, MySQL, and servlets.

## Key Features:

  - User Authentication: The application ensures secure user authentication and supports two roles: USER and ADMIN.
  - Cinema Hall Management: Users (both admin and regular users) can view available cinema halls, while only admins can add new cinema halls.
  - Movie Management: Users can browse through the list of movies, while admins have the authority to add new movies.
  - Movie Session Availability: Users can view available movie sessions, including showtimes, while admins can create and manage movie sessions.
  - Order Placement: Users can place orders for movie tickets, and admins can monitor all orders.
  - Shopping Cart: Users can manage their shopping carts, add or remove movie sessions, and complete their orders.
  - User Management: Admins have access to user-specific functionality, such as retrieving user details by email.

## Business Value:

  - Enhanced Ticket Purchasing: The Cinema-App simplifies and streamlines the ticket purchasing process, offering a user-friendly interface that allows users to easily browse movies, select showtimes, and book tickets. This convenience can attract more customers and increase ticket sales.
  - Efficient Management: The application provides admins with tools to manage cinema halls, movies, and showtimes effectively. This centralized control helps optimize operations and improve overall efficiency.
  - Personalized Experience: By storing user purchase history, the application can offer personalized recommendations, loyalty programs, or targeted promotions. This can foster customer loyalty and increase repeat business.
  - Secure Authentication: The implementation of role-based authentication ensures the security of user data and prevents unauthorized access, creating a trustworthy environment for users.
  - Insightful Reporting: The system's ability to generate reports on movie sessions, ticket sales, and user activity provides valuable insights for business analysis and decision-making.

## Technologies
    - Spring 
    - Spring security 
    - Hibernate 
    - Maven
    - Git
    - Tomcat
    - MySQL connector 
    - javax servlet 
    - log4j 
## Project Structure  
[cinema](src%2Fmain%2Fjava%2Fcinema) 
  - [config](src%2Fmain%2Fjava%2Fcinema%2Fconfig)
  - [controller](src%2Fmain%2Fjava%2Fcinema%2Fcontroller)
  - [dao](src%2Fmain%2Fjava%2Fcinema%2Fdao)
    - [impl](src%2Fmain%2Fjava%2Fcinema%2Fdao%2Fimpl)
  - [dto](src%2Fmain%2Fjava%2Fcinema%2Fdto)
    - [request](src%2Fmain%2Fjava%2Fcinema%2Fdto%2Frequest)
    - [response](src%2Fmain%2Fjava%2Fcinema%2Fdto%2Fresponse)
  - [exception](src%2Fmain%2Fjava%2Fcinema%2Fexception)  
  - [lib](src%2Fmain%2Fjava%2Fcinema%2Flib)
  - [model](src%2Fmain%2Fjava%2Fcinema%2Fmodel)
  - [security](src%2Fmain%2Fjava%2Fcinema%2Fsecurity)
  - [service](src%2Fmain%2Fjava%2Fcinema%2Fservice)
    - [impl](src%2Fmain%2Fjava%2Fcinema%2Fservice%2Fimpl)
    - [mapper](src%2Fmain%2Fjava%2Fcinema%2Fservice%2Fmapper)
  - [util](src%2Fmain%2Fjava%2Fcinema%2Futil)

##  Instructions for launching the project
   - fill the file src/main/resources/db.properties with the connection data to the DB, specifying your data.
   - When starting the application, a user is created with the roles ADMIN and USER,
  email "admin@gmail.com" and password "admin"
   - to log data in the src/main/resources/log4j2.xml file, you must specify the full path of the file in the "fileName" field
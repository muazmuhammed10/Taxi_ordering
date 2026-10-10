# Taxi Ordering System

A taxi booking and management application developed to simplify passenger bookings, driver management, and taxi departure coordination. The system supports passenger, driver, and administrator roles and provides a structured way to manage taxi requests and monitor operations.

**Project Type:** Academic and Software Engineering Portfolio Project  
**Status:** Completed

## Features

- **Passenger Management** — Support passenger accounts and taxi booking requests.
- **Driver Management** — Manage driver information and coordinate taxi assignments.
- **Taxi Booking** — Organize passengers according to their selected destinations.
- **Automatic Departure** — Trigger taxi departure when 16 passengers have selected the same destination.
- **Manual Departure** — Allow the administrator to initiate departure manually.
- **Role-Based Access** — Separate passenger, driver, and administrator functionality.
- **Database Integration** — Store and retrieve application data using MySQL.
- **Administrative Control** — Monitor bookings and coordinate taxi operations.

## Technology Stack

| Component | Technology |
|---|---|
| Core application and business logic | Java |
| Desktop user interface | JavaFX |
| UI styling | CSS |
| Database | MySQL |
| Database connectivity | JDBC |
| Development environment | Eclipse IDE |
| JavaFX SDK | JavaFX 21.0.7 |

The application uses Java for its core functionality, JavaFX for the desktop interface, JDBC for database connectivity, and MySQL for persistent data storage.

HTML can be included as a frontend technology if the completed version contains a separate HTML-based interface. JavaFX applications do not require HTML for their primary interface.

## System Roles

### 1. Passenger
- Access passenger functionality.
- Submit taxi booking requests.
- Select a destination.
- Participate in destination-based passenger grouping.

### 2. Driver
- Access driver functionality.
- View relevant taxi assignments and departure information.

### 3. Administrator
- Manage taxi operations.
- Monitor passenger grouping by destination.
- Initiate departure manually or use the 16-passenger departure condition.

## Special Feature: Destination-Based Departure

One of the main features is destination-based passenger grouping.

1. Passengers select their intended destinations.
2. The system organizes passengers according to their destinations.
3. When 16 passengers share the same destination, the system can trigger the automatic departure condition.
4. The administrator can also initiate departure manually.

This feature demonstrates business-rule implementation and coordination of multiple passenger booking requests.

## Database

The application uses MySQL with JDBC to connect the Java application to the database.

**Database name:** `TaxiOrderingSystem`

The database stores the information required to support passenger, driver, administrator, and taxi booking operations.

## Requirements

- Java Development Kit (JDK)
- Eclipse IDE or another compatible Java IDE
- JavaFX SDK 21.0.7
- MySQL Server
- MySQL JDBC driver

## Setup and Installation

1. Install the JDK, Eclipse IDE, JavaFX SDK, and MySQL Server.
2. Clone or download this repository.
3. Open the project in Eclipse.
4. Configure the JavaFX SDK and required JavaFX modules.
5. Add the MySQL JDBC driver to the project's build path.
6. Create or import the project database named `TaxiOrderingSystem`.
7. Update the database connection settings in the application to match your local MySQL configuration.
8. Run the project's main Java class from Eclipse.

**Note:** The exact database schema, Java main class, and connection settings depend on the source files included in the repository.

## Project Objectives

- Apply object-oriented programming concepts using Java.
- Integrate a Java application with a relational database.
- Implement role-based application functionality.
- Apply business rules to passenger grouping and taxi departure.
- Develop a practical solution to a transportation coordination problem.

## Future Improvements

- Online payment integration.
- Real-time taxi tracking.
- SMS or email notifications.
- Booking history and analytics.
- Automated testing and improved deployment workflows.

## Author

**Muaz Muhammed**

Software Engineering Student | Full-Stack Development | Cybersecurity

## License

This project is available for educational and portfolio demonstration purposes. Add a `LICENSE` file if you intend to distribute it under a specific open-source license.

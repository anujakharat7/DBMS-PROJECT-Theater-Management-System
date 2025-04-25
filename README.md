# Theatre Management System – DBMS Project (Group 10)

This project simulates a complete **Theatre Management System**, designed using **SQL** and **PL/SQL**, encompassing all core database concepts such as relationships, constraints, procedures, functions, and triggers.

It models the real-world scenario of managing performances, ticket reservations, payments, actors, employees, and customer reviews — all managed in a structured relational database.

#  Features

-  **Ticket Booking & Reservations**  
  Customers can reserve or purchase tickets for various performances in different theatres.

-  **Actor & Crew Management**  
  Maintain actor profiles, assign them to plays, and manage backstage crew roles.

- **Theatre Scheduling**  
  Each theatre hosts multiple plays, and each play can have multiple performances.

- **Payments & Reports**  
  Track customer payments and generate summary reports using PL/SQL.

- **Customer Reviews**  
  Users can rate and review plays they've attended.

- **Parking Facility Tracking**  
  Maintain availability of parking slots by vehicle type.

#  Database Design

# Tables Included:
- `Theatre`, `Play`, `Performance`, `Actor`, `Ticket`, `Customer`, `Reservation`, `Payment`, `Review`, `Employee`, `Crew`, `Parking`

# Constraints:
- Primary Keys, Foreign Keys  
- Check constraints (e.g., ID formats, rating limits, ticket status)  
- Not Null and Unique constraints

# Relationships:
- One-to-many: Theatre → Performance  
- Many-to-many: Actor ↔ Performance, Employee ↔ Theatre, Crew ↔ Performance  
- One-to-many: Customer → Reservation, Payment, Review

# SQL Concepts Demonstrated

-  **Data Definition Language (DDL)**  
  Table creation with constraints

-  **Data Manipulation Language (DML)**  
  Data insertion and updates

- **Queries (10 SQL Queries)**  
  Examples include filtering, sorting, joins, aggregations, and subqueries

-  **Stored Procedure**  
  Generates reports by position and total salary

  -  **Function**  
  (As defined in the project – customizable for logic like ticket status, available shows, etc.)

-  **Trigger**  
  Example use-case: auto-updating ticket or payment status

# Sample Data Highlights

- 5 Theatres (Mumbai-based) with varying capacities  
- 5 Popular Plays from different genres  
- 5 Actors and 5 Crew members  
- 5 Employee records across roles  
- 5 Sample customers with reservations and payments  
- Reviews and ratings for each play  
- Parking lot data (2-wheeler and 4-wheeler)

# Example Queries Included

1. Display theatres by capacity (descending)  
2. Crew members whose names start with 'D'  
3. Tickets priced between 100 to 899  
4. Increase employee salaries by 5%  
5. Filter reviews with "Very Good"  
6. Find available tickets and related shows  
7. Show with the least ticket price  
8. Employees with salary > 30,000  
9. Daily total payments  
10. PL/SQL report of employee positions and salary totals

# Scope & Objective

This project showcases the use of a **normalized relational schema** to efficiently manage complex interactions in a theatre ecosystem. It emphasizes real-world applications of database triggers, constraints, and PL/SQL logic in organizing events and transactions.

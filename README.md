# ASP.NET User Management System

This simple user management system, built with ASP.NET Core and the Repository Pattern, serves as a solid foundation for larger web applications. It offers essential user management features while maintaining a clean architecture. The system is easily extendable and customizable for more complex projects.

Features
- User Registration: Users can sign up with basic information.
- User Login: Secure authentication with password hashing.
- Role-based Authorization: Access levels based on roles (Admin, User, etc.).
- Repository Pattern: Facilitates data access while promoting separation of concerns and scalability.
- Dependency Injection: Manages service layer and repository instances.
- Modular Structure: Simplifies future development.
- Authentication: Implements JWT token-based authentication.

Technologies Used
- ASP.NET Core: A framework for building modern web applications.
- Entity Framework Core: An ORM for database operations.
- SQL Server: Database provider (modifiable as needed).
- Repository Pattern: Separates data access from business logic.
- AutoMapper: For mapping between data and view models.
- Dependency Injection: Built-in support in ASP.NET Core for efficient service management.

Project Structure
- Controllers: Manage incoming HTTP requests and direct them to services.
- Models: Represent the database structure.
- Repositories: Handle data access logic (CRUD operations).
- Data: A bridge from the app to the db and define tables relationships.
- DTOs: Facilitate safe and clean data manipulation.
- Mapping Config: Define mappings between models and DTOs.

Usage
This template can be a starting point for:
- Building web applications with authentication.
- Implementing role-based access control.
- Extending the system for complex scenarios (e.g., password reset, email verification).

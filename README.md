System with JWT Authentication
Introduction
This project is a demonstration of Role-Based Access Control (RBAC) using Spring Boot and JWT (JSON Web Tokens) for secure authentication and authorization. It fulfills the requirements outlined in the backend developer assignment by implementing features like user authentication, role-based access, and secure endpoints.

Features
User Authentication:

Users can register and log in to the system.
JWT is used to generate and validate tokens for secure communication.
Role-Based Authorization:

Supports roles such as ROLE_USER and ROLE_ADMIN.
Access to endpoints is restricted based on the user's assigned role.
Secure Endpoints:

Public Endpoints: Accessible to all users.
User-Specific Endpoints: Accessible only to authenticated users with ROLE_USER.
Admin-Specific Endpoints: Accessible only to users with ROLE_ADMIN.
Password Security:

Passwords are securely hashed using BCrypt.
Token Management:

JWT tokens are used for stateless authentication.
Tokens include user details and role information for role-based access.
Technologies Used
Spring Boot: Backend framework.
Spring Security: For authentication and authorization.
JWT: For stateless token-based authentication.
JPA/Hibernate: For database interaction.
H2 Database: Embedded database for testing.
Maven: Dependency management.

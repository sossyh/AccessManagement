
# AccessManagement

AccessManagement is an ASP.NET Core 8 application designed for handling authentication and authorization using JWT (JSON Web Token) authentication. This application follows best practices for securing .NET 8 Clean Architecture.

## Features

- JWT Authentication: Implements secure authentication using JSON Web Tokens.
- Authorization: Provides role-based access control (RBAC) for managing user permissions.
- Clean Architecture: Utilizes a clean and modular architecture for better code organization and maintainability.
- Secure APIs: Ensures secure communication between clients and servers.
- Logging and Error Handling: Implements logging and error handling mechanisms for better debugging and monitoring.

## Setup

1. Clone the repository:
   
       git clone https://github.com/sossyh/AccessManagement.git
  

2. Navigate to the project directory:
   
       cd AccessManagement
   

3. Install dependencies:
   
       dotnet restore
   

4. Configure database connection:
   Update the connection string in `appsettings.json` file with your database details.

5. Run migrations:
   
       dotnet ef database update
   

6. Run the application:
   
       dotnet run
   

## Usage

Once the application is running, you can access the APIs using your preferred REST client. Here are some sample endpoints:

- `/api/auth/login`: Endpoint for user authentication.
- `/api/auth/register`: Endpoint for user registration.
- `/api/users`: Endpoint for managing user accounts.

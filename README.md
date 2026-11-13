# The Caterist

A full-stack web application developed with C# ASP.NET Core MVC, Entity Framework Core, and MS SQL Server. Designed to manage event dining workflows, featuring structured backend business logic, relational database modeling, and role-based operational flows.

## Database Installation Instructions

The database scripts are included in the repository for smooth operation. You can set up the database using either of the following methods:

1. **Using SQL Server:** Run the `database_build_script.sql` file located in the project's main directory.
2. **Using Entity Framework Core:** Run the following command in your VS Code terminal to apply migrations automatically:
   ```bash
   dotnet ef database update

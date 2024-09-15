
# Task Management System

## Overview
The **Task Management System** is a web-based application built using **ASP.NET Core MVC**, **Entity Framework Core**, and **SQL Server**. It allows users to create, update, and manage tasks efficiently, providing functionalities like task filtering, task assignment, and user authentication.

This project follows **best coding practices** such as Dependency Injection, Repository Pattern, and Layered Architecture, making it scalable and maintainable.

## Features
- **Task Creation**: Users can create new tasks with details like Task Name, Description, Due Date, Priority, and Status.
- **Task Viewing**: Displays all tasks with filtering options based on Priority and Status.
- **Task Editing**: Allows users to update task details.
- **Task Deletion**: Enables users to delete tasks with a confirmation prompt.
- **Task Completion**: Tasks can be marked as "Completed".
- **User Authentication**: Built-in login system using ASP.NET Core Identity.
- **Task Assignment**: Assign tasks to different users within the system.
- **Task Search**: Search tasks by name.

## Technologies Used
- **ASP.NET Core MVC**: For the application's architecture.
- **Entity Framework Core**: For database access and ORM.
- **SQL Server**: For persistent storage of task data.
- **ASP.NET Core Identity**: For managing user authentication and roles.
- **Bootstrap**: For responsive and modern UI design.
- **LINQ**: For efficient database queries and data filtering.

## Database Schema
The database contains two main tables:
1. **Tasks**:
   - `Id`: Primary key.
   - `TaskName`: Name of the task.
   - `Description`: Detailed description of the task.
   - `DueDate`: Deadline for the task.
   - `Priority`: Task priority (Low, Medium, High).
   - `Status`: Current status (To Do, In Progress, Completed).
   - `UserId`: Foreign key linking the task to the user.
   
2. **AspNetUsers**:
   - Managed by ASP.NET Core Identity for user authentication.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jeya-Adlin/UserTaskManagementSystem.git

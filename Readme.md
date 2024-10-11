# TODO App - ASP.NET Core 8 MVC Razor Pages

A simple and classic TODO list application built with ASP.NET Core 8 MVC and Razor Pages. Users can add tasks categorized by type, set deadlines, mark tasks as completed, and delete completed tasks.

## Features

- Add tasks with categories.
- Set deadlines for tasks.
- Mark tasks as completed.
- Delete completed tasks.

## Technologies Used

- C#
- ASP.NET Core 8
- Razor Pages
- Entity Framework Core
- SQL Server (or another database of your choice)

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Before you begin, ensure you have the following installed:

- [.NET Core 8 SDK](https://dotnet.microsoft.com/download/dotnet-core/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or any other preferred C# IDE.
- [SQL Server](https://www.microsoft.com/en-us/sql-server) or a compatible database.

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/NikaL25/TodoApp.git
2. cd /TodoApp
3. dotnet restore


### Database Setup

"ConnectionStrings": {
  "DefaultConnection": "Data Source=DESKTOP-9CHL98U\SQLEXPRESS;Initial Catalog=todoapp;Integrated Security=True;Encrypt=True;Trust Server Certificate=True"
}

dotnet ef database update

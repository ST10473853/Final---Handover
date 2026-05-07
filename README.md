**Kias Kar Kompany - Vehicle Management System**

Project Description

Kias Kar Kompany is a simple ASP.NET Core MVC web application designed to manage vehicle listings for a car dealership.
The system allows users to perform full CRUD (Create, Read, Update, Delete) operations on vehicle records stored in a SQL 
Server database.


The application demonstrates the use of the MVC (Model-View-Controller) architecture, Entity Framework Core, and Razor Views.

--------------------------------------------------------------------------------------

**Features**

Add new vehicles
View a list of all vehicles

View detailed vehicle information

Edit existing vehicles

Delete vehicles

Responsive and user-friendly UI

Styled using Bootstrap and custom CSS

--------------------------------------------------------------------------------------

**Technologies Used**

ASP.NET Core MVC

C#

Entity Framework Core

SQL Server

HTML5 / CSS3

Bootstrap 5

Visual Studio

--------------------------------------------------------------------------------------

**Setup Instructions**


1. Clone the repository

git clone https://github.com/mickymouse777/Kias_Kar_Kompany.git

2. Open the project

Open the solution file (.sln) in Visual Studio

3. Configure Database Connection

Update the appsettings.json file:

"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=KiasKarKompanyDB;Trusted_Connection=True;TrustServerCertificate=True;"
}

4. Run Migrations (if required)

Open Package Manager Console and run:

Add-Migration InitialCreate
Update-Database


5. Run the application

Press F5 or click Run

The app will open in your browser at:

https://localhost:xxxx

--------------------------------------------------------------------------------------

**UI Improvements**

The application includes:

Bootstrap styling

Custom CSS enhancements

Card-based layouts

Hover effects

Modern buttons and badges

Responsive design


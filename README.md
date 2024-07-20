BlogWebApp

Description
BlogWebApp is a full-stack blogging application developed using Angular for the frontend, ASP.NET for the backend, and MSSQL Server for the database. The app features user registration, blog management, and a responsive design, providing a complete blogging experience.

Installation Instructions
Backend (ASP.NET)
1. Clone the repository:
	git clone https://github.com/yourusername/BlogWebApp.git

2. Navigate to the backend directory:
	cd BlogWebApp/Backend

3. Install dependencies:
	dotnet restore

4. Run the backend application:
	dotnet run

Frontend (Angular)
1. Navigate to the frontend directory:
	cd BlogWebApp/Frontend

2. Install dependencies:
	npm install

3. Run the frontend application:
	ng serve

Usage
1. Access the application: Open your browser and go to http://localhost:4200 for the frontend and http://localhost:5000 for the backend API.
2. Register an account: Go to the registration page to create a new user account.
3. Log in: Use the login page to authenticate.
4. Manage blogs: Create, read, update, and delete blogs. Users can also add comments and view blog statistics.

Technologies Used
Frontend: Angular, Bootstrap
Backend: ASP.NET Core, Entity Framework Core (Dapper is used for database access)
Database: MSSQL Server
Development Tools: Visual Studio Code, Visual Studio
Version Control: Git, GitHub

Features
User Authentication: Register, log in, and manage user sessions.
CRUD Operations: Create, read, update, and delete blog posts.
Hierarchical Comments: Nested comments for blog posts.
Responsive Design: Mobile-friendly layout and UI.
Image Uploads: Support for uploading and managing blog images.

Contributing Guidelines
1. Fork the repository and create a new branch for your feature or bug fix.
2. Write your code and ensure it passes tests.
3. Submit a pull request with a clear description of your changes.
For detailed contributing guidelines, please refer to CONTRIBUTING.md.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact Information
Project Maintainer: Sagar Hatagale
Email: sagar.hatagale.dev@gmail.com 

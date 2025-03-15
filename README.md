<h2>Laravel CRUD Project Description</h2>
Project Overview
This is a CRUD (Create, Read, Update, Delete) application built with Laravel. The project focuses on managing products, allowing users to perform basic operations such as adding, editing, viewing, and deleting records.

Key Features
1.Product Management: Users can create, read, update, and delete products.
2.User Authentication: Laravel's default authentication system is included.
3.Database Migrations: Ensures structured database creation and version control.
4.MVC Architecture: Uses Laravel’s Models, Views, and Controllers for clean code organization.
5.Blade Templating Engine: Views are structured using Laravel’s Blade templates for dynamic content rendering.
6.Routing: Web routes are defined in web.php for handling requests.

Technical Details
Models:
1.Product.php - Represents the products table in the database.
2.User.php - Manages user authentication and details.

Controllers:
1.ProductController.php - Handles all CRUD operations for products.

Views (Blade Templates):
1.products/list.blade.php - Displays a list of products.
2.products/create.blade.php - Form for adding new products.
3.products/edit.blade.php - Form for updating product details.
4.welcome.blade.php - Homepage.

Routes:
1.Defined in routes/web.php to map URLs to controller actions.

Migrations:
1.create_products_table.php - Defines the schema for the products table.
2.create_users_table.php - Manages user authentication.

Setup Instructions:
1.Clone the Project
  git clone <repository_url>
  cd crud-application
  
2.Install Dependencies
  composer install
  npm install
  
3.Set Up the Environment
  *Copy .env.example to .env and configure the database.
  cp .env.example .env
  php artisan key:generate
  
4.Run Migrations
  php artisan migrate
  
5.Start the Application
  php artisan serve

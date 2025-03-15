<h1>Laravel CRUD Project Description </h1>
<h2>Project Overview</h2>
<p></p>This is a CRUD (Create, Read, Update, Delete) application built with Laravel. The project focuses on managing products, allowing users to perform basic operations such as adding, editing, viewing, and deleting records.</p>
![CRUD-2](https://github.com/user-attachments/assets/df61ab1c-e6a1-4bfa-82c6-41080408e485)
![CRUD-1](https://github.com/user-attachments/assets/7fe96f50-646f-439b-9953-7d8d7275b64c)

<h2>Key Features</h2>
<p>1.Product Management: Users can create, read, update, and delete products.</p>
<p>2.User Authentication: Laravel's default authentication system is included.</p>
<p>3.Database Migrations: Ensures structured database creation and version control.</p>
<p>4.MVC Architecture: Uses Laravel’s Models, Views, and Controllers for clean code organization.</p>
<p>5.Blade Templating Engine: Views are structured using Laravel’s Blade templates for dynamic content rendering.</p>
<p>6.Routing: Web routes are defined in web.php for handling requests.</p>

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

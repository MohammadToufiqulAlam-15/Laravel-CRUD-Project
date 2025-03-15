<h1>Laravel CRUD Project Description </h1>
<h2>Project Overview</h2>
<p></p>This is a CRUD (Create, Read, Update, Delete) application built with Laravel. The project focuses on managing products, allowing users to perform basic operations such as adding, editing, viewing, and deleting records.</p>
![CRUD-2](https://github.com/user-attachments/assets/0bb91cd7-8280-4b45-9010-50b6f4021a17)
![CRUD-1](https://github.com/user-attachments/assets/e3e43480-18f8-4b13-b918-ed36b1e61941)

<h2>Key Features</h2>
<p>1.Product Management: Users can create, read, update, and delete products.</p>
<p>2.User Authentication: Laravel's default authentication system is included.</p>
<p>3.Database Migrations: Ensures structured database creation and version control.</p>
<p>4.MVC Architecture: Uses Laravel’s Models, Views, and Controllers for clean code organization.</p>
<p>5.Blade Templating Engine: Views are structured using Laravel’s Blade templates for dynamic content rendering.</p>
<p>6.Routing: Web routes are defined in web.php for handling requests.</p>

<h2>Technical Details</h2>
<h2>Models:</h2>
<p>1.Product.php - Represents the products table in the database.</p>
<p>2.User.php - Manages user authentication and details.</p>

<h2>Controllers:</h2>
<p>1.ProductController.php - Handles all CRUD operations for products.</p>

<h2>Views (Blade Templates):</h2>
<p>1.products/list.blade.php - Displays a list of products.</p>
<p>2.products/create.blade.php - Form for adding new products.</p>
<p>3.products/edit.blade.php - Form for updating product details.</p>
<p>4.welcome.blade.php - Homepage.</p>

<h2>Routes:</h2>
<p>1.Defined in routes/web.php to map URLs to controller actions.</p>

<h2>Migrations:</h2>
<p>1.create_products_table.php - Defines the schema for the products table.</p>
<p>2.create_users_table.php - Manages user authentication.</p>

<h2>Setup Instructions:</h2>
<h2>1.Clone the Project</h2>
  <p>git clone <repository_url></p>
  <p> cd crud-application</p>
  
<h2>2.Install Dependencies</h2>
  <p>composer install</p>
  <p>npm install</p>
  
<h2>3.Set Up the Environment</h2>
 <p>*Copy .env.example to .env and configure the database.</p>
  <p>cp .env.example .env</p>
  <p> php artisan key:generate</p>
  
<h2>4.Run Migrations</h2>
  <p>php artisan migrate</p>
  
<h2>5.Start the Application</h2>
  <p>php artisan serve</p>

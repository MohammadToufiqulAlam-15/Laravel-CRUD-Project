<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laravel CRUD Project Description</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
        h1, h2 { color: #333; }
        ul { list-style-type: none; padding: 0; }
        ul li { margin-bottom: 5px; }
        code { background: #f4f4f4; padding: 2px 4px; border-radius: 4px; }
    </style>
</head>
<body>
    <h1>Laravel CRUD Project Description</h1>
    <h2>Project Overview</h2>
    <p>This is a CRUD (Create, Read, Update, Delete) application built with Laravel. The project focuses on managing products, allowing users to perform basic operations such as adding, editing, viewing, and deleting records.</p>
    <img src="https://github.com/user-attachments/assets/df61ab1c-e6a1-4bfa-82c6-41080408e485" alt="CRUD Screenshot 1" width="600">
    <img src="https://github.com/user-attachments/assets/7fe96f50-646f-439b-9953-7d8d7275b64c" alt="CRUD Screenshot 2" width="600">
    
    <h2>Key Features</h2>
    <ul>
        <li><strong>Product Management:</strong> Users can create, read, update, and delete products.</li>
        <li><strong>User Authentication:</strong> Laravel's default authentication system is included.</li>
        <li><strong>Database Migrations:</strong> Ensures structured database creation and version control.</li>
        <li><strong>MVC Architecture:</strong> Uses Laravel’s Models, Views, and Controllers for clean code organization.</li>
        <li><strong>Blade Templating Engine:</strong> Views are structured using Laravel’s Blade templates for dynamic content rendering.</li>
        <li><strong>Routing:</strong> Web routes are defined in <code>web.php</code> for handling requests.</li>
    </ul>
    
    <h2>Technical Details</h2>
    <h3>Models</h3>
    <ul>
        <li><code>Product.php</code> - Represents the products table in the database.</li>
        <li><code>User.php</code> - Manages user authentication and details.</li>
    </ul>
    
    <h3>Controllers</h3>
    <ul>
        <li><code>ProductController.php</code> - Handles all CRUD operations for products.</li>
    </ul>
    
    <h3>Views (Blade Templates)</h3>
    <ul>
        <li><code>products/list.blade.php</code> - Displays a list of products.</li>
        <li><code>products/create.blade.php</code> - Form for adding new products.</li>
        <li><code>products/edit.blade.php</code> - Form for updating product details.</li>
        <li><code>welcome.blade.php</code> - Homepage.</li>
    </ul>
    
    <h3>Routes</h3>
    <p>Defined in <code>routes/web.php</code> to map URLs to controller actions.</p>
    
    <h3>Migrations</h3>
    <ul>
        <li><code>create_products_table.php</code> - Defines the schema for the products table.</li>
        <li><code>create_users_table.php</code> - Manages user authentication.</li>
    </ul>
    
    <h2>Setup Instructions</h2>
    <ol>
        <li><strong>Clone the Project</strong>
            <pre><code>git clone &lt;repository_url&gt;
cd crud-application</code></pre>
        </li>
        <li><strong>Install Dependencies</strong>
            <pre><code>composer install
npm install</code></pre>
        </li>
        <li><strong>Set Up the Environment</strong>
            <pre><code>cp .env.example .env
php artisan key:generate</code></pre>
        </li>
        <li><strong>Run Migrations</strong>
            <pre><code>php artisan migrate</code></pre>
        </li>
        <li><strong>Start the Application</strong>
            <pre><code>php artisan serve</code></pre>
        </li>
    </ol>
</body>
</html>

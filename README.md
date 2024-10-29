# QuickTasks

This is a simple To-Do List application built with Laravel.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [PHP](https://www.php.net/downloads) (version 7.3 or higher)
- [Composer](https://getcomposer.org/download/)
- [Laravel](https://laravel.com/docs/8.x/installation) (version 8.x or higher)
- A web server (e.g., Apache, Nginx)

## Installation

Follow these steps to set up the application:

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/repository-name.git
  Replace username and repository-name with your GitHub username and the repository name.

2. **Navigate to the project directory**
   ```bash
   cd repository-name

3. Install dependencies
   ```bash
   composer install

4. Set up the environment file Copy the .env.example file to a new .env file:
   ```bash
   cp .env.example .env

5. Generate the application key
   ```bash
   php artisan key:generate

6. Set up your database
     Create a new database in your preferred database management system (MySQL, PostgreSQL, etc.).<br>
     Update the .env file with your database configuration
   ```bash
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_username
   DB_PASSWORD=your_password

8. Run migrations
   ```bash
   php artisan migrate

9. Start the server
   ```bash
   php artisan serve

10. Access the application Open your web browser and go to http://localhost:8000/tasks to access the To-Do List application.

      **Features**
      - Add new tasks
      - Mark tasks as completed
      - Delete tasks
      - View all tasks
      
      **License**
      This project is licensed under the MIT License.
      ```bash
      Anda bisa mengganti `username` dan `repository-name` sesuai dengan informasi GitHub Anda. Setelah itu, tambahkan informasi ini ke file `readme.md` Anda untuk memberikan panduan kepada pengguna tentang cara        menjalankan aplikasi To-Do List setelah diupload di GitHub.



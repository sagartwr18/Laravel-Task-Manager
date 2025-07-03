# 📋 Laravel Task Manager

A simple yet powerful Task Management web application built with **Laravel**, **MySQL**, **JWT Authentication**, and **Blade + Bootstrap** for a responsive frontend.

---

## 🚀 Features

- ✅ **User Authentication** (Register/Login using JWT)
- 🗃️ **Add Tasks** with title, description & status
- ✏️ **Edit Tasks** (change title, description, or status)
- 📄 **View Task Details**
- ❌ **Delete Tasks**
- 🧠 **Status Options**: Pending, In Progress, Completed
- 🎨 **Clean UI** built using Bootstrap 5
- 🔐 **Secure REST APIs** for frontend-backend integration
- 📦 **Modular Laravel structure** for easy scalability
  
---

## 🧑‍💻 Tech Stack

| Layer         | Technology                     |
|---------------|--------------------------------|
| Backend       | Laravel 10                     |
| Frontend      | Blade Templating, Bootstrap 5  |
| Database      | MySQL                          |
| Auth System   | JWT (JSON Web Token)           |
| REST API      | Laravel API routes             |
| Tools         | Composer, Artisan CLI, Git     |

---

🔧 Setup Instructions
1. Clone the Repository
    git clone https://github.com/your-username/task-manager-laravel.git
    cd task-manager-laravel
2. Install Dependencies
    composer install
    npm install
3. Create .env and Generate App Key
    cp .env.example .env
    php artisan key:generate
4. Configure Database
   Edit .env file and update your DB credentials:
   DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
5. Run Migrations
   php artisan migrate
6. Install JWT Auth (if not installed)
   composer require tymon/jwt-auth
    php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"
    php artisan jwt:secret
7. Serve the Application
   php artisan serve
   Visit: http://127.0.0.1:8000

🙋‍♂️ Author
Sagar Tiwari
GitHub: github.com/sagartwr18

⭐ License
This project is open-sourced under the MIT License.




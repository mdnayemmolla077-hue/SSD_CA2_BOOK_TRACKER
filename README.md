# SSD_CA2_BOOK_TRACKER

BookTracker – Personal Reading Management Web Application

BookTracker is a web application designed to help users manage and organise their personal reading activities. It allows users to keep track of books they want to read, are currently reading, or have already completed.
Instead of relying on memory or scattered notes, this platform provides a centralised system where users can easily store and update their reading lists. The application focuses on simplicity and usability, making it suitable for both casual and active readers.
Many existing platforms are either too complex or focus heavily on social features. BookTracker solves this problem by offering a clean and focused experience where users can efficiently manage their own reading progress without unnecessary distractions.

Features
User authentication (register and login)
CRUD functionality for books (create, view, update, delete)
Ability to organise books by status:
Want to Read
Currently Reading
Completed
Personal dashboard to view all books
Users can only manage their own books
Form validation and error handling (client-side and server-side)
View individual book details
Clean and user-friendly interface

Installation

This project is developed using the Laravel framework. Follow the steps below to install and run the application.

1. Clone the repository
git clone YOUR_GITHUB_REPO_LINK
2. Navigate to the project folder
cd book-tracker
3. Install PHP dependencies
composer install
4. Install frontend dependencies
npm install
5. Create environment file

.env files are not included for security reasons. Use the example file:

cp .env.example .env
6. Update environment variables

Open the .env file and update:

DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=book_tracker
DB_USERNAME=root
DB_PASSWORD=yourpassword
7. Generate application key
php artisan key:generate
8. Create a database

This project uses MySQL.
Create a database named:

book_tracker
9. Run migrations
php artisan migrate
10. Run the development server
php artisan serve
 Access the application

Visit:

http://127.0.0.1:8000

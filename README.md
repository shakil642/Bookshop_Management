# 📚 Bookshop Management System

A web-based application designed to streamline bookstore operations, including inventory tracking, book searches, and data entry. This project is built using a PHP backend with a MySQL database, optimized for local development environments like XAMPP.

## 🚀 Features

* **Inventory Management**: Add and save new book records to the database via `add_book.php` and `save_book.php`.
* **Dynamic Search**: Filter and find specific books using the `search_book.php` interface.
* **Data Persistence**: Includes `book_list.sql` for quick database schema setup and initial data.
* **Centralized Dashboard**: A dedicated `dashboard/` directory for navigating system modules.
* **Structured UI**: Utilizes `bitnami.css` and a dedicated `img/` folder for a clean, consistent interface.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, and JavaScript.
* **Backend**: PHP.
* **Database**: MySQL (SQL).
* **Server Environment**: XAMPP / Apache.

## 📥 Installation & Setup

1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/shakil642/Bookshop_Management.git](https://github.com/shakil642/Bookshop_Management.git)
    ```

2.  **Move to Web Directory**: 
    Copy the `Bookshop_Management` folder into your XAMPP `htdocs` directory (usually `C:\xampp\htdocs`).

3.  **Database Configuration**:
    * Open your XAMPP Control Panel and start **Apache** and **MySQL**.
    * Go to `http://localhost/phpmyadmin/`.
    * Create a new database named `bookshop_db`.
    * Import the `book_list.sql` file located in the root directory.

4.  **Run the Application**:
    * Open your browser and navigate to `http://localhost/Bookshop_Management/index.php`.

## 📂 File Structure Highlights

* `index.php`: The landing page and entry point.
* `applications.html`: General application interface components.
* `save_book.php`: Backend logic to process and store book data.
* `search_results.php`: Displays query results from the database.
* `xampp/`: Configuration files specific to the local server environment.

---
**Developed by [Shakil Ahmed](https://github.com/shakil642)**

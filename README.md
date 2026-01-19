# ShaiBha - Pre-loved Fashion E-commerce Platform

ShaiBha is a curated marketplace for pre-loved fashion items, specializing in high-quality, authentic designer and branded clothing. The platform aims to make sustainable fashion accessible while offering unique pieces at affordable prices.

## Project Overview

The platform focuses on creating a premium shopping experience for customers looking for sustainable fashion options. Each item in the collection is carefully curated, authenticated, and described in detail to ensure customers have confidence in their purchases.

### Key Features

*   **User Management:** Secure user registration, login, and profile management.
*   **Product Catalog:** Browsing with advanced filtering, search, and detailed product pages.
*   **Shopping Cart:** Fully functional cart and checkout system.
*   **Order Management:** Order tracking, history, and status updates.
*   **Admin Dashboard:** Comprehensive panel for inventory, order, and customer management.
*   **Responsive Design:** Optimized for both mobile and desktop devices.
*   **Sustainability Focus:** Dedicated content to promote sustainable fashion.

## Technical Architecture

*   **Frontend:** HTML5, CSS3, JavaScript (Responsive design with custom CSS)
*   **Backend:** PHP (MVC-inspired architecture)
*   **Database:** MySQL
*   **Server:** Apache/Nginx

## Prerequisites

*   PHP 7.4 or higher
*   MySQL 5.7 or higher
*   Web Server (Apache recommended)

## Installation & Setup

1.  **Clone the Repository**
    ```bash
    git clone <repository_url>
    cd <repository_folder>
    ```

2.  **Database Setup**
    *   Create a new MySQL database (e.g., `shaibha_db`).
    *   Import the provided SQL schema file located at `database/ShaiBha_DB.sql`.
    *   This will create the necessary tables and insert default data (categories, admin user, etc.).

3.  **Configuration**
    *   Navigate to the `config/` directory.
    *   Edit `database.php` to update your database credentials:
        ```php
        $db_host = 'localhost';
        $db_name = 'your_database_name';
        $db_user = 'your_username';
        $db_pass = 'your_password';
        ```
    *   Edit `config.php` to adjust site-wide settings if necessary (Base URL, Site Name, etc.).

4.  **Run the Application**
    *   Configure your web server to point to the project root.
    *   Access the website via your browser (e.g., `http://localhost/shaibha`).

## Default Credentials

**Admin Panel:**
*   **Username:** `admin`
*   **Password:** `admin123`
*   **Login URL:** `/admin/` (or specific admin login path)

## Project Structure

```
/
├── admin/          # Admin panel files
├── cart/           # Shopping cart functionality
├── config/         # Configuration files (DB, Site settings)
├── css/            # Stylesheets
├── customer/       # Customer account functionality
├── database/       # SQL schema files
├── images/         # Static images
├── includes/       # Reusable PHP components (header, footer)
├── js/             # JavaScript files
├── pages/          # Static pages
├── services/       # Service logic
├── shop/           # Shop page functionality
├── uploads/        # User and product uploaded content
└── index.php       # Homepage
```

## Documentation

For a more detailed project outline, architecture diagrams, and database schema documentation, please refer to the `shaibha_project_outline.pdf` or `shaibha_project_outline.txt` files included in the repository.

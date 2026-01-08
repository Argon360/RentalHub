# RentalHub 🏠

**RentalHub** is a comprehensive web-based platform designed to simplify the process of renting properties. It connects landlords with potential tenants, offering a seamless interface for listing, browsing, and managing rental properties.

## 🚀 Features

*   **User Management**: Secure user registration and login system for both tenants and landlords.
*   **Property Listings**: Browse a wide range of rental properties with detailed descriptions and images.
*   **Advanced Search**: Filter properties based on location, price, amenities, and more.
*   **User Dashboard**: Personalized dashboard to manage saved properties and viewed listings.
*   **Admin Panel**: Dedicated admin area for managing users, listings, and platform content.
*   **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices.

## 🛠️ Tech Stack

*   **Frontend**: HTML5, CSS3, JavaScript
*   **Backend**: PHP
*   **Database**: MySQL
*   **Server**: Apache (via XAMPP/WAMP)

## ⚙️ Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/Argon360/RentalHub.git
    cd RentalHub
    ```

2.  **Database Setup**
    *   Open your MySQL interface (e.g., phpMyAdmin).
    *   Create a new database named `rental_db` (or similar).
    *   Import the `home_db.sql` file located in the root directory.

3.  **Configuration**
    *   Open the database connection file (usually `connect.php` or inside `components/`).
    *   Update the database credentials (host, username, password, db_name) to match your local setup.

4.  **Run the Application**
    *   Move the project folder to your server's root directory (e.g., `htdocs` for XAMPP).
    *   Open your browser and navigate to `http://localhost/RentalHub`.

## 📖 Usage

*   **Register/Login**: Create an account to start saving properties.
*   **List a Property**: (If implemented) Use the dashboard to add new rental listings.
*   **Admin Access**: Navigate to `/admin` to access administrative features.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Commit your changes (`git commit -m 'Add some feature'`).
4.  Push to the branch (`git push origin feature/YourFeature`).
5.  Open a Pull Request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
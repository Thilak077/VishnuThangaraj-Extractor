# Wishlist Management Spring Boot Application

This Spring Boot application is designed to manage wishlists for users. It provides functionality for user authentication, registration, and allows logged-in users to view, add, and delete items from their own wishlist database.

## Features

- User Authentication: Users can securely log in to the application.
- User Registration: New users can create an account with a unique username and password.
- Wishlist Management: Logged-in users can view, add, and delete items from their own wishlist.

## Technologies Used

- Spring Boot
- Spring Security
- Spring Data JPA
- Postgresql

## Setup Instructions

1. **Clone the repository:**
2. git clone https://github.com/VishnuThangaraj/Wishlist-Management.git
3. **Database Configuration:**
- Install and configure Postgresql.
- Update `application.properties` with your database credentials.
- spring.datasource.url = jdbc:postgresql://localhost:5432/--Mention Your Database Name here--
- spring.datasource.username = Your userName
- spring.datasource.password = Your Password
4. **Build and Run the Application:**
5. **Access the Application:**
Open your web browser and go to `http://localhost:8081/api/___`.

## Usage

1. **User Registration:**

- Navigate to the registration page.
- Fill in the required details (username, email, password).
- Click on the "Register" button.

2. **User Login:**

- Navigate to the login page.
- Enter your username and password.
- Click on the "Login" button.

3. **View Wishlist:**

- Once logged in, you will be redirected to your wishlist page.
- Here, you can view all the items in your wishlist.

4. **Add Item to Wishlist:**

- Click on the "Add Item" button.
- Enter the details of the item (name, description, etc.).
- Click on the "Add" button to add the item to your wishlist.

5. **Delete Item from Wishlist:**

- Each item in the wishlist will have a "Delete" button.
- Click on the "Delete" button next to the item you want to remove from your wishlist.



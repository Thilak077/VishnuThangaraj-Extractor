# Wishlist Management Spring Boot Application

This Spring Boot application is designed to manage wishlists for users. It provides functionality for user authentication, registration, and allows logged-in users to view, add, and delete items from their own wishlist database.

## Features

- User Authentication: Users can securely log in to the application.
- User Registration: New users can create an account with a unique username and password.
- Wishlist Management: Logged-in users can view, add, and delete items from their own wishlist.

## Requirements
- Java Version 17.0+
- Java IDE with Maven Support (eg. IntelliJ, Eclipse)
- PgAdmin (Postgresql) - Database
- PostMan ( Testing API)

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

- Navigate to the registration endpoint.
- Send the required details (name, email, gender, password) as JSON Object.
  
2. **User Login:**

- Navigate to the login endpoint.
- Send the required details as JSON Object.

3. **View Wishlist:**

- Once logged in, Jwt Token will be generated.
- Use the Jwt-Token to access the current user Wishlist.

4. **Add Item to Wishlist:**

- Send the the details of the item (name, description) as JSON Object.
- Authentication Required (Beared Token)

5. **Delete Item from Wishlist:**

- Send the Id of the wishlist item of the current user in to delete the Wishlist item in DELETE API.
- Authentication Required (Beared Token)

## Contribution

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](Apache2.0).

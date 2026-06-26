[README(2).md](https://github.com/user-attachments/files/29383035/README.2.md)[Upl# Clothing Store E-Commerce API

## Overview

The Clothing Store E-Commerce API is a Spring Boot RESTful application
that allows users to browse products, manage a shopping cart, update
their profile, and complete the checkout process. The project uses a
MySQL database and follows a layered architecture with Controllers,
Services, and Repositories.

This project was developed as part of the Year Up United Application
Development program.

------------------------------------------------------------------------

## Technologies Used

-   Java 21
-   Spring Boot
-   Spring Security
-   Spring Data JPA
-   Hibernate
-   MySQL
-   Maven
-   Swagger / OpenAPI
-   Git & GitHub

------------------------------------------------------------------------

## Features

### Authentication

-   User login
-   JWT authentication
-   Protected endpoints

### Categories

-   View all categories
-   View a category by ID
-   View products by category

### Products

-   View all products
-   Search and filter products
-   View product details
-   Create, update, and delete products (Admin)

### Shopping Cart

-   View shopping cart
-   Add products to cart
-   Update product quantity
-   Remove all items from cart

### User Profile

-   View profile information
-   Update profile information

### Checkout

-   Create an order from the shopping cart
-   Save order information
-   Save order line items
-   Clear the shopping cart after checkout

------------------------------------------------------------------------

## Bug Fixes

### Bug #1

Fixed the product search so all matching products are returned instead
of only featured products.

### Bug #2

Fixed product updates so stock quantities are saved correctly.

------------------------------------------------------------------------

## API Endpoints

### Authentication

-   POST `/login`
-   POST `/register`

### Categories

-   GET `/categories`
-   GET `/categories/{id}`
-   GET `/categories/{categoryId}/products`

### Products

-   GET `/products`
-   GET `/products/{id}`
-   POST `/products`
-   PUT `/products/{id}`
-   DELETE `/products/{id}`

### Shopping Cart

-   GET `/cart`
-   POST `/cart/products/{productId}`
-   PUT `/cart/products/{productId}`
-   DELETE `/cart`

### Profile

-   GET `/profile`
-   PUT `/profile`

### Orders

-   POST `/orders`

------------------------------------------------------------------------

## Database

Default database:

`clothingstore`

Update your MySQL username and password in `application.properties`.

------------------------------------------------------------------------

## Running the Application

1.  Clone the repository:

``` bash
git clone https://github.com/birukbelay175-bit/capstone-3-ecommerce-api.git
```

2.  Open the project in IntelliJ IDEA.
3.  Create the MySQL database.
4.  Update `application.properties`.
5.  Run `ECommerceApplication.java`.
6.  Open Swagger:

`http://localhost:8080/swagger-ui/index.html`

------------------------------------------------------------------------

## Project Structure

-   controllers
-   models
-   repository
-   service
-   security
-   config

------------------------------------------------------------------------

## Testing

The API was tested using Swagger UI.

Verified functionality: - Product search - Categories - Shopping cart -
Profile - Checkout - Authentication

------------------------------------------------------------------------

## Author

**Biruk Tafese**

Year Up United -- Application Development

GitHub: https://github.com/birukbelay175-bit
oading README(2).md…]()

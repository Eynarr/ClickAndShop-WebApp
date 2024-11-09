# Click&Shop - E-Commerce Web Structure

This project is a non-functional prototype for an e-commerce platform, created as part of the coursework for **Software Programming II** and **Database II**. The purpose is to provide a structured web application that demonstrates database interactions using **JSP**, **HTML**, and **CSS**. The backend connects to a custom database to simulate data interactions for users, orders, products, and reviews.

> **Note**: This project is not a fully operational e-commerce platform. It serves as a foundational structure where product additions, shopping cart functionality, and purchasing transactions are not implemented. Instead, the database interaction showcases core data retrieval and manipulation features using JSP.

## Project Overview

Click&Shop offers a simulated e-commerce environment that enables basic user interaction with a pre-defined database. All operations depend on the database structure and stored procedures created specifically for this project. The backend utilizes a custom database schema built with **PL/SQL**.

### Features

- **User Registration**: Allows new users to create an account.
- **User Login**: Authenticates users through credentials.
- **Review Registration**: Allows users to submit reviews for products.
- **Product Query by ID**: Displays product details by ID.
- **Order Query by User**: Shows all orders associated with a logged-in user.
- **Payment Count by User**: Shows the total number of payments made by the user.
- **Inventory Query**: Lists available products with details such as ID, name, description, and price.
- **User Reviews**: Displays all reviews submitted by a specific user.

### Database Schema

The database is structured specifically for this project. Key tables include:

- **Vendedor**: Stores vendor information.
- **Categoria**: Stores product categories.
- **UsuarioComprador**: Stores user information.
- **Telefono**: Stores phone numbers.
- **Carrito**: Manages user shopping carts.
- **Orden**: Tracks user orders.
- **Pago**: Tracks user payments.
- **Producto**: Stores product details.
- **OrdenItem**: Stores items associated with each order.
- **Resenhas**: Stores user reviews for products.

### File Structure

Key files in this repository:

- **HTML Files**
  - `ConsultaInventario.html`: Inventory query page.
  - `ConsultaProductos.html`: Product query page.
  - `Home.html`: Homepage for Click&Shop.
  - `IniciarSesion.html`: Login page.
  - `registroUsuario.html`: User registration page.
  - `Sobre Nosotros.html`: About Us page.

- **JSP Files**
  - `cerrar_sesion.jsp`: Manages user logout.
  - `consulta_inventario.jsp`: Backend for inventory queries.
  - `consulta_ordenes.jsp`: Backend for order queries.
  - `consulta_pagos.jsp`: Backend for payment queries.
  - `consulta_productos.jsp`: Backend for product queries.
  - `consulta_resenhas.jsp`: Backend for user reviews.
  - `guardar_resenha.jsp`: Backend for saving reviews.
  - `ingresar_resenha.jsp`: Interface for submitting reviews.
  - `iniciar_sesion.jsp`: Manages user login.
  - `registrar_usuario.jsp`: Manages user registration.

- **CSS Files**
  - `Clickandshop.css`: Main stylesheet.
  - `styleCR.css`, `styleIS.css`, `styleRU.css`: Additional stylesheets.

- **SQL File**
  - `DB Prog.sql`: SQL script for setting up the database schema and initial data.

# Food Delivery API with FastAPI and PostgreSQL

## Overview 🍕

Welcome to the Food Delivery API, a delightful REST API for a Pizza delivery service. Built for fun and learning, it leverages FastAPI for speedy development, SQLAlchemy for efficient database interactions, and PostgreSQL for robust data storage.

## Routes to Implement 🚀

Here are the key routes that power the functionality of this API:

| METHOD | ROUTE                                  | FUNCTIONALITY                      | ACCESS        |
| ------ | --------------------------------------| ---------------------------------- | ------------- |
| POST   | `/auth/signup/`                        | Register new user                  | All users     |
| POST   | `/auth/jwt/create/`                    | Login user                         | All users     |
| POST   | `/auth/jwt/refresh/`                   | Refresh the access token           | All users     |
| POST   | `/auth/jwt/verify/`                    | Verify the validity of a token     | All users     |
| POST   | `/orders/`                             | Place an order                     | All users     |
| POST   | `/orders/`                             | Get all orders                     | All users     |
| GET    | `/order/{order_id}/`                   | Retrieve an order                  | Superuser     |
| PUT    | `/orders/{order_id}/`                  | Update an order                    | All users     |
| PUT    | `/update-status/{order_id}/`           | Update order status                | Superuser     |
| DELETE | `/delete/{order_id}/`                  | Delete/Remove an order              | All users     |
| GET    | `/user/{user_id}/orders/`              | Get user's orders                  | All users     |
| GET    | `/user/{user_id}/order/{order_id}/`    | Get user's specific order           | All users     |
| GET    | `/docs/`                               | View API documentation             | All users     |

## Features 🚀

### 1. User Authentication and Authorization 🎫

Secure your application with user authentication and authorization. The API supports user registration, login, and token-based access control to ensure that only authorized users can perform certain actions.

### 2. Order Placement and Management 🍕

Effortlessly place new orders and manage existing ones. Users can create new orders, update order details, and view their order history. Superusers have the ability to retrieve specific orders and update order statuses.

### 3. BLAZAR Token Django Integration 🔐

Enhance the security of your API with BLAZAR Token Django. Enjoy the benefits of JSON Web Token (JWT) integration, user authentication, and a token refresh mechanism for improved security and user management.

### 4. PostgreSQL Database Integration 🐘

Leverage the power of PostgreSQL for reliable and efficient data storage. The API utilizes SQLAlchemy to interact seamlessly with the PostgreSQL database, ensuring data integrity and scalability.

### 5. FastAPI Framework for Rapid Development ⚡

Built with FastAPI, this API emphasizes speed and efficiency in development. FastAPI's automatic interactive documentation, validation, and serialization make the development process smooth and enjoyable.

### 6. Extensive API Documentation 📚

Explore the API effortlessly with comprehensive documentation. The API is equipped with Swagger UI, allowing developers to understand and interact with endpoints directly through the user-friendly interface.

### 7. Easy Setup and Configuration 🛠️

Get started quickly with a simple setup process. The provided instructions guide you through creating a virtual environment, installing dependencies, and migrating the database, ensuring a hassle-free setup.

### 8. Open Source and Contributions Welcome 🙌

This project is open source, and contributions from the community are welcome! Fork the repository, create issues, and submit pull requests to make this Food Delivery API even better.

### 9. BLAZAR Token Django Documentation 📘

Explore the additional security features provided by BLAZAR Token Django through its detailed documentation. Learn how to integrate and configure BLAZAR Token Django to enhance authentication and user management.

### 10. User-Friendly App Preview 📸

Visit the GitHub repository to preview the application and explore its features visually. Star the repository if you find it useful, and feel free to provide feedback or ask questions.

Feel free to reach out for questions or feedback. Happy coding! 🎉


## About BLAZAR Token Django 🔥

Enhance the security and authentication of your Food Delivery API with BLAZAR Token Django. BLAZAR Token Django is a powerful authentication solution that integrates seamlessly with Django projects, providing a secure and efficient way to manage user authentication.

### Key Features:

- **JWT (JSON Web Token) Integration:** BLAZAR Token Django uses JWTs to secure user authentication, providing a stateless and scalable solution.

- **User Authentication and Authorization:** Easily manage user authentication and authorization with BLAZAR Token Django, ensuring that only authorized users can access protected routes.

- **Token Refresh Mechanism:** BLAZAR Token Django includes a token refresh mechanism, allowing users to obtain a new access token without requiring reauthentication.

- **Enhanced Security:** With BLAZAR Token Django, your API benefits from enhanced security measures, protecting against common authentication vulnerabilities.


# Getting Started 🚀

## How to Run the Application

1. Clone or download the project to your local machine.
2. Change directory to the "online-shop-django" folder.
3. Ensure that you have Python 3, pip, and virtualenv installed on your machine.
4. Create a virtual environment using the following command:
   - For Mac and Linux: `python3 -m venv venv`
   - For Windows: `python -m venv venv`
5. Activate the virtual environment:
   - For Mac and Linux: `source venv/bin/activate`
   - For Windows: `venv\scripts\activate`
6. Install the application requirements by running: `pip install -r requirements.txt`
7. Migrate the database by executing: `python manage.py migrate`
8. Start the server: `python manage.py runserver`
9. You should now be able to access the application by visiting: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
10. Finally run the API


Don't forget to star this repository 🌟 if you find it useful!

## Contributions Welcome! 🙌

We invite contributions from the open-source community to enhance this Django-powered Online Store. Fork the repository, create issues, and submit pull requests. Together, we can elevate online retail solutions.

Thank you for choosing our Online Store project. We hope it serves your business well! For questions or feedback, please don't hesitate to reach out.

## How to Contribute

I welcome contributions to enhance and customize this project. If you would like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make the necessary changes in your branch.
4. Test your changes thoroughly.
5. Commit your changes and push them to your forked repository.
6. Submit a pull request, clearly describing the changes you have made.

## App Preview


🌐 Visit our [GitHub Repository](https://github.com/mohamadSaleh82/Food-Delivery-API)

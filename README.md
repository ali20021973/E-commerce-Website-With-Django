# E-commerce Website Project with Django and Vue

This project is a comprehensive guide to building a modern e-commerce website using Django and Vue.js. It covers setting up a RESTful API using Django Rest Framework for the backend and a separate Vue project for the frontend. For payment processing, the Stripe API is integrated.

## Project Overview

This e-commerce application includes features such as:

- Product catalog and detail views
- Category filtering
- Search functionality
- Shopping cart management
- User authentication (sign-up, login, account management)
- Order processing and checkout with Stripe
- Order history and user profile pages

## Technologies Used

- **Django**: A Python-based web framework used for the backend of the application.
- **Django Rest Framework (DRF)**: Used to create a RESTful API.
- **Vue.js**: A progressive JavaScript framework used for building the frontend application.
- **Stripe API**: Used for handling payments.

## Live Demo

Check out the [Live Demo](https://djackets.codewithstein.com/).

## Installation and Setup

### Backend (Django)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. Create a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Run the server:
    ```bash
    python manage.py runserver
    ```

### Frontend (Vue.js)

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm run serve
    ```

## Features

### Basic Features

- **Product Listing**: View all products with pagination and sorting.
- **Product Detail**: View details of a single product.
- **Shopping Cart**: Add products to the cart, view and modify cart contents.
- **User Authentication**: Register and login to manage orders and profile.
- **Order History**: View past orders and order details.
- **Payment Processing**: Securely process payments using Stripe.

### Advanced Features

- **Category View**: Browse products by category.
- **Search**: Search products by name or description.
- **Checkout Process**: Complete orders with a simple checkout flow.

## Deployment

### Deploy Django

1. Deploy the Django backend using your preferred method (e.g., Docker, Heroku).
2. Set up a production server with appropriate configurations.

### Deploy Vue

1. Build the Vue application:
    ```bash
    npm run build
    ```

2. Deploy the build files to your web server.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## License

This project is open source and available under the [MIT License](LICENSE).


# E-Commerce API

## Description
A Django Rest Framework-based API for an e-commerce platform that allows users to register as buyers or sellers, manage products, handle payments via Paystack, and performpayment distribution to sellers.

## Features
- User Authentication (Buyer/Seller)
- Product management
- Paystack Integration for Payments
- Order tracking
- Notifications for orders

## Installation
1. Clone the repository: 
2. Install dependencies: `pip install -r requirements.txt`
3. Set environment variables: `PAYSTACK_SECRET_KEY=your_key`
4. Run database migrations: `python manage.py migrate`
5. Start the server: `python manage.py runserver`

## API Endpoints
- **POST /api/products/**: Create a product (Seller)
- **GET /api/products/**: List products (Buyer)
- **POST /api/checkout/**: Checkout and initiate payment (Buyer)

## Testing
To run tests: `python manage.py test`

## License
This project is licensed under the MIT License.

## Contact
Created by [Your Name](https://yourwebsite.com).

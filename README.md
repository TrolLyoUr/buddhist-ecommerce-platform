# Buddhist E-Commerce Platform

## **Overview**

The **Buddhist E-Commerce Platform** is a comprehensive online store tailored for the Taiwanese market, specializing in Buddhist products such as statues, incense, and books. This platform is built using modern technologies to ensure scalability, security, and an excellent user experience.

## **Features**

- **User Management**
  - Account registration with email and social logins (Google, Facebook, Line)
  - Secure authentication and authorization using AWS Cognito
  - User profiles with personal information and shipping address management

- **Product Management**
  - Dynamic product listings with images, descriptions, prices, and stock status
  - Categorization for easy navigation
  - Detailed product pages with dimensions and materials

- **Shopping Cart & Checkout**
  - Add, remove, and update product quantities in the cart
  - Persistent cart for logged-in users
  - Multiple shipping options and payment methods (Bank Transfer, Cash on Delivery)

- **Order Management**
  - Order history and real-time tracking
  - Order confirmation via email

- **Admin Panel**
  - Manage products, categories, and orders
  - User account management
  - Basic analytics and reporting

- **Localization**
  - Support for Traditional Chinese and English languages
  - Culturally relevant content and imagery

- **Security & Compliance**
  - Data encryption in transit and at rest
  - PCI DSS compliance for payment processing
  - Protection against common vulnerabilities (SQL injection, XSS)

## **Tech Stack**

- **Frontend:** Angular, TypeScript, Apollo Angular (GraphQL)
- **Backend:** Node.js, TypeScript, Apollo Server (GraphQL)
- **Database:** AWS DynamoDB
- **Cloud Services:** AWS Lambda, AWS API Gateway, Amazon S3, AWS Cognito
- **Payment Integration:** Line Pay (Future Implementation), Bank Transfer, Cash on Delivery




# Deployment
The application is designed to be deployed using AWS services. Detailed deployment instructions are available in the DEPLOYMENT.md file.

# License
This project is licensed under the MIT License.

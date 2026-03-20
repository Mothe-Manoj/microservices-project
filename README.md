# Microservices Project Architecture

This document describes the architecture of the Microservices Project, detailing the various components and services involved.

## Infra-Steps
1. **Provisioning Infrastructure**: Set up cloud resources needed for deployment.
2. **Networking Setup**: Configure necessary network routes and security groups.
3. **Service Deployment**: Deploy each service to the cloud environment.
4. **Monitoring**: Implement logging and monitoring for all services.

## Services

### Ad Service
- Manages advertisements.
- Responsible for serving ads to users and tracking their performance.

### Cart Service
- Handles shopping cart operations.
- Maintains user's shopping cart session and integrates with other services to fetch product info.

### Checkout Service
- Manages the checkout process.
- Integrates with payment and cart services for a seamless user experience.

### Currency Service
- Provides real-time currency conversion.
- Handles multiple currencies for transactions.

### Email Service
- Responsible for sending emails.
- Manages notifications, alerts, and marketing emails.

### Frontend
- User interface for the microservices.
- Connects with backend services to display information to users.

### Load Generator
- Simulates user traffic to test the performance of services.
- Ensures that the architecture can handle a high load.

### Payment Service
- Processes payment transactions.
- Integrates with the checkout service and handles payment gateways.

### Product Catalog Service
- Manages product listings and details.
- Responsible for inventory management and product availability.

### Recommendation Service
- Provides product recommendations to users based on their behavior.
- Enhances user engagement and sales outcomes.

### Shipping Service
- Handles shipping logistics.
- Integrates with various shipping providers to track orders.

Each service operates independently to enhance modularity, scalability, and maintainability of the system.

<img width="1387" height="768" alt="image_96578c16" src="https://github.com/user-attachments/assets/96d83f6b-e8bc-45d6-8210-3e3966bfbf38" />


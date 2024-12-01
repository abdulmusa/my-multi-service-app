# my-multi-service-app
E-Commerce app that allows user to register, choose product and make an order.
Documentation
Setup Process:

Clone the repository.

Navigate to the root directory where the docker-compose.yml file is located.

Build and start the services using Docker Compose:

sh
docker-compose up --build
Access the services via their respective endpoints:

Product Service: http://localhost:5002/products

Order Service: http://localhost:5003/orders

User Service: http://localhost:5004/register and http://localhost:5004/login

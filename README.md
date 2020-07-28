# Project Intro
This project contains the infrastructure of the Ecommerce system.


Ecommerce Project includes：

|Repo|Purpose|Link|
| --- | --- | --- |
|ecommerce-order-service|Order service|[https://github.com/e-commerce-mock/ecommerce-order-service](https://github.com/e-commerce-mock/ecommerce-order-service)|
|ecommerce-order-query-service|Order query service|[https://github.com/e-commerce-mock/ecommerce-order-query-service](https://github.com/e-commerce-mock/ecommerce-order-query-service)|
|ecommerce-product-service|Product service|[https://github.com/e-commerce-mock/ecommerce-product-service](https://github.com/e-commerce-mock/ecommerce-product-service)|
|ecommerce-inventory-service|Inventory service|[https://github.com/e-commerce-mock/ecommerce-inventory-service](https://github.com/e-commerce-mock/ecommerce-inventory-service)|
|ecommerce-shared-model|Pure Shared model without Spring context|[https://github.com/e-commerce-mock/ecommerce-shared-model](https://github.com/e-commerce-mock/ecommerce-shared-model)|
|ecommerce-spring-common|Shared basic Spring configuration|[https://github.com/e-commerce-mock/ecommerce-spring-common](https://github.com/e-commerce-mock/ecommerce-spring-common)|
|ecommerce-devops|Infrastructure|[https://github.com/e-commerce-mock/ecommerce-devops](https://github.com/e-commerce-mock/ecommerce-devops)|

# Tech stacks
Spring Boot、Gradle、MySQL、Junit 5、Rest Assured、Docker、RabbitMQ、Ansible

# Directory Structure
- `local` mainly includes the infrastructure needed for the local development process, such as RabbitMQ and ELK, which are all started on the local machine through Docker.
- `remote` is mainly used for the infrastructure required by the production environment, mainly for the deployment scenario of "virtual machine + Docker", using the Vagrant virtual machine locally.


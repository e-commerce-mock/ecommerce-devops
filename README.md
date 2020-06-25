# 项目简介
该项目包含Ecommerce项目的基础设施。


Ecommerce项目包括：

|代码库|用途|地址|
| --- | --- | --- |
|order-backend|Order服务|[https://github.com/e-commerce-mock/order-backend](https://github.com/e-commerce-mock/order-backend)|
|product-backend|Product服务|[https://github.com/e-commerce-mock/product-backend](https://github.com/e-commerce-mock/product-backend)|
|inventory-backend|Inventory服务|[https://github.com/e-commerce-mock/inventory-backend](https://github.com/e-commerce-mock/inventory-backend)|
|common|共享依赖包|[https://github.com/e-commerce-mock/common](https://github.com/e-commerce-mock/common)|
|devops|基础设施|[https://github.com/e-commerce-mock/devops](https://github.com/e-commerce-mock/devops)|

# 技术选型
Spring Boot、Gradle、MySQL、Junit 5、Rest Assured、Docker、RabbitMQ、Ansible

# 目录结构
- local主要包含本地开发过程所需要用到的基础设施，比如RabbitMQ和ELK等，均通过Docker在本地机器启动。
- remote主要用于生产环境所需的基础设施，主要针对"虚拟机+Docker"的部署场景，本地使用Vagrant虚拟机。


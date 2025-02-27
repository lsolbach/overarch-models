# Order Service (Container)
## Description
Handles orders

## Technology
Java, Spring Boot

## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Shop Frontend](../../../../software-development/architecture/example/microservices/shop-frontend.md) | calls | [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) |  | get products, place orders |
| [Shopping Cart Service](../../../../software-development/architecture/example/microservices/shopping-cart-service.md) | request | [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | REST | Create Order |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | request | [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | REST | Payment for Order |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | request | [Notification Service](../../../../software-development/architecture/example/microservices/notification-service.md) | REST | Notify Customer |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | store | [Order Database](../../../../software-development/architecture/example/microservices/order-db.md) | JDBC | Order Data |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | request | [Shipping Service](../../../../software-development/architecture/example/microservices/shipping-service.md) | REST | Ship Order |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | request | [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | REST | Update Inventory |

### Asynchronous Publish/Subscribe Interfaces

#### Publishing/Producing
| From | Name | To Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | publish | [Order Topic](../../../../software-development/architecture/example/microservices/order-topic.md) | Kafka | OrderProcessedEvent, OrderCancelledEvent |

#### Subscribing/Consuming
| From | Name | Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | subscribe | [Payment Topic](../../../../software-development/architecture/example/microservices/payment-topic.md) | Kafka | PaymentProcessedEvent, PaymentFailedEvent |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | subscribe | [Shipping Topic](../../../../software-development/architecture/example/microservices/shipping-topic.md) | Kafka | ShippingProcessedEvent, ShippingFailedEvent |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | subscribe | [Shopping Cart Topic](../../../../software-development/architecture/example/microservices/shopping-cart-topic.md) | Kafka | ShoppingCartOrderedEvent |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)

### Tags
microservice, simple


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

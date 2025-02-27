# Payment Service (Container)
## Description
Handles payments

## Technology
Kotlin, Quarkus

## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | request | [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | REST | Payment for Order |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | request | [Account Service](../../../../software-development/architecture/example/microservices/account-service.md) | REST | Payment Data |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | request | [Payment System](../../../../software-development/architecture/example/microservices/payment-system.md) | REST | Trigger Payment |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | store | [Payment DB](../../../../software-development/architecture/example/microservices/payment-db.md) | JDBC | Payment Data |

### Asynchronous Publish/Subscribe Interfaces

#### Publishing/Producing
| From | Name | To Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | publish | [Payment Topic](../../../../software-development/architecture/example/microservices/payment-topic.md) | Kafka | PaymentProcessedEvent, PaymentFailedEvent |

#### Subscribing/Consuming
| From | Name | Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | subscribe | [Inventory Topic](../../../../software-development/architecture/example/microservices/inventory-topic.md) | Kafka | InventoryOutOfStockEvent |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | subscribe | [Account Topic](../../../../software-development/architecture/example/microservices/account-topic.md) | Kafka | AccountCreatedEvent, AccountUpdatedEvent, AccountDeactivatedEvent |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | subscribe | [Shopping Cart Topic](../../../../software-development/architecture/example/microservices/shopping-cart-topic.md) | Kafka | ShoppingCartOrderedEvent |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | subscribe | [Shipping Topic](../../../../software-development/architecture/example/microservices/shipping-topic.md) | Kafka | ShippingFailedEvent |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | subscribe | [Inventory Topic](../../../../software-development/architecture/example/microservices/inventory-topic.md) | Kafka | InventoryProcessedEvent |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)

### Tags
microservice, simple


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

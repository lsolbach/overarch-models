# Account Service (Container)
## Description
Handles user accounts

## Technology


## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | request | [Account Service](../../../../software-development/architecture/example/microservices/account-service.md) | REST | Payment Data |
| [Notification Service](../../../../software-development/architecture/example/microservices/notification-service.md) | request | [Account Service](../../../../software-development/architecture/example/microservices/account-service.md) | REST | Email for Account |
| [Shipping Service](../../../../software-development/architecture/example/microservices/shipping-service.md) | request | [Account Service](../../../../software-development/architecture/example/microservices/account-service.md) | REST | Account Address |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Account Service](../../../../software-development/architecture/example/microservices/account-service.md) | store | [Account Database](../../../../software-development/architecture/example/microservices/account-db.md) | JDBC | Account Data |

### Asynchronous Publish/Subscribe Interfaces

#### Publishing/Producing
| From | Name | To Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Account Service](../../../../software-development/architecture/example/microservices/account-service.md) | publish | [Account Topic](../../../../software-development/architecture/example/microservices/account-topic.md) | Kafka | AccountCreatedEvent, AccountUpdatedEvent, AccountDeactivatedEvent |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)

### Tags
advanced, microservice


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

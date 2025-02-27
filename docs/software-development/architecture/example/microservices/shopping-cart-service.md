# Shopping Cart Service (Container)
## Description
Handles the shopping cart

## Technology


## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Interfaces

### Synchronous Interfaces

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Shopping Cart Service](../../../../software-development/architecture/example/microservices/shopping-cart-service.md) | store | [Shopping Cart Database](../../../../software-development/architecture/example/microservices/shopping-cart-db.md) | MongoDB | Shopping Cart Data |
| [Shopping Cart Service](../../../../software-development/architecture/example/microservices/shopping-cart-service.md) | request | [Product Catalog Service](../../../../software-development/architecture/example/microservices/product-catalog-service.md) | REST | Product Data |
| [Shopping Cart Service](../../../../software-development/architecture/example/microservices/shopping-cart-service.md) | request | [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | REST | Create Order |

### Asynchronous Publish/Subscribe Interfaces

#### Publishing/Producing
| From | Name | To Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Shopping Cart Service](../../../../software-development/architecture/example/microservices/shopping-cart-service.md) | publish | [Shopping Cart Topic](../../../../software-development/architecture/example/microservices/shopping-cart-topic.md) | Kafka | ShoppingCartOrderedEvent |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)

### Tags
advanced, microservice


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

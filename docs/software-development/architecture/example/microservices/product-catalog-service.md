# Product Catalog Service (Container)
## Description
Handles the product catalog

## Technology
Java, Spring Boot

## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Shopping Cart Service](../../../../software-development/architecture/example/microservices/shopping-cart-service.md) | request | [Product Catalog Service](../../../../software-development/architecture/example/microservices/product-catalog-service.md) | REST | Product Data |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Product Catalog Service](../../../../software-development/architecture/example/microservices/product-catalog-service.md) | request | [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | REST | Check Inventory |
| [Product Catalog Service](../../../../software-development/architecture/example/microservices/product-catalog-service.md) | store | [Product Catalog Database](../../../../software-development/architecture/example/microservices/product-catalog-db.md) | MongoDB | Product Catalog |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)

### Tags
advanced, microservice


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

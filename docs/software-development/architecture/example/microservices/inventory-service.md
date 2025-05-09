
# Inventory Service (Container)
## Description
Handles inventory

## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Technology
Java, Spring Boot

## Tags
microservice, simple
## Incoming Synchronous Requests 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Product Catalog Service](../../../../software-development/architecture/example/microservices/product-catalog-service.md) | request | [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | REST | Check Inventory |
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | request | [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | REST | Update Inventory |
## Outgoing Synchronous Requests 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | store | [Inventory Database](../../../../software-development/architecture/example/microservices/inventory-db.md) | JDBC | Inventory Data |
## Outgoing Asynchronous Publish/Produce
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | publish | [Inventory Topic](../../../../software-development/architecture/example/microservices/inventory-topic.md) | Kafka | InventoryProcessedEvent, InventoryOutOfStockEvent |
## Outgoing Asynchronous Subscribe/Consume
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | subscribe | [Order Topic](../../../../software-development/architecture/example/microservices/order-topic.md) | Kafka | OrderProcessedEvent, OrderCancelledEvent |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

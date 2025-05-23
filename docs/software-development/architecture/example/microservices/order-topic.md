
# Order Topic (Container)
## Description
Order Events

## Parent
[Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md)

## Technology
Kafka

## Tags
event-driven, simple
## Incoming Asynchronous Publish/Produce 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Service](../../../../software-development/architecture/example/microservices/order-service.md) | publish | [Order Topic](../../../../software-development/architecture/example/microservices/order-topic.md) | Kafka | OrderProcessedEvent, OrderCancelledEvent |
## Incoming Asynchronous Subscribe/Consume 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Inventory Service](../../../../software-development/architecture/example/microservices/inventory-service.md) | subscribe | [Order Topic](../../../../software-development/architecture/example/microservices/order-topic.md) | Kafka | OrderProcessedEvent, OrderCancelledEvent |
| [Notification Service](../../../../software-development/architecture/example/microservices/notification-service.md) | subscribe | [Order Topic](../../../../software-development/architecture/example/microservices/order-topic.md) | Kafka | OrderProcessedEvent, OrderCancelledEvent |

## Container View
![Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.png)

[Container view for the Microservices example](../../../../software-development/architecture/example/microservices/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

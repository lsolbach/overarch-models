
# Payment System (System)
## Description
Handles Credit Card, PayPal, etc.


## Tags
simple

## Documentation
This is an external payment system that is used by the online shop system.
## Incoming Synchronous Requests 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md) |  | [Payment System](../../../../software-development/architecture/example/microservices/payment-system.md) |  | calls |
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | request | [Payment System](../../../../software-development/architecture/example/microservices/payment-system.md) | REST | Trigger Payment |

## System Context View
![Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.png)

[Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

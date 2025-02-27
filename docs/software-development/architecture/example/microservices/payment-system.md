# Payment System (System)
## Description
Handles Credit Card, PayPal, etc.

## Technology


## Documentation
This is an external payment system that is used by the online shop system.

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Payment Service](../../../../software-development/architecture/example/microservices/payment-service.md) | request | [Payment System](../../../../software-development/architecture/example/microservices/payment-system.md) | REST | Trigger Payment |
| [Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md) |  | [Payment System](../../../../software-development/architecture/example/microservices/payment-system.md) |  | calls |

## System Context View
![Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.png)

[Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.md)

### Tags
simple


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

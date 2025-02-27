# Payment System (System)
## Description
Handles Credit Card, PayPal, etc.

## Technology



## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md) | trigger payment | [Payment System](../../../../software-development/architecture/example/monolith/payment-system.md) | REST | credit card, paypal |
| [Online Shop Backend Application](../../../../software-development/architecture/example/monolith/online-shop-backend.md) | process payment | [Payment System](../../../../software-development/architecture/example/monolith/payment-system.md) | REST | credit card, paypal |

## System Context View
![Context view for the Online Shop Monolith example](../../../../software-development/architecture/example/monolith/context-view.png)

[Context view for the Online Shop Monolith example](../../../../software-development/architecture/example/monolith/context-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

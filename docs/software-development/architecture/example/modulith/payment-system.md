# Payment System (System)
## Description
Handles Credit Card, PayPal, etc.

## Technology



## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | trigger payment | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | credit card, paypal |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | process payment | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | credit card, paypal |
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | calls | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | process payment |

## System Context View
![Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.png)

[Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

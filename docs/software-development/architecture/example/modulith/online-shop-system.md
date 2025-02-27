# Online Shop (System)
## Description
An online shop system that sells products to customers.

## Technology


## Containers
These containers are the main processes of the Online Shop system.

| Container | Description |
|---|---|
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md)|  |
| [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md)| Stores products, orders, payments, etc. |
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md)|  |

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Customer](../../../../software-development/architecture/example/modulith/customer.md) | uses | [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | HTTPS | browse products, place orders |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | trigger payment | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | credit card, paypal |
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | sends email | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) |  | order confirmation, shipping notification |
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | ship | [Logistics System](../../../../software-development/architecture/example/modulith/logistics-system.md) | REST | products |

## System Context View
![Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.png)

[Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

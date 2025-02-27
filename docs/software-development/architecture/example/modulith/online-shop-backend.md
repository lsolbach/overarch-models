# Online Shop Backend Application (Container)
## Description


## Technology
Java EE

## Parent
[Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md)

## Subdomains/Bounded Contexts
The system consists of different subdomains which have been structured into bounded contexts

| Bounded Context | Description |
|---|---|
| [Inventory Context](../../../../software-development/architecture/example/modulith/inventory.md) |  |
| [Orders Context](../../../../software-development/architecture/example/modulith/orders.md) |  |
| [Payment Context](../../../../software-development/architecture/example/modulith/payment.md) |  |
| [Shipping Context](../../../../software-development/architecture/example/modulith/shipping.md) |  |

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | HTTPS | get products, place orders. |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | ship | [Logistics System](../../../../software-development/architecture/example/modulith/logistics-system.md) | REST | order |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | process payment | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | credit card, paypal |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | sends email | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) |  | order confirmation, shipping notification |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | products, orders |

## Container View
![Container view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/container-view.png)

[Container view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

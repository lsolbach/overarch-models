# Online Shop Backend Application (Container)
## Description


## Technology
Java EE

## Parent
[Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop Frontend Application](../../../../software-development/architecture/example/monolith/online-shop-frontend.md) | calls | [Online Shop Backend Application](../../../../software-development/architecture/example/monolith/online-shop-backend.md) | HTTPS | get products, place orders. |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop Backend Application](../../../../software-development/architecture/example/monolith/online-shop-backend.md) | sends email | [Email System](../../../../software-development/architecture/example/monolith/email-system.md) |  | order confirmation, shipping notification |
| [Online Shop Backend Application](../../../../software-development/architecture/example/monolith/online-shop-backend.md) | process payment | [Payment System](../../../../software-development/architecture/example/monolith/payment-system.md) | REST | credit card, paypal |
| [Online Shop Backend Application](../../../../software-development/architecture/example/monolith/online-shop-backend.md) | ship | [Logistics System](../../../../software-development/architecture/example/monolith/logistics-system.md) | REST | order |
| [Online Shop Backend Application](../../../../software-development/architecture/example/monolith/online-shop-backend.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/monolith/online-shop-db.md) | JDBC | products, orders |

## Container View
![Container view for the Online Shop Monolith example](../../../../software-development/architecture/example/monolith/container-view.png)

[Container view for the Online Shop Monolith example](../../../../software-development/architecture/example/monolith/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

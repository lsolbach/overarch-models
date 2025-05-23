# Context view for the Online Shop Monolith example

## Diagram
![Context view for the Online Shop Monolith example](../../../../software-development/architecture/example/monolith/context-view.png)

## Description
Shows the systems of the Online Shop Monolith example and their relations

## Roles
| Person/Role | Description |
|---|---|
| [Customer](../../../../software-development/architecture/example/monolith/customer.md)| A customer who buys products from the online shop. |

## Systems
| System | Description |
|---|---|
| [Email System](../../../../software-development/architecture/example/monolith/email-system.md)| Sends Emails e.g. to customers |
| [Logistics System](../../../../software-development/architecture/example/monolith/logistics-system.md)| Handles shipping with DHL, UPS, etc. |
| [Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md)| An online shop system that sells products to customers. |
| [Payment System](../../../../software-development/architecture/example/monolith/payment-system.md)| Handles Credit Card, PayPal, etc. |

## Synchronous Requests
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md) | sends email | [Email System](../../../../software-development/architecture/example/monolith/email-system.md) |  | order confirmation, shipping notification |
| [Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md) | ship | [Logistics System](../../../../software-development/architecture/example/monolith/logistics-system.md) | REST | products |
| [Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md) | trigger payment | [Payment System](../../../../software-development/architecture/example/monolith/payment-system.md) | REST | credit card, paypal |
| [Customer](../../../../software-development/architecture/example/monolith/customer.md) | uses | [Online Shop](../../../../software-development/architecture/example/monolith/online-shop-system.md) | HTTPS | browse products, place orders |

## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/view.md.cmb)


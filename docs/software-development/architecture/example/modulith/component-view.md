# Component view for the Online Shop Modulith example

## Diagram
![Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.png)

## Description
Shows the components of the Online Shop Modulith example and their relations

## Roles
| Person/Role | Description |
|---|---|
| [Customer](../../../../software-development/architecture/example/modulith/customer.md)| A customer who buys products from the online shop. |

## Systems
| System | Description |
|---|---|
| [Email System](../../../../software-development/architecture/example/modulith/email-system.md)| Sends Emails e.g. to customers |
| [Logistics System](../../../../software-development/architecture/example/modulith/logistics-system.md)| Handles shipping with DHL, UPS, etc. |
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md)| An online shop system that sells products to customers. |
| [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md)| Handles Credit Card, PayPal, etc. |

## Containers
| Container | Description |
|---|---|
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md)|  |
| [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md)| Stores products, orders, payments, etc. |
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md)|  |

## Components
| Component | Description |
|---|---|
| [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md)| Handles the inventory checks and updates |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md)| Handles the orders |
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md)| Handles the payment process |
| [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md)| Handles the shipping process |

## Synchronous Requests
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | Method Call | trigger shipping |
| [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | calls | [Logistics System](../../../../software-development/architecture/example/modulith/logistics-system.md) | REST | process shipping |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md) | Method Call | update inventory |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | Method Call | trigger payment |
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | calls | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | process payment |
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | HTTPS | shipping status |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) | SMTP | send order confirmation |
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | HTTPS | get products, place orders |
| [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | products |
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | payments |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | orders |
| [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | shipping status |
| [Customer](../../../../software-development/architecture/example/modulith/customer.md) | uses | [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | HTTPS | browse products, place orders |

## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/views/view.md.cmb)


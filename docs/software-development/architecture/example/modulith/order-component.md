# Order Component (Component)
## Description
Handles the orders

## Technology


## Parent
[Orders Context](../../../../software-development/architecture/example/modulith/orders.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | HTTPS | get products, place orders |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | Method Call | trigger shipping |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md) | Method Call | update inventory |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | Method Call | trigger payment |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | orders |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) | SMTP | send order confirmation |

## Component View
![Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.png)

[Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

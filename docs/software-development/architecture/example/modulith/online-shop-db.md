# Online Shop Database (Container)
## Description
Stores products, orders, payments, etc.

## Technology
DB/2

## Parent
[Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | products |
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | payments |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | orders |
| [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | shipping status |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | products, orders |

## Container View
![Container view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/container-view.png)

[Container view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)


# Payment Component (Component)
## Description
Handles the payment process

## Parent
[Payment Context](../../../../software-development/architecture/example/modulith/payment.md)
## Incoming Synchronous Requests 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | Method Call | trigger payment |
## Outgoing Synchronous Requests 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | calls | [Payment System](../../../../software-development/architecture/example/modulith/payment-system.md) | REST | process payment |
| [Payment Component](../../../../software-development/architecture/example/modulith/payment-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | payments |

## Component View
![Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.png)

[Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

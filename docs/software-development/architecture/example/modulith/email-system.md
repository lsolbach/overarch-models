
# Email System (System)
## Description
Sends Emails e.g. to customers

## Incoming Synchronous Requests 
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) | SMTP | send order confirmation |
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | sends email | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) |  | order confirmation, shipping notification |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | sends email | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) |  | order confirmation, shipping notification |

## System Context View
![Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.png)

[Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

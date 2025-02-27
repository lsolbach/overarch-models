# Email System (System)
## Description
Sends Emails e.g. to customers

## Technology



## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md) | sends email | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) |  | order confirmation, shipping notification |
| [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | sends email | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) |  | order confirmation, shipping notification |
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Email System](../../../../software-development/architecture/example/modulith/email-system.md) | SMTP | send order confirmation |

## System Context View
![Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.png)

[Context view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/context-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

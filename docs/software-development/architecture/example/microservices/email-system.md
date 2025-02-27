# Email System (System)
## Description
Sends Emails e.g. to customers

## Technology


## Documentation
This is an external email system that is used by the online shop system.

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Notification Service](../../../../software-development/architecture/example/microservices/notification-service.md) | request | [Email System](../../../../software-development/architecture/example/microservices/email-system.md) | SMTP | Send Email |
| [Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md) |  | [Email System](../../../../software-development/architecture/example/microservices/email-system.md) | SMTP | calls |

## System Context View
![Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.png)

[Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.md)

### Tags
simple


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

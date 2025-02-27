# Logistics System (System)
## Description
Handles shipping with DHL, UPS, etc.

## Technology


## Documentation
This is an external logistics system that is used by the online shop
system to handle the actual shipping with companies like DHL or UPS.

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Shipping Service](../../../../software-development/architecture/example/microservices/shipping-service.md) | request | [Logistics System](../../../../software-development/architecture/example/microservices/logistics-system.md) | REST | Ship Order |
| [Online Shop](../../../../software-development/architecture/example/microservices/online-shop.md) |  | [Logistics System](../../../../software-development/architecture/example/microservices/logistics-system.md) |  | calls |

## System Context View
![Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.png)

[Context view for the Microservices example](../../../../software-development/architecture/example/microservices/context-view.md)

### Tags
advanced


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

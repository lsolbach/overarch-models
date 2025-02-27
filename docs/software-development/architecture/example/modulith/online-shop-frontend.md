# Online Shop Frontend Application (Container)
## Description


## Technology
AngularJS

## Parent
[Online Shop](../../../../software-development/architecture/example/modulith/online-shop-system.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Customer](../../../../software-development/architecture/example/modulith/customer.md) | uses | [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | HTTPS | browse products, place orders |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Shipping Component](../../../../software-development/architecture/example/modulith/shipping-component.md) | HTTPS | shipping status |
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Online Shop Backend Application](../../../../software-development/architecture/example/modulith/online-shop-backend.md) | HTTPS | get products, place orders. |
| [Online Shop Frontend Application](../../../../software-development/architecture/example/modulith/online-shop-frontend.md) | calls | [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | HTTPS | get products, place orders |

## Container View
![Container view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/container-view.png)

[Container view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

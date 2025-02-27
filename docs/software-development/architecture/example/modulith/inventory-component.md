# Inventory Component (Component)
## Description
Handles the inventory checks and updates

## Technology


## Parent
[Inventory Context](../../../../software-development/architecture/example/modulith/inventory.md)

## Interfaces

### Synchronous Interfaces

#### Provided Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Order Component](../../../../software-development/architecture/example/modulith/order-component.md) | calls | [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md) | Method Call | update inventory |

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Inventory Component](../../../../software-development/architecture/example/modulith/inventory-component.md) | store and query | [Online Shop Database](../../../../software-development/architecture/example/modulith/online-shop-db.md) | JDBC | products |

## Component View
![Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.png)

[Component view for the Online Shop Modulith example](../../../../software-development/architecture/example/modulith/component-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)

(generated with docs/architecture-node.md.cmb)

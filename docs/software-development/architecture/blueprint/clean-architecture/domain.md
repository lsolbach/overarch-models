# domain (Package)

# Description
Contains the domain core of the component

## Documentation
The domain package contains the domain core of the component. It contains the
domain model, domain services, and domain events. The domain core is implemented
completely functional and is independent of any other layer.

## Classes
| Name | Description |
|---|---|
|[DomainAggregate](../../../../software-development/architecture/blueprint/clean-architecture/domain/domain-aggregate.md)|The root of a graph of domain entities and domain values with constency rules spanning the whole graph|
|[DomainEntity](../../../../software-development/architecture/blueprint/clean-architecture/domain/domain-entity.md)|Represents a domain object with an identity|
|[DomainEvent](../../../../software-development/architecture/blueprint/clean-architecture/domain/domain-event.md)|Represents a relevant event that happened in the domain|
|[DomainService](../../../../software-development/architecture/blueprint/clean-architecture/domain/domain-service.md)|Implements the domain logic that is not the responsibility of a domain object.|
|[DomainValue](../../../../software-development/architecture/blueprint/clean-architecture/domain/domain-value.md)|Represents a domain object without an identity|


## Navigation
[List of views in namespace](./views-in-namespace.md)
[List of all Views](../../../../views.md)

(generated with docs/package.md.cmb)

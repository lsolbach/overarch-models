# Concept Map of the Domain Driven Design Building Blocks Patterns

## Diagram
![Concept Map of the Domain Driven Design Building Blocks Patterns](../../../software-development/domain-driven-design/building-blocks/concept-view.png)

## Description
Shows the building block patterns and their relationships.

## Concepts
| Concept | Description |
|---|---|
| [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md)| Aggregates are collections of entities and value objects with their associations and form a transactional unit. Aggregates are referenced as a whole by an aggregate root entity, parts of the aggregate must not be referenced from outside. The aggregate root is responsible for the enforcement of the busines rules and invariants of the aggregate. |
| [Domain Events](../../../software-development/domain-driven-design/building-blocks/c-domain-events.md)| A domain object to propagate relevant domain activities in a distributed system. |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md)| Objects in the domain model which are defined by their identity rather than by their state. For example a Person is normally modelled as an entity. It represents the same person even when the attributes change. It is also a different person, even if it has the same state as another person. |
| [Factories](../../../software-development/domain-driven-design/building-blocks/c-factories.md)| A domain object for the creation of complex domain objects which enforce the invariants of these objects on creation. |
| [Model Driven Design](../../../software-development/domain-driven-design/modelling/c-model-driven-design.md)|  |
| [Modules](../../../software-development/domain-driven-design/building-blocks/c-modules.md)|  |
| [Repositories](../../../software-development/domain-driven-design/building-blocks/c-repositories.md)| Query access to aggregates expressed in the ubiquitous language |
| [Services](../../../software-development/domain-driven-design/building-blocks/c-services.md)| contains functionality which is not the responsiblity of an entity or value object |
| [Value Objects](../../../software-development/domain-driven-design/building-blocks/c-value-objects.md)| An object in the domain model, which has no conceptional identity but are identified by their state. Value objects should be modelled as immutable. |

## Other Relationships
| From | Name | To | Description |
|---|---|---|---|
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | access with | [Repositories](../../../software-development/domain-driven-design/building-blocks/c-repositories.md) |  |
| [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) | access with | [Repositories](../../../software-development/domain-driven-design/building-blocks/c-repositories.md) |  |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | act as root of | [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | encapsulate with | [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Value Objects](../../../software-development/domain-driven-design/building-blocks/c-value-objects.md) | encapsulate with | [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Value Objects](../../../software-development/domain-driven-design/building-blocks/c-value-objects.md) | encapsulate with | [Factories](../../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | encapsulate with | [Factories](../../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |
| [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) | encapsulate with | [Factories](../../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |
| [Model Driven Design](../../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express change with | [Domain Events](../../../software-development/domain-driven-design/building-blocks/c-domain-events.md) |  |
| [Model Driven Design](../../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express identity with | [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) |  |
| [Model Driven Design](../../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express model with | [Services](../../../software-development/domain-driven-design/building-blocks/c-services.md) |  |
| [Model Driven Design](../../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express state and computation with | [Value Objects](../../../software-development/domain-driven-design/building-blocks/c-value-objects.md) |  |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | push state change with | [Domain Events](../../../software-development/domain-driven-design/building-blocks/c-domain-events.md) |  |

## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/view.md.cmb)


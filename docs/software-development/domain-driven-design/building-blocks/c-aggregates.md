
# Aggregates (Concept)
## Description
Aggregates are collections of entities and value objects with their
  associations and form a transactional unit. Aggregates are referenced as a
  whole by an aggregate root entity, parts of the aggregate must not be
  referenced from outside. The aggregate root is responsible for the enforcement
  of the busines rules and invariants of the aggregate.


## Tags
pattern

## Documentation
It is difficult to guarantee the consistency of changes to objects in a model
  with complex associations. Objects are supposed to maintain their own internal
  consistent state, but they can be blindsighed by changes in other objects that
  are conceptually constituent parts. Cautious database locking schemes cause
  multiple users to interfere pointlessly with each other and can make a system
  unusable. Similar issues arise when distributing objects among multiple
  servers, or designing asynchronous transactions.
  
  Therefore,
  
  Cluster entities and value objects into aggregates and define boundaries around
  each. Choose one entity to be the root of each aggregate, and allow external
  objects to hold references to the root only (references to internal members
  passed out for use within a single operation only). Define properties and
  invariants for the aggregate as a whole and give enforcement responsibility to
  the root or some designated framework mechanism.
  
  Use the same aggregate boundaries to govern transactions and distribution.
  
  Within the aggregate boundary, apply consistent rules synchronously. Across
  boundaries, handle updates asynchronously.
  
  Keep an aggregate together on one server. Allow diferent aggregate to be
  distributed among nodes.
  
  When these design decisions are not beeing guided well by the aggregate
  boundaries, reconsider the model. Is the domain scenario hinting at an
  important new insight? Such changes often improve the model's expressiveness
  and flexibility as well as resolving the transactional and distribution issues.
## Other Relations
| From | Name | To | Description |
|---|---|---|---|
| [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) | access with | [Repositories](../../../software-development/domain-driven-design/building-blocks/c-repositories.md) |  |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | act as root of | [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Entities](../../../software-development/domain-driven-design/building-blocks/c-entities.md) | encapsulate with | [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Value Objects](../../../software-development/domain-driven-design/building-blocks/c-value-objects.md) | encapsulate with | [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Aggregates](../../../software-development/domain-driven-design/building-blocks/c-aggregates.md) | encapsulate with | [Factories](../../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |

## Concept Map
![Concept Map of the Domain Driven Design Building Blocks Patterns](../../../software-development/domain-driven-design/building-blocks/concept-view.png)

[Concept Map of the Domain Driven Design Building Blocks Patterns](../../../software-development/domain-driven-design/building-blocks/concept-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

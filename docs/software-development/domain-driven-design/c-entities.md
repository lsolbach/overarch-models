# Entities (Concept)
## Description
Objects in the domain model which are defined by their identity rather than
by their state. For example a Person is normally modelled as an entity. It
represents the same person even when the attributes change. It is also a
different person, even if it has the same state as another person.

## Documentation
Many objects represent a thread of continuity and identity, going through a
lifecycle, though their attributes may change.

Some objects are not defined primarily by their attributes. They represent a
thread of identity that runs though time and often across distinct
representations. Sometimes such an object must be matched with another object
even though attributes differ. An object must be distinguished from other
objects even though they might have the same attributes. Mistaken identity
can lead to data corruption.

Therefore,

When an object is distinguished by its identity, rathe than its attributes,
make this primary to its definition in the model. Keep the class definition
simple and focused on lifecycle continuity and identity.

Define a means of distinguishing each object regardless of its form or history.
Be alert to requirements that call for matching objects by attributes. Define
an operation that is guaranteed to produce a unique result for each object,
possibly by attaching a symbol that is guaranteed unique. This means of
identification may come from the outside, or it may be an arbitrary identifier
created by and for the system, but it must correspond to the identity
distinctions in the model.

The model must define what it means to be the same thing.

## Relation from
| From | Name | To | Description |
|---|---|---|---|
| [Model Driven Design](../../software-development/domain-driven-design/c-model-driven-design.md) | express identity with | [Entities](../../software-development/domain-driven-design/c-entities.md) |  |

## Related to
| From | Name | To | Description |
|---|---|---|---|
| [Entities](../../software-development/domain-driven-design/c-entities.md) | access with | [Repositories](../../software-development/domain-driven-design/c-repositories.md) |  |
| [Entities](../../software-development/domain-driven-design/c-entities.md) | act as root of | [Aggregates](../../software-development/domain-driven-design/c-aggregates.md) |  |
| [Entities](../../software-development/domain-driven-design/c-entities.md) | encapsulate with | [Factories](../../software-development/domain-driven-design/c-factories.md) |  |
| [Entities](../../software-development/domain-driven-design/c-entities.md) | encapsulate with | [Aggregates](../../software-development/domain-driven-design/c-aggregates.md) |  |
| [Entities](../../software-development/domain-driven-design/c-entities.md) | push state change with | [Domain Events](../../software-development/domain-driven-design/c-domain-events.md) |  |

## Concept Map
![Concept Map of the Domain Driven Design Patterns](../../software-development/domain-driven-design/concept-view.png)
[Concept Map of the Domain Driven Design Patterns](../../software-development/domain-driven-design/concept-view.md)

### Tags
pattern


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)

(generated with docs/concept.md.cmb)

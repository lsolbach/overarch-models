# Concept Map of the Domain Driven Design Patterns

## Diagram
![Concept Map of the Domain Driven Design Patterns](../../software-development/domain-driven-design/concept-view.png)

## Description
Shows the concepts of Domain Driven Design and their relationships.

## Concepts
| Concept | Description |
|---|---|
| [Abstract Core](../../software-development/domain-driven-design/distillation/c-abstract-core.md)| The most fundamental differentiating concepts in the model, factored into distinct classes, abstract classes, or interfaces. |
| [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md)| Aggregates are collections of entities and value objects with their associations and form a transactional unit. Aggregates are referenced as a whole by an aggregate root entity, parts of the aggregate must not be referenced from outside. The aggregate root is responsible for the enforcement of the busines rules and invariants of the aggregate. |
| [Anti-Corruption Layer](../../software-development/domain-driven-design/context-mapping/c-anti-corruption-layer.md)| The anti-corruption layer is an architectural layer to separate the domain model from outside models. It enables the domain model to access the data of the outside model as expected by the domain model. In a clean architecture, an adapter is the place to implement the anti- corruption layer by mapping the outside model to the domain model. |
| [Big Ball of Mud](../../software-development/domain-driven-design/context-mapping/c-big-ball-of-mud.md)| A Big Ball of Mud is a casually, even haphazardly, structured system. Its organization, if one can call it that, is dictated more by expediency than design. Yet, its enduring popularity cannot merely be indicative of a general disregard for architecture. |
| [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md)| A descrition of a boundary (typically a subsystem or the work of a particular team) within which a particular model is defined and applicable. |
| [Building Blocks](../../software-development/domain-driven-design/building-blocks.md)| Part II: The Building Blocks of a Model-Driven Design |
| [Clean Architecture](../../software-development/domain-driven-design/c-clean-architecture.md)|  |
| [Cohesive Mechanisms](../../software-development/domain-driven-design/distillation/c-cohesive-mechanisms.md)|  |
| [Conformist](../../software-development/domain-driven-design/context-mapping/c-conformist.md)|  |
| [Context](../../software-development/domain-driven-design/c-context.md)| The setting in which a word or statement appears that determines its meaning. Statements about a model can only be understood in a context. |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md)| The context map provides an overview for all models and their boundaries and interfaces. |
| [Context Mapping](../../software-development/domain-driven-design/context-mapping.md)| Part IV: Context Mapping for Strategic Design |
| [Continuous Integration](../../software-development/domain-driven-design/modelling/c-continuous-integration.md)| A process of merging all code and other implementation artifacts frequently, with automated tests to flag fragmentation quickly. |
| [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md)| The most valuable part of the domain model. |
| [Customer/Supplier](../../software-development/domain-driven-design/context-mapping/c-customer-supplier.md)| A clear relationship between two teams, where the downstream team is the customer of the upstream team. |
| [Distillation](../../software-development/domain-driven-design/distillation.md)| Part V: Distillation for Strategic Design |
| [Domain](../../software-development/domain-driven-design/c-domain.md)| A sphere of knowledge, influence or activity. The subject area to which a user applies a program is the domain of the software. |
| [Domain Driven Design](../../software-development/domain-driven-design/domain-driven-design.md)| An approach to the development of complex software in which we focus on the core domain, explore models in a creative collaboration of domain practitioners and software practitioners, and speak a ubiquitous language within an explicitly bounded context. |
| [Domain Events](../../software-development/domain-driven-design/building-blocks/c-domain-events.md)| A domain object to propagate relevant domain activities in a distributed system. |
| [Domain Vision Statement](../../software-development/domain-driven-design/distillation/c-domain-vision-statement.md)| A short description of the core domain and the value it will bring. |
| [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md)| Objects in the domain model which are defined by their identity rather than by their state. For example a Person is normally modelled as an entity. It represents the same person even when the attributes change. It is also a different person, even if it has the same state as another person. |
| [Evolving Order](../../software-development/domain-driven-design/large-scale-structure/c-evolving-order.md)| A conceptual large-scale structure that evolves with the application, possibly changing to a completely different type of structure along the way. |
| [Factories](../../software-development/domain-driven-design/building-blocks/c-factories.md)| A domain object for the creation of complex domain objects which enforce the invariants of these objects on creation. |
| [Generic Subdomains](../../software-development/domain-driven-design/distillation/c-generic-subdomains.md)| A cohesive subdomain that is not the motivation for the project and does not capoure specialized knowledge. |
| [Hands On Modellers](../../software-development/domain-driven-design/modelling/c-hands-on-modellers.md)| Developers must be involved with the model and have contact with domain experts. |
| [Highlighted Core](../../software-development/domain-driven-design/distillation/c-highlighted-core.md)| Describes the core elements of the domain and their interactions. |
| [Knowledge-level](../../software-development/domain-driven-design/large-scale-structure/c-knowledge-level.md)| A distinct set of objects that can be used to describe and constrain the structure and behavior of the basic model. |
| [Large Scale Structure](../../software-development/domain-driven-design/large-scale-structure/c-large-scale-structure.md)|  |
| [Large-scale Structure](../../software-development/domain-driven-design/large-scale-structure.md)| Part VI: Large-scale Structure for Strategic Design |
| [Layered Architecture](../../software-development/domain-driven-design/c-layered-archtecture.md)| Isolates the expression of the domain model and the business logic, and eliminates any dependency on infrastructure, user interface, or application logic that is not business logic. |
| [Model](../../software-development/domain-driven-design/c-model.md)| A system of abstractions that describes selected aspects of a domain and can be used to solve problems related to that domain. |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md)|  |
| [Modules](../../software-development/domain-driven-design/building-blocks/c-modules.md)|  |
| [Open Host Service](../../software-development/domain-driven-design/context-mapping/c-open-host-service.md)| An open protocol that gives access to your subsystem as a set of services. |
| [Partnership](../../software-development/domain-driven-design/context-mapping/c-partnership.md)| A partnership between the teams in charge of the two contexts, when the teams will succeed or fail together. |
| [Pluggable Component Framework](../../software-development/domain-driven-design/large-scale-structure/c-pluggable-component-framework.md)| A framework that allows diverse implementations of those interfaces to be freely substituted. |
| [Published Language](../../software-development/domain-driven-design/context-mapping/c-published-language.md)| A well-documented shared language that can express the necessary domain information as a common medium of communication, translating as necessary into and out of that language. |
| [Putting the Model to Work](../../software-development/domain-driven-design/putting-the-model-to-work.md)| Part I: Putting the Model to Work |
| [Repositories](../../software-development/domain-driven-design/building-blocks/c-repositories.md)|  |
| [Responsibility Layers](../../software-development/domain-driven-design/large-scale-structure/c-responsibility-layers.md)|  |
| [Segregated Core](../../software-development/domain-driven-design/distillation/c-segregated-core.md)|  |
| [Separate Ways](../../software-development/domain-driven-design/context-mapping/c-separate-ways.md)| A bounded context with no connection to the others at all, allowing developers to find simple, specialized solutions within this small scope. |
| [Services](../../software-development/domain-driven-design/building-blocks/c-services.md)|  |
| [Shared Kernel](../../software-development/domain-driven-design/context-mapping/c-shared-kernel.md)|  |
| [Supple Design](../../software-development/domain-driven-design/supple-design.md)| Part III: Supple Design |
| [System Metaphor](../../software-development/domain-driven-design/large-scale-structure/c-system-metaphor.md)|  |
| [Ubiquitous Language](../../software-development/domain-driven-design/modelling/c-ubiquitous-language.md)| A language around the domain model used by all team members within a bounded context to connect all the activities of the team with the software. |
| [Value Objects](../../software-development/domain-driven-design/building-blocks/c-value-objects.md)| An object in the domain model, which has no conceptional identity but are identified by their state. Value objects should be modelled as immutable. |
| [free](../../software-development/domain-driven-design/free.md)| A software development context in which the direction, success or failure of development work in other contexts has little effect on delivery. |
| [mutually dependent](../../software-development/domain-driven-design/mutually-dependent.md)| A situation in which two software development projects in separate contexts must both be delivered in order for either to be considered a success. |
| [upsteam-downstream](../../software-development/domain-driven-design/upstream-downstream.md)| A relationship between two groups in which the “upstream” group’s actions affect project success of the “downstream” group, but the actions of the downstream do not significantly affect projects upstream. |

## Other Relationships
| From | Name | To | Description |
|---|---|---|---|
| [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) | access with | [Repositories](../../software-development/domain-driven-design/building-blocks/c-repositories.md) |  |
| [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md) | access with | [Repositories](../../software-development/domain-driven-design/building-blocks/c-repositories.md) |  |
| [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) | act as root of | [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md) | assess/overview relationships with | [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) |  |
| [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) | avoid overinvesting in | [Generic Subdomains](../../software-development/domain-driven-design/distillation/c-generic-subdomains.md) |  |
| [Evolving Order](../../software-development/domain-driven-design/large-scale-structure/c-evolving-order.md) | concepts enter | [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | coordinate interdependent contexts | [Partnership](../../software-development/domain-driven-design/context-mapping/c-partnership.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | coordinate upstream/downstream | [Customer/Supplier](../../software-development/domain-driven-design/context-mapping/c-customer-supplier.md) |  |
| [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) | culivate rich model with | [Ubiquitous Language](../../software-development/domain-driven-design/modelling/c-ubiquitous-language.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | define model within | [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md) |  |
| [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) | encapsulate with | [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Value Objects](../../software-development/domain-driven-design/building-blocks/c-value-objects.md) | encapsulate with | [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md) |  |
| [Value Objects](../../software-development/domain-driven-design/building-blocks/c-value-objects.md) | encapsulate with | [Factories](../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |
| [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) | encapsulate with | [Factories](../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |
| [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md) | encapsulate with | [Factories](../../software-development/domain-driven-design/building-blocks/c-factories.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express change with | [Domain Events](../../software-development/domain-driven-design/building-blocks/c-domain-events.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express identity with | [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express model with | [Services](../../software-development/domain-driven-design/building-blocks/c-services.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | express state and computation with | [Value Objects](../../software-development/domain-driven-design/building-blocks/c-value-objects.md) |  |
| [Open Host Service](../../software-development/domain-driven-design/context-mapping/c-open-host-service.md) | formalized as | [Published Language](../../software-development/domain-driven-design/context-mapping/c-published-language.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | free teams to go | [Separate Ways](../../software-development/domain-driven-design/context-mapping/c-separate-ways.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | isolate domain expressions with | [Clean Architecture](../../software-development/domain-driven-design/c-clean-architecture.md) |  |
| [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md) | keep model unified with | [Continuous Integration](../../software-development/domain-driven-design/modelling/c-continuous-integration.md) |  |
| [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) | model gives structure to | [Ubiquitous Language](../../software-development/domain-driven-design/modelling/c-ubiquitous-language.md) |  |
| [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md) | names enter | [Ubiquitous Language](../../software-development/domain-driven-design/modelling/c-ubiquitous-language.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | overlap contexts | [Shared Kernel](../../software-development/domain-driven-design/context-mapping/c-shared-kernel.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | overlap unilaterally as | [Conformist](../../software-development/domain-driven-design/context-mapping/c-conformist.md) |  |
| [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) | point the way with | [Domain Vision Statement](../../software-development/domain-driven-design/distillation/c-domain-vision-statement.md) |  |
| [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) | push state change with | [Domain Events](../../software-development/domain-driven-design/building-blocks/c-domain-events.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | seggregate the conceptual messes | [Big Ball of Mud](../../software-development/domain-driven-design/context-mapping/c-big-ball-of-mud.md) |  |
| [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) | structure through | [Evolving Order](../../software-development/domain-driven-design/large-scale-structure/c-evolving-order.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | support multiple clients through | [Open Host Service](../../software-development/domain-driven-design/context-mapping/c-open-host-service.md) |  |
| [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) | translate and isolate unilaterally with | [Anti-Corruption Layer](../../software-development/domain-driven-design/context-mapping/c-anti-corruption-layer.md) |  |
| [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) | work in autonomous, clean | [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md) |  |

## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/views/view.md.cmb)


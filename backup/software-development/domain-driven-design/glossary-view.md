# Glossary for Domain Driven Design
[A](#A) [B](#B) [C](#C) [D](#D) [E](#E) [F](#F) [G](#G) [H](#H) [I](#I) [K](#K) [L](#L) [M](#M) [O](#O) [P](#P) [R](#R) [S](#S) [U](#U) [V](#V) 

## A

### [Abstract Core](../../software-development/domain-driven-design/distillation/c-abstract-core.md) (Concept)
The most fundamental differentiating concepts in the model, factored
into distinct classes, abstract classes, or interfaces.

### [Aggregates](../../software-development/domain-driven-design/building-blocks/c-aggregates.md) (Concept)
Aggregates are collections of entities and value objects with their
  associations and form a transactional unit. Aggregates are referenced as a
  whole by an aggregate root entity, parts of the aggregate must not be
  referenced from outside. The aggregate root is responsible for the enforcement
  of the busines rules and invariants of the aggregate.

### [Anti-Corruption Layer](../../software-development/domain-driven-design/context-mapping/c-anti-corruption-layer.md) (Concept)
The anti-corruption layer is an architectural layer to separate the domain
model from outside models. It enables the domain model to access the data of
the outside model as expected by the domain model.
In a clean architecture, an adapter is the place to implement the anti-
corruption layer by mapping the outside model to the domain model.

### [Assertions](../../software-development/domain-driven-design/supple-design/assertions.md) (Concept)
state post-conditions of operations and invariants of classes and aggregates

## B

### [Big Ball of Mud](../../software-development/domain-driven-design/context-mapping/c-big-ball-of-mud.md) (Concept)
A Big Ball of Mud is a casually, even haphazardly, structured system.
Its organization, if one can call it that, is dictated more by expediency than
design. Yet, its enduring popularity cannot merely be indicative of a general
disregard for architecture.

### [Bounded Context](../../software-development/domain-driven-design/modelling/c-bounded-context.md) (Concept)
A descrition of a boundary (typically a subsystem or the work of
a particular team) within which a particular model is defined and applicable.

### [Building Blocks](../../software-development/domain-driven-design/building-blocks.md) (Concept)
Part II: The Building Blocks of a Model-Driven Design

## C

### [Clean Architecture](../../software-development/domain-driven-design/c-clean-architecture.md) (Concept)


### [Closure of Operations](../../software-development/domain-driven-design/supple-design/closure-of-operations.md) (Concept)
define an operation whose return type is the same as the type
of its argument(s)

### [Cohesive Mechanisms](../../software-development/domain-driven-design/distillation/c-cohesive-mechanisms.md) (Concept)


### [Conceptual Contours](../../software-development/domain-driven-design/supple-design/conceptual-contours.md) (Concept)
decompose design elements into cohesive units

### [Conformist](../../software-development/domain-driven-design/context-mapping/c-conformist.md) (Concept)


### [Context](../../software-development/domain-driven-design/c-context.md) (Concept)
The setting in which a word or statement appears that determines its meaning.
Statements about a model can only be understood in a context.

### [Context Map](../../software-development/domain-driven-design/context-mapping/c-context-map.md) (Concept)
 The context map provides an overview for all models and their boundaries and
interfaces.

### [Context Mapping](../../software-development/domain-driven-design/context-mapping.md) (Concept)
Part IV: Context Mapping for Strategic Design

### [Continuous Integration](../../software-development/domain-driven-design/modelling/c-continuous-integration.md) (Concept)
A process of merging all code and other implementation artifacts
frequently, with automated tests to flag fragmentation quickly.

### [Core Domain](../../software-development/domain-driven-design/distillation/c-core-domain.md) (Concept)
The most valuable part of the domain model.

### [Customer/Supplier](../../software-development/domain-driven-design/context-mapping/c-customer-supplier.md) (Concept)
A clear relationship between two teams, where the downstream team is the customer
of the upstream team.

## D

### [Declarative Design](../../software-development/domain-driven-design/supple-design/declarative-design.md) (Concept)


### [Distillation](../../software-development/domain-driven-design/distillation.md) (Concept)
Part V: Distillation for Strategic Design

### [Domain](../../software-development/domain-driven-design/c-domain.md) (Concept)
A sphere of knowledge, influence or activity.
The subject area to which a user applies a program is the domain of the software.

### [Domain Driven Design](../../software-development/domain-driven-design/domain-driven-design.md) (Concept)
An approach to the development of complex software
in which we focus on the core domain, explore models in a creative
collaboration of domain practitioners and software practitioners, and speak a
ubiquitous language within an explicitly bounded context.

### [Domain Events](../../software-development/domain-driven-design/building-blocks/c-domain-events.md) (Concept)
A domain object to propagate relevant domain activities in a distributed system.

### [Domain Vision Statement](../../software-development/domain-driven-design/distillation/c-domain-vision-statement.md) (Concept)
A short description of the core domain and the value it will bring.

## E

### [Entities](../../software-development/domain-driven-design/building-blocks/c-entities.md) (Concept)
Objects in the domain model which are defined by their identity rather than
by their state. For example a Person is normally modelled as an entity. It
represents the same person even when the attributes change. It is also a
different person, even if it has the same state as another person.

### [Established Formalisms](../../software-development/domain-driven-design/supple-design/established-formalisms.md) (Concept)


### [Evolving Order](../../software-development/domain-driven-design/large-scale-structure/c-evolving-order.md) (Concept)
A conceptual large-scale structure that evolves with the application, possibly
  changing to a completely different type of structure along the way.

## F

### [Factories](../../software-development/domain-driven-design/building-blocks/c-factories.md) (Concept)
A domain object for the creation of complex domain objects which enforce the
invariants of these objects on creation.

### [free](../../software-development/domain-driven-design/free.md) (Concept)
A software development context in which the direction, success or failure of
development work in other contexts has little effect on delivery.

## G

### [Generic Subdomains](../../software-development/domain-driven-design/distillation/c-generic-subdomains.md) (Concept)
A cohesive subdomain that is not the motivation for the project and does
not capoure specialized knowledge.

## H

### [Hands On Modellers](../../software-development/domain-driven-design/modelling/c-hands-on-modellers.md) (Concept)
Developers must be involved with the model and have contact with domain experts.

### [Highlighted Core](../../software-development/domain-driven-design/distillation/c-highlighted-core.md) (Concept)
Describes the core elements of the domain and their interactions.

## I

### [Intention-Revealing Interfaces](../../software-development/domain-driven-design/supple-design/intention-revealing-interfaces.md) (Concept)
name classes and operations to describe their effect and purpose

## K

### [Knowledge-level](../../software-development/domain-driven-design/large-scale-structure/c-knowledge-level.md) (Concept)
A distinct set of objects that can be used to describe and constrain the
  structure and behavior of the basic model.

## L

### [Large Scale Structure](../../software-development/domain-driven-design/large-scale-structure/c-large-scale-structure.md) (Concept)


### [Large-scale Structure](../../software-development/domain-driven-design/large-scale-structure.md) (Concept)
Part VI: Large-scale Structure for Strategic Design

### [Layered Architecture](../../software-development/domain-driven-design/c-layered-archtecture.md) (Concept)
Isolates the expression of the domain model and the business logic, and
eliminates any dependency on infrastructure, user interface, or application logic
that is not business logic.

## M

### [Model](../../software-development/domain-driven-design/c-model.md) (Concept)
A system of abstractions that describes selected aspects of a domain
and can be used to solve problems related to that domain.

### [Model Driven Design](../../software-development/domain-driven-design/modelling/c-model-driven-design.md) (Concept)


### [Modules](../../software-development/domain-driven-design/building-blocks/c-modules.md) (Concept)


### [mutually dependent](../../software-development/domain-driven-design/mutually-dependent.md) (Concept)
A situation in which two software development projects in separate contexts
must both be delivered in order for either to be considered a success.

## O

### [Open Host Service](../../software-development/domain-driven-design/context-mapping/c-open-host-service.md) (Concept)
An open protocol that gives access to your subsystem as a set of services.

## P

### [Partnership](../../software-development/domain-driven-design/context-mapping/c-partnership.md) (Concept)
A partnership between the teams in charge of the two
contexts, when the teams will succeed or fail together.

### [Pluggable Component Framework](../../software-development/domain-driven-design/large-scale-structure/c-pluggable-component-framework.md) (Concept)
A framework that allows diverse implementations of those interfaces to be
freely substituted.

### [Published Language](../../software-development/domain-driven-design/context-mapping/c-published-language.md) (Concept)
A well-documented shared language that can express the necessary domain
information as a common medium of communication, translating as necessary into
and out of that language.

### [Putting the Model to Work](../../software-development/domain-driven-design/putting-the-model-to-work.md) (Concept)
Part I: Putting the Model to Work

## R

### [Repositories](../../software-development/domain-driven-design/building-blocks/c-repositories.md) (Concept)
Query access to aggregates expressed in the ubiquitous language

### [Responsibility Layers](../../software-development/domain-driven-design/large-scale-structure/c-responsibility-layers.md) (Concept)


## S

### [Segregated Core](../../software-development/domain-driven-design/distillation/c-segregated-core.md) (Concept)


### [Separate Ways](../../software-development/domain-driven-design/context-mapping/c-separate-ways.md) (Concept)
A bounded context with no connection to the others at all, allowing
developers to find simple, specialized solutions within this small scope.

### [Services](../../software-development/domain-driven-design/building-blocks/c-services.md) (Concept)
contains functionality which is not the responsiblity of an entity or value object

### [Shared Kernel](../../software-development/domain-driven-design/context-mapping/c-shared-kernel.md) (Concept)


### [Side-Effect-Free Functions](../../software-development/domain-driven-design/supple-design/side-effect-free-functions.md) (Concept)
implement logic with functions that return results without observable side effects

### [Standalone Classes](../../software-development/domain-driven-design/supple-design/standalone-classes.md) (Concept)
when possible create classes that are self-contained and can be understood alone

### [Supple Design](../../software-development/domain-driven-design/supple-design.md) (Concept)
Part III: Supple Design

### [System Metaphor](../../software-development/domain-driven-design/large-scale-structure/c-system-metaphor.md) (Concept)


## U

### [Ubiquitous Language](../../software-development/domain-driven-design/modelling/c-ubiquitous-language.md) (Concept)
A language around the domain model used by all team members within a
bounded context to connect all the activities of the team with the software.

### [upsteam-downstream](../../software-development/domain-driven-design/upstream-downstream.md) (Concept)
A relationship between two groups in which the “upstream” group’s actions
affect project success of the “downstream” group, but the actions of the
downstream do not significantly affect projects upstream.

## V

### [Value Objects](../../software-development/domain-driven-design/building-blocks/c-value-objects.md) (Concept)
An object in the domain model, which has no conceptional identity but are
identified by their state. Value objects should be modelled as immutable.




(generated by [Overarch](https://github.com/soulspace-org/overarch) with template views/glossary-view.md.cmb)
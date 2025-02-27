# Service A (Container)
## Description
Microservice

## Technology


## Parent
[Blueprint System](../../../../../software-development/architecture/blueprint/microservices/event-driven/system.md)

## Interfaces

### Synchronous Interfaces

#### Used Services

| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Service A](../../../../../software-development/architecture/blueprint/microservices/event-driven/service-a.md) | stores | [Datastore A](../../../../../software-development/architecture/blueprint/microservices/event-driven/datastore-a.md) |  | aggregate A |

### Asynchronous Publish/Subscribe Interfaces

#### Publishing/Producing
| From | Name | To Queue/Topic | Technology | Description |
|---|---|---|---|---|
| [Service A](../../../../../software-development/architecture/blueprint/microservices/event-driven/service-a.md) | publishes | [A Topic](../../../../../software-development/architecture/blueprint/microservices/event-driven/topic-a.md) |  | domain events for aggregate A |

## Container View
![Container View of the Event Driven Microservices Blueprint](../../../../../software-development/architecture/blueprint/microservices/event-driven/container-view.png)

[Container View of the Event Driven Microservices Blueprint](../../../../../software-development/architecture/blueprint/microservices/event-driven/container-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../../views.md)

(generated with docs/architecture-node.md.cmb)

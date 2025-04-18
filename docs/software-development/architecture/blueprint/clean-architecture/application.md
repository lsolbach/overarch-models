
# application (Package)
## Description
Contains the application services implementing the orchestration of the use
          cases of the component


## Documentation
The application package contains the application services implementing the orchestration
of the use cases of the component. The application package also contains interfaces
for the adapters needed by the application services.

The application services establish transactional boundaries, load required data,
call the domain logic from the domain core, store any results and send the
domain events produced in the domain core.
          
The application services are triggered by driving adapters from the adaper layer
and they call the driven adapters from the adapter layer.
## Interfaces
| Interface | Description |
|---|---|
| [DomainEventPublisherInterface](../../../../software-development/architecture/blueprint/clean-architecture/application/domain-event-publisher-interface.md)| The interface for the domain event publisher adapters |
| [RepositoryInterface](../../../../software-development/architecture/blueprint/clean-architecture/application/repository-interface.md)| The interface for the repository adapters |
## Classes
| Class | Description |
|---|---|
| [ApplicationService](../../../../software-development/architecture/blueprint/clean-architecture/application/application-service.md)| Implements the orchestration of a use case |

## Code View
![Code View of the Clean Architecture Blueprint](../../../../software-development/architecture/blueprint/clean-architecture/code-view.png)

[Code View of the Clean Architecture Blueprint](../../../../software-development/architecture/blueprint/clean-architecture/code-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)

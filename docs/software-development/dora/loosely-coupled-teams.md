# Loosely coupled teams (Concept)
## Description
Enable teams to test, deploy, and change systems without dependencies on other teams

## Documentation
Research from the DORA team shows that effective organizational and technical
structures are predictors for achieving continuous delivery. Whether you’re
using Kubernetes or mainframes, your architecture enables teams to adopt
practices that foster higher levels of software delivery performance.

When teams adopt continuous delivery practices, adopting the following
architectural practices drives successful outcomes:

* Teams can make large-scale changes to the design of their systems without the
  permission of somebody outside the team or depending on other teams.
* Teams are able to complete work without needing fine-grained communication
  and coordination with people outside the team.
* Teams deploy and release their product or service on demand, independently
  of the services it depends on or of other services that depend on it.
* Teams do most of their testing on demand, without requiring an integrated
  test environment.
* Teams can deploy during normal business hours with negligible downtime.

It’s possible to achieve these outcomes with mainframe technologies.
It’s also possible to fail to achieve them even when using the latest, most
trendy technologies. Many organizations invest lots of time and effort in
adopting technologies, but fail to achieve critical software delivery outcomes,
due to limitations imposed by architecture.

When the architecture of the system is designed to enable teams to test,
deploy, and change systems without dependencies on other teams, teams
require little communication to get work done. In other words, both the
architecture and the teams are loosely coupled.

This connection between communication bandwidth and systems architecture was
first discussed by Melvin Conway, who said, “organizations which design systems
… are constrained to produce designs which are copies of the communication
structures of these organizations.” To counteract tightly-coupled architectures
and help support better communication patterns, teams and organizations can use
the Inverse Conway Maneuver, whereby team structures and patterns are designed
to promote the expected architectural state. In this way, team communication
patterns support and enforce the architectural patterns that are built.

With a tightly coupled architecture, small changes can result in large-scale,
cascading failures. As a result, anyone working in one part of the system must
constantly coordinate with anyone else working in another part of the system,
including navigating complex and bureaucratic change management processes.

Microservices architectures are supposed to enable these outcomes, as should
any true service-oriented architecture. In practice, many so-called
service-oriented architectures don’t permit testing and deploying services
independently of each other, and thus won’t let teams achieve higher software
delivery performance. It’s essential to be strict about these outcomes when
implementing service-oriented and microservice architectures.

## Related to
| From | Name | To | Description |
|---|---|---|---|
| [Loosely coupled teams](../../software-development/dora/loosely-coupled-teams.md) | enables | [Fast Flow](../../software-development/dora/fast-flow.md) |  |

## Concept Map
![Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.png)
[Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.md)

### Tags
process, capability, core


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)

(generated with docs/concept.md.cmb)

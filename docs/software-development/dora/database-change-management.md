# Database change management (Concept)
## Description
Make sure database changes don't cause problems or slow you down.

## Documentation
Database changes are often a major source of risk and delay when performing deployments. DevOps Research and Assessment (DORA) investigated which database-related practices help during the process of implementing continuous delivery, improving both software delivery performance and availability.

DORA’s research found that integrating database work into the software delivery process positively contributes to continuous delivery. But how can your teams improve your database delivery as part of implementing continuous delivery? A few practices predict performance outcomes.

DORA discovered that good communication and comprehensive configuration management that includes the database matter. Teams that do well at continuous delivery store their database changes as scripts in version control and manage these changes in the same way they manage production application changes. Furthermore, when changes to the application require database changes, these teams discuss them with the people responsible for the production database, and ensure the engineering team has visibility into the progress of pending database changes.

When teams follow these practices, database changes don’t slow them down or cause problems when they perform code deployments.

## Related to
| From | Name | To | Description |
|---|---|---|---|
| [Database change management](../../software-development/dora/database-change-management.md) | enables | [Fast Flow](../../software-development/dora/fast-flow.md) |  |

## Concept Map
![Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.png)
[Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.md)

### Tags
capability, technical, core


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)

(generated with docs/concept.md.cmb)

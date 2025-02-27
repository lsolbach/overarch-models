# Continouos delivery (Concept)
## Description
Make deploying software a reliable, low-risk process that can be performed on demand at any time.

## Documentation
Continuous delivery is the ability to release changes of all kinds on demand quickly, safely, and sustainably. Teams that practice continuous delivery well are able to release software and make changes to production in a low-risk way at any time—including during normal business hours—without impacting users.

You can apply the principles and practices of continuous delivery to any software context, including the following:

    * Updating services in a complex distributed system.
    * Upgrading mainframe software.
    * Making infrastructure configuration changes.
    * Making database schema changes.
    * Updating firmware automatically.
    * Releasing new versions of a mobile app.

When your team practices continuous delivery, you can answer “yes” to the following questions:

    * Is our software in a deployable state throughout its lifecycle?
    * Do we prioritize keeping the software deployable over working on new features?
    * Is fast feedback on the quality and deployability of the system we are working on available to everyone on the team?
    * When we get feedback that the system is not deployable (such as failing builds or tests), do we make fixing these issues our highest priority?
    * Can we deploy our system to production, or to end users, at any time, on demand?

Continuous delivery is commonly conflated with continuous deployment, but they are separate practices. Continuous deployment is when teams try to deploy every code change to production as soon as possible. Continuous deployment works well for web services, but can’t be applied to software such as firmware or mobile apps. Continuous delivery is applied to all kinds of software including firmware and mainframe systems, and in highly regulated environments. You can and should start with continuous delivery, even if you never intend to start using continuous deployment.

Continuous delivery and continuous deployment are mistakenly viewed as risky and not suited to regulated or safety critical domains. In fact, the goal of continuous delivery is to reduce software risk, and DORA research has shown consistently that high performers achieve higher levels of reliability and availability. The technical practices that drive continuous delivery—continuous testing, shifting left on security, and comprehensive testing and observability—are even more important in highly regulated and safety-critical domains. Continuous delivery has been successfully applied many times in highly regulated domains such as financial services and government.

## Related to
| From | Name | To | Description |
|---|---|---|---|
| [Continouos delivery](../../software-development/dora/continuous-delivery.md) | enables | [Fast Flow](../../software-development/dora/fast-flow.md) |  |

## Concept Map
![Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.png)
[Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.md)

### Tags
capability, technical, core


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)

(generated with docs/concept.md.cmb)

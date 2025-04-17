# Concept Map for Cloud Computing

## Diagram
![Concept Map for Cloud Computing](../../software-development/cloud/concept-view.png)

## Description
Shows the concepts related to Cloud Computing and their relationships.

## Concepts
| Concept | Description |
|---|---|
| [Broad network access](../../software-development/cloud/broad-network-access.md)| Capabilities are available over the network and accessed through standard mechanisms that promote use by heterogeneous thin or thick client platforms (e.g., mobile phones, tablets, laptops, and workstations). |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md)| A model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction. |
| [Cloud Computing Platform](../../software-development/cloud/cloud-computing-platform.md)| A  set of tools, services, and infrastructure that enables developers to build, deploy, and manage applications on the cloud. Cloud computing platforms may include services such as virtual machines, databases, AI, machine learning, and IoT, as well as developer tools for building and deploying applications. |
| [Cloud Deployment Model](../../software-development/cloud/cloud-deployment-model.md)| Cloud deployment models include Public Cloud, Private Cloud, Hybrid Cloud, and Multi-Cloud. |
| [Cloud Migration Strategy](../../software-development/cloud/cloud-migration-strategy.md)| A plan for moving applications, data, and other business elements to a cloud computing environment. A cloud migration strategy typically includes an assessment of the current environment, identification of workloads to be migrated, selection of the appropriate cloud deployment model, and implementation of the migration plan. |
| [Cloud Native Application](../../software-development/cloud/cloud-native-application.md)| A cloud-native application is an application that is designed and built specifically for cloud environments. Cloud-native applications are typically developed using microservices architecture, containerization, and serverless computing to take advantage of the scalability, flexibility, and cost-effectiveness of cloud computing. |
| [Cloud Provider](../../software-development/cloud/cloud-provider.md)| A company that offers cloud computing services, such as virtual machines, storage, databases, and applications, to customers over the internet. |
| [Cloud Service Model](../../software-development/cloud/cloud-service-model.md)| The type of service provided by a cloud provider |
| [Landing Zone](../../software-development/cloud/landing-zone.md)| A landing zone is a pre-configured environment in the cloud that provides a foundation for migrating workloads and applications. A landing zone typically includes network configurations, security policies, and governance controls to ensure a secure and compliant cloud environment. |
| [Measured service](../../software-development/cloud/measured-service.md)| Cloud systems automatically control and optimize resource use by leveraging a metering capability1 at some level of abstraction appropriate to the type of service (e.g., storage, processing, bandwidth, and active user accounts). Resource usage can be monitored, controlled, and reported, providing transparency for both the provider and consumer of the utilized service. |
| [On-demand self-service](../../software-development/cloud/on-demand-self-service.md)| A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction with each service provider. |
| [Rapid elasticity](../../software-development/cloud/rapid-elasticity.md)| Capabilities can be elastically provisioned and released, in some cases automatically, to scale rapidly outward and inward commensurate with demand. To the consumer, the capabilities available for provisioning often appear unlimited and can be appropriated in any quantity at any time. |
| [Resource pooling](../../software-development/cloud/resource-pooling.md)| The provider's computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically assigned and reassigned according to consumer demand. |

## Features
| From | Name | To | Description |
|---|---|---|---|
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Rapid elasticity](../../software-development/cloud/rapid-elasticity.md) | essential characteristic |
| [Cloud Adoption Framework](../../software-development/cloud/framework/cloud-adoption-framework.md) | has | [Cloud Migration Strategy](../../software-development/cloud/cloud-migration-strategy.md) | The Cloud Adoption Framework has cloud migration strategies. |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Cloud Service Model](../../software-development/cloud/cloud-service-model.md) | Cloud computing has cloud service models. |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [On-demand self-service](../../software-development/cloud/on-demand-self-service.md) | essential characteristic |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Measured service](../../software-development/cloud/measured-service.md) | essential characteristic |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Cloud Adoption Framework](../../software-development/cloud/framework/cloud-adoption-framework.md) | Cloud Computing has Cloud Adoption Framework. |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Broad network access](../../software-development/cloud/broad-network-access.md) | essential characteristic |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Resource pooling](../../software-development/cloud/resource-pooling.md) | essential characteristic |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Cloud Deployment Model](../../software-development/cloud/cloud-deployment-model.md) | Cloud computing has cloud deployment models. |
| [Cloud Computing](../../software-development/cloud/cloud-computing.md) | has | [Well-Architected Framework](../../software-development/cloud/framework/well-architected-framework.md) | Cloud Computing has Well-Architected Framework. |

## Other Relationships
| From | Name | To | Description |
|---|---|---|---|
| [Cloud Computing Platform](../../software-development/cloud/cloud-computing-platform.md) | implements | [Cloud Computing](../../software-development/cloud/cloud-computing.md) | A cloud computing platform implements cloud computing. |
| [Cloud Provider](../../software-development/cloud/cloud-provider.md) | provides | [Cloud Computing Platform](../../software-development/cloud/cloud-computing-platform.md) | A cloud provider provides a cloud computing platform. |

## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/views/view.md.cmb)


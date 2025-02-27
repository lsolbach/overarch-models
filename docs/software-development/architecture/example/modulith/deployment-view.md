# Deployment view for the Online Shop modulith example

## Diagram
![Deployment view for the Online Shop modulith example](../../../../software-development/architecture/example/modulith/deployment-view.png)

## Description
Shows the deployment of the Online Shop modulith example

## Nodes
| Name | Technology | Description |
|---|---|---|
| [App VM 1](../../../../software-development/architecture/example/modulith/app-vm1.md) |  | Application Server Virtual Machine 1 |
| [Application Server](../../../../software-development/architecture/example/modulith/application-server.md) | IBM WebSphere |  |
| [Data Center](../../../../software-development/architecture/example/modulith/data-center.md) |  | The data center where the online shop is hosted. |
| [Database Server](../../../../software-development/architecture/example/modulith/db-server.md) | DB/2 |  |
| [DB VM 1](../../../../software-development/architecture/example/modulith/db-vm1.md) |  | Database Server Virtual Machine 1 |
| [Internal Network](../../../../software-development/architecture/example/modulith/internal-network.md) |  |  |
| [Perimeter Network](../../../../software-development/architecture/example/modulith/perimeter-network.md) |  |  |
| [Web Server](../../../../software-development/architecture/example/modulith/web-server.md) | Apache Tomcat |  |
| [Web VM 1](../../../../software-development/architecture/example/modulith/web-vm1.md) |  | Web Server Virtual Machine 1 |

## Links
| From | Name | To | Technology | Description |
|---|---|---|---|---|
| [Perimeter Network](../../../../software-development/architecture/example/modulith/perimeter-network.md) | links to | [Internal Network](../../../../software-development/architecture/example/modulith/internal-network.md) |  | The Perimeter Network links to the Internal Network via firewall. |


## Navigation
[List of views in namespace](./views-in-namespace.md)
[List of all Views](../../../../views.md)

(generated with docs/views/deployment-view.md.cmb)

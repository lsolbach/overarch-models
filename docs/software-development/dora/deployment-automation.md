# Deployment automation (Concept)
## Description
Best practices and approaches for deployment automation and reducing manual intervention in the release process.

## Documentation
Deployment automation is what enables you to deploy your software to testing and production environments with the push of a button. Automation is essential to reduce the risk of production deployments. It’s also essential for providing fast feedback on the quality of your software by allowing teams to do comprehensive testing as soon as possible after changes.

An automated deployment process has the following inputs:

    * Packages created by the continuous integration (CI) process (these packages should be deployable to any environment, including production).
    * Scripts to configure the environment, deploy the packages, and perform a deployment test (sometimes known as a smoke test).
    * Environment-specific configuration information.

We recommend that you store the scripts and configuration information in version control. Your deployment process should download the packages from an artifact repository (for example, Artifact Registry, Nexus, Artifactory, or your CI tool’s built-in repository).

The scripts usually perform the following tasks:

    * Prepare the target environment, perhaps by installing and configuring any necessary software, or by starting up a virtual host from a pre-prepared image in a cloud provider such as Google Cloud.
    * Deploy the packages.
    * Perform any deployment-related tasks such as running database migration scripts.
    * Perform any required configuration.
    * Perform a deployment test to make sure that any necessary external services are reachable, and that the system is functioning.

## Related to
| From | Name | To | Description |
|---|---|---|---|
| [Deployment automation](../../software-development/dora/deployment-automation.md) | enables | [Fast Flow](../../software-development/dora/fast-flow.md) |  |

## Concept Map
![Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.png)
[Concept Map for DevOps Research and Assessment (DORA)](../../software-development/dora/concept-view.md)

### Tags
capability, technical, core


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)

(generated with docs/concept.md.cmb)

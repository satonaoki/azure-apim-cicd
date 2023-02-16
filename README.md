# Azure API Management CI/CD Example (deprecated)

This is an example of CI/CD pipleines for Azure API Management. 

"Extract" pipeline extracts API definitions and other configuration from one API Management instance (typically "dev" environment), store them to Git repo, and create a PR.

"Deploy" pipeline deploys (publisher) them to other API Management instances (such as "test" and "prod" environments).

---

# Note (as of February 2023)

This example uses ["Azure API Management DevOps Resource Kit"](https://github.com/Azure/azure-api-management-devops-resource-kit).

I recommend using ["APIOps Toolkit for Azure APIM"](https://azure.github.io/apiops/) instead.

- [Use DevOps and CI/CD to publish APIs](https://learn.microsoft.com/en-us/azure/api-management/devops-api-development-templates)
- [Automate API deployments with APIOps](https://learn.microsoft.com/en-us/azure/architecture/example-scenario/devops/automated-api-deployments-apiops)

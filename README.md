# References Architectures

## Microsoft Enterprise-Scale References Architectures

https://github.com/Azure/Enterprise-Scale

The Enterprise-Scale architecture is modular by design and allows customers to start with foundational Landing Zones that support their application portfolios, regardless of whether the applications are being migrated or are newly developed and deployed to Azure. The architecture can scale alongside the customer's business requirements regardless of scale point. In this repository we are providing the following five templates representing different scenarios composed using ARM templates.

| Reference implementation | Description | ARM Template | Link |
|:-------------------------|:-------------|:-------------|------|
| Contoso | On-premises connectivity using Azure vWAN |[![Deploy To Azure](https://learn.microsoft.com/en-us/azure/templates/media/deploy-to-azure.svg)](https://portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2FeslzArm.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2Feslz-portal.json) | [Detailed description](./docs/reference/contoso/Readme.md) |
| AdventureWorks | On-premises connectivity with Hub & Spoke  |[![Deploy To Azure](https://learn.microsoft.com/en-us/azure/templates/media/deploy-to-azure.svg)](https://portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2FeslzArm.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2Feslz-portal.json) | [Detailed description](./docs/reference/adventureworks/README.md) |
| WingTip | Azure without hybrid connectivity |[![Deploy To Azure](https://learn.microsoft.com/en-us/azure/templates/media/deploy-to-azure.svg)](https://portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2FeslzArm.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2Feslz-portal.json) | [Detailed description](./docs/reference/wingtip/README.md) |
| Trey Research | On-premises connectivity with Hub and Spoke for small Enterprises | [![Deploy To Azure](https://learn.microsoft.com/en-us/azure/templates/media/deploy-to-azure.svg)](https://portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Ftreyresearch%2FarmTemplates%2Fes-lite.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2Fdocs%2Freference%2Ftreyresearch%2FarmTemplates%2Fportal-es-lite.json) | [Detailed description](./docs/reference/treyresearch/README.md) |
| Azure Gov | Reference implementation that can be deployed to Azure gov and includes all options in a converged experience | [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.svg?sanitize=true)](https://portal.azure.us/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2FeslzArm.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FEnterprise-Scale%2Fmain%2FeslzArm%2Ffairfaxeslz-portal.json) | N/A


## Azure landing zone for SCCA-compliant organizations.
https://github.com/Azure/missionlz

## Hub and Spoke Landing Zone 
https://github.com/adelagar/HubSpokeLandingZone

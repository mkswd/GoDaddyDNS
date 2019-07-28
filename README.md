## Objective

Tasks packages to manage GoDaddy DNS Zone from Azure DevOps release pipeline.

Tasks provides:
- A Record Manager
- CName Record Manager

## Note
Due to some GoDaddy limitation, the delete functionnality only works properly if at least One DNS Records is existing on the desired record type.

## Service Endpoint
![ServiceEndpoint](img/v0/ServiceEndpoint_v0.jpg)

## A Record Manager (required parameters)
![ARecord_Task_inputs](img/v0/ARecord_v0.jpg)

## CNAME Record Manager (required parameters)
![CNAMERecord_Task_inputs](img/v0/cnameRecord_v0.jpg)

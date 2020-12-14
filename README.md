## Welcome

Welcome to the Prisma Cloud Azure workshop! Prisma™ Cloud is a cloud security posture management (CSPM) and cloud workload protection platform (CWPP) solution. It provides comprehensive visibility and threat detection across your organization’s hybrid, multi-cloud environment (Azure, AWS, GCP, Alibaba, Kubernetes). 

This workshop was created as a walkthrough for an in person or virtual workshop, however you may feel free to run through at your own pace.
### Some Pre-requisites

* An Azure Subscription
  * This can be any Azure subscription where you have the owner role assignment. We will also be performing some actions in Azure AD and other services that may require the Application Administrator or Global Administrator level of access on the tenant level.
  * You can sign up for a new Azure accout [here](https://bit.ly/azure-free-sub-trial)

* A Prisma Cloud Enterprise Account
  * You can sign up for Palo Alto Prisma Cloud trial [https://marketplace.paloaltonetworks.com/s/](https://marketplace.paloaltonetworks.com/s/)

* An Azure DevOps Organization
  * You can sign up [here](https://app.vsaex.visualstudio.com/).

* A JIRA Account
  * You can sign up for a free trial [here](https://www.atlassian.com/software/jira/free).

* A GitHub Account
  * You'll need a personal GitHub account. You can sign up for free [here](https://github.com/join).

  ### Agenda

The workshop is designed to take approximately 5-6 hours to complete. It can be spread out over a 1 day or 2 days workshop.

|    | Module                   | Format       |
|----|--------------------------|--------------|
| 00 | [Setup Pre-Requisites](walkthroughs/0-prerequisites.md)                         | Hands on Lab |
| 02 | [Onboard Azure Subscription to Prisma Cloud](walkthroughs/1-onboard-azure-sub.md) | Hands on Lab |
| 03 | [Onboard Azure AD to Prisma Cloud](walkthroughs/2-onboard-azure-ad.md)                | Hands on Lab |
| 04 | [Configure JIRA integration in Prisma Cloud](walkthroughs/3-jira-integration.md) | Hands on Lab |
| 05 | [Deploy vulnerable workload using terraform](walkthroughs/4-deploy-vulnearble-workload.md) | Hands on Lab |
| 06 | [Respond and remediate issues with Prisma Cloud](walkthroughs/5-respond-and-remediate.md)  | Hands on Lab |
| 07 | [Enable auto-remediation and verify](walkthroughs/6-configure-auto-remediation.md) | Hands on Lab |
| 08 | Implement IaC scanning    | Hands on Lab |
| 09 | Wrap / Clean Up     | Hands on Lab |
----

[Next](full/1-create-aro-cluster.md)
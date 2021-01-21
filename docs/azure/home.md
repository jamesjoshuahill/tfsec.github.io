---
layout: default
title: AZURE Checks
permalink: /docs/azure/home/
search_exclude: true
has_children: true
nav_order: 1
---

The included AZURE checks are listed below. For more information about each check, see the link provided.

| Code  | Summary | Details |
|:-------|:-------------|:----------|
|AZU001|An inbound network security rule allows traffic from `/0`.|[AZU001](/docs/azure/AZU001)|
|AZU002|An outbound network security rule allows traffic to `/0`.|[AZU002](/docs/azure/AZU002)|
|AZU003|Unencrypted managed disk.|[AZU003](/docs/azure/AZU003)|
|AZU004|Unencrypted data lake storage.|[AZU004](/docs/azure/AZU004)|
|AZU005|Password authentication in use instead of SSH keys.|[AZU005](/docs/azure/AZU005)|
|AZU006|Ensure AKS cluster has Network Policy configured|[AZU006](/docs/azure/AZU006)|
|AZU007|Ensure RBAC is enabled on AKS clusters|[AZU007](/docs/azure/AZU007)|
|AZU008|Ensure AKS has an API Server Authorized IP Ranges enabled|[AZU008](/docs/azure/AZU008)|
|AZU009|Ensure AKS logging to Azure Monitoring is Configured|[AZU009](/docs/azure/AZU009)|
|AZU010|Ensure HTTPS is enabled on Azure Storage Account|[AZU010](/docs/azure/AZU010)|
|AZU011|Storage containers in blob storage mode should not have public access|[AZU011](/docs/azure/AZU011)|
|AZU012|The default action on Storage account network rules should be set to deny|[AZU012](/docs/azure/AZU012)|
|AZU013|Trusted Microsoft Services should have bypass access to Storage accounts|[AZU013](/docs/azure/AZU013)|
|AZU014|Storage accounts should be configured to only accept transfers that are over secure connections|[AZU014](/docs/azure/AZU014)|
|AZU015|The minimum TLS version for Storage Accounts should be TLS1_2|[AZU015](/docs/azure/AZU015)|
|AZU016|When using Queue Services for a storage account, logging should be enabled.|[AZU016](/docs/azure/AZU016)|
|AZU017|SSH access should not be accessible from the Internet, should be blocked on port 22|[AZU017](/docs/azure/AZU017)|
|AZU018|Auditing should be enabled on Azure SQL Databases|[AZU018](/docs/azure/AZU018)|
|AZU019|Database auditing rentention period should be longer than 90 days|[AZU019](/docs/azure/AZU019)|

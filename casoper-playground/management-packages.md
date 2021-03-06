---
title: Azure Management Libraries for .NET 
description: A listing of all of the .NET SDK for Azure libraries and NuGet packages.
keywords: Azure .NET, SDK, Azure .NET API Reference, Azure .NET class library
author: camsoper
manager: douge
ms.author: casoper
ms.date: 03/06/2016
ms.topic: managed-reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.assetid: 
---

# Azure Management Libraries for .NET

Use these libraries to **manage** Azure resources in your applications.

> [!WARNING]
> This is currently a list of packages, but will be fleshed out with popular management-plane scenarios, etc.  These will link to "Get Started".

## Packages

> [!TIP]
> [Fluent libraries](https://azure.microsoft.com/blog/simpler-azure-management-libraries-for-net/) improve the developer experience by providing a higher-level, object-oriented API optimized for readability and writability. They clarify what is required vs. optional vs. non-modifiable. These libraries can run side-by-side with non-fluent libraries, so use the fluent packages if you prefer that syntax. [Microsoft.Azure.Management.Fluent](https://www.nuget.org/packages/Microsoft.Azure.Management.Fluent) is a rollup package that contains all of the fluent management libraries.

Service | Fluent package | Standard package
--------|---------------------------|-------------------------
[Analysis Services](/azure/analysis-services/) | | [![Microsoft.Azure.Management.Analysis](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Analysis.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.ApiManagement)
[ApiManagement](/azure/api-management/) | | [![Microsoft.Azure.Management.ApiManagement](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.ApiManagement.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.ApiManagement)
[Authorization](/rest/api/authorization) | | [![Microsoft.Azure.Management.Authorization](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Authorization.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Authorization)
[Automation](/azure/automation/) | | [![Microsoft.Azure.Management.Automation](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Automation.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation)
[Backup](/azure/backup/) | | [![Microsoft.Azure.Management.RecoveryServices.Backup](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.RecoveryServices.Backup.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices.Backup)
[Batch](/azure/batch/) | [![Microsoft.Azure.Management.Batch.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Batch.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch.Fluent) | [![Microsoft.Azure.Management.Batch](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Batch.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch)
[Billing](/azure/billing/) | | [![Microsoft.Azure.Management.Billing](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Billing.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing)
[CDN](/azure/cdn/) | [![Microsoft.Azure.Management.Cdn.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Cdn.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) | [![Microsoft.Azure.Management.Cdn](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Cdn.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn)
[Cognitive Services](/azure/cognitive-services/) | | [![Microsoft.Azure.Management.CognitiveServices](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.CognitiveServices.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.CognitiveServices)
[Commerce](/azure/billing/billing-usage-rate-card-overview) | | [![Microsoft.Azure.Commerce.UsageAggregates](https://img.shields.io/nuget/vpre/Microsoft.Azure.Commerce.UsageAggregates.svg)](https://www.nuget.org/packages/Microsoft.Azure.Commerce.UsageAggregates)
[Container Registry](/azure/container-registry) | | [![Microsoft.Azure.Management.ContainerRegistry](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.ContainerRegistry.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerRegistry)
[Customer Insights](/dynamics365/customer-insights) | | [![Microsoft.Azure.Management.CustomerInsights](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.CustomerInsights.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.CustomerInsights)
[Data Factory](/azure/data-factory/) | | [![Microsoft.Azure.Management.DataFactories](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.DataFactories.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories)
[Data Lake Analytics](/azure/data-lake-analytics/) | | [![Microsoft.Azure.Management.DataLake.Analytics](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.DataLake.Analytics.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Analytics)
[Data Lake Store](/azure/data-lake-store/) | | [![Microsoft.Azure.Management.DataLake.Store](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.DataLake.Store.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store)<br/>[![Microsoft.Azure.Management.DataLake.StoreUploader](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.DataLake.StoreUploader.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.StoreUploader)
[DevTest Labs](/azure/devtest-lab/) | | [![Microsoft.Azure.Management.DevTestLabs](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.DevTestLabs.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.DevTestLabs)
[DNS](/azure/dns/) | [![Microsoft.Azure.Management.Dns.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Dns.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns.Fluent) | [![Microsoft.Azure.Management.Dns](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Dns.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns)
[Graph](/rest/api/graphrbac) | | [![Microsoft.Azure.Graph.RBAC](https://img.shields.io/nuget/vpre/Microsoft.Azure.Graph.RBAC.svg)](https://www.nuget.org/packages/Microsoft.Azure.Graph.RBAC)
[HD Insight](/azure/hdinsight/) | | [![Microsoft.Azure.Management.HDInsight](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.HDInsight.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight)
[Key Vault](/azure/key-vault/) | [![Microsoft.Azure.Management.KeyVault.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.KeyVault.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent) | [![Microsoft.Azure.Management.KeyVault](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.KeyVault.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault)
[Log Analytics](/azure/log-analytics/) | | [![Microsoft.Azure.Management.OperationalInsights](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.OperationalInsights.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.OperationalInsights)
[Logic Apps](/azure/logic-apps/) | | [![Microsoft.Azure.Management.Logic](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Logic.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Logic)
[MachineLearning](/azure/machine-learning/) | | [![Microsoft.Azure.Management.MachineLearning](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Logic.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.MachineLearning)
[Media Services](/azure/media-services/) | | [![Microsoft.Azure.Management.Media](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Media.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Media)
[Monitor](/azure/monitoring-and-diagnostics/) | | [![Microsoft.Azure.Insights](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Insights.svg)](https://www.nuget.org/packages/Microsoft.Azure.Insights)
[Notification Hubs](/azure/notification-hubs/) | | [![Microsoft.Azure.Management.NotificationHubs](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.NotificationHubs.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs)
[PowerBI Embedded](/azure/power-bi-embedded/) | | [![Microsoft.Azure.Management.PowerBIEmbedded](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.PowerBIEmbedded.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.PowerBIEmbedded)
[Recovery Services](/azure/site-recovery/) | | [![Microsoft.Azure.Management.RecoveryServices](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.RecoveryServices.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices)
[Redis Cache](/azure/redis-cache/) | [![Microsoft.Azure.Management.Redis.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Redis.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) | [![Microsoft.Azure.Management.Redis](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Redis.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis)
[Resource Manager](/azure/azure-resource-manager/) | [![Microsoft.Azure.Management.ResourceManager.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.ResourceManager.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) | [![Microsoft.Azure.Management.ResourceManager](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.ResourceManager.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager)
[Scheduler](/azure/scheduler/) | | [![Microsoft.Azure.Management.Scheduler](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Scheduler.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Scheduler)
[Search](/azure/search/) |  | [![Microsoft.Azure.Management.Search](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Search.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Search)
[Service Bus](/azure/service-bus/) | | [![Microsoft.Azure.Management.ServiceBus](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.ServiceBus.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus)
[SQL Database](/azure/sql-database/) | [![Microsoft.Azure.Management.Sql.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Sql.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent) | [![Microsoft.Azure.Management.Sql](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Sql.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql)
[Storage](/azure/storage/) | [![Microsoft.Azure.Management.Storage.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Storage.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) | [![Microsoft.Azure.Management.Storage](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Storage.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage)<br/>[![Microsoft.Azure.Storage.DataMovement](https://img.shields.io/nuget/vpre/Microsoft.Azure.Storage.DataMovement.svg)](https://www.nuget.org/packages/Microsoft.Azure.Storage.DataMovement)
[Stream Analytics](/azure/stream-analytics/) | | [![Microsoft.Azure.Management.StreamAnalytics](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.StreamAnalytics.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics)
[Traffic Manager](/azure/traffic-manager/) | [![Microsoft.Azure.Management.TrafficManager.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.TrafficManager.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent) | [![Microsoft.Azure.Management.TrafficManager](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.TrafficManager.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager)
[Virtual Machines](/azure/virtual-machines/) | [![Microsoft.Azure.Management.Compute.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Compute.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent)| [![Microsoft.Azure.Management.Compute](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Compute.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute)
[Virtual Network](/azure/virtual-network/) | [![Microsoft.Azure.Management.Network.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Network.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) | [![Microsoft.Azure.Management.Network](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Network.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Network)
[Web Apps](/azure/app-service-web) | [![Microsoft.Azure.Management.AppService.Fluent](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.AppService.Fluent.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) | [![Microsoft.Azure.Management.Websites](https://img.shields.io/nuget/vpre/Microsoft.Azure.Management.Websites.svg)](https://www.nuget.org/packages/Microsoft.Azure.Management.Websites)


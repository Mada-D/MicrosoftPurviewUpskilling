# Microsoft Purview Upskilling


## :dart: Objectives
The objective for this learning path is to help every user building knowledge on Microsoft Purview, starting with basic activities, official documentation or tutorials, and then deep dive into more complex scenarios. 
<br>
<br>
## :exclamation: Mandatory prerequisites

1. If you are <b>new to Azure</b>, [Azure Fundamentals](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/) is the best place to start your cloud journey. Estimate time of completion: 8 hours.

    >:bulb: By following the online learning paths, you will gain basic knowledge of cloud services and how those services are provided with Azure, but also become familiar with concepts of networking, storage, compute, application support, and application development.
3. If you are familiar with Azure concepts, but you are <b>new to Azure Data Services</b>, then [Microsoft Azure Data Fundamentals](https://docs.microsoft.com/en-us/learn/certifications/exams/dp-900) is your next step in your Azure Purview upskilling journey.  Estimate time of completion: 6 hours.

    >:bulb: By following the online learning paths, you will get the foundational knowledge of core data concepts and how they are implemented using Microsoft Azure data services.
5. An [Azure account](https://azure.microsoft.com/en-us/free/) with an <b>active subscription</b>.

    >:bulb: For the technical exercises, you have to use your own subscription and make sure that:
    > * Your must have permissions to create resources in your Azure subscription.
    > * Your subscription must have the following resource providers registered: **Microsoft.Purview**, **Microsoft.Storage**, and **Microsoft.EventHub**. Instructions on how to register a resource provider via the Azure Portal can be found [here](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-providers-and-types#azure-portal).
<br>
<br>

 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>
 
## :books: Learning Modules


### Table of Contents

1. [Introduction to Microsoft Purview](#1-introduction-to-microsoft-purview)
2. [Hands-on workshop](#2-hands-on-workshop)
3. [Security & Networking](#3-security--networking)
4. [Monitoring](#4-monitoring)
5. [Business Continuity and Disaster Recovery](#5-business-continuity-and-disaster-recovery)
6. [Architecture considerations](#6-architecture-considerations)
7. [Advanced topics with RestAPIs and custom development](#7-advanced-topics-with-restapis-and-custom-development)


## 1. <b>Introduction to Microsoft Purview</b>
* [A guide to data governance](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4GEtu) - estimate time of completion: 90 min.
* [Vision and demo of Microsoft Purivew](https://www.youtube.com/watch?v=aKiBFmiJEBQ) - estimate time of completion: 45 min.
* [Introduction to Microsoft Purview](https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-purview/) - estimate time of completion: 30 min.
* [Overview of Microsoft Purview](https://docs.microsoft.com/en-us/azure/purview/overview) - estimate time of completion: 10 min.
* [Microsoft Purview product glossary](https://docs.microsoft.com/en-us/azure/purview/reference-azure-purview-glossary) - estimate time of completion: 10 min.
* <b>Microsoft Purview main components</b> <i>(there are many more components within Microsoft Purview, but the ones below are the most common. For a full list, please check the official documentation [here](https://docs.microsoft.com/en-us/azure/purview/))</i>:
     * Data Map
          * Collections
            * [Create and manage collections](https://docs.microsoft.com/en-us/azure/purview/how-to-create-and-manage-collections) - estimate time of completion: 10 min.
            * [Best practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-collections) - estimate time of completion: 15 min.
          * Sources
            * [Supported sources and file types](https://docs.microsoft.com/en-us/azure/purview/azure-purview-connector-overview) - estimate time of completion: 10 min.
            * [User Guide](https://docs.microsoft.com/en-us/azure/purview/manage-data-sources) - estimate time of completion: 10 min.
         * Classification
           * [Classification Concept](https://docs.microsoft.com/en-us/azure/purview/concept-classification) - estimate time of completion: 10 min.
           * [Supported Classifications](https://docs.microsoft.com/en-us/azure/purview/supported-classifications)  - estimate time of completion: 2 hours.
           * [Custom Classifications](https://docs.microsoft.com/en-us/azure/purview/create-a-custom-classification-and-classification-rule) - estimate time of completion: 10 min.
           * [Classification Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-classification) - estimate time of completion: 10 min.
         * Data Lineage
           * [Data Lineage Concept](https://docs.microsoft.com/en-us/azure/purview/concept-data-lineage) - estimate time of completion: 10 min.
           * [User Guide](https://docs.microsoft.com/en-us/azure/purview/catalog-lineage-user-guide) - estimate time of completion: 10 min.
           * [Best practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-lineage-azure-data-factory) - estimate time of completion: 10 min.
            
     * Data Catalog
          * Glossary 
             * [Business Glossary Concept](https://docs.microsoft.com/en-us/azure/purview/concept-business-glossary) - estimate time of completion: 10 min.
             * [User Guide](https://docs.microsoft.com/en-us/azure/purview/how-to-create-import-export-glossary) - estimate time of completion: 10 min.
             * [Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-glossary) - estimate time of completion: 10 min. 
           
          * Data Policies
            * [Data Owner policies concept](https://docs.microsoft.com/en-us/azure/purview/concept-data-owner-policies) - estimate time of completion: 10 min. 
            * [User Guide on how to enable data use governance](https://docs.microsoft.com/en-us/azure/purview/how-to-enable-data-use-governance) - estimate time of completion: 10 min. 
        * Data Insights
            * [Data Insights concept](https://docs.microsoft.com/en-us/azure/purview/concept-insights) - estimate time of completion: 10 min. 


 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>

## 2. <b>Hands-on workshop</b>
* [Microsoft Purview Workshop](https://github.com/tayganr/purviewlab) - estimate time of completion: 5 hours.


 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>

## 3. <b>Security & Networking</b>
* Data Level
    * [Access Control in Microsoft Purview](https://docs.microsoft.com/en-us/azure/purview/catalog-permissions) - estimate time of completion: 10 min.
    * [Data Owner policies](https://docs.microsoft.com/en-us/azure/purview/concept-data-owner-policies) - estimate time of completion: 10 min.
* Account Level
    * [Private endpoints](https://docs.microsoft.com/en-us/azure/purview/catalog-private-link) - estimate time of completion: 1 hour.
    * [Conditional Access](https://docs.microsoft.com/en-us/azure/purview/catalog-conditional-access) - estimate time of completion: 10 min.
    * [Integrate Microsoft Purview with Azure Security Products](https://docs.microsoft.com/en-us/azure/purview/how-to-integrate-with-azure-security-products) - estimate time of completion: 10 min.
    * [Security Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-security) - estimate time of completion: 20 min.
    * [Networking Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-network) - estimate time of completion: 15 min.
    * [Azure security baseline for Microsoft Purview](https://docs.microsoft.com/en-us/security/benchmark/azure/baselines/purview-security-baseline) - estimate time of completion: 2 hours, by going through the referenced materials.


 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>

## 4. <b>Monitoring</b>
* [Microsoft Purview metrics in Azure Monitor](https://docs.microsoft.com/en-us/azure/purview/how-to-monitor-with-azure-monitor) - estimate time of completion: 10 min.
* [Microsoft Purview: Audit logs, diagnostics, and activity history](https://docs.microsoft.com/en-us/azure/purview/tutorial-purview-audit-logs-diagnostics) - estimate time of completion: 10 min.

 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>

## 5. <b>Business Continuity and Disaster Recovery</b>
* [Disaster Recovery Overview](https://docs.microsoft.com/en-us/azure/purview/disaster-recovery) -  estimate time of completion: 10 min.
* [Disaster recovery Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-migration) -  estimate time of completion: 15 min.
    

 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>

## 6. <b>Architecture considerations</b>
* [Default Microsoft Purview Account](https://docs.microsoft.com/en-us/azure/purview/concept-default-purview-account) -  estimate time of completion: 5 min.
* [Microsoft Purview Limits](https://docs.microsoft.com/en-us/azure/purview/how-to-manage-quotas) -  estimate time of completion: 5 min.
* [Microsoft Purview Checklist](https://docs.microsoft.com/en-us/azure/purview/tutorial-azure-purview-checklist) -  estimate time of completion: 10 min.
* [Business processes for managing data effectively](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-asset-lifecycle) -  estimate time of completion: 10 min.
* [Account architecture Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-accounts) -  estimate time of completion: 5 min.
* [Automation Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-automation) -  estimate time of completion: 10 min.
    

 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>

## 7. <b>Advanced topics with RestAPIs and custom development</b>
* RestAPIs basics
    * [Architecture](https://atlas.apache.org/2.0.0/Architecture.html), [Atlas Model](https://cwiki.apache.org/confluence/display/ATLAS/Atlas+Model) and [API definition](https://atlas.apache.org/api/v2/index.html) from Apache.org
    * [Tutorial](https://docs.microsoft.com/en-us/azure/purview/tutorial-using-rest-apis) on using the REST API in MS Docs
    * [API methods](https://docs.microsoft.com/en-us/azure/purview/tutorial-using-rest-apis#view-the-rest-apis-documentation) supported by Purview
    * [Azure Purview REST API Deep Dive](https://www.youtube.com/watch?v=4qzjnMf1GN4&feature=youtu.be)
    * [CLI wrapper to Microsoft Purview APIs](https://www.youtube.com/watch?v=ycr1G5iMM6U)
    * [API Documentation](https://github.com/Azure/Purview-Samples/raw/master/rest-api/PurviewCatalogAPISwagger.zip) 
* Microsoft Purview REST API: 
     * [Part 1: Getting Started](https://www.linkedin.com/pulse/azure-purview-rest-api-part-1-getting-started-raihan-alam/)
     * [Part 2: Type Definition & Entities](https://www.linkedin.com/pulse/azure-purview-rest-api-part-2-type-definition-entities-raihan-alam/)
     * [Part 3: Custom Lineage](https://www.linkedin.com/pulse/azure-purview-rest-api-part-3-custom-lineage-raihan-alam/)
     * [Part 4: Understanding Relationship and Lineage](https://www.linkedin.com/pulse/azure-purview-rest-api-part-4-understanding-lineage-raihan-alam/)

* Packages/samples/SDKs
    * [Microsoft Purview Samples](https://github.com/Azure/Purview-Samples) 
    * [Microsoft Purview Catalog client library for .NET](https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/purview/Azure.Analytics.Purview.Catalog) 
    * [PurviewCLI](https://github.com/tayganr/purviewcli)    
    * [PyApacheAtlas](https://github.com/wjohnson/pyapacheatlas)  
* Custom data sources
    * [Data Source](https://github.com/microsoft/Purview-Custom-Connector-Solution-Accelerator/blob/master/examples/tag_db/tag_db.md)
    * [Analysis Services](https://github.com/wjohnson/pyapacheatlas/blob/master/samples/notebooks/Purview_Analysis_Services_Custom.ipynb)
* Lineage
    * [SSIS Lineage](https://github.com/microsoft/Purview-Custom-Connector-Solution-Accelerator/blob/master/examples/ssis/ssis.md)    
    * [Databricks Lineage](https://github.com/intellishore/data-lineage-databricks-to-purview)    
    * [PowerBI Full Lineage](https://github.com/franmer2/AzurePurviewFullPBILineage_US)    
    * [WebApp Lineage](https://github.com/pietheinstrengholt/purview-nodejs-lineage-registration)    
* [Publish and subscribe to Kafka](https://github.com/devlace/purview-pubsub)    
* [Purview Classification drift notifier](https://github.com/mdrakiburrahman/purview-classification-drift-notifier)    
* [Containerized app for declaring custom sensitivity labels to assets as glossary terms](https://github.com/mdrakiburrahman/purview-asset-ingestor)    
* [ARM template for Microsoft Purview](https://github.com/kkaarel/azurepurview)    


 <div align="right"><a href="#azure-purview-upskilling">↥ back to top</a></div>







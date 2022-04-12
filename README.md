# Azure Purview Upskilling


## :dart: Objectives
The objective for this learning path is to help every user building knowledge on Azure Purview, starting with basic activities, official documentation or tutorials, and then deep dive into more complex scenarios. 
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

 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>
 
## :books: Learning Modules
1. <b>Introduction to Azure Purview</b>
    * [Vision and demo of Azure Purivew](https://www.youtube.com/watch?v=aKiBFmiJEBQ) - estimate time of completion: 45 min.
    * [Introduction to Azure Purview](https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-purview/) - estimate time of completion: 30 min.
    * [Overview of Azure Purview](https://docs.microsoft.com/en-us/azure/purview/overview) - estimate time of completion: 10 min.
    * [Azure Purview product glossary](https://docs.microsoft.com/en-us/azure/purview/reference-azure-purview-glossary) - estimate time of completion: 10 min.
    * <b>Azure Purview main components</b> <i>(there are many more components within Azure Purview, but the ones below are the most common. For a full list, please check the official documentation [here](https://docs.microsoft.com/en-us/azure/purview/))</i>:
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


<br>
 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>

2. <b>Hands-on workshop</b>
    * [Azure Purview Workshop](https://github.com/tayganr/purviewlab) - estimate time of completion: 5 hours.


<br>

 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>

3. <b>Security & Networking</b>
    * Data Level
        * [Access Control in Azure Purview](https://docs.microsoft.com/en-us/azure/purview/catalog-permissions) - estimate time of completion: 10 min.
        * [Data Owner policies](https://docs.microsoft.com/en-us/azure/purview/concept-data-owner-policies) - estimate time of completion: 10 min.
    * Account Level
        * [Private endpoints](https://docs.microsoft.com/en-us/azure/purview/catalog-private-link) - estimate time of completion: 1 hour.
        * [Conditional Access](https://docs.microsoft.com/en-us/azure/purview/catalog-conditional-access) - estimate time of completion: 10 min.
        * [Integrate Azure Purview with Azure Security Products](https://docs.microsoft.com/en-us/azure/purview/how-to-integrate-with-azure-security-products) - estimate time of completion: 10 min.
        * [Security Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-security) - estimate time of completion: 20 min.
        * [Networking Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-network) - estimate time of completion: 15 min.
        * [Azure security baseline for Azure Purview](https://docs.microsoft.com/en-us/security/benchmark/azure/baselines/purview-security-baseline) - estimate time of completion: 2 hours, by going through the referenced materials.


<br>

 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>

4. <b>Monitoring</b>
    * [Azure Purview metrics in Azure Monitor](https://docs.microsoft.com/en-us/azure/purview/how-to-monitor-with-azure-monitor) - estimate time of completion: 10 min.
    * [Azure Purview: Audit logs, diagnostics, and activity history](https://docs.microsoft.com/en-us/azure/purview/tutorial-purview-audit-logs-diagnostics) - estimate time of completion: 10 min.


<br>

 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>

6. <b>Business Continuity and Disaster Recovery</b>
    * [Disaster Recovery Overview](https://docs.microsoft.com/en-us/azure/purview/disaster-recovery) -  estimate time of completion: 10 min.
    * [Disaster recovery Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-migration) -  estimate time of completion: 15 min.
    
<br>

 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>

7. <b>Architecture considerations</b>
    * [Default Azure Purview Account](https://docs.microsoft.com/en-us/azure/purview/concept-default-purview-account) -  estimate time of completion: 5 min.
    * [Azure Purview Limits](https://docs.microsoft.com/en-us/azure/purview/how-to-manage-quotas) -  estimate time of completion: 5 min.
    * [Azure Purview Checklist](https://docs.microsoft.com/en-us/azure/purview/tutorial-azure-purview-checklist) -  estimate time of completion: 10 min.
    * [Business processes for managing data effectively](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-asset-lifecycle) -  estimate time of completion: 10 min.
    * [Account architecture Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-accounts) -  estimate time of completion: 5 min.
    * [Automation Best Practices](https://docs.microsoft.com/en-us/azure/purview/concept-best-practices-automation) -  estimate time of completion: 10 min.
    
<br>

 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>

8. <b>Advanced topics with RestAPIs and custom development</b>
    * Packages/samples/SDKs
        * [Azure Purview Samples](https://github.com/Azure/Purview-Samples) 
        * [Azure Purview Catalog client library for .NET](https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/purview/Azure.Analytics.Purview.Catalog) 
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
    * [ARM template for Azure Purview](https://github.com/kkaarel/azurepurview)    


 <div align="right"><a href="#AzurePurviewUpskilling">↥ back to top</a></div>







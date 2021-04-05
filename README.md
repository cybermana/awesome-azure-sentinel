# Awesome Azure Sentinel [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources, repos, scripts, tools, queries and learning resouces about the Azure Sentinel. Inspired by Sindre Sorhus and his [awesome](https://github.com/sindresorhus/awesome) collection

## About Awesome Azure Sentinel

Imagine a cloud-native Security Incident and Event Management (SIEM) and Security Orchestration & Automated Response (SOAR) platform that enables you to proactively detect, respond and recover from security related incidents. Azure Sentinel is a next-generation, cloud-native SIEM/SOAR platform that enables you to proactively detect and respond to emerging threats and risks that impact your business.

Brought to you by [Cybermana](https://www.cybermana.net) - helping you unlock the power of your cyber resilience.

## Contents

- [Important Resources](#important-resources)
  - [Licensing](#licensing)
  - [Products by Region](#products-by-region)
  - [Updates and Roadmaps](#updates-and-roadmaps)
- [Azure Sentinel](#azure-sentinel)
- [Communities](##communities)
- [Learning Resources](##learning-resources)

## Important Resources

> About this section. As well as learning about the tech, its important that you also get to know about the licensing, service availability and product roadmaps. We've collated some important resources that we think you should check out. Of course, if you'd prefer to jump straight into the interesting stuff then [click here](##technologies).

### Licensing

COMING SOON

### Products by Region

It's important to understand which Microsoft Cloud Service is available within which Microsoft Region, as this may influence how you choose to use them.

- [Azure Data Centre Locations](https://azure.microsoft.com/en-gb/global-infrastructure/geographies/) - Learn more about where the Microsoft data centres are located and how that may impact your cloud journey.
- [Azure Products by Region](https://azure.microsoft.com/en-us/global-infrastructure/services/) - Learn more about which Microsoft products are available in which Microsoft Data Centre.

### Updates and Roadmaps

- [Roadmap: Azure Sentinel](https://azure.microsoft.com/en-us/updates/?category=security&query=azure%20sentinel) - Learn more about the Azure roadmap and what is in the pipeline for the future.
- [What's new in Azure Sentinel?](https://docs.microsoft.com/en-gb/azure/sentinel/whats-new) - Learn more about what's new in Microsoft Azure Sentinel.
- [Important upcoming changes to Azure Security Center?](https://docs.microsoft.com/en-us/azure/security-center/upcoming-changes) - Learn more about what's upcoming with Azure Security Center.

## Azure Sentinel

### Useful Resources

- [Introduction to Azure Sentinel](https://docs.microsoft.com/en-gb/azure/sentinel/overview)
- [What's new in Azure Sentinel?](https://docs.microsoft.com/en-gb/azure/sentinel/whats-new)
- [Azure Sentinel Documentation](https://docs.microsoft.com/en-gb/azure/sentinel/)

### Design and Deploy

- [Quickstart: Onboarding Azure Sentinel](https://docs.microsoft.com/en-us/azure/sentinel/quickstart-onboard)
- [Deploying and managing Azure Sentinel as Code with ARM Templates](https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928)
- [Deploying and managing Azure Sentinel Ninja Style with ARM templates and CI/CD pipelines](https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-ninja-style/ba-p/1858073)
- [Deploying and Managing Azure Sentinel as Code with Terraform](https://msandbu.org/automating-azure-sentinel-deployment-using-terraform-and-powershell/)

### Data Connectors

- [Connect Data Sources](https://docs.microsoft.com/en-us/azure/sentinel/connect-data-sources)
- [The **Grand List** of Azure Sentinel Data Connectors](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-the-connectors-grand-cef-syslog-direct-agent/ba-p/803891)
- [Create custom connectors for Azure Sentinel](https://docs.microsoft.com/en-us/azure/sentinel/create-custom-connector)

### Log Management

- [Using Azure Data Explorer for long-term retention of Azure Sentinel logs](https://techcommunity.microsoft.com/t5/azure-sentinel/using-azure-data-explorer-for-long-term-retention-of-azure/ba-p/1883947)
- [Export log data from Azure Sentinel to Azure Storage and Event Hub](https://docs.microsoft.com/en-us/cli/azure/monitor/log-analytics/workspace/data-export?view=azure-cli-latest)
- [Export log data from Azure Sentinel to long-term storage using Logic Apps](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/logs-export-logic-app)
- [Configure table level retention settings to set fine-grained retention periods](https://techcommunity.microsoft.com/t5/premier-field-engineering/azure-log-analytics-data-retention-by-type-in-real-life/ba-p/1416287)
- [Configure resource-level role based access control (RBAC)](https://techcommunity.microsoft.com/t5/azure-sentinel/controlling-access-to-azure-sentinel-data-resource-rbac/ba-p/1301463)
- [Configure table-level role based access control (RBAC)](https://techcommunity.microsoft.com/t5/azure-sentinel/table-level-rbac-in-azure-sentinel/ba-p/965043)
- [Delete Personal Data or PII from your Azure Sentinel and Log Analytics Workspaces](https://docs.microsoft.com/en-gb/azure/azure-monitor/logs/personal-data-mgmt)
- [Learn how to audit Azure Sentinel activities](https://techcommunity.microsoft.com/t5/azure-sentinel/auditing-azure-sentinel-activities/ba-p/1718328)
- [Use Private Links to ensure logs never leave your private network](https://docs.microsoft.com/en-us/azure/azure-monitor/logs/private-link-security)

### Visualising log data with Azure Sentinel Workbooks

- [Visualise and monitor your data with Azure Sentinel Workbooks](https://docs.microsoft.com/en-us/azure/sentinel/tutorial-monitor-your-data)
- [Billy York's Azure Monitor Workbook Training](https://youtu.be/iGiPpD_-10M)
- [Top Azure Sentinel Workbooks](https://docs.microsoft.com/en-gb/azure/sentinel/top-workbooks)
- [Investigation Insights Workbook](https://techcommunity.microsoft.com/t5/azure-sentinel/announcing-the-investigation-insights-workbook/ba-p/1816903)
- [Visualise MS Teams Collaboration in Azure Sentinel Workbooks](https://techcommunity.microsoft.com/t5/azure-sentinel/graph-visualization-of-external-teams-collaborations-in-azure/ba-p/1356847)
- [Visualise Impossible Travel Events in Azure Sentinel Workbooks](https://techcommunity.microsoft.com/t5/azure-sentinel/how-to-use-azure-sentinel-to-follow-a-users-travel-and-map-their/ba-p/981716)
- [Visualise Insecure Protocols in Azure Sentinel Workbooks](https://techcommunity.microsoft.com/t5/azure-sentinel/azure-sentinel-insecure-protocols-workbook-implementation-guide/ba-p/1197564)
- [Visualse Microsoft Endpoint Manager enrolled devices in Azure Sentinel Workbooks](https://techcommunity.microsoft.com/t5/azure-sentinel/secure-working-from-home-deep-insights-at-enrolled-mem-assets/ba-p/1424255)
- [Azure Sentinel Workbooks Gallery (Github)](https://github.com/Azure/Azure-Sentinel/tree/master/Workbooks)

### Enrich log data with threat intelligence

- [Import threat intelligence into Azure Sentinel](https://docs.microsoft.com/en-us/azure/sentinel/import-threat-intelligence)
- [Manage your threat indicators in Azure Sentinel](https://docs.microsoft.com/en-us/azure/sentinel/import-threat-intelligence#manage-your-threat-indicators-in-the-new-threat-intelligence-area-of-azure-sentinel)
- [Generate alerts and incidents with Threat Intelligence Analytics](https://techcommunity.microsoft.com/t5/azure-sentinel/become-an-azure-sentinel-ninja-the-complete-level-400-training/ba-p/1246310)
- [Visualise your threat intelligence using Azure Sentinel Workbooks](https://docs.microsoft.com/en-us/azure/sentinel/import-threat-intelligence#workbooks-provide-insights-about-your-threat-intelligence)
- [Ingest AlienVault OTX threat intelligence into Azure Sentinel](https://azurecloudai.blog/2020/12/04/how-to-connect-alienvault-otx-to-azure-sentinel/)
- [**Playbook**: Get Threat Intelligence from OTX](https://github.com/richlilly2004/Azure-Sentinel/tree/master/Playbooks/Get-TIfromOTX)

### Enrich log data with vulnerability management data

- [Integrate Vulnerability Management in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/how-to-integrate-vulnerability-management-in-azure-sentinel/ba-p/1635728)
- [**Playbook**: Get Tenable.IO Vulnerability Data](https://github.com/richlilly2004/Azure-Sentinel/tree/master/Playbooks/Get-TenableVulns)

### Threat Hunting with Azure Sentinel

- [Construct KQL statements for Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/construct-kusto-query-language-statements/)
- [Analyze query results using KQL](https://docs.microsoft.com/en-gb/learn/modules/analyze-results-kusto-query-language/)
- [Build multi-table statements using KQL](https://docs.microsoft.com/en-gb/learn/modules/build-multi-table-statements-kusto-query-language/)
- [Work with data in Azure Sentinel using Kusto Query Language](https://docs.microsoft.com/en-gb/learn/modules/work-with-data-kusto-query-language/)
- [Explain threat hunting concepts in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/what-is-threat-hunting-azure-sentinel/)
- [Threat hunting with Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/hunt-threats-sentinel/)
- [Hunt for threats using notebooks in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/perform-threat-hunting-sentinel-with-notebooks/)

## Communities

- [Tech Community: Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-sentinel/bg-p/AzureSentinelBlog)

## Learning Resources

- [Become an Azure Sentinel Ninja](https://techcommunity.microsoft.com/t5/azure-sentinel/become-an-azure-sentinel-ninja-the-complete-level-400-training/ba-p/1246310)
- [Introduction to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/intro-to-azure-sentinel/)
- [Create and manage Azure Sentinel workspaces](https://docs.microsoft.com/en-gb/learn/modules/create-manage-azure-sentinel-workspaces/)
- [Query logs in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/query-logs-azure-sentinel/)
- [Use watchlists in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/use-watchlists-azure-sentinel/)
- [Utilize threat intelligence in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/utilize-threat-intelligence-azure-sentinel/)
- [Connect data to Azure Sentinel using data connectors](https://docs.microsoft.com/en-gb/learn/modules/connect-data-to-azure-sentinel-with-data-connectors/)
- [Connect Microsoft services to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/connect-microsoft-services-to-azure-sentinel/)
- [Connect Microsoft 365 Defender to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/connect-microsoft-defender-365-to-azure-sentinel/)
- [Connect Windows hosts to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/connect-windows-hosts-to-azure-sentinel/)
- [Connect Common Event Format logs to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/connect-common-event-format-logs-to-azure-sentinel/)
- [Connect syslog data sources to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/connect-syslog-data-sources-to-azure-sentinel/)
- [Connect threat indicators to Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/connect-threat-indicators-to-azure-sentinel/)
- [Threat detection with Azure Sentinel analytics](https://docs.microsoft.com/en-gb/learn/modules/analyze-data-in-sentinel/)
- [Threat response with Azure Sentinel playbooks](https://docs.microsoft.com/en-gb/learn/modules/threat-response-sentinel-playbooks/)
- [Security incident management in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/incident-management-sentinel/)
- [Use entity behavior analytics in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/use-entity-behavior-analytics-azure-sentinel/)
- [Query, visualize, and monitor data in Azure Sentinel](https://docs.microsoft.com/en-gb/learn/modules/query-data-sentinel/)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

If you'd like to learn more about the Cybermana community then check us out at:

- [The Cybermana Website](https://www.cybermana.net)
- [Our LinkedIn Community](https://www.linkedin.com/company/cybermana)
- [Our Facebook Community](https://www.facebook.com/cybermanaUK/ )
- [Twitter](https://twitter.com/CybermanaUK )

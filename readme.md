# Speaker

![Sergio Zenatti Filho](qrcode.JPG)


# Welcome to **Learning Series – Session 1: Azure Data Services - The Beginning**

## Azure Overview

- [Azure global infrastructure](https://infrastructuremap.microsoft.com/)
- [Azure Products by Region](https://azure.microsoft.com/en-us/explore/global-infrastructure/products-by-region/)
- [Azure Free/Trial Account](https://azure.microsoft.com/en-gb/free/)
- [Starting with Azure](https://azure.microsoft.com/en-us/)

## Azure Data Services and Architecture

- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/)
- [Microsoft - Github](https://github.com/microsoft)
- [Microsoft Azure - Github](https://github.com/azure)
- [Power BI Samples](https://github.com/microsoft/powerbi-desktop-samples/blob/main/README.md)
- [Azure architecture icons](https://learn.microsoft.com/en-us/azure/architecture/icons/)
- [Azure Design by David Summers](https://github.com/David-Summers/Azure-Design)

## Training and Certification

- [Microsoft Azure Virtual Training Day:Fundamentals](https://info.microsoft.com/AU-HCSAzureHybridInfra-CATALOG-FY21-07Jul-07-MicrosoftAzureVirtualTrainingDayFundamentals-SRDEM33006_CatalogDisplayPage.html)
- [AZ-900 Azure Fundamentals Study Cram by John Savill's](https://www.youtube.com/watch?v=tQp1YkB2Tgs)
- [Microsoft Azure Virtual Training Day:Data Fundamentals](https://info.microsoft.com/AU-AzureSQL-CATALOG-FY21-02Feb-10-MicrosoftAzureVirtualTrainingDayDataFundamentals-SRDEM60617_CatalogDisplayPage.html)
- [DP-900 Data Fundamentals Study Cram by John Savill's](https://www.youtube.com/watch?v=0gtpasITVnk)
- [Virtual Training Days - ANZ](https://www.microsoft.com/en-au/business/learn/cloud-training-events/virtual-training-days/)
- [Microsoft Certifications](https://learn.microsoft.com/en-us/certifications/)

# Welcome to **Learning Series – Session 2: Azure Data Services - Moving Data**

## ETL and ELT

- [Azure Data Architecture Guide - ETL and ELT](https://learn.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl)
- [Modern Data Warehouse and Reverse ETL](https://www.jamesserra.com/archive/2021/04/modern-data-warehouse-reverse-etl/)
- [From Warehouse to Lakehouse - ETL/ELT Design Patterns With Azure Data Services](https://sqlofthenorth.blog/2021/03/29/elt-etl-design-patterns-with-azure-data-services/)

## (OLTP) Online Transaction Processing and (OLAP) Online Analytical Processing

- [Azure Data Architecture Guide - OLAP](https://learn.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-analytical-processing)
- [Azure Data Architecture Guide - OLTP](https://learn.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-transaction-processing)

## Batch and Streaming

- [Azure Data Architecture Guide - Batch Processing](https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/batch-processing)
- [Azure Data Architecture Guide - Streaming Processing](https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/stream-processing)

## Data Ingestion Patterns

- Full data ingestion: loads all data every data ingestion;
- Delta (Incremental) data ingestion: loads the changed data between an old watermark and a new watermark;
- [Incrementally load data from a source data store to a destination data store](https://learn.microsoft.com/en-us/azure/data-factory/tutorial-incremental-copy-overview)
- Change Data Capture (CDC) / Change Tracking: only read the source data that has changed since the last time the pipeline ran;
- [What is change data capture (CDC)?](https://learn.microsoft.com/en-us/sql/relational-databases/track-changes/about-change-data-capture-sql-server?view=sql-server-ver16)
- [Change data capture in Azure Data Factory and Azure Synapse Analytics](https://learn.microsoft.com/en-us/azure/data-factory/concepts-change-data-capture)
- Homogeneous data ingestion: is a pattern where data is moved between similar data storage systems, like Microsoft SQL Server to Microsoft SQL Server or similar formats like Parquet to Parquet;
- Heterogeneous data ingestion: is a pattern where data must be transformed, like changing a CSV file to Parquet or Parquet to Microsoft SQL Server;

## Data Ingestion OnPrem to Azure

- [Choose an Azure solution for data transfer](https://learn.microsoft.com/en-us/azure/storage/common/storage-choose-data-transfer-solution)

## Data Orchestration

- [Choose a data pipeline orchestration technology in Azure](https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/pipeline-orchestration-data-movement)

## Considerations

There are some principles to build a data ingestion to move data from Data Sources to an Analytics Platform. 

- Understand the data ingestion requirements and choose appropriate approach;
- Build a data ingestion pipeline that meets performance, latency, scale, security and governance needs;

## Next Step (Free Online Training)

- [Data integration at scale with Azure Data Factory or Azure Synapse Pipeline](https://learn.microsoft.com/en-us/training/paths/data-integration-scale-azure-data-factory/)
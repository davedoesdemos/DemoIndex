# DemoIndex

## Azure Demos

This is an index for all of the demo goodness on the site. Please also check out [My YouTube Channel](https://www.youtube.com/c/davedoesdemos) for video demos and [davedoesdemos.com](https://davedoesdemos.com) for other info.

[Data Lake Documentation and Opinions](https://github.com/davedoesdemos/DatalakeDocs)
This repo contains my opinions on best practices and other documentation around a data lake. Please consider this incomplete, and read it alongside other documentation from other sources. It will be updated as and when my thoughts change and I discuss topics with my team.

### Data DevOps (aka DataOps) Series

| SubCategory | Demo Instructions | YouTube Video | Description |
|:-----------:|-------------------|---------------|:-----------:|
| Azure Data Factory | [DevOps with ADF](https://github.com/davedoesdemos/DataDevOps/blob/master/Data_Factory/ADFDevOps.md) | [Video](https://youtu.be/CW5GXIEhePE ) | This demo shows how to use DevOps techniques with Azure Data Factory.  |
| Azure Databricks | [DevOps with Databricks](https://github.com/davedoesdemos/DataDevOps/blob/master/Databricks/DatabricksDevOps.md) | [Video](https://youtu.be/R7tJZelEt-Q ) | This demo shows how to use DevOps techniques with Azure Databricks Notebooks.  |
| Testing | [Intro to testing](https://github.com/davedoesdemos/DataDevOps/blob/master/TestingIntro/README.md) | [Video](https://youtu.be/H_IaqNDJ11c) | This demo introduces the process of testing in Azure DevOps  |
| Testing | [Data testing](https://github.com/davedoesdemos/DataDevOps/blob/master/Testing/README.md) | [No Video Yet](https://youtu.be/H_IaqNDJ11c) | This demo introduces data platform testing in Azure DevOps  |
| Python Testing | [Python testing](https://github.com/davedoesdemos/DataDevOps/tree/master/PythonTesting) | [No Video Yet](https://youtu.be/H_IaqNDJ11c) | This demo introduces python testing in Azure DevOps  |


### General Demos

| Category | SubCategory | Demo Instructions | YouTube Video | Description |
|:--------:|-------------|-------------------|:-------------:|-------------|
| Azure Data Factory | Ingest | [Google Big Query Ingest](https://github.com/davedoesdemos/GBQDemo/blob/master/GBQDemo.md) | [Video](https://www.youtube.com/watch?v=oRqRt7ya_DM) | This demo shows how to get Google BigQuery data into an Azure data lake using Azure Data Factory.  |
| Azure Data Factory | Ingest | [SFTPIngest](https://github.com/davedoesdemos/SFTPIngest/blob/master/SFTPIngest.md) | [Video](https://youtu.be/hjKPxK3hNT4) | This demo shows how to ingest data from an SFTP source to your Azure Data Lake |
| Azure Data Factory | External Data | [Quickwins-WeatherData](https://github.com/davedoesdemos/Quickwins-WeatherData/blob/master/QuickwinsWeatherData.md) | [Video](https://www.youtube.com/watch?v=CZFx9GVShn0) | This quick win demo is a very short and concise way to get weather data into your data lake to use for analytics. Here we use openweathermap.org but this example would work with any API source of data.  |
| Azure Data Factory | Data Flows | [Preview ADF Data Flows](https://github.com/davedoesdemos/PreviewMappingDataFlow/blob/master/PreviewMappingDataFlow.md) | [No Video Yet]() | This demo takes you through the preview mapping data flows functionality in Azure Data Factory. Sample data is included to make this a quick and easy one to try. |
| Azure Data Factory | DevOps | [Quickwins-ADFGit](https://github.com/davedoesdemos/Quickwins-ADFGit/blob/master/ADFGit.md) | [No Video Yet]() | This demo shows how to use Git repositories to version control and merge code from dev to prod in Data Factory |
| Logic Apps | Data Capture | [Quickwins-FormsData](https://github.com/davedoesdemos/Quickwins-FormsData/blob/master/QuickwinsFormsData.md) | [Video](https://youtu.be/PGnwvwJKs4g) | This demo shows how you can use a simple HTML form stored in Blob storage to submit data and store it as JSON (or any other format) in Logic Apps  |
| Logic Apps | Azure API | [Scale a Power BI Embedded Instance using Logic Apps](https://github.com/davedoesdemos/PBIEScale) | [No Video Yet](https://youtu.be/) | This demo shows how you can use a Logic App to scale a Power BI Embedded instance. This technique can be used for any Azure API call  |
| Cosmos DB | Gremlin | [CosmosDBGremlinPowerBI](https://github.com/davedoesdemos/CosmosDBGremlinPowerBI/blob/master/CosmosDBGremlinPowerBI.md) | [Video](https://youtu.be/kP9_8mbDXYA) | Build a graph database in Cosmos DB with the Gremlin model and then surface that graph data into Power BI |
| Power BI | Streaming Data | [Quickwins-PowerBIStreaming ](https://github.com/davedoesdemos/Quickwins-PowerBIStreaming/blob/master/PowerBIStreaming.md) | [No Video Yet]() | This very quick demo shows how to set up a streaming data source in PowerBI and generate some data with a Logic App to test it. |
| Cognitive Services | Translation | [Book Translator ](https://github.com/davedoesdemos/BookTranslator/blob/master/README.md) | [No Video Yet]() | This C# project is a book translator. It takes in a book in XML format and translates using the Azure cognitive services to a new language |
| Azure Functions | Streaming Data | [CSV from Blob to Event Hubs](https://github.com/davedoesdemos/CSVBlobToEventHub/blob/master/README.md) | [Video](https://youtu.be/_4yDWfaW89A ) | This project is a function app that collects CSVs from Blob and injects the rows one at a time into an Event Hub instance with optional delay |
| Stream Analytics Jobs | Streaming Data | [Global data distribution](https://github.com/davedoesdemos/globaldatareplication) | [Video](https://youtu.be/rfN0YGpdnNE) | This demo shows how to use Stream Analytics to distribute data from Event Hubs into SQL Servers globally with minimal latency using the CSV function app as a source |
| Storage | Tiering | [Logic App to archive new data](https://github.com/davedoesdemos/BlobArchiveFunction/blob/master/LogicApp.md) | [Video](https://youtu.be/uku7HN4zaDc) | This demo shows how to programmatically move data immediately to archive tier when it's ingested into a storage account using a Logic App. |
| Storage | Tiering | [Function App to archive new data](https://github.com/davedoesdemos/BlobArchiveFunction/blob/master/FunctionApp.md) | [No Video Yet](https://youtu.be/uku7HN4zaDc) | This demo shows how to programmatically move data immediately to archive tier when it's ingested into a storage account using a Function. |
| Storage | Tiering | [Function App to change tier by prefix or folder](https://github.com/davedoesdemos/BlobArchiveFunction/blob/master/BlobRecall.md) | [No Video Yet](https://youtu.be/uku7HN4zaDc) | This demo shows how to programmatically move data to a different tier based on container, prefix (folder) and a tier parameter. |
| Log Analytics | Data Ingest | [Function App to ingest files as data into Log Analytics](https://github.com/davedoesdemos/loganalyticsfunction) | [No Video Yet](https://youtu.be/uku7HN4zaDc) | This demo shows how to ingest text data (such as unsupported logs) into Log Analytics when they land on a storage account |
| Storage | Data Upload Website | [Web interface to upload file data to Blob storage with drag and drop](https://github.com/davedoesdemos/dataupload) | [Video](https://youtu.be/3khzPbmHbAQ) | This demo shows how to use HTML and Javascript to upload files to Azure using a drag and drop website hosted in a storage account |
| Logic Apps | GitHub | [Long term Github traffic statistics](https://github.com/davedoesdemos/githubstats) | [video](https://youtu.be/S5kxhPDQaxs) | This demo shows how to get long term Github traffic statistics and insights using Logic Apps and the API to create reports beyond the 14 days Gihub provides |
| IoT Hub | Events | [IoT Hub Event processor](https://github.com/davedoesdemos/IoTtoEvents) | [No video yet](https://youtu.be/) | This demo shows how to get values from a JSON array submitted to IoT Hub and process the elements in Event Hubs or SQL Server |


## Garmin App and Demo Series

| Category | SubCategory | Demo Instructions | YouTube Video | Description |
|:--------:|-------------|-------------------|:-------------:|-------------|
| Application | ConnectIQ | [ConnectIQ App Code](https://github.com/davedoesdemos/ConnectIQ-Watch-IoT) | No Video | The code repository for the ConnectIQ apps |
| Streaming Data | Intro | [ConnectIQ Garmin watch demo app](https://github.com/davedoesdemos/ConnectIQ-Watch-IoT/blob/master/IoTWatchInstructions.md) | [Video](https://youtu.be/_39eKRNK3UU) | Introduction to the Garmin IoT Project |
| Streaming Data | Event Hubs | [Watch demo infrastructure](https://github.com/davedoesdemos/ConnectIQ-Watch-IoT/blob/master/IoTWatchInstructions.md) | [Video](https://youtu.be/9llyGjfKiLo) | Create your ingest infrastructure and Power BI dashboard |
| Streaming Data | Predictive Model | [Watch Demo HR check with machine learning](https://github.com/davedoesdemos/ConnectIQ-Watch-IoT/blob/master/MLModelTraining.md) | [No Video Yet]() | Transform data and train a machine learning model |

## MTC Data Lake In a Day

[Data Lake in a Day](https://github.com/davedoesdemos/DataLakeInADay/blob/master/README.md)
* [Lab 1 - Getting Internal data with Azure Data Factory and the integration Runtime](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Lab1/Lab1.md) ([video](https://youtu.be/tDvNjbbbASY))
* [Lab 2 - Getting external data using Logic App](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Lab2/Lab2.md) ([video](https://youtu.be/mw6KK5tun0Y))
* [Lab 3 - Processing Data using Mapping Data Flows](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Lab3b/Lab3b.md) ([video](https://youtu.be/U6CsAuRg9us))
  * [Optional alternative lab 3 with Databricks](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Lab3a/Lab3a.md)
* [Lab 4 - Load data into SQL DW](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Lab4/Lab4.md) ([video](https://youtu.be/uzqFsZv2sCI))
* [Lab 5 - Load into Power BI](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Lab5/Lab5.md)

* [Session 1 - Data Platform Overview and Options](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Session1/Session1.md) ([video](https://youtu.be/vVvb1muzQZA))
* [Session 2 - Organising a Data Lake](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Session2/Session2.md) ([video](https://youtu.be/gRaj7gYSi3A))
* [Session 3 - The Wider Ecosystem](https://github.com/davedoesdemos/DataLakeInADay/blob/master/Session3/Session3.md)

## Documentation

[Data Platform Backup and DR](https://github.com/davedoesdemos/DataPlatformBackupDR)

## Deploy Samples

ARM Template samples for various products

[SQL Server Managed Instance](https://github.com/davedoesdemos/DeploySQLMI)

## How I Demo

[How I create demos](https://github.com/davedoesdemos/HowToVideo) [Video](https://youtu.be/bOGHp4RfWXA)
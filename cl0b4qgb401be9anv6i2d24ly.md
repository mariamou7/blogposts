## Azure IoT News – March 2022 by Think About IoT

## Week 1-6/3
### Related to Azure IoT News
🔸 API language runtime version specification in **Azure Static Web Apps** is now available.

Azure Static Web Apps allow the configuration of various settings such as routing, authentication, and networking via the staticwebapp.config.json file. You can now specify an API language runtime via the same configuration file. 

Read more [here](https://azure.microsoft.com/en-gb/updates/generally-available-specify-api-language-runtime-version-in-azure-static-web-apps/).

## Week 7-13/3
### Related to Azure IoT News

🔸 **SOAP** and **XML** request and response validation are now in general availability.

With the release of SOAP and XML features, you will be able to reduce the API attack surface for SOAP or XML-based REST APIs by blocking or logging ill-formed API requests or responses and admitting only those, whose bodies adhere to the declared XML schema.

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-soap-and-xml-request-and-response-validation/).

## Week 14-20/3
🔸 Pin analytics tile to dashboards in **Azure IoT Central**.

Continually monitor the data by pinning it as a tile on a dashboard. To pin an analytics tile, you will need to save the analysis query first. While pinning, you will get the option to select the desired dashboard. After pinning, you can update the tile's size, location, and title by editing the dashboard.

Read more [here](https://azure.microsoft.com/en-gb/updates/iotc-pinanalyticstodashboard/).

🔸 On 31 March 2023, Event Grid on **Azure IoT Edge** public preview will be retired. 

Before that date, please transition to the standard messaging protocol for IoT (MQTT) on Azure IoT Edge. Applications using Event Grid on IoT preview release will no longer be supported after 31 March 2023.

Read more [here](https://azure.microsoft.com/en-gb/updates/migrate-to-mqtt-broker-on-azure-iot-edge-by-31-march-2023/).

🔸 **IoT Hub** on Azure Stack Hub public preview will be retired on 30 September 2022.

Before that date, it's recommended to migrate to Azure IoT Edge gateway. Alternatively, you can host a VM on another physical hardware of your choice.

Read more [here](https://azure.microsoft.com/en-gb/updates/azure-iot-hub-on-azure-stack-hub-preview-will-be-retired-and-it-will-not-go-to-ga/).

### Related to Azure IoT News
🔸 **Azure Synapse** Link for **Azure Cosmos DB** partitioning Spark 3.1 is now in public preview.

Partition your Azure Cosmos DB analytical data using keys that are critical for your business logic to achieve better query and data load performance. Partition pruning results in faster analytical queries and loads as fewer data is scanned in the partitioned stores. You can also benefit from the data processing improvements if your workloads have many updates or deletes.

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-azure-synapse-link-for-azure-cosmos-db-partitioning-spark-31/).

🔸 Protect **Azure Static Web Apps** environments with a password.

Password protection is a user-friendly feature that provides low-level security. It can be used in addition to Static Web Apps Authentication.

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-protect-azure-static-web-apps-environments-with-a-password-2/).

🔸 Azure Private Link support in **Azure API Management** is now in public preview.

With this, incoming traffic to Azure API Management's gateway can be secured to clients running in a virtual network through Azure Private Link. This will limit access to Azure API Management by assigning a virtual network private IP address to the Azure API Management gateway using Azure Private Link.

Previously, only Developer and Premium tiers supported this integration with a virtual network. With this update, you can now integrate to clients in a virtual network privately, using the tiers-Developer, Basic, Standard, and Premium.

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-azure-private-link-support-in-azure-api-management-2/).

🔸 Extended support for **Microsoft .NET** Core 3.1 will end on 3 December 2022.

After that date, your applications hosted on Functions will continue to run and your applications will not be impacted. However, Microsoft will no longer provide patches or customer service for .NET Core 3.1.

Read more [here](https://azure.microsoft.com/en-gb/updates/extended-support-for-microsoft-net-core-31-will-end-on-3-december-2022/).

## Week 21-27/3
🔸 Connect and manage devices in **Azure IoT Central** without models.

You can now connect devices, send data, and run commands without having first to create a device model/template, enabling a low friction first-run experience.

Once the devices are cloud-connected, you can progressively build the models to leverage a wide set of out-of-the-box capabilities in Azure IoT Central.

In addition to running commands on devices without models, you can also create relationships between devices without having to first create device templates and attach gateway devices to unassigned leaf devices, enabling you to easily represent device topologies.

Read more [here](https://azure.microsoft.com/en-gb/updates/iotc-manage-devices-without-models/).

### Related to Azure IoT News
🔸 **Azure Time Series Insights** will be retired on 31 March 2025.

That will happen, because Azure Data Explorer now provides a data analytics service for streaming telemetry data. Due to that, you have to make a transition to using Azure Data Explorer by that date.

Read more [here](https://azure.microsoft.com/en-gb/updates/we-ll-retire-azure-time-series-insights-on-31-of-march-2025/).

🔸 On 31 March 2023, Microsoft is making the resource providers for the **Azure API Management** zone redundant in each region.

You have to review your VNET configurations that may be affected by IP address changes.

Read more [here](https://azure.microsoft.com/en-gb/updates/ip-address-changes-will-begin-affecting-your-ability-to-manage-your-virtual-networkenabled-api-management-services-on-31-marc/).

🔸 **Azure Machine Learning** user-defined functions are now in general availability in **Azure Stream Analytics**.

Read more [here](https://azure.microsoft.com/en-gb/updates/ga-amludf-asa/).

🔸 **Azure Data Explorer** supports multiple databases per data connection.

So far, the target database was always the database associated with the data connection.

Now, you can dynamically route the data to an alternate database, by setting the Database ingestion property. For security reasons, this option is disabled by default.

To send the data to a different database, you must first set the connection as a multi-database data connection. 

Read more [here](https://azure.microsoft.com/en-gb/updates/azure-data-explorer-now-supports-multiple-databases-on-a-single-data-connection/).

🔸 User-assigned managed identities in **Stream Analytics**.

This solves a common challenge when building cloud applications related to credential management. Keeping the credentials secure is important and shouldn't be stored in developer workstations or checked into source control.

Read more [here](https://azure.microsoft.com/en-gb/updates/asa-uami/).

## Week 28-31/3
There isn't any news for this week, yet.

## Closing
That’s all folks! 👋

Take care of yourself! 🙂

If you have any questions, please reach out!

P.S. This article will be updated every single week for this month, so don’t forget to check it again when February will come to the end.

You can also be informed about [Azure IoT News for February 2022](https://www.thinkaboutiot.com/index.php/2022/02/01/azure-iot-news-february-2022-by-think-about-iot/).
## Azure IoT News – January 2022 by Think About IoT

Happy New Year, all! ✨

## Week 1-2/1
There wasn't any news in the first little week of this month.

## Week 3-9/1
In this week there is 3 news about Azure IoT Central. Let's take a look at them!

🔸 Display limits on tiles increased to 100 homogeneous devices on **Azure IoT Central** Dashboard.

This change makes it easier to visualize and analyse data across a larger device group simultaneously.

Read more [here](https://azure.microsoft.com/en-gb/updates/increaseddevicelimitsontiles/).

🔸 Data mapping for transforming data at ingress in **Azure IoT Central**.

Capabilities: 
- send device telemetry in different shapes
- transform the telemetry into structured data at Azure IoT Central ingress
- map a JSON path in a device message to a friendly name (alias) at a device level

- leverage data to create device templates and device management experiences in IoT Central, such as Rules
- export the mapped data to any destination

- send industrial equipment data into IoT Central
- create device management experience for industrial equipment

- map the data for any device
- navigate to a device Raw data view
- expand any telemetry message
- add an alias by hover the mouse pointer over a message path
- verify that IoT Central is mapping the telemetry by checking the ‘_mappeddata’ section in Raw data

Read more [here](https://azure.microsoft.com/en-gb/updates/datamappinginazureiotcentral/).

🔸 Support for copying dashboards added to **Azure IoT Central**.

With this new capability:
- leverage existing work to build new dashboards by simply duplicating an existing dashboard
- save time
- eliminate the need to build a similar dashboard from the ground up

Read more [here](https://azure.microsoft.com/en-gb/updates/copydashboardsiniotcentral/).

## Week 10-16/1

🔸 **Azure Sphere OS** version 22.01 is expected on the 26th of January!

Azure Sphere OS version 22.01 is now available for evaluation in the Retail Eval feed.

Areas of special focus for compatibility testing with 22.01 should include apps and functionality utilizing: 

- Timestamps or structs that contain time
- WifiConfig_getNetworkDiagnostics()
- Manually configured DNS entries
- DMA

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-azure-sphere-os-version-2201-expected-on-jan-26/).

### Related to IoT Azure news

🔸 **Azure Static Web Apps** enterprise-grade edge is now in public preview.

Use this update to:
- increase your website page load speed
- enhance security
- optimize reliability for your global applications

- have global presence in 118+ edge locations
- proactive protection against Distributed Denial of Service (DDoS) attacks
- have native support of end-to-end IPv6 connectivity and HTTP/2 protocol

This secure cloud CDN platform combines the capabilities of:
- Azure Static Web Apps
- Azure Front Door
- Azure Content Delivery Network (CDN) standard

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-azure-static-web-apps-enterprisegrade-edge/).

## Week 17-23/1
🔸 Azure **IoT Edge** tools for Visual Studio extension now support **Visual Studio** 2022.

You can:

- code, build, deploy, simulate and debug your IoT Edge solutions in Visual Studio 2022
- target different platforms (Linux amd64, Linux arm32v7, Linux arm64v8, Windows amd64)
- add a new IoT Edge module (C#/C) to solution with support of .NET 6 for C# module
- edit, build and debug IoT Edge modules locally on your Visual Studio machine
- build and push docker images of IoT Edge modules
- run IoT Edge modules in a local or remote simulator
- manage IoT Edge devices and modules in IoT Hub

Read more [here](https://azure.microsoft.com/en-gb/updates/edgevs2022/).

### Related to IoT Azure news

🔸 **Azure Machine Learning** Announcement for January 2022.

Multiple private endpoint support enables to set up of common scenarios for more complex virtual network (VNet) architecture.

With a storage account, IP firewall support by Azure Machine Learning, the customers have the flexibility to let the public users use the data in storage behind the virtual network without configuring the private link enabled workspace.

Read more [here](https://azure.microsoft.com/en-gb/updates/azure-machine-learning-announcements-january-2022-general-availability-announcement/).

🔸 Managed Certificate support for **Azure API Management** is now in public preview.

This enables to easily and quickly secure custom domains with a free SSL certificate provisioned, managed and automatically renewed by Azure API Management.

This feature is available in all tiers of Azure API Management at no cost. 

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-managed-certificate-support-for-azure-api-management/).

## Week 24-30/1
🔸 **Azure Percept** DK January (2201) software update is now available in public preview.

New OS/firmware Over the Air (OTA) package and USB cable update image are available.

Read more [here](https://azure.microsoft.com/en-gb/updates/apdk2201update/).

🔸 New **Azure Maps** features historical weather, air quality, and tropical storms are now in general availability.

Develop weather and climatology enabled solutions using the historical weather, air quality and tropical storms features from Azure Maps Weather Services. 

Like the other Azure Maps Weather Services, the data in these new features come from worldwide leading weather services provider, AccuWeather.

Here are the specifics on what these new features include:

- Historical feature weather provides actuals, normals, and records climatology data by day, for a specified date range, up to 31 days in a single API request. Historical data may be available as far back as 5 to 40+ years and includes, temperatures, precipitation, snowfall, snow depth, and cooling/heating degree day information, depending on the location and service.

- Air quality feature provides detailed information about the current and forecasted concentration of air pollutants and air quality. Forecasted information is available by the hour (upcoming 1, 12, 24, 48, 72, and 96 hours) and by day (upcoming 1 to 7 days). Information includes, pollution levels, air quality index values, the dominant pollutant, and a brief statement summarizing risk level and suggested precautions.

- Tropical storms feature provides information on government-issued active tropical storms, government-issued forecasted tropical storms, the locations of an individual government-issued tropical storm, and the ability to search government-issued tropical storms by year, basin ID, and government ID. Tropical storms are also known as, hurricanes, cyclones, and typhoons, depending on the region of the world.

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-new-azure-maps-features-historical-weather-air-quality-and-tropical-storms/).

### Related to IoT Azure news

🔸 There are some regular **Azure API Management** updates in general availability.

New updates:
- Published developer portals are now automatically upgraded to new portal releases, without the need to republish the portal manually.
- Curly brackets can now be used in a SOAP action URL template to define a wildcard SOAP action, which will match any SOAP request that doesn't have a dedicated action defined in the API. The value inside the curly brackets doesn't affect the execution.
- Availability zones are now supported in the East Asia region.

Fixes:
- Newly created diagnostic settings will no longer be configured to log request query parameters by default.
- Self-hosted gateway now properly handles a certificate change for existing hostnames.
- Multiple validate-content policies can now be specified in a single policy section.
- It is now possible to delete a resource group with a stv2-based API Management service in a virtual network.
- ConfigurationChange event is no longer logged in Resource Health for API Management service backups.
- tracestate header values are no longer truncated after the first key-value pair.
- An attempt to deploy a stv2 API Management service into a virtual network subnet with a stv1 API Management service will now result in a descriptive error message.

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-azure-api-management-updates-january-2022/).

## Week 31/1
There wasn't any news on the last day of this month.

## Closing

That’s all folks! 👋 

Take care of yourself! 🙂

If you have any questions, please reach out!

P.S. This article will be updated every single week for this month, so don’t forget to check it again when January will come to the end.

You can also be informed about  [Azure IoT News for December 2021](https://www.thinkaboutiot.com/index.php/2021/12/10/azure-iot-news-december-2021-by-think-about-iot/).
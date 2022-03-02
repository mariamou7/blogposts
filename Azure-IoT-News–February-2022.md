## Azure IoT News – February 2022 by Think About IoT

## Week 1-6/2
🔸 **Azure IoT Edge** for **Linux** on Windows (EFLOW) update is now in public preview.

This update release contains the following improvements:

- Support for Azure IoT Edge 1.2 which add:
- Edge Identity Service
- Integration with on-premises PKI infrastructure via EST standard
- Storing certificates in HSMs via the PKCS11 standard
- Ability to configure a nested hierarchy of IoT Edge devices
- Generic MQTT broker

- Microsoft Defender for IoT can be enabled in EFLOW so that the system can be managed

- Arm64 and AMD64 chip support

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-azure-iot-edge-for-linux-on-windows-eflow-update/).

🔸 The **Azure Sphere OS** 22.01 release is cancelled.

Azure Sphere OS version 22.01, previously scheduled to release for general availability on Jan 26, is cancelled. The next release of Azure Sphere will be version 22.02.

During the evaluation period for 22.01, an intermittent network connection failure was discovered during the OS update process when using the ENC28J60 Ethernet interface for Internet connectivity. To adhere to Microsoft's quality standards is cancelling the 22.01 release while we investigate this. The Retail Eval feed will continue to deliver version 22.01 until MS publish version 22.02 in approximately three weeks.

The 22.01 evaluation release did not include critical security updates, and this cancellation will not impact the security of Azure Sphere-based products.

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-the-azure-sphere-os-2201-release-is-cancelled/).

🔸 **IoT Edge** monitoring with Azure Monitor is now generally available.

Simplify monitoring and troubleshooting of Azure IoT Edge devices with deep integration with Azure Monitor through a set of built-in metrics, the IoT Edge Metrics Collector module, and a set of curated visualizations.

With this integration, can:

- Analyze the efficiency of solution
- Choose hardware to fit the performance demands on devices
- Monitor locked down assets
- Unify cloud and edge monitoring
- Proactively identify issues with metrics-based alerts
- Rapidly troubleshoot problems
- Create custom metrics and dashboards

The latest IoT Edge metrics collector module release 1.0.3 is now available in the [Microsoft container registry](https://hub.docker.com/_/microsoft-azureiotedge-metrics-collector).

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-iot-edge-monitoring-with-azure-monitor/).

🔸 **Azure IoT Edge** now supports Ubuntu Server 20.04 and ARM64.

Read more [here](https://azure.microsoft.com/en-gb/updates/azure-iot-edge-adds-support-for-ubuntu-server-2004-and-arm64/).

### Related to IoT Azure news

🔸 **Azure Functions** support for **PowerShell** on **Linux OS** is now generally available in Azure Functions runtime 4.0 on all hosting plans.

Read more [here](https://azure.microsoft.com/en-gb/updates/generally-available-powershell-on-linux-os-in-azure-functions/).

## Week 7-13/2
🔸 Regional deployments for all new and existing **IoT Central** applications are now available.

All existing IoT Central applications that were previously associated with geography are now migrated to the standard Azure region. This follows the [update from August 2021](https://www.thinkaboutiot.com/index.php/2021/08/13/azure-iot-news-august-2021-by-think-about-iot/) where regional support was introduced for new applications, which is now expanded to existing applications as well.

This update allows all existing applications to improve their security posture by taking advantage of secure data egress via managed identities.

Read more [here](https://azure.microsoft.com/en-gb/updates/regionaldeployments/).

🔸 Search results page improvements in **Azure IoT Central**.

With this update, the search results experience has been redesigned allowing to filter off the results by different search fields such as device name, device ID, property values, and cloud property values. Have been also added bold text for matched terms (highlights). 

Read more [here](https://azure.microsoft.com/en-gb/updates/searchimprovements/).

🔸 Improved getting started material in **Azure IoT Central** documentation.

Find guidance and support with:
- updated documentation including new FAQ articles,
- guides for each phase of the solution development process, and
- a reorganized landing page and table of contents

The new FAQ articles include:
- Why should I start with Azure IoT Central?
- What’s the difference between aPaaS and PaaS offerings?
- How do I move between aPaaS and PaaS solution approach?
- How do I extend Azure IoT Central if it’s missing something I need?
- What are Azure IoT Central’s scale limits?

Read more [here](https://azure.microsoft.com/en-gb/updates/generally-available-improved-getting-started-material-in-iot-central-documentation/).

🔸 Find developer resources easily with the **IoT Central GitHub** repository.

Build solutions on Azure IoT Central and access architecture docs, integration patterns, tools, and sample code in a single, consolidated place.

- Connect devices and take full advantage of all the features that Azure IoT Central offers
- Debug and test devices that are connected to Azure IoT Central
- Build companion applications using the Azure IoT Central APIs
- Transform and compute device data when connecting to Azure IoT Central

Read more [here](https://azure.microsoft.com/en-gb/updates/new-iot-central-github-repo/).

## Week 14-20/2
🔸 **Azure Sphere** OS version 22.02 is expected on the 28th of February.

This version is now available for evaluation in the Retail Eval feed. The retail evaluation period provides 2 weeks for backwards compatibility testing.

When 22.02 is generally available later in February, an updated SDK will be included.

Areas of special focus for compatibility testing with 22.02 should include apps and functionality using:
- Timestamps or structs that contain time
- WifiConfig_getNetworkDiagnostics()
- Manually configured DNS entries
- DMA
- DHCP
- Wired Ethernet connections

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-azure-sphere-version-2202-expected-on-feb-28-2022/).

🔸 New learning content on the **Azure IoT Central** homepage!

Explore learning resources such as architecture diagrams, documentation, and videos on the updated Azure IoT Central homepage. Information is organized by key workflows (connect, manage, analyze, secure, extend) and this structure is repeated across the navigation menu and documentation.

See the new home page [here](https://apps.azureiotcentral.com/).

Read more [here](https://azure.microsoft.com/en-gb/updates/iotcentralhomepagelearningcontent/).

### Related to IoT Azure news

🔸 **Developer portal widget** for embedding custom **HTML** code is now in general availability.

Use custom HTML code widget to extend developer portal's functionality when previously, you had to develop your own widget and self-host the extended developer portal to embed a custom HTML code.

Read more [here](https://azure.microsoft.com/en-gb/updates/general-availability-developer-portal-widget-for-embedding-custom-html-code/).

🔸 Public preview for Azure Tables extension for **Azure Functions**.

The input and output bindings for Tables in Azure Functions have been updated to include new features, and they are now defined in their own extension.

You can now:
- Connect to Cosmos DB Tables API
- Connect to Storage Tables using identity-based connections
- .NET customers can bind to types from Azure.Data.Tables
- Use Tables alongside the V5 Storage extensions

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-azure-tables-extension-for-azure-functions/).

🔸 **Azure Machine Learning**, February 2022 announcements.

Accelerate the onboarding of team members to automatedML by eliminating manual tasks and reducing data-related errors with automatic time series ID detection. 

View and customize automatedML model’s training code:
- Model transparency and trust for full control and customization of the model's training code. 
- Supports scenarios that require model training code deployed in production, as well as control and customization of the code.

Read more [here](https://azure.microsoft.com/en-gb/updates/public-preview-azure-machine-learning-february-2022-announcements/).

## Week 21-27/2
🔸 Updated navigation menu in **Azure IoT Central**.

The navigation menu has been improved by re-ordering, re-grouping, and re-naming pages. 

Details of the changes include:

- Grouping the navigation menu according to key tasks flows (connect, analyze, manage, extent, security, and settings)

- Renaming pages as follows:
- Analytics → Data explorer
- Your application → App management
- Customize your application → App appearance
- Customize help → Help links
- Application template export → App template export
- Device file upload → Device file storage
- Device connection →   Device connection groups

- Cleaning up URLs to match page names
- Updating the roles' page to match the new organization
- Updating the default page to be devices (instead of dashboard)
- Adding a notification informing users of the navigation menu changes

Read more [here](https://azure.microsoft.com/en-gb/updates/iotcentral-updated-navigation-menu/).

## Monday 28/2
🔸 The **Azure Sphere** 22.02 feature release is now available.

This feature includes the following components:
- Updated Azure Sphere OS
- Updated Azure Sphere SDK for Windows and for Linux
- Updated Azure Sphere extensions for Visual Studio and for Visual Studio Code
- Updated samples and tutorials

Read more [here](https://azure.microsoft.com/en-gb/updates/iotcentral-updated-navigation-menu/).

## Closing

That’s all folks! 👋 

Take care of yourself! 🙂

If you have any questions, please reach out!

P.S. This article will be updated every single week for this month, so don’t forget to check it again when February will come to the end.

You can also be informed about [Azure IoT News for January 2022](https://www.thinkaboutiot.com/index.php/2022/01/05/azure-iot-news-january-2022-by-think-about-iot/).

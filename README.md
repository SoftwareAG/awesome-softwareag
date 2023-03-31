<p align="center">
<a href="https://www.softwareag.com/en_corporate.html"><img src="https://info.softwareag.com/rs/858-DJP-749/images/SAG_logo_200x200_New.png" style="max-width: 75% !important;"></a></br>
</p>

# Awesome Software AG [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
**A curated list of awesome Software AG open source repositories, tools, libraries and other resources.**

> If you want to contribute to this awesome list, please take a look at our [contribution guidelines](https://github.com/SoftwareAG/awesome-softwareag/blob/master/CONTRIBUTING.md). 
If you see a project that is no longer maintained or is not a good fit, please submit a pull request or [contact us](mailto:technologycommunity@softwareag.com?subject=Github/SoftwareAG). Thank you!


## Contents
* [webMethods](#webmethods)
* [Cumulocity IoT](#cumulocity-iot)
  * [Cumulocity IoT custom widgets](#cumulocity-iot-custom-widgets)
  * [Cumulocity IoT device agents](#cumulocity-iot-device-agents)
* [Adabas and Natural](#adabas-and-natural)
  * [adapya – Adabas Python packages](#adapya--adabas-python-packages)
  * [Adabas Node.js packages](#adabas-nodejs-packages)
* [ARIS](#aris)
 
## webMethods
 
[webMethods-io-examples](https://github.com/SoftwareAG/webMethods-io-examples) - Collection of examples for beginner webMethods.io developers. It consists of common use cases and starting points for developers getting up to speed with webMethods.io. webMethods.io is an integration platform that enables a wide variety of integration tasks to be accomplishes quickly and easily with a graphical/API interface.

[webmethods-suite-logfile-archiver](https://github.com/SoftwareAG/webmethods-suite-logfile-archiver) - Archive and (after a customizable retention period) delete log files from webMethods Suite products.

[webmethods-integrationserver-wxsocketadapter](https://github.com/SoftwareAG/webmethods-integrationserver-wxsocketadapter) - This Socket Adapter project covers two demands of advanced Integration Server users and developers:

 &ndash; Demoing how to develop a custom coded on-premise Integration Server adapter.<br/>
 &ndash; Providing a light-weight way to connect low level devices and applications into the world of Integration Server.
 
[webmethods-integration-examples](https://github.com/SoftwareAG/webmethods-integration-examples) - Collection of examples for using webMethods Integration platform.
 
[webmethods-integrationserver-pgpencryption](https://github.com/SoftwareAG/webmethods-integrationserver-pgpencryption) - Provides a sample Integration Server package for PGP encryption and decryption.
 
[webmethods-integrationserver-skyprofiler](https://github.com/SoftwareAG/webmethods-integrationserver-skyprofiler) - SKYProfiler is a performance monitoring tool for Integration Server. SKYProfiler tracks the service invocations and the monitored data can be seen in real time.

[webmethods-opencaf-codesample](https://github.com/SoftwareAG/webmethods-opencaf-codesample) - This OpenCAF showcase demonstrates the majority of default JSF components available in webMethods Composite Application Framework (CAF).

<br>

[![124621](https://user-images.githubusercontent.com/23717841/228481674-58d1678e-7206-4367-a211-2ecdd376e0e2.png) Back to top](#contents)

## Cumulocity IoT

[cumulocity-os-repo-overview](https://github.com/SoftwareAG/cumulocity-os-repo-overview) - This repository generates on a daily basis a table of all open-source repositories for Cumulocity IoT. It gives a brief overview of all available IoT open-source repositories for Cumulocity IoT.

[cumulocity-migration-tool](https://github.com/SoftwareAG/cumulocity-migration-tool) - A Cumuocity web app to migrate applications, dashboards, groups, devices, simulators, smart rules, images, and managed objects between tenants.

[cumulocity-iot-examples](https://github.com/SoftwareAG/cumulocity-iot-examples) - Collection of examples for beginner Cumulocity IoT developers.

[cumulocityr](https://github.com/SoftwareAG/cumulocityr) - R client for the Cumulocity IoT API. 

[cumulocity-app-builder](https://github.com/SoftwareAG/cumulocity-app-builder) - Application builder for Cumulocity IoT. A simple way to combine dashboards into a full web application with no coding.

### Cumulocity IoT custom widgets
[cumulocity-demo-widget](https://github.com/SoftwareAG/cumulocity-demo-widget) - The Demo Widget for Cumulocity IoT projects is created using Angular Library and later it's deployed in App Builder as a Cumulocity IoT widget. It fetches Inventory data based on the device id and displays the same in a widget.

[cumulocity-smart-map-widget](https://github.com/SoftwareAG/cumulocity-smart-map-widget) - The Smart Map widget helps you to track real-time device locations indoors with multi-floor infrastructure as well as outdoors.

[cumulocity-device-chart-widget](https://github.com/SoftwareAG/cumulocity-device-chart-widget) - This is an Angular widget, which is designed to display the chart based on the device-specific inventory data. The widget also comes with an inbuilt color picker, which helps you to customize chart/border colors. It includes a wide variety of chart types - Vertical Bar Chart, Horizontal Bar Chart, Donut Chart, Pie Chart and etc.

[cumulocity-datapoints-charting-widget](https://github.com/SoftwareAG/cumulocity-datapoints-charting-widget) - The Data Points Charting Widget allows you to create real-time graphs showing customizable amounts of data from one or more devices. It supports a wide variety of chart types, including line charts, bar charts, and donut charts.

[cumulocity-smart-map-settings-widget](https://github.com/SoftwareAG/cumulocity-smart-map-settings-widget) - The Smart map settings widget is created using Angular Library and it can be deployed in App Builder and Cockpit as a Cumulocity IoT widget. It allows you to mark and create a Geography on a specified location. After the Geography is created, it allows you to create floors, Geofences, and device positioning. 

[cumulocity-data-points-map-widget](https://github.com/SoftwareAG/cumulocity-data-points-map-widget) - The Data Points Map widget displays measurements and device locations on the map. The widget works for single devices and device groups. The clustering of markers can be enabled in case you need to support a large set of devices.

<details>
<summary>More Awesome Cumulocity IoT widgets</summary>

* [Cumulocity IoT 3D model viewer widget](https://github.com/SoftwareAG/cumulocity-3d-model-viewer-widget)
* [Cumulocity IoT DataHub widget](https://github.com/SoftwareAG/cumulocity-datahub-widget)
* [Cumulocity IoT indoor air quality widget](https://github.com/SoftwareAG/cumulocity-indoor-air-quality-widget) 
* [Cumulocity IoT image animation widget](https://github.com/SoftwareAG/cumulocity-image-animation-widget)
* [Cumulocity IoT video widget](https://github.com/SoftwareAG/cumulocity-video-widget)
* [Cumulocity IoT asset viewer widget](https://github.com/SoftwareAG/cumulocity-asset-viewer-widget)
* [Cumulocity IoT Markdown widget](https://github.com/SoftwareAG/cumulocity-markdown-widget) 
* [Cumulocity IoT KPI overview widget](https://github.com/SoftwareAG/cumulocity-kpi-overview-widget)
* [Cumulocity IoT bar chart widget](https://github.com/SoftwareAG/cumulocity-barchart-widget)
* [Cumulocity IoT Power BI widget](https://github.com/SoftwareAG/cumulocity-power-bi-widget)
* [Cumulocity IoT tracking replay widget](https://github.com/SoftwareAG/cumulocity-tracking-replay-map-widget)
* [Cumulocity IoT silo capacity widget](https://github.com/SoftwareAG/cumulocity-silo-capacity-widget)
* [Cumulocity IoT weather forecast widget](https://github.com/SoftwareAG/cumulocity-weather-forecast-widget)
* [Cumulocity IoT devices at risk widget](https://github.com/SoftwareAG/cumulocity-device-at-risk-widget)
* [Cumulocity IoT Trendminer chart widget](https://github.com/SoftwareAG/trendminer-chart-widget)
* [Cumulocity IoT advanced radial gauge widget](https://github.com/SoftwareAG/cumulocity-advanced-radial-gauge-widget)
* [Cumulocity IoT ticketing integration setup widget](https://github.com/SoftwareAG/c8y-ticketing-integration-setup-widget)
* [Cumulocity IoT device control and status widget](https://github.com/SoftwareAG/cumulocity-device-control-widget)
* [Cumulocity IoT compass widget](https://github.com/SoftwareAG/cumulocity-compass-widget)
* [Cumulocity IoT devices details widget](https://github.com/SoftwareAG/cumulocity-device-details-widget)

</details>

### Cumulocity IoT device agents
[cumulocity-devicemanagement-agent](https://github.com/SoftwareAG/cumulocity-devicemanagement-agent) - A Cumulocity IoT Reference Agent written in Python to demonstrate most of the Device Management Capabilities of Cumulocity IoT. The agent can be run in a docker container or natively on a device with preferrable with linux OS (e.g raspberry pi) or any other operating system.

[c8yMQTT](https://github.com/SoftwareAG/c8yMQTT) - A Python3 Cumulocity Agent for MQTT and Rasperry PI. The Cumulocity Python agent is divided into two Python modules.

[cumulocity-agents-linux](https://github.com/SoftwareAG/cumulocity-agents-linux) - The Cumulocity IoT Linux agent is a generic agent for connecting Linux-powered devices to Cumulocity's IoT platform. It runs on all major Linux distributions (Ubuntu, Debian, Raspberry Pi OS, CentOS, etc.).

[cumulocity-python-agent](https://github.com/SoftwareAG/cumulocity-python-agent) - A Cumulocity IoT Agent in Python containing the basic functionalities.

[cumulocity-remote-access-agent](https://github.com/SoftwareAG/cumulocity-remote-access-agent) - A simple Python agent demonstrating the remote access capabilities of Cumulocity IoT. The main purpose is to demonstrate and use the Cloud Remote Access in other agents.

[cumulocity-agents-netcomm](https://github.com/SoftwareAG/cumulocity-agents-netcomm) - The Cumulocity NetComm Agent is a dedicated agent software for connecting the NetComm router to Cumulocity IoT.

[cumulocity-hono-agent](https://github.com/SoftwareAG/cumulocity-hono-agent) - This is an agent/microservice that integrates with Eclipse Hono. This Microservice will act as a Consumer Application, listens to all Telemetry & Event Data provided by Hono and forward the Data to Cumulocity IoT.

<details>
<summary>More Awesome Cumulocity IoT agents</summary>

* [Cumulocity IoT Dynamic MQTT Mapping Service](https://github.com/SoftwareAG/cumulocity-dynamic-mqtt-mapper)
* [Cumulocity IoT REST to MQTT bridge](https://github.com/SoftwareAG/cumulocity-rest2mqtt-bridge)
* [Cumulocity IoT IEC 60870-5-104 protocol](https://github.com/SoftwareAG/cumulocity-iec104)
* [Cumulocity IoT OPC-UA agent for Java](https://github.com/SoftwareAG/cumulocity-agents-opc)
* [Cumulocity IoT electron agent](https://github.com/SoftwareAG/cumulocity-electron-agent)
* [Cumulocity IoT Modbus Demo](https://github.com/SoftwareAG/cumulocity-modbus-demo)

</details>

<br>

[![124621](https://user-images.githubusercontent.com/23717841/228481674-58d1678e-7206-4367-a211-2ecdd376e0e2.png) Back to top](#contents)

## Adabas and Natural

[adabas-natural-code-samples](https://github.com/SoftwareAG/adabas-natural-code-samples) - A collection of Natural Code samples and snippets that can be used by Natural developers to implement standard or specific programming patterns.

[adabas-rest-webapp](https://github.com/SoftwareAG/adabas-rest-webapp) - A web application that provides access to Adabas REST server tasks and data. 

### adapya – Adabas Python packages

[adapya-adabas](https://github.com/SoftwareAG/adapya-adabas) - Adapya-adabas implements the Adabas database API for Python. It can access local and remote Adabas databases. adapya-adabas comes with scripts and sample programs to show its features. It is being used on Linux, mainframe z/OS, Solaris and Windows.

[adapya-base](https://github.com/SoftwareAG/adapya-base) - Adapya-base provides the foundations for the other adapya packages – e.g. the Datamap class. adapya-base comes with scripts to transfer files from mainframe or process SMF performance records.

[adapya-entirex](https://github.com/SoftwareAG/adapya-entirex) - adapya-entirex implements the EntireX API for Python. Using the Advanced Communication Interface (ACI) it allows persistent messaging with the EntireX Broker. EntireX is a component in the webMethods high-performance communication infrastructure.

[adapya-era](https://github.com/SoftwareAG/adapya-era) - Adapya-era implements the messages API with the Event Replicator for Adabas. The Event Replicator for Adabas is an add-on product to Adabas that allows replicating database data to other systems. Client programs (also called target adapters) receive event replication data through a messaging system like MQ series or EntireX Broker. adapya-era can be used to write target adapters in Python. The package also consists of scripts that can send requests to the Replicator and receive event data via the EntireX Broker messaging system.

[adabas-go-api](https://github.com/SoftwareAG/adabas-go-api) - This module provides direct access to Adabas database data in a Golang-based application. This contains all transactional operations on the database.

[adabas-admin-restful-client](https://github.com/SoftwareAG/adabas-admin-restful-client) - Software AG Adabas RESTful client administration generated using the Adabas RESTful server SWAGGER definition.

### Adabas Node.js packages

[adabas-tcp](https://github.com/SoftwareAG/adabas-tcp) - adabas-tcp provides an access to Adabas from Node.js using the Adabas TCP connection.

<br>

[![124621](https://user-images.githubusercontent.com/23717841/228481674-58d1678e-7206-4367-a211-2ecdd376e0e2.png) Back to top](#contents)

## ARIS

[cumulocity-to-aris-pm](https://github.com/SoftwareAG/cumulocity-to-aris-pm) - This project is a template demoing how to transfer Cumulocity IoT data to an ARIS Process Mining tenant. It is composed of two microservices:

- the first microservice creates the source tables in ARIS and upload the first set of data within it
- the second one loads the data in the process storage of ARIS. 

<br>

[![124621](https://user-images.githubusercontent.com/23717841/228481674-58d1678e-7206-4367-a211-2ecdd376e0e2.png) Back to top](#contents)

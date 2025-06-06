---
layout: main
title: Releases - Arrigo Local
description: Change Log
---
# Change Log

## 1.5.24

2025-05-22

- **Reset Password TP#35260**: Resolved an issue where the reset password button was not appearing on custom login pages.
- **Link Icon Breadcrumb TP#36536**: Updated to display the link icon's title instead of its technical name.
- **Search Bar TP#35424**: Fixed an issue where the search bar appeared when pressing 'f' after tabbing. The new shortcut to open the search bar is **Ctrl + Space**.
- **User Descriptions TP#32108**: User descriptions for an area are now displayed in a tooltip when hovering over an element.
- **Reversed Digitals TP#32861**: Added a feature similar to **Reversed Alarm Titles**, but for digital signals.
- **Maneuver Panel TP#38378, TP#40627**:
    - Now supports multiline text editing.
    - Comma-separated number formatting is now supported.
    - Fixed a bug related to number formatting.
- **Version Info TP#40798**: Fixed a broken link when holding down the left click on the Arrigo logo. The installed Arrigo version is now displayed.
- **Signal Colors TP#40906**: Resolved an issue where the selected signal color was not being applied. The option to select a color is only available for signals added from Arrigo.
- **Language Changes TP#40786**: Standardized the language so that all instances now say **New Alarm** instead of some saying **New A Alarm**.
- **Arrigo Startup TP#34228**: Fixed an issue where Arrigo sometimes failed to start due to an intermittent timing problem.
- **Collecting signals TP#40518**: Resolved an issue where the **Collected Signals** view displayed elements other than controller variables.
- **Prepareoffline TP#39244**: Ensured that the **prepareoffline** flag on the Arrigo installer works correctly.

## 1.5.21

2024-12-17

- **Removed .NET 7 dependency.**

## 1.5.20

2024-12-11

- **.NET Update, TP#36796** Changes so the newest .NET 8 Hosting Bundle is installed. 
- **Alarm Filters, TP#37063** Fixed issue with Alarm Filters being reset when selecting an alarm in the list.
- **Alarm Visibility, TP#34900** Fixed an issue where the root folder alarms were not appearing in the alarms view.
- **Chart export, TP#26368** Added Title column to CSV chart export.
- **Chart export, TP#26368** Changed XLSX chart export signal name to signal title.
- **Chart export, TP#26368** Fixed issue with exporting (and parsing) chart signals that are not in db.
- **Chart Axis Configuration, TP#36028** "Include axis configuration" is now checked (instead of "include saved filters") if axis configuration exists.
- **Maneuver panel, TP#36033** Improved handling of inputting values.
- **Modifying hostname, TP#35949** Allows for modification of the structure of folders in IIS. More information about the new apiurl property can be found here: [Advanced Configuration](https://arrigodocs.regincontrols.com/Install%20and%20Configure/Settings/00_globalsettings.json/#globalsettingsjson)
- **Versioning Bug, TP#35606:** Fixes issue where old component wouldn't be overwritten by installation.
- **Widget icons, TP#36136** List widget icons now appear more compact for smaller screens.

## 1.5.18

2024-09-25

- **Notification button, TP#31325:** Added new "Read all" button to read all notifications.
- **Customise port, TP#33142:** Added support to change what port Arrigo is hosted on.
- **Maneuver panel:** Enabled maneuver panel by default if theme/settings.json file doesn't already exist.
- **Attach project:** Added redundancy to forcefully terminate processes.

**General Updates:** We have updated multiple third party libraries of the system.


------

*Component Versions*

- Frontend: 1.2.40
- Arrigo Local API: 1.5.32
- Arrigo Local Scada Function: 1.5.16
- Arrigo config transpiler: 1.5.53
- Arrigo Local Services  
  - Wamp Host: 1.1.31
  - Domain Controller: 1.1.25
  - Volumes: 1.2.7
  - Chart Service: 1.1.6
  - State Service: 1.1.10
  - DB Service: 1.1.2
  - Server-Side Functions: 1.1.4

Requires an **EXO 2024** installation.

## 1.5.12

2024-05-20

- **View Designer, TP#31164:** Color element's style property is now evaluated properly.

- **View Designer, TP#26396:** Added support for binding the visible and enabled fields of a click area to a variable.

- **Chart export, TP#29569, TP#29219:** When exporting values from a chart, the date format is now consistent.

- **Chart export, TP#30853, TP#29569, TP#30892, TP#31467:** When exporting values from a chart, all configured signals and their values are exported properly.

- **Chart export, TP#27964:** Added button to select between exporting raw values or capped decimal numbers (Default cap is 2).

- **Chart export, TP#31280:** Removed spaces from the number format.

- **Chart export, TP#30417:** Changed so that .xlsx is the pre-selected file format.

- **View, TP#32069:** Fixed an issue where older animation view files would throw an index out of range exception when opening.

  

------

*Component Versions*

- Frontend: 1.2.30
- Arrigo Local API: 1.5.17
- Arrigo Local Scada Function: 1.5.12
- Arrigo config transpiler: 1.5.45
- Arrigo Local Services  
  - Wamp Host: 1.1.24
  - Domain Controller: 1.1.19
  - Volumes: 1.2.5
  - Chart Service: 1.1.0
  - State Service: 1.1.3
  - DB Service: 1.1.2
  - Server-Side Functions: 1.1.1

Requires an **EXO 2024** installation.

## 1.5.2

2024-03-18

- Frontend: [1.2.20](./frontend.html#1220)

- Arrigo Local API: [1.5.15](./arrigolocalapi.html#1515)

- Arrigo Local Scada Function: [1.5.10](./arrigolocalscadafunction.html#1510)

- Arrigo config transpiler: [1.5.33](./arrigo.config.transpiler.html#1533)

- Arrigo Local Services  
  - Wamp Host: [1.1.7](./services/arrigo-wamp-host.html#117)
  - Domain Controller: [1.1.19](./services/arrigo-domain-controller.html#1119)
  - Volumes: [1.2.5](./services/arrigo-volumes.html#125)
  - Chart Service: [1.1.0](./services/arrigo-services-chart.html#110)
  - State Service: [1.1.3](./services/arrigo-services-state.html#113)
  - DB Service: [1.1.2](./services/arrigo-services-db.html#112)
  - Server-Side Functions: [1.1.1](./services/arrigo-serverside-functions.html#111)

- Required EXO installation: **EXO 2024 Edition 1 - 20**

## 1.4.85
2024-03-11
- Frontend: [1.1.309](./frontend.html#11309)

- Arrigo Local API: [1.4.111](./arrigolocalapi.html#14111)

- Arrigo Local Scada Function: [1.4.21](./arrigolocalscadafunction.html#1421)

- Arrigo config transpiler: [1.4.10](./arrigo.config.transpiler.html#1410)

- Arrigo Local Services  
  - Wamp Host: [1.0.92](./services/arrigo-wamp-host.html#1092)
  - Domain Controller: [1.0.7](./services/arrigo-domain-controller.html#107)
  - Volumes: [1.1.151](./services/arrigo-volumes.html#11151)
  - Chart Service: [1.0.2](./services/arrigo-services-chart.html#102)
  - State Service: [1.0.3](./services/arrigo-services-state.html#103)
  - DB Service: [1.0.2](./services/arrigo-services-db.html#102)
  - Server-Side Functions: [1.0.2](./arrigo-serverside-functions.html#102)

- Required EXO installation: [EXO 2023 Edition 1 - 0224](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.4.76
2024-01-17
- Frontend: [1.1.248](./frontend.html#11248)

- Arrigo Local API: [1.4.90](./arrigolocalapi.html#1490)

- Arrigo Local Scada Function: [1.4.16](./arrigolocalscadafunction.html#1416)

- Arrigo config transpiler: [1.4.9](./arrigo.config.transpiler.html#149)

- Arrigo Local Services  
  - Wamp Host: [1.0.92](./services/arrigo-wamp-host.html#1092)
  - Domain Controller: [1.0.7](./services/arrigo-domain-controller.html#107)
  - Volumes: [1.1.151](./services/arrigo-volumes.html#11151)
  - Chart Service: [1.0.2](./services/arrigo-services-chart.html#102)
  - State Service: [1.0.3](./services/arrigo-services-state.html#103)
  - DB Service: [1.0.2](./services/arrigo-services-db.html#102)
  - Server-Side Functions: [1.0.2](./arrigo-serverside-functions.html#102)

- Required EXO installation: [EXO 2023 Edition 1 - 0224](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.4.75
2024-01-17
- Frontend: [1.1.248](./frontend.html#11248)

- Arrigo Local API: [1.4.90](./arrigolocalapi.html#1490)

- Arrigo Local Scada Function: [1.4.16](./arrigolocalscadafunction.html#1416)

- Arrigo config transpiler: [1.4.9](./arrigo.config.transpiler.html#149)

- Arrigo Local Services  
  - Wamp Host: [1.0.92](./services/arrigo-wamp-host.html#1092)
  - Domain Controller: [1.0.7](./services/arrigo-domain-controller.html#107)
  - Volumes: [1.1.151](./services/arrigo-volumes.html#11151)
  - Chart Service: [1.0.2](./services/arrigo-services-chart.html#102)
  - State Service: [1.0.3](./services/arrigo-services-state.html#103)
  - DB Service: [1.0.2](./services/arrigo-services-db.html#102)
  - Server-Side Functions: [1.0.2](./arrigo-serverside-functions.html#102)

- Required EXO installation: [EXO 2023 Edition 1 - 0198](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.4.73
2024-01-16
- Frontend: [1.1.244](./frontend.html#11244)

- Arrigo Local API: [1.4.90](./arrigolocalapi.html#1490)

- Arrigo Local Scada Function: [1.4.16](./arrigolocalscadafunction.html#1416)

- Arrigo config transpiler: [1.4.9](./arrigo.config.transpiler.html#149)

- Arrigo Local Services  
  - Wamp Host: [1.0.92](./services/arrigo-wamp-host.html#1092)
  - Domain Controller: [1.0.7](./services/arrigo-domain-controller.html#107)
  - Volumes: [1.1.151](./services/arrigo-volumes.html#11151)
  - Chart Service: [1.0.2](./services/arrigo-services-chart.html#102)
  - State Service: [1.0.3](./services/arrigo-services-state.html#103)
  - DB Service: [1.0.2](./services/arrigo-services-db.html#102)
  - Server-Side Functions: [1.0.2](./arrigo-serverside-functions.html#102)

- Required EXO installation: [EXO 2023 Edition 1 - 0198](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

### arrigo-attach-project
- Fix: AZ#2522: Only include Arrigo processes when checking for restarting processes (#18)

## 1.4.37
2023-10-17
- Frontend: [1.1.130](./frontend.html#11130)

- Arrigo Local API: [1.4.23](./arrigolocalapi.html#1423)

- Arrigo Local Scada Function: [1.4.12](./arrigolocalscadafunction.html#1412)

- Arrigo config transpiler: [1.4.4](./arrigo.config.transpiler.html#144)

- Arrigo Local Services  
  - Wamp Host: [1.0.92](./services/arrigo-wamp-host.html#1092)
  - Domain Controller: [1.0.7](./services/arrigo-domain-controller.html#107)
  - Volumes: [1.1.142](./services/arrigo-volumes.html#11142)
  - Chart Service: [1.0.2](./services/arrigo-services-chart.html#102)
  - State Service: [1.0.3](./services/arrigo-services-state.html#103)
  - DB Service: [1.0.2](./services/arrigo-services-db.html#102)
  - Server-Side Functions: [1.0.0](./arrigo-serverside-functions.html#100)

- Required EXO installation: [EXO 2023 Edition 1 - 0198](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.4.33
2023-10-11
- Frontend: [1.1.113](./frontend.html#11113)

- Arrigo Local API: [1.4.43](./arrigolocalapi.html#1443)

- Arrigo Local Scada Function: [1.4.12](./arrigolocalscadafunction.html#1412)

- Arrigo config transpiler: [1.4.4](./arrigo.config.transpiler.html#144)

- Arrigo Local Services  
  - Wamp Host: [1.0.92](./services/arrigo-wamp-host.html#1092)
  - Domain Controller: [1.0.7](./services/arrigo-domain-controller.html#107)
  - Volumes: [1.1.142](./services/arrigo-volumes.html#11142)
  - Chart Service: [1.0.2](./services/arrigo-services-chart.html#102)
  - State Service: [1.0.3](./services/arrigo-services-state.html#103)
  - DB Service: [1.0.2](./services/arrigo-services-db.html#102)
  - Server-Side Functions: [1.0.0](./arrigo-serverside-functions.html#100)

- Required EXO installation: [EXO 2023 Edition 1 - 0198](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.3.96
2023-09-25
- Frontend: [1.0.574](./frontend.html#10574)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0198](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.3.93
2023-09-20
- Frontend: [1.0.574](./frontend.html#10574)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0075](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.3.90
2023-09-15
- Frontend: [1.0.565](./frontend.html#10565)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0075](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.3.86
2023-07-10
- Frontend: [1.0.554](./frontend.html#10554)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0075](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.3.85
2023-07-06
- Frontend: [1.0.554](./frontend.html#10554)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0053](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)


## 1.3.74
2023-06-14
- Frontend: [1.0.534](./frontend.html#10534)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0053](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

## 1.3.73
2023-06-14
- Frontend: [1.0.529](./frontend.html#10529)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0053](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)


## 1.3.72
2023-06-07
- Frontend: [1.0.528](./frontend.html#10528)

- Arrigo Local API: [1.3.24](./arrigolocalapi.html#1324)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.263](./arrigolocalservices.html#10263)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0053](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=etZpaa)

### General

All services and the API are now Dotnet 7 compatible.  
This release will install a newer version of the [Dotnet Windows Hosting Bundle](https://download.visualstudio.microsoft.com/download/pr/19927e80-7df2-4906-badd-439502008177/cb55d49c06a3691965b4bcf934ead822/dotnet-hosting-7.0.5-win.exe) (7.0.5).

## 1.3.48
2023-05-12
- Frontend: [1.0.528](./frontend.html#10528)

- Arrigo Local API: [1.3.15](./arrigolocalapi.html#1315)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.233](./arrigolocalservices.html#10233)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0039](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

## 1.3.44
2023-05-08
- Frontend: [1.0.521](./frontend.html#10521)

- Arrigo Local API: [1.3.15](./arrigolocalapi.html#1315)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.233](./arrigolocalservices.html#10233)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0039](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

### Installer

- Fix: Removing the EXOSERVICE_PM2 env.var (#48)

## 1.3.43
2023-05-05
- Frontend: [1.0.521](./frontend.html#10521)

- Arrigo Local API: [1.3.15](./arrigolocalapi.html#1315)

- Arrigo Local Scada Function: [1.3.11](./arrigolocalscadafunction.html#1311)

- Arrigo Local Services: [1.0.233](./arrigolocalservices.html#10233)

- Arrigo config transpiler: [1.3.7](./arrigo.config.transpiler.html#137)

- Required EXO installation: [EXO 2023 Edition 1 - 0039](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

### arrigo-attach-project

- Feature: Support for service snippets (#11)

## 1.3.27
2023-04-26
- Frontend: [1.0.514](./frontend.html#10514)

- Arrigo Local API: [1.3.12](./arrigolocalapi.html#1312)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0039](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

## 1.3.26
2023-04-26
- Frontend: [1.0.514](./frontend.html#10514)

- Arrigo Local API: [1.3.10](./arrigolocalapi.html#1310)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0039](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

**Note that** this version has no added functionality or fixes. It is only the required EXO installation/release that has changed.

## 1.3.25
2023-04-25
- Frontend: [1.0.514](./frontend.html#10514)

- Arrigo Local API: [1.3.12](./arrigolocalapi.html#1312)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0035](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

## 1.3.24
2023-04-13
- Frontend: [1.0.514](./frontend.html#10514)

- Arrigo Local API: [1.3.10](./arrigolocalapi.html#1310)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0035](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/ERrkxf-WOwxLq1ZMkCZLxeoBi9qA2lVyGw2X-ixvJLzx_w?e=VZqiUE)

**Note that** this version has no added functionality or fixes. It is only the required EXO installation/release that has changed.

## 1.3.23
2023-04-12
- Frontend: [1.0.514](./frontend.html#10514)

- Arrigo Local API: [1.3.10](./arrigolocalapi.html#1310)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0028](https://abregin.sharepoint.com/:b:/s/ReginSoftwareDistribution/EZumEJZS5VtGr-KLctV0B9QBmz533nMCGBY1UptyYePmQQ?e=QNPwHs)

### arrigo-attach-project

- Hotfix: Only check for project path correctness when attaching project

## 1.3.21
2023-04-05
- Frontend: [1.0.514](./frontend.html#10514)

- Arrigo Local API: [1.3.10](./arrigolocalapi.html#1310)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0028](https://abregin.sharepoint.com/:b:/s/ReginSoftwareDistribution/EZumEJZS5VtGr-KLctV0B9QBmz533nMCGBY1UptyYePmQQ?e=QNPwHs)

### arrigo-attach-project

- Fix: Aborting if trying to attach to attach Arrigo to a project that is not the currently attached EXO project (#10)

## 1.3.20
2023-04-03
- Frontend: [1.0.511](./frontend.html#10511)

- Arrigo Local API: [1.3.10](./arrigolocalapi.html#1310)

- Arrigo Local Scada Function: [1.3.5](./arrigolocalscadafunction.html#135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2023 Edition 1 - 0027](https://abregin.sharepoint.com/:b:/s/ReginSoftwareDistribution/EZumEJZS5VtGr-KLctV0B9QBmz533nMCGBY1UptyYePmQQ?e=QNPwHs)

## 1.3.5
2023-02-16
- Frontend: [1.0.498](./frontend.html#10498)

- Arrigo Local API: [1.3.1](./arrigolocalapi.html#131)

- Arrigo Local Scada Function: [1.3.3](./arrigolocalscadafunction.html#133)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2022 Edition 1 - 0013](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/EU9Zh4__YLNFkFpa4KS4PLUBEBKjme8gcxy0BH1M1QSAbQ?e=hJmgcr)

## 1.3.4
2023-02-14
- Frontend: [1.0.493](./frontend.html#10493)

- Arrigo Local API: [1.3.1](./arrigolocalapi.html#131)

- Arrigo Local Scada Function: [1.3.3](./arrigolocalscadafunction.html#133)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.3.2](./arrigo.config.transpiler.html#132)

- Required EXO installation: [EXO 2022 Edition 1 - 0013](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/EU9Zh4__YLNFkFpa4KS4PLUBEBKjme8gcxy0BH1M1QSAbQ?e=hJmgcr)

## 1.3.2
2023-02-02
- Frontend: [1.0.493](./frontend.html#10493)

- Arrigo Local API: [1.3.1](./arrigolocalapi.html#131)

- Arrigo Local Scada Function: [1.3.1](./arrigolocalscadafunction.html#131)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.228](./arrigo.config.transpiler.html#10228)

- Required EXO installation: [EXO 2022 Edition 1 - 0013](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/EU9Zh4__YLNFkFpa4KS4PLUBEBKjme8gcxy0BH1M1QSAbQ?e=hJmgcr)

## 1.3.1
2023-01-30
- Frontend: [1.0.493](./frontend.html#10493)

- Arrigo Local API: [1.3.1](./arrigolocalapi.html#131)

- Arrigo Local Scada Function: [1.3.1](./arrigolocalscadafunction.html#131)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.227](./arrigo.config.transpiler.html#10227)

- Required EXO installation: [EXO 2022 Edition 1 - 0013](https://abregin.sharepoint.com/:u:/s/ReginSoftwareDistribution/EU9Zh4__YLNFkFpa4KS4PLUBEBKjme8gcxy0BH1M1QSAbQ?e=hJmgcr)

## 1.1.312
2023-02-16
- Frontend: [1.0.498](./frontend.html#10498-legacy)

- Arrigo Local API: [1.0.240](./arrigolocalapi.html#10240)

- Arrigo Local Scada Function: [1.1.146](./arrigolocalscadafunction.html#11146)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.234](./arrigo.config.transpiler.html#10234)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)

## 1.1.311
2023-02-14
- Frontend: [1.0.490](./frontend.html#10490)

- Arrigo Local API: [1.0.240](./arrigolocalapi.html#10240)

- Arrigo Local Scada Function: [1.1.146](./arrigolocalscadafunction.html#11146)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.234](./arrigo.config.transpiler.html#10234)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)

## 1.1.304
2023-02-02
- Frontend: [1.0.490](./frontend.html#10490)

- Arrigo Local API: [1.0.240](./arrigolocalapi.html#10240)

- Arrigo Local Scada Function: [1.1.142](./arrigolocalscadafunction.html#11142)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.228](./arrigo.config.transpiler.html#10228)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)

## 1.1.299
2023-01-18
- Frontend: [1.0.490](./frontend.html#10490)

- Arrigo Local API: [1.0.240](./arrigolocalapi.html#10240)

- Arrigo Local Scada Function: [1.1.142](./arrigolocalscadafunction.html#11142)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.227](./arrigo.config.transpiler.html#10227)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)


## 1.1.298
2023-01-16
- Frontend: [1.0.489](./frontend.html#10489)

- Arrigo Local API: [1.0.239](./arrigolocalapi.html#10239)

- Arrigo Local Scada Function: [1.1.141](./arrigolocalscadafunction.html#11141)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.225](./arrigo.config.transpiler.html#10225)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)


## 1.1.296

2022-11-29
- Frontend: [1.0.467](./frontend.html#10460)

- Arrigo Local API: [1.0.237](./arrigolocalapi.html#10237)

- Arrigo Local Scada Function: [1.1.136](./arrigolocalscadafunction.html#11136)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.225](./arrigo.config.transpiler.html#10225)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)

## 1.1.294

2022-11-29
- Frontend: [1.0.467](./frontend.html#10467)

- Arrigo Local API: [1.0.231](./arrigolocalapi.html#10231)

- Arrigo Local Scada Function: [1.1.135](./arrigolocalscadafunction.html#11135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.218](./arrigo.config.transpiler.html#10218)

- Required EXO installation: EXO 2019 Edition 4 Build [323](./arrigo.exo.releases.html#323)


## 1.1.292

2022-11-29
- Frontend: [1.0.460](./frontend.html#10460)

- Arrigo Local API: [1.0.231](./arrigolocalapi.html#10231)

- Arrigo Local Scada Function: [1.1.135](./arrigolocalscadafunction.html#11135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.218](./arrigo.config.transpiler.html#10218)

- Required EXO installation: EXO 2019 Edition 4 Build [315](./arrigo.exo.releases.html#315)

### Installer

- Fix: AZ#998 Check that processes that are not killed by EXOstop are killed before trying to overwrite them

## 1.1.290

2022-10-28
- Frontend: [1.0.454](./frontend.html#10454)

- Arrigo Local API: [1.0.230](./arrigolocalapi.html#10230)

- Arrigo Local Scada Function: [1.1.135](./arrigolocalscadafunction.html#11135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.214](./arrigo.config.transpiler.html#10214)

- Required EXO installation: EXO 2019 Edition 4 Build [315](./arrigo.exo.releases.html#315)


## 1.1.287

2022-10-21
- Frontend: [1.0.450](./frontend.html#10450)

- Arrigo Local API: [1.0.229](./arrigolocalapi.html#10229)

- Arrigo Local Scada Function: [1.1.135](./arrigolocalscadafunction.html#11135)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.214](./arrigo.config.transpiler.html#10214)

- Required EXO installation: EXO 2019 Edition 4 Build [294](./arrigo.exo.releases.html#294)


## 1.1.274

2022-09-21
- Frontend: [1.0.409](./frontend.html#10409)

- Arrigo Local API: [1.0.223](./arrigolocalapi.html#10223)

- Arrigo Local Scada Function: [1.1.133](./arrigolocalscadafunction.html#11133)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.214](./arrigo.config.transpiler.html#10214)

- Required EXO installation: EXO 2019 Edition 4 Build [294](./arrigo.exo.releases.html#294)


**Note** 
This release will install a newer version of the [.NET Windows Hosting Bundle](https://download.visualstudio.microsoft.com/download/pr/3f4a4c4f-f969-41b3-b9d5-0b889261646b/0c24d7226927c10847b5efecc3528ee0/dotnet-hosting-3.1.26-win.exe) (3.1.26).  

## 1.1.269

2022-09-07
- Frontend: [1.0.401](./frontend.html#10401)

- Arrigo Local API: [1.0.222](./arrigolocalapi.html#10222)

- Arrigo Local Scada Function: [1.1.132](./arrigolocalscadafunction.html#11132)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.214](./arrigo.config.transpiler.html#10214)

- Required EXO installation: EXO 2019 Edition 4 Build [289](./arrigo.exo.releases.html#289)

## 1.1.267

2022-07-06
- Frontend: [1.0.380](./frontend.html#10380)

- Arrigo Local API: [1.0.221](./arrigolocalapi.html#10221)

- Arrigo Local Scada Function: [1.1.131](./arrigolocalscadafunction.html#11131)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.180](./arrigo.config.transpiler.html#10180)

- Required EXO installation: EXO 2019 Edition 4 Build [253](./arrigo.exo.releases.html#253)

## 1.1.265

2022-06-17
- Frontend: [1.0.373](./frontend.html#10373)

- Arrigo Local API: [1.0.217](./arrigolocalapi.html#10217)

- Arrigo Local Scada Function: [1.1.131](./arrigolocalscadafunction.html#11131)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.180](./arrigo.config.transpiler.html#10180)

- Required EXO installation: EXO 2019 Edition 4 Build [253](./arrigo.exo.releases.html#253)

## 1.1.261

2022-06-09
- Frontend: [1.0.373](./frontend.html#10373)

- Arrigo Local API: [1.0.215](./arrigolocalapi.html#10215)

- Arrigo Local Scada Function: [1.1.131](./arrigolocalscadafunction.html#11131)

- Arrigo Local Services: [1.0.211](./arrigolocalservices.html#10211)

- Arrigo config transpiler: [1.0.179](./arrigo.config.transpiler.html#10179)

- Required EXO installation: EXO 2019 Edition 4 Build [253](./arrigo.exo.releases.html#253)

### Installer

- Fix: Using the sid instead of account name when setting folder permissions as BUILTIN\Administrators (better language support)
- Minor fixes for "offline mode"


## 1.1.240

2022-05-25
- Frontend: [1.0.354](./frontend.html#10354)

- Arrigo Local API: [1.0.208](./arrigolocalapi.html#10208)

- Arrigo Local Scada Function: [1.1.115](./arrigolocalscadafunction.html#11115)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.165](./arrigo.config.transpiler.html#10165)

- Required EXO installation: EXO 2019 Edition 4 Build [253](./arrigo.exo.releases.html#253)

**Note**  
This release will install a newer version of [Node.js](https://nodejs.org/dist/v16.15.0/node-v16.15.0-x64.msi) (16.15.0).  
To succeessfully install this release on an _offline server_ you must also first download and install Node.js manually on the target machine.

## 1.1.238
2022-05-25
- Frontend: [1.0.354](./frontend.html#10354)

- Arrigo Local API: [1.0.208](./arrigolocalapi.html#10208)

- Arrigo Local Scada Function: [1.1.115](./arrigolocalscadafunction.html#11115)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.163](./arrigo.config.transpiler.html#10163)

- Required EXO installation: EXO 2019 Edition 4 Build [253](./arrigo.exo.releases.html#253)

**Note**  
This release will install a newer version of [Node.js](https://nodejs.org/dist/v16.15.0/node-v16.15.0-x64.msi) (16.15.0).  
To succeessfully install this release on an _offline server_ you must also first download and install Node.js manually on the target machine.

### Tools and Runtime

- TP#14560: Virtual paths in AreaProperties.Exo (#12)
- ViewAppLib: Language fixes in TimeChannelEditor
- TP-15417:Fixed onManeuver code for Selector (interactive symbol)

## 1.1.236
2022-03-11
- Frontend: [1.0.346](./frontend.html#10346)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.115](./arrigolocalscadafunction.html#11115)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.163](./arrigo.config.transpiler.html#10163)

- Required EXO installation: EXO 2019 Edition 4 Build [243](./arrigo.exo.releases.html#423)

## 1.1.226
2022-03-11
- Frontend: [1.0.329](./frontend.html#10329)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.114](./arrigolocalscadafunction.html#11114)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.163](./arrigo.config.transpiler.html#10163)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)

## 1.1.223
2022-03-10
- Frontend: [1.0.326](./frontend.html#10326)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.114](./arrigolocalscadafunction.html#11114)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.163](./arrigo.config.transpiler.html#10163)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)


## 1.1.217
2022-03-04
- Frontend: [1.0.315](./frontend.html#10315)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.112](./arrigolocalscadafunction.html#11112)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.162](./arrigo.config.transpiler.html#10162)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)

### ArrigoAttach

- Hotfix:  Set IIS AppPool\ArrigoAppPool read rights on exoproject folder  (TP#14558)

- Hotfix: Rewrite pm2 list wrapper using json output. (#6)

## 1.1.216
2022-02-28
- Frontend: [1.0.311](./frontend.html#10311)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.112](./arrigolocalscadafunction.html#11112)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.162](./arrigo.config.transpiler.html#10162)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)

## 1.1.215
2022-02-25
- Frontend: [1.0.307](./frontend.html#10307)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.112](./arrigolocalscadafunction.html#11112)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.162](./arrigo.config.transpiler.html#10162)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)

## 1.1.213
2022-02-24
- Frontend: [1.0.307](./frontend.html#10307)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.111](./arrigolocalscadafunction.html#11111)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.162](./arrigo.config.transpiler.html#10162)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)

## 1.1.208
2022-02-17
- Frontend: [1.0.307](./frontend.html#10307)

- Arrigo Local API: [1.0.206](./arrigolocalapi.html#10206)

- Arrigo Local Scada Function: [1.1.111](./arrigolocalscadafunction.html#11111)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.160](./arrigo.config.transpiler.html#10160)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)

### Tools and Runtime

- Removed 'SelectColor' suggest in 'ArrigoChartTool'

- Hotfix: Updated default values for reports (TP#13315)

**Note**  
This release will install a newer version of the [.NET Windows Hosting Bundle](https://download.visualstudio.microsoft.com/download/pr/5b681079-0068-4c70-be77-af30f1154a83/cd5d074d8328fbc0b3bebf87c88ae082/dotnet-hosting-3.1.22-win.exe) (3.1.22).  
To succeessfully install this release on an _offline server_ you must also first download and install the Hosting Bundle manually on the target machine.

## 1.1.203
2022-02-04
- Frontend: [1.0.300](./frontend.html#10300)

- Arrigo Local API: [1.0.205](./arrigolocalapi.html#10205)

- Arrigo Local Scada Function: [1.1.111](./arrigolocalscadafunction.html#11111)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.157](./arrigo.config.transpiler.html#10157)

- Required EXO installation: EXO 2019 Edition 4 Build [226](./arrigo.exo.releases.html#226)


## 1.1.202
2022-01-28
- Frontend: [1.0.300](./frontend.html#10300)

- Arrigo Local API: [1.0.205](./arrigolocalapi.html#10205)

- Arrigo Local Scada Function: [1.1.111](./arrigolocalscadafunction.html#11111)

- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)

- Arrigo config transpiler: [1.0.157](./arrigo.config.transpiler.html#10157)

- Required EXO installation: EXO 2019 Edition 4 Build [108](./arrigo.exo.releases.html#108)



## 1.1.199
2022-01-14
- Frontend: [1.0.289](./frontend.html#10289)

- Arrigo Local API: [1.0.205](./arrigolocalapi.html#10205)

- Arrigo Local Scada Function: [1.1.107](./arrigolocalscadafunction.html#11107)

- Arrigo Local Services: [1.0.201](./arrigolocalservices.html#10201)

- Arrigo config transpiler: [1.0.157](./arrigo.config.transpiler.html#10157)

- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.196
2021-12-21
- Frontend: [1.0.287](./frontend.html#10287)

- Arrigo Local API: [1.0.204](./arrigolocalapi.html#10204)

- Arrigo Local Scada Function: [1.1.107](./arrigolocalscadafunction.html#11107)

- Arrigo Local Services: [1.0.200](./arrigolocalservices.html#10200)

- Arrigo config transpiler: [1.0.157](./arrigo.config.transpiler.html#10157)

- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.188

2021-12-10
- Frontend: [1.0.278](./frontend.html#10278)

- Arrigo Local API: [1.0.204](./arrigolocalapi.html#10204)

- Arrigo Local Scada Function: [1.1.107](./arrigolocalscadafunction.html#11107)

- Arrigo Local Services: [1.0.197](./arrigolocalservices.html#10197)

- Arrigo config transpiler: [1.0.156](./arrigo.config.transpiler.html#10156)

- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.187

2021-12-08
- Frontend: [1.0.271](./frontend.html#10271)

- Arrigo Local API: [1.0.203](./arrigolocalapi.html#10203)

- Arrigo Local Scada Function: [1.1.106](./arrigolocalscadafunction.html#11106)

- Arrigo Local Services: [1.0.194](./arrigolocalservices.html#10194)

- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.185
2021-12-03
- Frontend: [1.0.271](./frontend.html#10271)

- Arrigo Local API: [1.0.203](./arrigolocalapi.html#10203)

- Arrigo Local Scada Function: [1.1.103](./arrigolocalscadafunction.html#11102)

- Arrigo Local Services: [1.0.193](./arrigolocalservices.html#10193)

- Required EXO installation: EXO 2019 Edition 4 Build 108


## 1.1.182
2021-12-03
- Frontend: [1.0.269](./frontend.html#10269)

- Arrigo Local API: [1.0.203](./arrigolocalapi.html#10203)

- Arrigo Local Scada Function: [1.1.103](./arrigolocalscadafunction.html#11102)

- Arrigo Local Services: [1.0.193](./arrigolocalservices.html#10193)

- Required EXO installation: EXO 2019 Edition 4 Build 108


## 1.1.169

2022-02-07
- Frontend: [1.0.263](./frontend.html#10263)
- Arrigo Local API: [1.0.199](./arrigolocalapi.html#10199)
- Arrigo Local Scada Function: [1.1.96](./arrigolocalscadafunction.html#1196)
- Arrigo Local Services: [1.0.202](./arrigolocalservices.html#10202)
- Required EXO installation: EXO 2019 Edition 4 Build 226

### Installer

- Fix: Fixed argument typo (unsignedcadafunction vs unsigned**s**cadafunction)
- Fix: Checking if the running user is member of BUILTIN\Administrators (#25)

## 1.1.165

2021-11-09
- Frontend: [1.0.251](./frontend.html#10251)
- Arrigo Local API: [1.0.196](./arrigolocalapi.html#10196)
- Arrigo Local Scada Function: [1.1.92](./arrigolocalscadafunction.html#1192)
- Arrigo Local Services: [1.0.185](./arrigolocalservices.html#10185)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### Installer

- Fix: Setting the ExecutionPolicy to Bypass for CurrentUser at startup (TP#11426)

### ArrigoAttach

- Fix: Saving pm2 configuration when attaching project (TP#11425)

## 1.1.155

2021-10-21
- Frontend: [1.0.248](./frontend.html#10248)
- Arrigo Local API: [1.0.196](./arrigolocalapi.html#10196)
- Arrigo Local Scada Function: [1.1.92](./arrigolocalscadafunction.html#1192)
- Arrigo Local Services: [1.0.185](./arrigolocalservices.html#10185)
- Required EXO installation: EXO 2019 Edition 4 Build 108


## 1.1.151

2021-10-14

- Frontend: [1.0.245](./frontend.html#10245)
- Arrigo Local API: [1.0.196](./arrigolocalapi.html#10196)
- Arrigo Local Scada Function: [1.1.92](./arrigolocalscadafunction.html#1192)
- Arrigo Local Services: [1.0.185](./arrigolocalservices.html#10185)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### Installer

- Fix: Setting the ExecutionPolicy to Bypass at startup (TP#11426) (#22)
- Fix: Machine global installation of npm/pm2 to handle multiple users (TP#11425) (#21)

### Tools and Runtime

- Improvements in how 'Arrigo Attach' handles pm2 (processes are always run as SYSTEM)
- 'Arrigo Attch' now sets permissions on the project folder to prevent API read/write errors
- DateDialogBox referred to non-existing textfile (exists only for CW) for month names (TP#11554)
- Fixed file copy section for PIDBasic_Operation_Legacy.Rwlv in Template 'Update Template Views' (TP#11555)
- New attribute for previous route in Arrigo (UsePreviousRoute) (TP#9503)
- Reports: Corrected from and to date in filter option (TP#11460)
- Arrigo BMS and Controller Web - Password style in List View not working (TP#9605)
- Added a new attribute (Tolerance) for chart customization (TP#10255)
- View popup bring to front not working (TP#10589)

## 1.1.139

2021-09-17

- Frontend: [1.0.224](./frontend.html#10224)
- Arrigo Local API: [1.0.191](./arrigolocalapi.html#10191)
- Arrigo Local Scada Function: [1.1.91](./arrigolocalscadafunction.html#1191)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.137

2021-09-13

- Frontend: [1.0.224](./frontend.html#10224)
- Arrigo Local API: [1.0.190](./arrigolocalapi.html#10190)
- Arrigo Local Scada Function: [1.1.91](./arrigolocalscadafunction.html#1191)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### Installer

- Feature: TP-10983 Try set ExecutionPolicy on startup (#20)

## 1.1.135

2021-09-08

- Frontend: [1.0.213](./frontend.html#10213)
- Arrigo Local API: [1.0.190](./arrigolocalapi.html#10190)
- Arrigo Local Scada Function: [1.1.91](./arrigolocalscadafunction.html#1191)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.131

2021-08-27

- Frontend: [1.0.206](./frontend.html#10206)
- Arrigo Local API: [1.0.186](./arrigolocalapi.html#10186)
- Arrigo Local Scada Function: [1.1.91](./arrigolocalscadafunction.html#1191)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### General

- Support for OpenUserArea and OpenTab in conversion - no information is lost. (no support in runtime yet, more to come)

## 1.1.130

2021-08-27

- Frontend: [1.0.206](./frontend.html#10206)
- Arrigo Local API: [1.0.185](./arrigolocalapi.html#10185)
- Arrigo Local Scada Function: [1.1.91](./arrigolocalscadafunction.html#1191)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### General

* Added global arguments support for embedded views

## 1.1.127

2021-08-24

- Frontend: [1.0.205](./frontend.html#10205)
- Arrigo Local API: [1.0.184](./arrigolocalapi.html#10184)
- Arrigo Local Scada Function: [1.1.90](./arrigolocalscadafunction.html#1190)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108


## 1.1.126

2021-08-23

- Frontend: [1.0.205](./frontend.html#10205)
- Arrigo Local API: [1.0.183](./arrigolocalapi.html#10183)
- Arrigo Local Scada Function: [1.1.89](./arrigolocalscadafunction.html#1189)
- Arrigo Local Services: [1.0.184](./arrigolocalservices.html#10184)
- Required EXO installation: EXO 2019 Edition 4 Build 108

## 1.1.121

2021-08-10

- Frontend: [1.0.201](./frontend.html#10201)
- Arrigo Local API: [1.0.182](./arrigolocalapi.html#10182)
- Arrigo Local Scada Function: [1.1.88](./arrigolocalscadafunction.html#1188)
- Arrigo Local Services: [1.0.183](./arrigolocalservices.html#10183)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### General

* Support for global arguments in tools

## 1.1.114 

2021-07-14

- Frontend: [1.0.199](./frontend.html#10199)
- Arrigo Local API: [1.0.182](./arrigolocalapi.html#10182)
- Arrigo Local Scada Function: [1.1.87](./arrigolocalscadafunction.html#1187)
- Arrigo Local Services: [1.0.183](./arrigolocalservices.html#10183)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### Installer

* All bulky file copy operations now display progress and log copied files
* ALI checks that the effective Powershell ExecutionPolicy is correct when starting up, and exists the installer if it isn't

### Tools

* Various template fixes (TP#8833, 9425)
* Added more Arrigo tool options in project builder (detach, view instructions, view status,view logs) (TP#9220)
* Arrigo Link icon Single Timechannel (TP#9811)
* Arrigo BMS and Controller Web - Password style in List View not working (TP#9605)

## 1.1.99

2021-08-19

- Frontend: [1.0.187](./frontend.html#10187)
- Arrigo Local API: [1.0.176](./arrigolocalapi.html#10176)
- Arrigo Local Scada Function: [1.1.84](./arrigolocalscadafunction.html#1184)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### Installer

* Fix: Better version handling

## 1.1.98

2021-06-23

- Frontend: [1.0.187](./frontend.html#10187)
- Arrigo Local API: [1.0.176](./arrigolocalapi.html#10176)
- Arrigo Local Scada Function: [1.1.84](./arrigolocalscadafunction.html#1184)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4 Build 108

### Installer

* Showing General Instructions after installation is complete


### Tools

* Template fixes (TP#9643)

## 1.1.84

2021-06-11

- Frontend: [1.0.187](./frontend.html#10187)
- Arrigo Local API: [1.0.176](./arrigolocalapi.html#10176)
- Arrigo Local Scada Function: [1.1.84](./arrigolocalscadafunction.html#1184)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Installer

* Starting the installer with `-force` disables the check for newer versions online
* The installer now does a strict check of the specific EXO release installed on the machine. If it differs from the version the installer is built against, the user is notified and the installation is aborted.

### Tools

* Various template fixes (TP#8259, 9425)
* "Select/Append picture from shared folder" now opens the correct folder (TP#8355)
* New icons for various tools and templates
* First day of week and language in calendar is selected based on the language/locale of the browser (TP#7796)
* Added support for "ViewType Widget" in ListViewTool. Attributes for Lists are limited or disabled when ViewType=Widget
* FolderViewsTool: Only view files with ViewType=Widget can be added/selected/picked in Widget File attribute (TP#8262)
* "Use legacy theme" as an option when converting Area (TP#9114)
* Support for multiple calls to include with same arguments in the same view
* Both View Designers now handle high DPI modes (TP#9099)
* Fixed issue regarding multiple Control Curve windows (TP#9106)
* Dialog boxes for numeric, textselect etc. now have multiline text elements for description text

## 1.1.76

2021-05-28

- Frontend: [1.0.180](./frontend.html#10180)
- Arrigo Local API: [1.0.174](./arrigolocalapi.html#10174)
- Arrigo Local Scada Function: [1.1.82](./arrigolocalscadafunction.html#1182)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Installer

* Fix: Better handling of major upgrades of EXOscada (no need to `-force` the installation) (TP#8998)
* Fix: Handling Cyrillic characters in usernames

### Tools

* Time Channel editor: Fixed create new period when 0 periods in chart. Progress feedback during download. Rescaling to small screens ("phone view").
* Calendar: Fixed no. of holiday periods. Progress feedback during download. Rescaling to small screens - "one month mode"
* Max and min Values are now bound in RwUiSymbol (TP\#7590)
* Time Channel editor: New list view template for Time channel editor
* HolidayCalendar: New list view template for holiday calendar (for use in e.g. controller web)
* CommandBar convert error fix. ViewTitle on ClickArea convert to Window Title (TP#8996)
* View Designer: Template for Fan Man/Auto fixed (TP#8407)
* BACnet signals through OPC are now writable (TP#9045)
* Writing to string types in Computer Signals is now supported (TP#9053)
* Various fixes in the "Upgrade Arrigo BMS" tool
* Fix for Bargraph and OpenViewInTab for LinkIcons
* Fix for TimeChannel file lookup when converting area

## 1.1.64

2021-05-12

- Frontend: [1.0.172](./frontend.html#10172)
- Arrigo Local API: [1.0.171](./arrigolocalapi.html#10171)
- Arrigo Local Scada Function: [1.1.81](./arrigolocalscadafunction.html#1181)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Installer

* Fixed another bug regarding console output

## 1.1.61

2021-05-12

- Frontend: [1.0.172](./frontend.html#10172)
- Arrigo Local API: [1.0.171](./arrigolocalapi.html#10171)
- Arrigo Local Scada Function: [1.1.81](./arrigolocalscadafunction.html#1181)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Installer

* Fixed a bug which could cause the console output to stop even though the installer was running correctly

## 1.1.60

2021-05-11

- Frontend: [1.0.172](./frontend.html#10172)
- Arrigo Local API: [1.0.171](./arrigolocalapi.html#10171)
- Arrigo Local Scada Function: [1.1.81](./arrigolocalscadafunction.html#1181)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Installer

* Trying different ways of detecting if the Dotnet Hosting Bundle is installed before failing

## 1.1.58

2021-05-07

- Frontend: [1.0.168](./frontend.html#10168)
- Arrigo Local API: [1.0.169](./arrigolocalapi.html#10169)
- Arrigo Local Scada Function: [1.1.81](./arrigolocalscadafunction.html#1181)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Installer

* Downloading the Dotnet Hosting Bundle instead of bundling it
* Added error codes, and links to descriptions, on all fatal errors

## 1.1.56
2021-05-06

- Frontend: [1.0.168](./frontend.html#10168)
- Arrigo Local API: [1.0.168](./arrigolocalapi.html#10168)
- Arrigo Local Scada Function: [1.1.81](./arrigolocalscadafunction.html#1181)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Views


### Tools
* Hotfix: Folder Tool checks for existing .foldermeta file
* Fix: Copying the correct files when creating an Area in Project Builder


## 1.1.51 
2021-05-04 

- Frontend: [1.0.164](./frontend.html#10164)
- Arrigo Local API: [1.0.166](./arrigolocalapi.html#10166)
- Arrigo Local Scada Function: [1.1.81](./arrigolocalscadafunction.html#1181)
- Arrigo Local Services: [1.0.176](./arrigolocalservices.html#10176)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Views
- ControlCurve view - better place for texts and values

### Tools
- Copying templates (account and default) when running the command "Upgrade project to current Arrigo BMS version". Remove the existing "Proj:EXOscada/ArrigoBMSProjectVersion.ExoXml" if the tool doesn't start
- Bug fix: File arguments in FolderViewsTool now work as expected

## 1.1.45 
2021-04-30 
- Frontend: [1.0.163](./frontend.html#10163)
- Arrigo Local API: [1.0.164](./arrigolocalapi.html#10164)
- Arrigo Local Scada Function: [1.1.80](./arrigolocalscadafunction.html#1180)
- Arrigo Local Services: [1.0.136](./arrigolocalservices.html#10136)
- Required EXO installation: EXO 2019 Edition 4  Build 29

### Views
- Report view
- Generic svg view
- Custom filter in svg view
- Charts Save load works
- Open document in link icons

### Tools
- Added generic svg views
- Support for ServerSide Functions in generic svg views, view designer and list view tools
- Reports service
- State service
- Database service
- Fetch service
- Templates for reports



## 1.0.323

2021-04-01

- Frontend: [1.0.137](./frontend.html#10137)
- Arrigo Local API: [1.0.163](./arrigolocalapi.html#10163)
- Arrigo Local Scada Function: [1.0.72](./arrigolocalscadafunction.html#1072)
- Required EXO installation: EXO 2019 Edition 3  Build 793

## 1.0.322

2021-03-31

- Frontend: [1.0.130](./frontend.html#10130)
- Arrigo Local API: [1.0.162](./arrigolocalapi.html#10162)
- Arrigo Local Scada Function: [1.0.72](./arrigolocalscadafunction.html#1072)
- Required EXO installation: EXO 2019 Edition 3  Build 793

### Views



### Tools/Templates




## 1.0.317

2021-03-09

- Frontend: [1.0.120](./frontend.html#10120)
- Arrigo Local API: [1.0.161](./arrigolocalapi.html#10161)
- Arrigo Local Scada Function: [1.0.70](./arrigolocalscadafunction.html#1070)
- Required EXO installation: EXO 2019 Edition 3  Build 793

### Views

- Arrigo BMS/CW2: Button Yellow when variable connected to Visible

### Tools/Templates

- Hotfix: Fixed "Browse" for the "Select controller" in template wizard step.

  

## 1.0.315

*2021-03-01*

- Frontend: [1.0.118](./frontend.html#10118)

- Arrigo Local API: [1.0.161](./arrigolocalapi.html#10161)

- Arrigo Local Scada Function: [1.0.70](./arrigolocalscadafunction.html#1070)

- Required EXO installation: EXO 2019 Edition 3  Build 793

### Installer


### Views

- ArrigoFolderViews/View Designer templates: Visual updates for Contol Curve Editor
- ArrigoFolderViews templates: Calendar view and link icon added
- ArrigoFolderViews/View Designer templates: New features and visual updates regarding the Time Channel Editor
- Undo button (reverts to current controller time channel set-up)
- Manual text-editing of times possible
- Added touch functionality
- Visual feedback after time editing and download to controller
- Added a line showing current time and weekday/holiday.
- Added read/write support for analog, digial, integer ComputerSignals (only numerics) in Arrigo

### Tools

- Bug fix: "Open file" in ArrigoFolderView tool open wrong folder
- Always open an existing ArrigoFolderViewsFile in the area even if the current path in AreaProperties not exist
- Hot fix: ProjectBuilder crash when trying to open ArrigoFolder on project level
- Hot fix: CW2 Fonts is not updated when new theme file is loaded
- ArrigoConvertTool minor fix.



## 1.0.312
*2021-02-12*

- Frontend: [1.0.109](./frontend.html#10109)

- Arrigo Local API: [1.0.161](./arrigolocalapi.html#10161)

- Arrigo Local Scada Function: [1.0.70](./arrigolocalscadafunction.html#1070)

- Required EXO installation: EXO 2019 Edition 3  Build 793

### Installer

* The ReginAppPool is stopped when installing EXO components to prevent issues where files are in use
* The install log is now copied by the bootstrapper instead of the scripts
* The theme and images folders are excluded from deletion when installing a new frontend

### Views

- 

### Tools

- Arrigo Folder tools can now be opened from the project/account node in Project Builder
- Added a template for the project/account folder

## 1.0.299
*2021-01-22*

- Frontend: [1.0.91](./frontend.html#1.0.91)

- Arrigo Local API: [1.0.154](./arrigolocalapi.html#10154)

- Arrigo Local Scada Function: [1.0.69](./arrigolocalscadafunction.html#1069)

- Required EXO installation: EXO 2019 Edition 3  Build 793


### Installer

No Changes.

### Views

- Major improved speed and performance
- Persistent links to all routes. You are now free to bookmark anything
- Support for 2D rotation in views
- %Include(file, arg1,  arg2)% macro in views and config files
- Lots of bug fixes and improvements

### Tools

- Bug fixes
- Chart tool opens correctly from link icons
- Improved link icon feature list

## 1.0.295
*2021-01-13*

- Frontend: 1.0.68
- Arrigo Local API: 1.0.147
- Arrigo Local Scada Function: 1.1.60
- Required EXO installation: EXO 2019 Edition 3  Build 767

### Installer

- Fixed a bug where the Arrigo BMS SCADA Function could be downgraded by the EXO installation.

- Removed the old Flash fix from the installer. Use FlashEnabler-1.0.7 instead!

## 1.0.277
*2020-12-16*


### Runtime

- Fixed a bug that could crash the Arrigo BMS Scada function when unadvising variables.

## 1.0.269
*2020-12-07*

### Installer

- Messages in the installer log are now timestamped
- Running the Flash fixer (KB4577586) as a part of the installation
- Saving the ArrigoLocalInstaller version in versions.json


### Runtime

- Various fixes regarding images in views
- Fixed a bug where long startup times could deadlock the Arrigo BMS Scada function
- Fixed a bug that prevented the User Log/History from showing
- Fixed a bug that made logins fail under certain conditions

## 1.0.265
*2020-11-24*

### Installer

- Added the option to pin an installer, i.e. skip the online check for newer versions
- No output from bootstrapper when in quiet mode
- Added the "latest" mode which will let customers try production-ready code that hasn't been tested as much as "stable"

### Tools

- New look for animated fan symbol
- Hotfix: Enable name change for Link Icons
- Various template fixes

### Runtime

- Message timestamps are now delivered as UTC
- Handling non-existing connection strings
- Subscribed OneShots are only returned when they have a "valid" value, i.e. they're not "Pending"
- Reading variables is now approx. 40-200 times faster
- Added a new mutation for writing data based on keys in the view content
- Writing to variables from within an SVG now works as expected

## 1.0.247
*2020-11-06*

### Installer

- Preparing for Windows update KB4577586 (Flash removal). 
- Args passing when installation upgrade
- Folders were created in the disk root if the installer was run directly after a fresh EXO installation.
- Powershell version check
- Unsafe Mode flag added. Lets you try to install on unsupported OS'es. 
- Added a "press any key to continue" when running in unsafe mode

### Tools

- Greater support for Shared: in tools. 
- Hotfix: Chart arguments did not show up in folder views tool
- Hotfix: Argument template missing in FolderViewsTool.

### Templates

- ViewAppLib+ListViewTemplates+ViewDesignerTemplates:PTS19054:New fan,pump and compressor symbol
- Icon-path error in station's ArrigoBMS.Exocommands
- Preparing for area types
- New Corrigo 5.0 template and related files


### Runtime

- Fix bug in arguments in many instances of same shared viewfile. 

## 1.0.239
*2020-10-27*

This is the first release targeting EXO 2019 Edition 3. 

### Installer 
- Check for new version automatically
- Targets EXO 2019 Edition 3

### FolderTool
- Fix: icons
- Fix: icon suggests

### FolderViewsTool
- Fix: icons

### Templates
- Minor fixes.

## 1.0.233
*2020-10-26*
The first one. The hot stuff. So hot that we haven't even tried every aspect of it ourselves. Try it out, you will not be disappointed.
- Widgets
- Link icons in groups
- Arguments in folder views files
- Lots of svg files included

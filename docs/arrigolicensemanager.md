---
layout: main
title: Releases - Arrigo Licens Manager
description: Change Log
---

# Change Log

## 1.2.2

*2024-04-12*

### New Features

- **Port Readdressing**: Implemented a feature that automatically assigns an available port to the backend service if the default port is already in use. This ensures smooth operation even in environments with conflicting port allocations. To disable this functionality, supply a port (between 49152 and 65535) by running the installer with "-p PORT" where PORT is the port number.

### Fixes/Improvements

- **Enhanced Stability**: Made various enhancements to the overall stability and reliability of the application.
- **Fixed Dependency Issue**: Resolved an issue where the license manager required an Arrigo Local installation to function.

## 1.1.7

*2024-03-12*

### Migration
- Migration: No changes, only migrated to AB Regin's domain. 

## 1.0.131

*2024-02-15*

### Fixes/Improvements
- Fix: Copy and paste buttons for certificates.
- Fix: Various fixes to reduce operator errors during offline activation/deactivation.
  
## 1.0.128

*2023-10-04*

### Fixes/Improvements
- Fix: Added a clear error message if the License Manager fails to initiate due to a broken certificate.
- Fix: Clarified "Created" to "Added" before the date a license was addedon the License Cards.

## 1.0.121

*2023-06-08*

### Fixes/Improvements
- Fix: The license manager no longer uses the machine name over the WAMP, resolves issues with too long machine names.
- Fix: The shortcut for the license manager now gets the correct path to the icon, delete the icon before updating the license manager to get the correct path if it's already installed.

## 1.0.99

*2023-03-13*

### Fixes/Improvements
- Fix: Upgrade to .Net 7 for the arrigo-wamp-host.

## 1.0.96

*2023-03-01*

### Fixes/Improvements
- Fix: AZ#1746 Now checks version correctly so latest version don't trigger download latest version of license manager installer prompt
- Fix: AZ#1747 Crashes when writing install log, directory is now created to the installer doesn't crash when installing for the first time
- Fix: When choosing to download the latest the program now terminates correctly so the installation of the old version does't proceed

## 1.0.91

*2023-02-22*

### Fixes/Improvements
- Fix: LMI crashes if computer lacks internet connection
- Fix: Checks for newer versions of License Manager Installer correctly
- Fix: Logs installed version

## 1.0.69

*2023-01-30*

### Fixes/Improvements

- Initial release.

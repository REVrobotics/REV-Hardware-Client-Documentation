# REV Hardware Client Overview

The REV Hardware Client is software designed to make managing REV devices easier for the user. This Client automatically detects connected device\(s\), downloads the latest software for those device\(s\), and allows for seamless updating of the device\(s\).

| Latest REV Hardware Client - Version 1.2.0 |
| :---: |
| [![](.gitbook/assets/download-latest-rev-hardware-client.svg)](https://www.revrobotics.com/content/sw/rev-hw-client/REV-Hardware-Client-Setup-1.2.0.exe) |

### Feature Summary

* Automatically detect supported devices when connected via USB
* Connect a REV Control Hub via WiFi
* One Click update of all software on connected devices
* Pre-download software updates without a connected device
* Back up and restore user data from supported devices \(Control Hub and SPARK MAX\)
* Install and switch between DS and RC applications on Android Devices
* Access the Robot Control Console on the Control Hub
* Auto-update to latest version of the REV Hardware Client
* Display devices connected via RS485

### Supported Devices

* REV Control Hub \(REV-31-1595\)
* REV Expansion Hub \(REV-31-1153\)
* REV Driver Hub \(REV-31-1596\)
* Android Device via ADB
* REV SPARK MAX \(REV-11-2158\)
* Generic CAN Devices

### Change Log

#### Version 1.2.0

* General updates:
  * Allow installing previous versions of software
  * Show client updates are available more subtly 
  * Reconnect to ADB if it resets 
  * Show manufacturer names for generic android devices
  * Fixes issues with Control Hub and Expansion Hub firmware falsely saying out of date
  * Other minor bug fixes
* Control Hub specific updates:
  * Shows warning when the Control Hub internal communication is not responding
  * Shows warning when Control Hub webserver is not running
  * Full screen mode for Program and Manage Tab
  * Prompts to backup Control Hub data if backup on file is over a week old
  * Confirmation now required to restore backed up files
  * Fix issues with not all files being restored
* SPARK MAX specific updates:
  * Fixed bug where Alternate Encoder telemetry data was displaying incorrectly
  * Allow for complete Factory Reset of all parameters on SPARK MAX
  * Disabled setting of parameters that have no effect in current configuration
  * Fixed bug where the Client would turn white on selecting SPARK MAX

#### Version 1.1.0

* Adds support for SPARK MAX and other CAN devices 
* Allows for updating SPARK MAX devices, installing APIs, running motors, and viewing data from the SPARK MAX and its motor. 
* Shows all recognized devices on a CAN bus, and the data that is sent on the bus

#### Version 1.0.0

* Original Release




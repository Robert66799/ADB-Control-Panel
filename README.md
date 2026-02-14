# ADB Utility Toolkit

A batch-based interface for managing Android devices through ADB (Android Debug Bridge). This script provides a menu system to automate common tasks and service starts.

**Note: This is currently a Windows-only program. A Linux version is planned for a future update.**

**Disclaimer: This program was developed primarily with the assistance of AI.**
<img width="1101" height="576" alt="image" src="https://github.com/user-attachments/assets/490c4074-f57d-432a-8d7c-a682a8bab7a1" />

## Features

* **Shizuku Service:** Launches the Shizuku service via ADB and monitors the device connection status to handle reconnections.
* **Device Control:** Provides shortcuts for rebooting to system, recovery, or bootloader, as well as remote shutdown.
* **Application Management:** Simplifies installing APKs from a PC or internal phone storage and includes an uninstallation menu.
* **File Operations:** Built-in commands to push files to the device or pull files from the device.
* **Connectivity:** Includes tools for ADB over Wi-Fi, including pairing and wireless toggles.
* **Tool Integration:** Automatically detects and integrates scrcpy for screen mirroring if the executable is present in the script directory.

## Requirements

* **Windows OS:** Designed for use in the Windows Command Prompt.
* **Android Platform Tools:** ADB must be installed and accessible in your system PATH.
* **Developer Options:** USB Debugging must be enabled on the target Android device.

## Setup Guide: Installing ADB and Adding to PATH

To use this script, you must have the Android SDK Platform Tools installed and configured on your Windows system. Check out https://droidwin.com/how-to-add-adb-to-path-in-windows-11/ for more info.  (I am not at all affiliated with DroidWin or any of its affiliates)

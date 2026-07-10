# windows-pc-health-check-guide
A beginner-friendly guide for performing Windows PC health checks and basic troubleshooting.
# Windows PC Health Check Guide

## Overview

This guide explains basic steps to check the health and performance of a Windows computer. These steps can help identify common hardware, software, and performance issues.

This guide is intended for beginner IT technicians and users who want to perform basic troubleshooting.

## 1. Check System Specifications

Checking system specifications helps identify the computer's hardware and operating system information.

### Steps:

1. Press `Windows Key + I` to open Settings.
2. Select **System**.
3. Select **About**.
4. Review:
   - Processor (CPU)
   - Installed RAM
   - Windows version
   - Device name

### Why this matters:

Knowing the system specifications helps determine if a computer meets software requirements and can help diagnose performance issues.

## 2. Check Storage Space

Checking available storage helps identify if low disk space is causing performance issues or preventing updates and software installations.

### Steps:

1. Press `Windows Key + I` to open Settings.
2. Select **System**.
3. Select **Storage**.
4. Review:
   - Total storage capacity
   - Available free space
   - Storage usage by category

### Why this matters:

A computer with very little free storage may experience slower performance, update failures, or problems installing new applications.

A general recommendation is to keep some free space available on the drive to allow Windows and applications to function properly.

## 3. Check Memory Usage (RAM)

Checking memory usage helps identify if a computer is running slowly because of high RAM usage or too many background processes.

### Steps:

1. Press `Ctrl + Shift + Esc` to open Task Manager.
2. Select the **Performance** tab.
3. Select **Memory**.
4. Review:
   - Total installed RAM
   - Current memory usage
   - Available memory
   - Memory speed

You can also review the **Processes** tab to identify applications using large amounts of memory.

### Why this matters:

When a computer runs out of available memory, performance can decrease because Windows may rely more heavily on storage through virtual memory.

High memory usage may be caused by:
- Too many applications running at the same time
- Background programs
- Browser tabs
- Malware or unwanted software
- Insufficient RAM for the user's workload****

## 4. Check Windows Updates

Checking Windows Updates ensures the computer has the latest security patches, bug fixes, and feature updates installed.

### Steps:

1. Press `Windows Key + I` to open Settings.
2. Select **Windows Update**.
3. Click **Check for updates**.
4. Review:
   - Available updates
   - Update history
   - Failed updates (if any)

### Why this matters:

Keeping Windows updated helps:
- Improve security
- Fix software bugs
- Improve system stability
- Maintain compatibility with applications and hardware

If updates fail, common troubleshooting steps include:
- Restarting the computer
- Checking internet connectivity
- Ensuring enough storage space is available
- Running the Windows Update Troubleshooter

## 5. Check Device Manager

Device Manager allows technicians to view installed hardware and check for driver or hardware-related issues.

### Steps:

1. Right-click the **Start Menu** button.
2. Select **Device Manager**.
3. Review the list of installed hardware.
4. Look for:
   - Yellow warning icons
   - Unknown devices
   - Disabled hardware
   - Missing drivers

### Common categories to check:

- Network adapters
- Display adapters
- Audio inputs and outputs
- Bluetooth devices
- Storage controllers

### Why this matters:

Device Manager helps identify hardware problems and driver issues that may cause:
- No internet connection
- No sound
- Display problems
- Hardware not being recognized

Common troubleshooting steps include:
- Updating drivers
- Uninstalling and reinstalling drivers
- Restarting the computer
- Checking for Windows updates

## 6. Run System File Checker (SFC)

System File Checker (SFC) is a Windows command-line tool used to scan and repair corrupted system files.

### Steps:

1. Open the Start Menu.
2. Search for **Command Prompt**.
3. Right-click and select **Run as administrator**.
4. Type: sfc /scannow
5. Press **Enter**.
6. Wait for the scan to complete.

### Why this matters:

Corrupted Windows system files can cause:
- Application crashes
- System instability
- Windows errors
- Performance issues

SFC can automatically repair many common Windows file problems.

### Common results:

- **"Windows Resource Protection did not find any integrity violations"**
  - No corrupted files were found.

- **"Windows Resource Protection found corrupt files and successfully repaired them"**
  - Issues were detected and fixed.

- **"Windows Resource Protection found corrupt files but was unable to fix some of them"**
  - Additional troubleshooting may be required.

## 7. Check Task Manager Performance

Task Manager provides information about running applications, background processes, and system resource usage. It is commonly used to identify performance issues.

### Steps:

1. Press `Ctrl + Shift + Esc` to open Task Manager.
2. Select the **Processes** tab.
3. Review:
   - CPU usage
   - Memory usage
   - Disk usage
   - Network usage

4. Select the **Performance** tab to view:
   - CPU performance
   - Memory usage
   - Storage activity
   - Network activity
   - GPU usage

### Why this matters:

High resource usage can cause slow performance and may indicate:
- Too many applications running
- Resource-heavy programs
- Background processes
- Malware or unwanted software
- Hardware limitations

### Common troubleshooting steps:

- Close unnecessary applications.
- Restart the computer.
- Disable unnecessary startup applications.
- Investigate programs using excessive resources.
- Check for software updates.

## 8. Basic Troubleshooting Checklist

When troubleshooting a Windows computer, follow a structured approach to identify and resolve issues.

### Step 1: Identify the Problem

Ask the user:
- What issue are you experiencing?
- When did the issue start?
- Has anything changed recently?
- Is the problem affecting one user or multiple users?

### Step 2: Perform Basic Checks

Check:
- Is the computer powered on?
- Are cables connected properly?
- Is the device connected to the internet?
- Are there any error messages?

### Step 3: Check System Health

Review:
- System specifications
- Available storage
- RAM usage
- Windows updates
- Device Manager
- Task Manager performance

### Step 4: Attempt a Solution

Possible solutions:
- Restart the computer
- Install updates
- Update drivers
- Close unnecessary applications
- Run system repair tools

### Step 5: Document the Resolution

Record:
- The problem
- Steps taken
- Final solution
- Any follow-up actions needed

### Why documentation matters:

Clear documentation helps other technicians understand previous issues and creates a knowledge base for future troubleshooting.

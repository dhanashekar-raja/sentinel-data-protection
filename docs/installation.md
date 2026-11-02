
# Installation Guide

## Overview

This guide explains the installation workflow for Sentinel Data Protection.

## Prerequisites

Before installing the application, verify the following:

- The target server meets the documented system requirements.
- You have administrative permissions.
- The installation package is available.
- Required network connections are configured.

## Installation Procedure

### Step 1: Obtain the Installation Package

Download the installation package from the designated software distribution location.

### Step 2: Extract the Package

Extract the downloaded archive to a local directory.

Example PowerShell command:

```powershell
Expand-Archive -Path ".\Sentinel.zip" -DestinationPath ".\Sentinel"
```

### Step 3: Run the Installer

Open the extracted directory and launch the installer using an account with the required administrative permissions.

### Step 4: Complete the Installation

Follow the installation wizard and review the configuration options.

### Step 5: Verify the Installation

Confirm that the installation completes successfully.

!!! note "NOTE"
    The installation commands and package names in this exercise are illustrative. They do not represent a tested installer.

## Troubleshooting

| Issue                    | Recommended Action                |
| ------------------------ | --------------------------------- |
| Installation fails       | Review the installation logs.     |
| Insufficient permissions | Verify administrative privileges. |
| Package unavailable      | Check the distribution location.  |


## Verify the Installation

After completing the installation, verify that Sentinel Data Protection is installed correctly.

### Verification Procedure

1. Open the application installation directory.
2. Confirm that the application files are present.
3. Verify that the required application services are running.
4. Review the installation logs for errors.
5. Confirm that the application interface is accessible.

### Expected Result

The installation is considered successful when the application files are present, required services are running, and the application interface is accessible.

!!! note "NOTE"
    The verification procedure is illustrative. Actual verification steps depend on the product's installation architecture.

## Default Application Port

The default application port is 8443.

Administrators must ensure that the port is available before starting the application.

## Related Information

- [Getting Started](getting-started.md)
- [Product Documentation](index.md)
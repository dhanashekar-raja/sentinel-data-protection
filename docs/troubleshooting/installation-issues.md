# Installation Issues

This guide describes common issues that may occur during the installation of Sentinel Data Protection and provides recommended troubleshooting steps.

## Overview

Installation issues can occur because of missing prerequisites, insufficient permissions, network restrictions or incorrect installation settings.

Before troubleshooting:

- Review the installation prerequisites.
- Confirm that the installation package is available and has not been corrupted.
- Verify that you have the required administrative permissions.
- Record the error message and the stage at which the installation failed.

## Common Installation Issues

The following table describes example installation problems and their recommended resolutions.

| Issue | Possible cause | Recommended action |
|---|---|---|
| Installation does not start | Insufficient permissions | Run the installer with the required administrative privileges. |
| Prerequisite validation fails | Required dependency is missing | Review the prerequisite requirements and install the missing dependency. |
| Installation package cannot be opened | Package is incomplete or corrupted | Obtain a fresh installation package and retry. |
| Connection to the service fails | Network restriction or incorrect endpoint | Verify network connectivity and endpoint settings. |
| Installation stops unexpectedly | Insufficient disk space or system resources | Check available disk space and system resource availability. |
| Configuration step fails | Invalid or incomplete configuration | Review the supplied configuration values and retry. |

!!! note "ILLUSTRATIVE TROUBLESHOOTING SCENARIOS"
    These issues and resolutions are examples for this portfolio project. They are not verified product error messages or vendor-supported remediation procedures.

## Troubleshooting Procedures

### Installation Does Not Start

**Symptom:** The installation process does not launch or stops immediately after execution.

**Possible cause:** The installer does not have sufficient permissions.

**Resolution:**

1. Verify that the installation package is available.
2. Right-click the installer.
3. Select the appropriate option to run it with administrative privileges.
4. Follow the installation prompts.
5. Verify whether the installation completes successfully.

If the problem persists, review the operating system's security logs and installation error messages.

### Prerequisite Validation Fails

**Symptom:** The installer reports that one or more prerequisites are missing.

**Possible cause:** The target environment does not meet the required software or system dependencies.

**Resolution:**

1. Review the installation requirements.
2. Identify the missing dependency.
3. Install the required dependency using an approved installation source.
4. Restart the installation process.
5. Confirm that prerequisite validation completes successfully.

### Installation Package Cannot Be Opened

**Symptom:** The installation package fails to open or reports an invalid package error.

**Possible cause:** The downloaded package may be incomplete or corrupted.

**Resolution:**

1. Verify that the package was downloaded successfully.
2. Check the package file size against the expected download size, if available.
3. Obtain a fresh copy from the approved distribution source.
4. Retry the installation.

### Connection to the Service Fails

**Symptom:** The installation process cannot establish a connection to a required service.

**Possible cause:** Network restrictions, DNS resolution problems or incorrect endpoint configuration.

**Resolution:**

1. Verify that the target system has network connectivity.
2. Confirm that the configured service endpoint is correct.
3. Check whether firewall or network security rules restrict the connection.
4. Contact the network administrator if connectivity remains unavailable.
5. Retry the installation after resolving the connectivity issue.

### Configuration Step Fails

**Symptom:** The installation completes some steps but fails while applying configuration settings.

**Possible cause:** One or more configuration values may be invalid or incomplete.

**Resolution:**

1. Record the displayed error message.
2. Review the configuration values.
3. Verify that mandatory fields are populated.
4. Correct any invalid values.
5. Retry the failed configuration step, if supported by the installer.

## Collect Information for Support

If the installation issue remains unresolved, collect the following information before escalating it.

| Information | Description |
|---|---|
| Product version | Version of the installation package. |
| Operating system | Operating system and version of the target environment. |
| Installation stage | Stage at which the installation failed. |
| Error message | Complete error message or error code. |
| Recent changes | Any recent system, network or configuration changes. |
| Troubleshooting performed | Steps already completed and their results. |

!!! tip "SUPPORT INFORMATION"
    Include relevant installation logs and screenshots when submitting a support request. Remove passwords, access tokens and other sensitive information before sharing diagnostic files.

## Installation Verification

After resolving an installation issue, verify that the installation completed successfully.

- [ ] Confirm that the installation process completed.
- [ ] Verify that the required product components are available.
- [ ] Confirm that the relevant services are running, where applicable.
- [ ] Review installation logs for unresolved errors.
- [ ] Proceed with the initial configuration.

For the complete installation procedure, see [Installation](../installation.md).

## Related Documentation

- [Installation](../installation.md)
- [Configuration](../configuration.md)
- [Common Issues](common-issues.md)
- [Getting Started](../getting-started.md)
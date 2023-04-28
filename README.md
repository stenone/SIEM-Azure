# SIEM Azure Sentinel MAP Project for Monitoring Failed Login Attempts

## Overview

The SIEM Azure Sentinel MAP project is designed to help monitor and visualize failed login attempts to a virtual machine in Microsoft Azure. By creating a log analytics workspace, integrating with Azure Security Center, and leveraging Azure Sentinel, this project enables you to detect and respond to potential security threats in real-time.

## Features and Benefits

- Real-time monitoring and visualization of failed login attempts
- Integration with Azure Security Center for advanced threat detection and protection
- Customizable log data extraction and storage
- Automated alerts for potential security threats

## Architecture

The SIEM Azure Sentinel MAP project is built on top of Microsoft Azure and integrates with various security tools and technologies, including:

- Virtual Machine for hosting your applications and storing your data
- Log Analytics Workspace for centralizing and analyzing log data
- Azure Security Center for monitoring and protecting your Azure resources
- Azure Sentinel for advanced threat detection and protection

## Getting Started

To set up the SIEM Azure Sentinel MAP project for monitoring failed login attempts, follow these steps:

1. Create a Microsoft Azure subscription and deploy a virtual machine in Azure.
2. Allow all traffic in the firewall settings of the virtual machine.
3. Create a Log Analytics Workspace to centralize and analyze log data.
4. Enable gathering VM logs in Azure Security Center to detect potential security threats.
5. Connect Log Analytics to the virtual machine to extract and store log data.
6. Set up Azure Sentinel to monitor the log data and send automated alerts when potential security threats are detected.
7. Log into the virtual machine with Remote Desktop and initiate a failed login attempt to generate log data.
8. Observe Event Viewer Logs in the virtual machine to confirm the log data has been generated.
9. Turn off the Windows Firewall on the virtual machine to allow the PowerShell script to run.
10. Download the PowerShell script to extract geo data from attackers.
11. Get a Geolocation.io API Key to use with the PowerShell script.
12. Run the PowerShell script to extract geo data from attackers and store it in the Log Analytics Workspace.
13. Create a custom log in Log Analytics Workspace to bring in the extracted geo data.
14. Create custom fields and extract fields from raw custom log data to make it easily searchable and understandable.
15. Test the custom fields and extracts to ensure they are working correctly.
16. Set up a map in Azure Sentinel with Latitude and Longitude or country to visualize the geo data and failed login attempts.
17. Fix any map plot sizes to ensure they are accurate and easy to read.

For detailed instructions on how to deploy and configure the project, please refer to the [project documentation](link-to-documentation).

## Contributions

We welcome contributions from the community to help improve the SIEM Azure Sentinel MAP project. To contribute, please submit bug reports, feature requests, and pull requests on our [GitHub repository](link-to-github-repo).

## Conclusion

The SIEM Azure Sentinel MAP project is a comprehensive security solution that enables organizations to monitor and visualize failed login attempts in real-time. By integrating with various security tools and technologies, this project provides a powerful solution for detecting and responding to potential security threats.
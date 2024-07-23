Finding and Using Windows Event Logs
Windows Event Logs are crucial for monitoring and maintaining the security and health of a Windows-based system. They record significant system, security, and application events, providing a detailed log of activities and incidents.

What Are Windows Event Logs?
Windows Event Logs are a comprehensive record of system activities and events, categorized into several types:

Application Logs: Events logged by applications or programs.
System Logs: Events logged by the operating system.
Security Logs: Security-related events such as login attempts and resource access.
Setup Logs: Events related to the installation of Windows.
Forwarded Events: Events forwarded from other machines.

Accessing Event Logs
Open Event Viewer:
Press Win + R to open the Run dialog.
Type eventvwr and press Enter.

Navigate the Event Viewer:
Event Viewer is organized into different categories:
Windows Logs: Includes Application, Security, System, Setup, and Forwarded Events logs.
Applications and Services Logs: Contains logs from specific applications and services.

View and Filter Logs:
Select a log (e.g., System) to view its events.
Click on an event to see its details.
Use the filter option to narrow down events based on criteria such as date, event level, or event ID.

Analyzing Event Logs
Analyzing event logs is critical for identifying and responding to security incidents. Here are common scenarios:
Detecting Unauthorized Access:
Check Security logs for login attempts (e.g., Event ID 4625 for failed attempts).
Look for successful logins at unusual times or from unexpected IP addresses (Event ID 4624).

Monitoring System Health:
Review System logs for hardware or system errors.
Investigate frequent Error or Critical events.

Troubleshooting Application Issues:
Use Application logs to identify and resolve application crashes or errors.

Correlating Events:
Combine logs from different sources (e.g., Security and System) to get a comprehensive view of an incident.

    #Windows Firewall Configuration Task
Overview
This project documents the steps taken to configure, test, and analyze Windows Firewall rules as part of a security and network traffic control exercise. The task includes exporting existing rules, creating a custom block rule, verifying its effectiveness, and restoring the firewall to its original state.

    Contents of This Repository
→ Inbound Rules CSV – Exported inbound firewall rules for reference
→ Outbound Rules CSV – Exported outbound firewall rules for reference
→ Firewall Configuration Task Report – Detailed documentation of all steps performed
→ Testing Output – PowerShell output used to validate the block rule

    Key Tasks Performed

→ Accessed Windows Firewall advanced settings through the Windows Security interface.
→ Exported and reviewed all inbound and outbound firewall rules.
→ Created a custom inbound rule to block TCP traffic on Port 23 (Telnet).
→ Tested the new rule using PowerShell to confirm the port was blocked.
→ Removed the test rule to restore the original firewall configuration.
→ Documented the full process, including GUI steps and PowerShell commands.
→ Summarized how firewall rules inspect packets and enforce security policies.

    Purpose of the Task

→ To understand how Windows Firewall manages and filters network traffic.
→ To gain hands-on experience with creating, testing, and removing firewall rules.
→ To observe how packet attributes (port, protocol, profile) influence the firewall's decisions.
→ To document a complete workflow for firewall configuration and validation.

    How to Use This Repository

→ Review the CSV files to understand the system's firewall state before configuration.
→ Read the main report for a step-by-step explanation of the task.
→ Use the PowerShell output to see how the block rule behaved during testing.
→ Apply the same steps on any Windows environment to replicate the learning process.

    Tools and Commands Used

→ Windows Defender Firewall with Advanced Security (GUI)
→ PowerShell
Command used for testing:
Test-NetConnection -ComputerName localhost -Port 23

    Final Notes:

This task demonstrates how firewall rules can effectively control network access, enhance security, and block unwanted protocols. The documentation and exported data provided here can serve as a reference for future firewall configuration or troubleshooting exercises.

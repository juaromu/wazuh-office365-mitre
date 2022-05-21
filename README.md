# OFFICE 365 - MITRE ENRICHED EVENTS USING WAZUH DETECTION RULES

Microsoft provides a single pane of glass for all Office 365 tasks through the Office 365 management APIs. This includes service communications, security, compliance, reporting and auditing related events.
Wazuh can help you get insight into this vast array of information by ingesting it and alerting based on custom rules.

[Wazuh Blog Entry](https://wazuh.com/blog/monitor-office-365-with-wazuh)

The detection rules file included here maps Office365 Workloads, Operations and LogonErrors (Operation = UserLoginFailed) to [Mitre ATT&CK TTPs](https://attack.mitre.org/matrices/enterprise/cloud/office365/)

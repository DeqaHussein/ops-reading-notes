
1. Indicators of Compromise (IoCs) Detected by GuardDuty:
   - **Behavioral Anomalies:** GuardDuty looks for anomalous behavior within your AWS environment, such as unusual API calls, unexpected resource launches, or unusual ingress and egress traffic patterns.
   - **Known Malicious IPs:** GuardDuty maintains a threat intelligence feed and cross-references network traffic against a list of known malicious IP addresses.
   - **IAM Policy Anomalies:** GuardDuty examines AWS Identity and Access Management (IAM) policies and alerts on any deviations or potential misconfigurations that could indicate a security issue.
   - **Unauthorized Access:** The service monitors authentication and authorization logs for signs of unauthorized access attempts or unusual patterns that might indicate compromised credentials.

2. Data Sources Utilized by GuardDuty:
   - **VPC Flow Logs:** GuardDuty analyzes VPC (Virtual Private Cloud) Flow Logs to identify potential malicious traffic and patterns.
   - **CloudTrail Logs:** GuardDuty leverages AWS CloudTrail logs to detect unusual or suspicious activity related to API calls and changes to AWS resources.
   - **DNS Logs:** GuardDuty examines DNS query logs for signs of malicious activity, such as communication with known malicious domains.
   - **CloudWatch Events:** The service uses CloudWatch Events to detect and analyze events related to AWS resources.
   - **Threat Intelligence Feeds:** GuardDuty incorporates threat intelligence feeds to identify known malicious IP addresses and other indicators of compromise.

3. Access Behavior and Detection of Malicious Activity:
   - GuardDuty employs machine learning algorithms and behavioral analysis to establish a baseline of normal behavior within your AWS environment.
   - Deviations from this baseline, such as unusual access patterns or unexpected resource launches, can trigger alerts for potential malicious activity.
   - For example, if there's a sudden surge in API calls, unauthorized access attempts, or if an unusual combination of IAM permissions is detected, GuardDuty can flag these as potential security issues.
   - By continuously monitoring and analyzing logs and events from different data sources, GuardDuty aims to identify and alert on activities indicative of security threats or compromises.

Resource-Chatgpt

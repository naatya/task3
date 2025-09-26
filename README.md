Localhost Vulnerability Assessment
This document summarizes the steps and findings of a basic Vulnerability Assessment (VA) performed on a local system, using the OpenVAS (Greenbone Security Assistant) scanning tool.
Methodology Overview:
The assessment followed the standard 8-step process to identify, analyze, and document security weaknesses on the host 127.0.0.1 (localhost).
Installation and Target Setup: OpenVAS was installed, and the scan target was configured as the local machine (127.0.0.1).
Scan Execution: A full vulnerability scan was initiated to cover all services and ports on the target.
Analysis and Review: Upon completion, the scan report was reviewed, and vulnerabilities were categorized by Severity Level (Critical, High, Medium).
Remediation Research: The most critical findings (e.g., Weak Cipher Suites and Outdated Software) were researched to determine simple, practical fixes, such as configuration changes or software patching.
Documentation: The top vulnerabilities were formally documented in a structured table, including the severity, a brief description, and the recommended mitigation steps.
Evidence Collection: Screenshots of the scan setup, results summary, and detailed vulnerability findings were captured as proof of work.
Conclusion:
The assessment successfully identified security configuration weaknesses on the localhost. The documented findings and mitigation steps provide a clear path for securing the system by prioritizing necessary software updates and configuration adjustments.

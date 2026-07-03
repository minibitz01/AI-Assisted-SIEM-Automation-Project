# AI-Assisted-SIEM-Automation-Project
Built an AI-assisted SIEM lab that simulates a Security Operations Center (SOC) using AWS, Windows Server 2025, Elastic SIEM, endpoint monitoring, and Tines automation. The project ingests endpoint logs, generates alerts, and delivers AI-generated summaries to support incident triage.

The project collects endpoint logs, generates security alerts through detection rules, and uses workflow automation to deliver AI-generated alert summaries for analyst review and incident triage.

# Technologies Used
AWS EC2
Windows Server 2025
Elastic SIEM
Elastic Agent
Tines
Webhooks
AI-generated alert summaries
Architecture


Windows Server 2025 (AWS EC2)
          ↓
     Elastic Agent
          ↓
      Elastic SIEM
          ↓
   Detection Rules
          ↓
      SIEM Alerts
          ↓
         Tines
          ↓
    AI Alert Summary
          ↓
   Email Notification
          ↓
   Security Analyst
   
# What I Learned
SIEM Engineering
How to deploy and configure an Elastic SIEM environment
How SIEM platforms ingest and normalize logs
How security events are converted into alerts
How SIEM correlation rules are created and tuned
Cloud Infrastructure
How to provision a Windows Server 2025 EC2 instance
How to configure networking and firewall settings
How to manage credentials and remote access
Endpoint Monitoring
How to install and configure Elastic Agents
How endpoint telemetry is collected and sent to Elastic
How to monitor login activity, processes, applications, and security events
Detection Engineering
How to create custom detection rules
How to use Windows Event ID 4625 (failed login events)
How to investigate and reduce false positives
Security Automation
How to build workflows in Tines
How to integrate Tines with Elastic SIEM using webhooks
How to automate alert handling and notifications
AI-Assisted Incident Triage
How to send SIEM alerts into an automated workflow
How to generate AI-based alert summaries
How AI can assist analysts by reducing manual triage effort
Skills Demonstrated
SIEM Administration
Detection Engineering
Endpoint Security Monitoring
Security Automation
Workflow Design
Cloud Security Fundamentals
Incident Triage
AI-Augmented Security Operations

# Project Outcome

Successfully built an end-to-end SOC simulation that collects endpoint telemetry, generates detections, and automates alert summarization and analyst notification using Elastic SIEM and Tines.

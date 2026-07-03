# AI-Assisted SIEM Automation Project

## Overview
Built an AI-assisted Security Information and Event Management (SIEM) lab that simulates a Security Operations Center (SOC) using AWS, Windows Server 2025, Elastic SIEM, endpoint monitoring, and Tines workflow automation. The project collects endpoint telemetry, generates security alerts through detection rules, and uses workflow automation to deliver AI-generated alert summaries for analyst review and incident triage.

---

## Architecture

```text
AWS EC2 (Windows Server 2025)
            ↓
      Elastic Agent
            ↓
       Elastic SIEM
            ↓
     Detection Rules
            ↓
       SIEM Alerts
            ↓
      Tines Workflow
            ↓
    AI Alert Summary
            ↓
    Email Notification
            ↓
      Security Analyst
```

---

## Technologies Used
- AWS EC2
- Windows Server 2025
- Elastic SIEM
- Elastic Agent
- Tines
- Webhooks
- AI-generated alert summaries

---

## Project Workflow

1. Provisioned an AWS EC2 instance running Windows Server 2025.
2. Installed and configured an Elastic Agent on the endpoint.
3. Connected endpoint telemetry and security logs to Elastic SIEM.
4. Collected and monitored endpoint activity, including:
   - Login events
   - Processes
   - Applications
   - Security events
   - Network activity
5. Created and tuned detection rules within Elastic SIEM.
6. Generated security alerts based on suspicious activity.
7. Sent alerts to Tines using webhooks.
8. Automated alert handling and AI-generated summaries.
9. Delivered email notifications containing alert context and recommended actions for analyst review and incident triage.

---

## Detection Engineering

### Example Detection Rule
**Windows Event ID:** 4625

**Purpose:** Detect failed login attempts and generate alerts for analyst investigation.

**Alert Flow:**

```text
Failed Login Event
        ↓
Generate Alert
        ↓
Send to Tines
        ↓
Generate AI Summary
        ↓
Email Analyst
        ↓
Investigate or Escalate
```

---

## Skills Demonstrated
- SIEM Administration
- Detection Engineering
- Endpoint Security Monitoring
- Security Automation
- Workflow Design
- Cloud Infrastructure
- Incident Triage
- Webhook Integration
- AI-Augmented Security Operations

---

## What I Learned

### SIEM Engineering
- How to deploy and configure an Elastic SIEM environment
- How SIEM platforms ingest and normalize logs
- How security events are converted into alerts
- How SIEM correlation and detection rules are created and tuned

### Cloud Infrastructure
- How to provision and configure a Windows Server 2025 EC2 instance
- How to configure networking, firewall settings, and remote access
- How to manage credentials and endpoint connectivity

### Endpoint Monitoring
- How to install and configure Elastic Agents
- How endpoint telemetry is collected and sent to Elastic
- How to monitor login activity, processes, applications, and security events

### Security Automation
- How to build workflows in Tines
- How to integrate Tines and Elastic SIEM using webhooks
- How to automate alert handling and notifications

### AI-Assisted Incident Triage
- How to send SIEM alerts into an automated workflow
- How to generate AI-based alert summaries
- How AI can assist analysts by reducing manual triage effort

---

## Project Outcome
Successfully built an end-to-end SOC simulation that collects endpoint telemetry, generates detections, and automates alert summarization and analyst notification using Elastic SIEM and Tines.

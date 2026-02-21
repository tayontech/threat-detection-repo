# 🛡️ Cloud and SaaS Threat Detections Repository

This repository contains a curated collection of threat detection queries designed for Cloud and SaaS application environments. These detections are organized to provide security teams with the ability to identify suspicious and malicious activity.

---

## 📂 Repository Structure

Detections are organized by the platform they monitor.

| Directory | Description | Examples of Events Monitored |
| --- | --- | --- |
| `aws/` | Detections targeting **AWS** services. | IAM changes, resource creation, privilege escalation. |
| `okta/` | Detections for **Okta** authentication events. | Suspicious sign-ons, MFA manipulation, policy changes. |
| `github/` | Detections for **GitHub Enterprise** and repository audits. | Repository visibility changes, secret scanning alerts, PAT abuse. |
| `azure/` | Detections for **Azure/Microsoft 365** events. | App consent, unusual mailbox access, brute-force attempts. |
| `gcp/` | Detections for **Google Cloud Platform** events. | Storage bucket changes, service account key compromise. |
| `gworkspace/` | Detections for **Google Workspace** activities. | External file sharing, unusual Drive access, Admin audit logs. |

---

**⚠️ IMPORTANT:**
Security logs are rarely standardized. You should review and adjust the **field names** in these queries to match your specific SIEM/log management schema (e.g., Splunk, Sentinel, Panther, or ELK).

---

## 🚀 Usage

### 1. Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/tayontech/threat-detections-repo.git
cd threat-detections-repo

```

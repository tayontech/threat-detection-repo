# 🛡️ Cloud and SaaS Threat Detections Repository

This repository contains a curated collection of **threat detection queries** designed for Cloud and SaaS application environments. These detections are organized to provide security teams with out-of-the-box logic to identify suspicious and malicious activity.

---

## 📂 Repository Structure

Detections are organized by the platform they monitor. 

| Directory | Description | Examples of Events Monitored |
| :--- | :--- | :--- |
| `aws/` | Detections targeting **AWS** services (CloudTrail, GuardDuty, VPC Flow Logs, etc.). | IAM changes, resource creation/deletion, privilege escalation. |
| `okta/` | Detections for **Okta** authentication and administrative events. | Suspicious sign-ons, MFA manipulation, policy changes. |
| `azure/` | (e.g.) Detections for **Azure/Microsoft 365** events (Azure AD, Exchange Online, etc.). | App consent, unusual mailbox access, failed brute-force attempts. |
| `gcp/` | (e.g.) Detections for **Google Cloud Platform** events. | Storage bucket changes, service account key compromise. |
| `gworkspace/` | Detections for **Google Workspace (formerly G Suite)** activities (Admin, Drive, Gmail Logs). | External sharing of sensitive documents, unusual file access, Admin audit log changes. |

---

**⚠️ IMPORTANT:**

You should review and adjust the field names in the detection queries to match your specific environment's data schema, as I understand that field naming and data requirements can differ significantly between security platforms and organizations.


## 🚀 Usage

### 1. Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone [https://github.com/tayontech/threat-detections-repo.git](https://github.com/tayontech/threat-detections-repo.git)

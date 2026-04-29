# Microsoft Sentinel Deployment

## Template

Used the **Sentinel-All-In-One** template:
> Azure-Sentinel/Tools/Sentinel-All-In-One at master · Azure/Azure-Sentinel · GitHub

Pressed **Deploy the template for automation**.

---

## Basics

| Parameter | Value |
|---|---|
| Subscription | az-intr-isc-dev01 |
| Location | West Europe |
| Resource Group Name | SEC-Monitoring |
| Workspace Name | SEC-Monitoring |
| Daily Ingestion Limit (GB) | 10 |
| Retention (days) | 90 |
| Pricing Tier | Pay-as-you-go |

---

## Settings

| Setting | Value |
|---|---|
| Enable User Entity Behavior Analytics (UEBA) | No |
| Enable Sentinel Health Diagnostics | Yes |

---

## Content Hub Solutions

| Category | Selected |
|---|---|
| Microsoft Content Hub Solutions | 12 selected (incl. Azure Active Directory, Azure Activity, Dynamics 365 CE) |
| Essentials Content Hub Solutions | 9 selected |
| Training and Tutorials Content Hub Solutions | 2 selected |

---

## Data Connectors

| Setting | Value |
|---|---|
| Data connectors to onboard | 11 selected |
| Azure Active Directory log types to enable | 2 selected |

---

## Analytics Rules

| Setting | Value |
|---|---|
| Enable Scheduled Alert Rules | Yes |
| Severity levels enabled | High, Medium, Low, Informational (all 4) |

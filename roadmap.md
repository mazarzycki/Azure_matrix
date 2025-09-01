# ⚡ Azure 80/20 Study Roadmap

This roadmap is based on the **80/20 Azure Matrix Service Map**. The idea is simple:  
20% of services and concepts deliver 80% of the real-world value.  

Here’s a 6-week plan to master that 20%, document your learning, and build a portfolio that proves your skills.

---

## ⏳ Duration
- **6 weeks total** (about 1–2 hours per day, Mon–Fri → ~60–70 focused hours).
- Each week = one pillar focus, with practice + documentation.
- Week 6 = integration & portfolio (labs, GitHub, blog posts).

---

## 🟦 Week 1 — Identity & Access (The Foundation)
🎯 **Goal:** Understand how access is controlled and secured in Azure.

### Topics
- Entra ID basics: tenants, users, groups, RBAC vs ABAC.
- Conditional Access + MFA.
- Privileged Identity Management (PIM).
- Managed identities & service principals.

### Labs
- Create a new tenant, add test users/groups.
- Apply RBAC at subscription & resource group level.
- Configure MFA & a Conditional Access policy.
- Use a managed identity to access Key Vault.

### Blog Documentation Ideas
- *“Why Identity is the Core of Azure Security”*
- *“Hands-on with Conditional Access: A Beginner’s Guide”*
- *“Managed Identities vs Service Principals Explained with Labs”*

---

## 🟩 Week 2 — Logging & Monitoring (See the Code)
🎯 **Goal:** Learn to collect and query logs, detect threats, and monitor systems.

### Topics
- Azure Monitor basics (metrics vs logs, alerts).
- Log Analytics workspace (data sources, schemas).
- KQL fundamentals (filtering, aggregation, joins).
- Microsoft Sentinel: data connectors, incidents, playbooks.
- Defender for Cloud: Secure Score & recommendations.
- Azure Policy basics.
- Key Vault integration with identities.

### Labs
- Deploy Log Analytics workspace, connect a VM.
- Write KQL queries (top processes, failed logins).
- Connect Sentinel to the workspace.
- Create a Sentinel alert + Logic App playbook.
- Assign a built-in Azure Policy and check compliance.

### Blog Documentation Ideas
- *“Learning KQL: The Language Behind Microsoft Sentinel”*
- *“Step-by-Step Guide: Onboarding Logs into Azure Monitor”*
- *“How I Automated Sentinel Alerts with Logic Apps”*

---

## 🟨 Week 3 — Infrastructure Core (The Dojo Floor)
🎯 **Goal:** Be comfortable deploying, securing, and troubleshooting Azure infra.

### Topics
- Virtual Machines (size, disks, availability zones).
- App Services (plans, scaling, deployment slots).
- Storage Accounts (Blob, Files, SAS tokens, encryption).
- Networking (VNets, NSGs, private endpoints).
- Azure DNS (zones, records).

### Labs
- Deploy a Linux VM + install Nginx.
- Connect VM to Log Analytics.
- Deploy a sample web app to App Service with a custom domain.
- Secure a storage account with SAS token.
- Create a VNet with subnets & NSG rules.
- Configure DNS zone with A + CNAME record.

### Blog Documentation Ideas
- *“Deploying My First Azure VM and Connecting Logs to Sentinel”*
- *“How to Secure Azure Storage with SAS Tokens”*
- *“Azure Networking Basics: VNets, Subnets, and NSGs in Practice”*

---

## 🟥 Week 4 — Automation & Deployment (Your Upload Port)
🎯 **Goal:** Automate everything you’ve learned so far.

### Topics
- Azure CLI + PowerShell (resource CRUD, queries).
- Bicep basics (parameters, modules, deployments).
- GitHub Actions / Azure DevOps YAML pipelines.
- Logic Apps automation.
- Automation Accounts + Runbooks.

### Labs
- Deploy a VM using CLI + Bicep.
- Write a YAML pipeline to deploy an App Service.
- Create a Logic App to auto-close Sentinel low-severity alerts.
- Schedule a runbook in Automation Account.

### Blog Documentation Ideas
- *“Infrastructure as Code with Azure Bicep: My First Template”*
- *“Deploying Apps Automatically with GitHub Actions + Azure”*
- *“Everyday Azure Automation: Logic Apps and Runbooks in Action”*

---

## 🟪 Week 5 — Integration & Hands-On Challenges
🎯 **Goal:** Mix all pillars into end-to-end mini-projects.

### Topics
- Combine identity, monitoring, infra, and automation.
- Practice incident response (alert → playbook).
- Harden environment with Defender for Cloud + Policy.

### Labs
- End-to-end lab: deploy VM + app + monitoring + Sentinel rule + automation.
- Simulate incident response (failed logins → alert → playbook).
- Document setup in GitHub repo.

### Blog Documentation Ideas
- *“Building an End-to-End Azure Security Lab”*
- *“Incident Response in Azure Sentinel: A Realistic Demo”*
- *“Azure Policy + Defender for Cloud: Hardening My Lab”*

---

## 🟫 Week 6 — Portfolio & Mastery Loop
🎯 **Goal:** Solidify knowledge + create public proof.

### Topics
- Review weak spots (labs, repeat KQL, CLI, Bicep).
- Refactor notes into a clear GitHub repo.
- Write blog posts from earlier weeks.
- Create a LinkedIn summary of your journey.

### Labs
- Consolidate Bicep templates and YAML pipelines.
- Re-run Sentinel rules and automation.
- Publish GitHub repo with documentation.

### Blog Documentation Ideas
- *“My 6-Week Azure 80/20 Journey”*
- *“Top 5 Lessons I Learned While Building My Azure Lab”*
- *“How I Documented My Azure Learning to Build a Portfolio”*

---

# 🧩 Productivity Principles
- **Daily block:** 1 hour lab + 15 min quick notes.
- **Weekly review:** Re-run last week’s labs, refine notes.
- **Spaced repetition:** Revisit KQL, CLI, and Bicep every week.
- **Portfolio-first mindset:** Every lab → commit notes/code to GitHub.

# ⚡ The 80/20 Azure Matrix Service Map

## In Azure, not all knowledge is equal. Mastering just 20% of the services will give you 80% of the impact — and put you ahead of most engineers. This README is your shortcut to that 20%.

## 🟦 1. Identity & Access
1. **Entra ID (Azure AD)**
   - Tenants, directories, subscriptions
   - Users, groups, roles (RBAC vs ABAC)
   - Conditional Access policies
   - MFA, Passwordless
   - Identity Protection (risk-based sign-in)
   - Privileged Identity Management (PIM)
   - External identities (B2B/B2C)

2. **Role-Based Access Control (RBAC)**
   - Built-in vs custom roles
   - Resource scope: subscription → resource group → resource
   - Least privilege principle

3. **Managed Identities & Service Principals**
   - System-assigned vs user-assigned managed identities
   - Key Vault access with managed identities
   - App registration basics

---

## 🟩 2. Logging, Monitoring & Security
4. **Azure Monitor**
   - Metrics vs logs
   - Alerts & action groups
   - Diagnostic settings

5. **Log Analytics Workspace**
   - Data ingestion sources
   - Tables & schemas
   - Cost control (retention, ingestion caps)

6. **Kusto Query Language (KQL)**
   - Filtering, projections, joins
   - Aggregations & summarization
   - Time-based queries
   - Custom detection queries

7. **Microsoft Sentinel**
   - Data connectors (Azure, O365, Syslog, custom)
   - Analytics rules & scheduled queries
   - Hunting queries
   - Incidents & investigation graph
   - Automation (Logic Apps / Playbooks)

8. **Microsoft Defender for Cloud (formerly Security Center)**
   - Secure Score
   - Recommendations & compliance (CIS, NIST, ISO)
   - Just-in-time VM access
   - Integration with Defender for Endpoint

9. **Azure Policy**
   - Built-in vs custom policies
   - Assignments at scope (MG, subscription, RG)
   - Initiative (policy set) vs single policy
   - Compliance reporting

10. **Key Vault**
   - Secrets, keys, certificates
   - Access policies vs RBAC
   - Integration with apps (managed identity access)

---

## 🟨 3. Infrastructure Core
11. **Virtual Machines (IaaS)**
   - VM sizing, regions, availability zones
   - OS images & custom images
   - Disk types (Standard vs Premium SSD)
   - Extensions (e.g. log collection)

12. **App Services (PaaS)**
   - App Service Plans
   - Deployment slots
   - Scaling (manual vs autoscale)
   - Authentication / Authorization

13. **Storage Accounts**
   - Blob, File, Table, Queue
   - Storage tiers (hot, cool, archive)
   - Shared Access Signatures (SAS)
   - Encryption (at rest, in transit, CMK vs Microsoft-managed keys)

14. **Azure Networking**
   - VNets, subnets, address spaces
   - Network Security Groups (NSG) vs Application Security Groups (ASG)
   - Private endpoints & service endpoints
   - VPN Gateway vs ExpressRoute
   - Azure Firewall & Azure Bastion (basic exposure)

15. **Azure DNS**
   - Zones & records (A, CNAME, TXT, MX)
   - Private DNS integration with VNets
   - Split-horizon (internal vs external DNS)

---

## 🟥 4. Automation & Deployment
16. **Azure CLI & PowerShell**
   - az login, context, switching subs
   - Resource group CRUD operations
   - VM & storage provisioning
   - Querying resources with JMESPath

17. **Bicep / ARM Templates**
   - Resource declaration syntax
   - Parameters, variables, outputs
   - Modules for reusable infra
   - Deployment scope (subscription vs RG vs MG)

18. **Azure DevOps / GitHub Actions**
   - YAML pipelines basics (stages, jobs, steps)
   - Service connections / service principals
   - CI/CD for App Services or Containers
   - Secrets management in pipelines

19. **Logic Apps**
   - Triggers & actions
   - Connectors (Office 365, Sentinel, Teams)
   - Monitoring automation (e.g. auto-close low alerts)

20. **Automation Accounts**
   - Runbooks (PowerShell, Python)
   - Scheduling jobs
   - Hybrid worker for on-prem automation

---

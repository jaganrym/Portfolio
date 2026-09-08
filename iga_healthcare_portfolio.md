# Portfolio Case Study: Healthcare & Academic IGA Transformation
**Role:** Identity Governance & Administration (IGA) Architect / Lead Consultant  
**Client:** Major U.S. Healthcare Organization & Affiliated University  
**Tech Stack:** Saviynt Enterprise Identity Cloud (EIC), Microsoft Identity Manager (MIM), Oracle DB, ITSM  

---

## 🎯 Executive Summary
Led the strategic discovery, data remediation, and architectural roadmap to unify the fragmented identity landscapes of a major **U.S. healthcare network** and its affiliated **academic university**. The overarching corporate vision was to consolidate these historically siloed entities into a single, integrated healthcare organization. 

By designing a migration path from dual legacy platforms to a unified, cloud-native **Saviynt Enterprise Identity Cloud (EIC)** platform, this initiative eliminates massive management overhead, redundant software costs, and workforce inefficiencies while establishing a robust, zero-trust security posture.

---

## 🛑 The Challenge: Legacy Complexity & Data Decay

### 1. Operational Silos & High TCO
The university and hospital systems operated completely separate, independent IGA platforms. This division resulted in duplicate administrative teams, redundant software licensing fees, and highly fragmented governance processes that severely inflated the Total Cost of Ownership (TCO).

### 2. Broken Automation & Manual Ticket Overload
User and application provisioning relied entirely on manual **ITSM/MIM ticket workflows**. Automated provisioning was non-existent due to systemic data gaps, creating operational bottlenecks and lengthy delays for access requests.

### 3. Compromised Identity Warehouse (Oracle DB)
The legacy **Microsoft Identity Manager (MIM)** platform was backed by an unmaintained **Oracle Identity Database**. This repository suffered from severe data corruption and missing fields. Vital identity attributes—such as **Manager, Department, and Location**—were systematically unpopulated or outdated, making programmatic access control impossible.

### 4. Severe Governance Lapses (Stale & Orphaned Accounts)
Due to the absence of automated **Joiner-Mover-Leaver (JML)** processes and consistent manual offboarding human errors, the environment suffered from severe security exposure. A significant volume of **orphaned and stale accounts** proliferated across both the university and hospital systems.

---

## 🗺️ The Strategic Roadmap: Saviynt Cloud Vision
The core objective of the transformation roadmap was to migrate the combined enterprise away from legacy infrastructure and onto a modern **Saviynt Cloud IGA** platform to achieve:

* **Unified App Onboarding:** Consolidate and onboard 100% of applications from both the university and hospital environments into a single tenant.
* **End-to-End Automation:** Implement automated provisioning, streamlined identity lifecycle orchestration, and **Day-Zero access** capability.
* **Advanced Compliance & Governance:** Deploy automated Access Certifications, Role-Based Access Control (RBAC), and strict Segregation of Duties (SoD) enforcement.
* **Privileged Access Integration:** Align Privileged Access Management (PAM) policies to secure high-risk infrastructure and administrator credentials across the merged entity.

---

## 🛠️ Phase 1 Execution: Deep-Dive Discovery & Remediation
To establish a trustworthy baseline for the Saviynt cloud migration, I executed an exhaustive technical discovery and data-cleansing phase:

### 🔍 Identity Correlation & Audit
Conducted a deep-dive technical assessment of the legacy Oracle database to map, correlate, and reconcile disjointed identities across both the university and hospital ecosystems.

### 🧪 Attribute Sanity Refinement
Evaluated data completeness across millions of fields, identifying and mapping missing core attributes (Manager, Department, Location) required to successfully feed the upcoming Saviynt automation engine.

### 🧼 Stale & Orphaned Account Remediation
Isolated and quantified the vast footprint of abandoned accounts caused by legacy lifecycle lapses. Formulated a rigorous cleanup and de-provisioning strategy to secure the perimeter *before* onboarding applications to the cloud.

---

## 💡 Key Takeaways & Impact
* **Strategic Alignment:** Successfully mapped out the identity architecture required to merge two massive, distinct enterprise cultures (Healthcare & Higher Education) into one cohesive security boundary.
* **Risk Mitigation:** Prevented "garbage in, garbage out" cloud migration issues by fixing underlying data quality issues in the Oracle warehouse first.
* **Security Hardening:** Directly reduced the attack surface by building the framework to purge thousands of unmanaged, stale accounts across both organizations.
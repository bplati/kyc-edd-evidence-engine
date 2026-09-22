# 🛡️ KYC/EDD Evidence Engine v8 (MVP Overview)

**Automated OSINT & Compliance Screening Engine**  
A Lightweight Cloudflare Workers Serverless Architecture for Sanctions, PEP, and Adverse Media Risk Identification.

---

## 🚀 Interactive Live Demo & Access

The application is fully deployed, verified, and end-to-end tested as a production-grade Proof of Concept (PoC) on **Cloudflare Workers Edge Infrastructure**.

* **Live MVP Environment:** [https://redacted.workers.dev/](https://redacted.workers.dev/) *(укажи свою реальную ссылку)*
* **Status:** 🟢 **Active & Fully Operational** (Latest build verified and tested)
* **Access Control:** 🔑 **Evaluation keys / tokens must be requested directly from the owner.**

> **Note for Evaluators & Recruiters:**  
> To protect external provider API quotas and maintain edge security, public token access is disabled by default. **Temporary evaluation tokens are issued upon request.** Please contact me via LinkedIn or Email to receive an active access token to test live OSINT screenings and deterministic fixtures (**Demo A / Demo B**).

---

## 📄 Project Documentation & Architecture Overview

For intellectual property and security reasons, the underlying codebase is maintained in a private repository. However, the complete product architecture, system specs, and governance framework are fully documented in the attached evaluation document:

👉 **[Download / View KYC/EDD Evidence Engine Specification (PDF)](./KYC_EDD_Evidence_Engine_v8_Overview.pdf)**

---

## 🛠️ Core Capabilities & Tech Stack

* **Edge Architecture:** Cloudflare Workers (JavaScript ES Modules) with Cloudflare D1 (SQLite) and Workers Rate-Limiting bindings.
* **API Integrations:** 
  * **OpenSanctions API:** Sanctions, watchlists, and PEP/RCA screening with identity conflict resolution.
  * **GDELT DOC API:** Bounded adverse-media and public-news discovery.
* **Auditability & Integrity:** Automatic SHA-256 integrity hashing for deterministic 10-section screening report bundles.
* **Data Privacy & Security:** Volatile browser-token authentication, 7-day automated D1 retention purge, and zero public exposure of historical records.

---

## 👤 Author & Access Requests

**Bogdan Plationov**  
*AML & Compliance Professional | Financial Crime Risk & Process Automation*  
* **LinkedIn:** [linkedin.com/in/plationov](https://linkedin.com/in/plationov)
* **Email:** b.plationov@live.com

# Awesome-CPQ

# Top CPQ Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Configure-Price-Quote, Product Configuration, Guided Selling, Pricing Rules & Quote Generation*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CPQ (Configure, Price, Quote)**. These tools enable sales teams, manufacturers, and solution providers to configure complex products, apply dynamic pricing and discount rules, generate accurate proposals/quotes, and streamline the path from opportunity to order while reducing errors and sales cycle time.

**Examples** include Salesforce CPQ, Conga CPQ, Oracle CPQ, DealHub, Logik.io, PROS Smart CPQ, Experlogix, Configure One, Epicor CPQ, and Tacton (the category leaders and widely adopted solutions).

**Open-source emphasis**: This section is heavily expanded with every major active project and framework for self-hosting, product configuration engines, quote generation, pricing infrastructure, and integration with open ERPs/CRMs — ideal for manufacturers, MSPs, custom solution providers, and companies seeking full control over configuration logic and pricing rules without proprietary lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Salesforce CPQ](https://www.salesforce.com/products/cpq/overview/)** (part of Revenue Cloud)  
  Leading native CPQ solution tightly integrated with Salesforce CRM for product configuration, guided selling, pricing rules, approvals, and quote-to-cash automation.
- **[Conga CPQ](https://conga.com/)**  
  Robust CPQ platform focused on complex product configuration, document generation, and revenue lifecycle management with strong Salesforce and Microsoft integrations.
- **[Oracle CPQ](https://www.oracle.com/cx/sales/cpq/)**  
  Enterprise-grade Configure-Price-Quote solution within Oracle CX, supporting complex configurations, multi-channel selling, and deep ERP integration.
- **[DealHub](https://dealhub.io/)**  
  Modern CPQ and revenue platform emphasizing speed, guided selling, interactive proposals, and deal desk collaboration.
- **[Logik.io](https://www.logik.io/)**  
  Cloud-native CPQ designed for complex product configuration with a visual rules engine and strong focus on manufacturability and accuracy.
- **[PROS Smart CPQ](https://pros.com/)**  
  AI-powered CPQ and pricing optimization platform that combines configuration, dynamic pricing, and deal guidance.
- **[Experlogix](https://www.experlogix.com/)**  
  Flexible CPQ solution supporting complex configurable products, visual configuration, and integration with major CRM/ERP systems.
- **[Configure One](https://www.configureone.com/)**  
  Specialist CPQ for manufacturers of complex, engineered-to-order products with strong CAD and BOM generation capabilities.
- **[Epicor CPQ](https://www.epicor.com/)**  
  CPQ tailored for complex configurable products, offering 3D/AR visualization, CAD drawings, automatic BOMs, and multi-channel quoting.
- **[Tacton](https://www.tacton.com/)**  
  Constraint-based CPQ platform known for handling highly complex product configuration and manufacturing integration.
- **[Cincom CPQ](https://www.cincom.com/)**  
  Established solution for complex selling environments with configuration, pricing, and proposal automation.
- **[Hive CPQ](https://www.hivecpq.com/)**  
  User-friendly CPQ focused on manufacturers, with 3D configuration, real-time pricing, and error-free quote generation.

## Open-Source GitHub Projects
- **[openCPQ](https://github.com/webXcerpt/openCPQ)**  
  Mature open-source (MIT) JavaScript library for building in-browser product configurators and CPQ functionality. Provides reusable building blocks so developers can focus on product models rather than low-level configurator mechanics.
- **[SwiftCPQ](https://github.com/christopher-talke/SwiftCPQ)**  
  Open-source (AGPL-3.0) vendor-agnostic proposal and quote generation tool designed as an accessible alternative to proprietary MSP/IT quoting platforms (ConnectWise CPQ, Quoter, etc.). Features an intuitive editor, product catalog, flexible pricing, and PDF templates.
- **[ERPNext](https://github.com/frappe/erpnext)**  
  Fully open-source (GPL) ERP with strong product configuration, pricing rules, quotation, sales order, and BOM capabilities. Ideal foundation for building custom CPQ workflows, especially in manufacturing and distribution.
- **[Odoo Community](https://github.com/odoo/odoo)**  
  Popular open-core ERP/CRM platform. Community edition plus available modules support product variants, pricing, quotations, and sales workflows; many organizations extend it into full CPQ solutions (note: some advanced features require Enterprise).
- **[Lotus](https://github.com/uselotus/lotus)**  
  Open-source pricing and packaging infrastructure that supports usage-based, seat-based, and complex subscription models — useful as a modern pricing engine alongside configuration tools.
- **[Flexprice](https://github.com/flexprice/flexprice)**  
  Open-source (AGPL) usage-based pricing, metering, and billing platform that can be self-hosted. Complements CPQ by handling sophisticated pricing logic, credits, and feature access control.
- **[Oreko](https://github.com/orekoapp/oreko)**  
  Open-source (AGPL) self-hosted visual quote and invoice builder with a modern block-based editor. Strong for professional services, agencies, and simpler product quoting needs.
- **[CPyQ](https://github.com/delliott0000/CPyQ)**  
  Early-stage open-source Python-based CPQ platform with client/server architecture, WebSocket state synchronization, and extensibility for different product domains.
- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)** / **[Twenty](https://github.com/twentyhq/twenty)**  
  Leading open-source CRMs that include quoting, product catalogs, and opportunity management. Frequently used as the front-end layer for custom CPQ implementations.

### Additional Strong Open-Source Options
- Community product configurator modules and constraint engines built on top of **Odoo** or **ERPNext**.
- AI-assisted quote systems and rule engines (various GitHub projects using LLMs + structured product data).
- **Dolibarr** for simpler open-source quoting and sales document generation.
- Headless commerce frameworks (e.g., Vendure, Medusa) that support configurable products and quote-to-order flows.
- Custom constraint solvers and configuration engines implemented with open-source rule engines or Prolog-style systems.

**Frameworks for building custom systems**: Combine **openCPQ** (browser configuration) or constraint engines with **ERPNext** / **Odoo Community** for product masters, pricing, quoting, and order management, plus **Lotus** or **Flexprice** for advanced pricing logic, and an open-source CRM (**Twenty** / **SuiteCRM**) for the sales process — creating a fully owned, extensible CPQ stack.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- CPQ tools should be evaluated for configuration complexity handling, pricing rule expressiveness, quote accuracy, approval workflows, ERP/CRM integration quality, and long-term maintainability of product models.
- Self-hosted open-source solutions require solid product data modeling, rule testing, security hardening, and ongoing maintenance of configuration logic.
---
**Made for sales operations, solution engineers, manufacturers of complex products, MSPs, and anyone who wants open, controllable, and cost-effective Configure-Price-Quote capabilities.**
Let's make product configuration and quoting more open, transparent, and free from proprietary lock-in.

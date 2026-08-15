# Awesome-Identity-Resolution-Platform

## Top Identity Resolution Platform Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Customer Identity Graphs, Entity Resolution, Deterministic & Probabilistic Matching, Cross-Device Identity, Unified Profiles & Record Linkage*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Resolution**. These tools stitch together fragmented customer, device, and household identifiers across channels and data sources to create unified profiles — enabling accurate targeting, personalization, measurement, and analytics while navigating privacy constraints.

**Examples** include LiveRamp, Amperity, Reltio, mParticle, Segment Personas, BlueConic, Tealium, ActionIQ, Treasure Data, Zeta Global, FullContact, Zeotap, Acxiom, Near, Tapad, Infutor, RingLead, Experian Identity, TransUnion TruAudience, LiveRamp Safe Haven, Neustar, and Lotame (the category leaders and widely used platforms).

**Open-source emphasis**: Full commercial-scale open-source identity graphs comparable to LiveRamp or Amperity are rare. This section prioritizes the strongest available open-source entity resolution, record linkage, and identity-stitching libraries and frameworks that data and engineering teams use to build custom identity resolution systems inside their own warehouses or infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description & Core Capabilities | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[LiveRamp](https://liveramp.com/)** | Enterprise identity resolution and data collaboration platform with RampID deterministic graph, cross-channel identity translation, and Safe Haven clean rooms. | Starts at **$833/mo** ($10,000/yr base RampID resolution tier on AWS/Snowflake Marketplace; enterprise contracts avg $50,000–$150,000/yr). | **No free-forever plan**; 14-day to 30-day Proof of Concept (POC) / test-drive with up to 10,000 sample records upon sales approval. |
| **[Amperity](https://amperity.com/)** | AI-powered customer data platform specializing in patented Stitch identity resolution (probabilistic & deterministic) for unified enterprise Customer 360 profiles. | Starts at **$5,000/mo** ($60,000/yr base platform tier for Customer Data Cloud compute & Amp credits; enterprise contracts avg $100k–$250k+/yr). | **No free-forever plan**; 30-day custom sandbox / POC trial with up to 50,000 customer test records upon discovery demo. |
| **[Reltio](https://www.reltio.com/)** | Cloud-native Master Data Management (MDM) and entity resolution platform for creating real-time trusted golden customer records. | **Free Forever Tier** available on Identity 360; Paid Enterprise MDM editions start at **$3,333/mo** ($40,000/yr on AWS Marketplace). | **Free Forever Plan** (Identity 360) supporting up to **10,000 unique consolidated profiles**; 30-day test drive for industry Velocity Packs. |
| **[mParticle](https://www.mparticle.com/)** | Real-time customer data platform with native IDSync multi-identifier resolution, cross-device rule stitching, and mobile SDK pipelines. | Starts at **$1,500/mo** ($18,000/yr base package for data ingestion and IDSync; average enterprise deployment ~$156,000/yr). | **No free-forever plan**; 30-day developer sandbox / POC trial with up to 100,000 test events upon sales consultation. |
| **[Twilio Segment](https://segment.com/)** (Unify) | Real-time identity resolution engine (Segment Unify) and customer profile merging across mobile, web, and server event pipelines. | **Free Forever Tier** on Connections; Team plan starts at **$120/mo** (up to 10k MTUs); Unify identity add-on starts at **$1,250/mo** ($15,000/yr). | **Free Forever Plan** on Connections (up to **1,000 MTUs** and 2 data sources); 14-day free trial on Team & Business CDP features. |
| **[BlueConic](https://www.blueconic.com/)** | Pure-play customer data platform featuring automated profile unification, multi-identifier graph stitching, and real-time behavioral segmentation. | Starts at **$2,500/mo** ($30,000/yr base subscription tier for up to 100,000 active unified customer profiles). | **No free-forever plan**; 14-day to 30-day guided Proof of Concept (POC) trial upon scheduling an enterprise platform demo. |
| **[Tealium](https://tealium.com/)** (AudienceStream) | Enterprise Customer Data Hub and CDP delivering real-time visitor stitching, omnichannel identity unification, and tag management. | Starts at **$2,500/mo** ($30,000/yr for entry EventStream + AudienceStream bundle managing up to 1M events/mo). | **No free-forever plan**; 30-day sandbox / POC trial with up to 500,000 test events upon enterprise sales discovery. |
| **[ActionIQ](https://www.actioniq.com/)** (Uniphore) | Composable CDP providing zero-copy data warehouse integration, Hybrid Identity Resolution, and enterprise audience orchestration. | Starts at **$8,333/mo** ($100,000/yr base enterprise subscription for composable identity and audience management). | **No free-forever plan**; 30-day enterprise Proof of Concept (POC) sandbox environment following custom data scoping. |
| **[Treasure Data](https://www.treasuredata.com/)** | Enterprise CDP using a "No Compute" model to deliver high-scale identity resolution, IoT/event data unification, and predictive analytics. | Starts at **$3,500/mo** ($42,000/yr base subscription for profile management and behavioral event ingestion on AWS Marketplace). | **No free-forever plan**; 30-day enterprise POC trial environment on AWS Marketplace / enterprise evaluation. |
| **[Zeta Global](https://zetaglobal.com/)** | Marketing and identity platform combining proprietary Data Cloud graph (2.4B+ profiles), deterministic resolution, and omni-channel activation. | Starts at **$5,000/mo** ($60,000/yr base platform license or equivalent annual media commitment). | **No free-forever plan**; 30-day custom match-rate diagnostic & POC trial on a sample customer list upon sales engagement. |
| **[FullContact](https://www.fullcontact.com/)** | Identity resolution and data enrichment APIs powered by persistent PersonID, multi-identifier graph matching, and household linkages. | Starts at **$99/mo** (Developer API tier with up to 2,500 lookups/mo; commercial API packages start at **$500/mo** or $6,000/yr). | **Free Developer Trial Key** with **1,000 free API match/enrichment queries** (no expiration for initial test credits). |
| **[Zeotap](https://zeotap.com/)** | Customer data platform and ID+ graph providing deterministic and probabilistic identity resolution with strict European GDPR compliance. | Starts at **$2,500/mo** ($30,000/yr base tier for identity resolution and profile management up to 250,000 profiles). | **No free-forever plan**; 30-day guided POC trial and sandbox environment following enterprise sales demo. |
| **[Acxiom](https://www.acxiom.com/)** (Real ID) | Enterprise identity resolution featuring the InfoBase identity graph and Acxiom Real ID for in-warehouse matching on Snowflake and Databricks. | Starts at **$2,000/mo** ($24,000/yr entry licensing or **$0.02–$0.05 per matched record** on Snowflake Marketplace). | **Snowflake Marketplace Test Drive** allowing up to **1,000 sample record matches**; 30-day proof of concept for enterprise datasets. |
| **[Experian](https://www.experian.com/)** (Identity Resolution) | Bureau-grade identity resolution and ConsumerView graph enabling offline-to-online deterministic linkage, householding, and enrichment. | Starts at **$2,500/mo** ($30,000/yr minimum annual commitment or **$0.02–$0.08 per match lookup**). | **No free-forever plan**; 30-day sample data match-rate diagnostic test (up to 5,000 record test batch) via enterprise sales. |
| **[TransUnion](https://www.transunion.com/)** (TruAudience) | Identity graph and resolution suite (including Neustar OneID / Fabrick) for cross-screen identity, measurement, and privacy-first matching. | Starts at **$3,000/mo** ($36,000/yr base identity graph access and query license on Snowflake/AWS Marketplace). | **TruAudience Data Health Assessment (DHA)** free trial on Snowflake with up to **2,500 record matches**; 30-day POC trial. |
| **[Tapad](https://www.tapad.com/)** | Cross-device identity resolution and digital device graph linking cookies, MAIDs, CTV IDs, and household devices for omnichannel targeting. | Starts at **$3,000/mo** ($36,000/yr entry graph licensing and data feed access). | **No free-forever plan**; 30-day POC match assessment on sample cross-device dataset (up to 10,000 test device IDs). |
| **[Infutor](https://www.infutor.com/)** (Verisk) | Consumer identity resolution and TrueSource graph with real-time IDMax API for lead verification and CRM identity attribute completion. | Starts at **$500/mo** ($6,000/yr base API subscription or **$0.03–$0.07 per API lookup**). | **No free-forever plan**; 14-day free API test trial with up to **1,000 test lookups** upon developer account registration. |
| **[Lotame](https://www.lotame.com/)** (Panorama ID) | Cookieless identity resolution (Panorama ID) and Spherical CDP for first-party data onboarding, enrichment, and cross-channel activation. | Starts at **$2,500/mo** ($30,000/yr base subscription for Spherical onboarding & identity platform). | **Free Forever Open Access** for Panorama ID generation/deployment for publishers/web; 30-day POC for Spherical CDP platform. |
| **[ZoomInfo RingLead](https://www.ringlead.com/)** | Revenue operations and data orchestration platform for lead-to-account matching, CRM deduplication, data cleansing, and automated routing. | Starts at **$500/mo** ($6,000/yr base package for CRM deduplication; full Operations suite starts at **$20,000/yr**). | **No free-forever plan**; 14-day guided sandbox trial and CRM data quality health scan (up to 10,000 CRM records) upon scheduling a demo. |

## Open-Source GitHub Projects
- **[Splink](https://github.com/moj-analytical-services/splink)**  
  Leading open-source probabilistic record linkage and entity resolution framework (Python/SQL/Spark). Implements scalable Fellegi-Sunter models with transparent match weights — the strongest pure open-source option for building production identity resolution pipelines.
- **[Zingg](https://github.com/zinggAI/zingg)**  
  Scalable open-source entity resolution tool using active learning and Spark. Designed for large datasets and practical data-mastering workflows.
- **[dedupe](https://github.com/dedupeio/dedupe)**  
  Mature Python library for fuzzy matching, deduplication, and entity resolution using active learning. Excellent for structured data and teams that want flexible, inspectable matching logic.
- **[PyJedAI](https://github.com/AI-team-UoA/pyJedAI)**  
  Open-source toolkit implementing state-of-the-art entity resolution clustering and matching algorithms.
- **[DeepMatcher](https://github.com/anhaidgroup/deepmatcher)**  
  Deep learning-based entity matching library for more complex, semantic record linkage scenarios.
- **[RudderStack dbt ID Resolution](https://github.com/rudderlabs/dbt-id-resolution)** and similar warehouse-native patterns  
  Open examples and dbt projects for performing identity resolution directly inside the data warehouse using event and identify data.
- **Neo4j Entity Resolution Examples & Graph Approaches**  
  Graph-database patterns and community projects that model identity as connected nodes and relationships for resolution and analysis.
- **Emerging Semantic / LLM-based Entity Resolution Frameworks** (e.g., SERF and related projects)  
  Newer open-source efforts that apply embeddings and large language models to semantic entity resolution.
- **Record Linkage and Blocking Libraries**  
  Supporting open-source tools for candidate generation, string comparison, and evaluation that form building blocks of custom identity systems.
- **c1v-id and lightweight identity resolvers**  
  Focused open-source libraries designed for fast identity lookups in AI agents, CRM deduplication, and real-time matching scenarios.

### Additional Strong Open-Source Options
- Privacy-preserving and clean-room related open components that complement identity workflows.
- First-party ID and publisher identity open initiatives (e.g., SharedID-style approaches).
- Data quality and normalization libraries used as preprocessing steps before resolution.
- Graph analytics and community detection algorithms applied to identity graphs.
- Integration of open entity resolution engines with open CDP pipelines (RudderStack, Jitsu, Snowplow) for end-to-end first-party identity systems.

**Frameworks for building custom systems**: Most sophisticated open implementations run **Splink** or **Zingg** (or a combination of blocking + matching libraries) on data inside a warehouse or Spark cluster, often orchestrated with dbt. The resulting unified IDs feed analytics, activation, and personalization layers. Teams with strong graph expertise may model identity relationships in Neo4j or similar stores. Full commercial-scale graphs still typically rely on proprietary data networks; open-source tools excel at resolving *your* first-party and known data.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity resolution platforms should be evaluated for match accuracy (deterministic vs probabilistic), graph coverage, privacy and consent compliance (GDPR, CCPA, etc.), real-time vs batch capabilities, transparency of matching logic, and total cost of ownership.
- Open-source entity resolution tools give full control and auditability of matching models but require significant data engineering effort, high-quality input data, and ongoing tuning. They do not automatically provide the large third-party identity graphs offered by commercial providers.
---
**Made for data engineers, identity architects, CDP teams, and privacy-conscious organizations that want transparent, controllable identity resolution infrastructure.**
Let's make customer identity graphs and entity resolution more open, inspectable, and free from black-box proprietary matching.

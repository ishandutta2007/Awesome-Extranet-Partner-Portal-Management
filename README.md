# Awesome-Extranet-Partner-Portal-Management

## Top Extranet & Partner Portal Management Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Channel Enablement, Deal Registration & Self-Hosted Partner Workspaces*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Extranet & Partner Portal Management**. These tools help organizations collaborate with external partners—resellers, distributors, agencies, and suppliers—covering everything from deal registration and channel marketing to secure document exchange and project collaboration.

**Examples** include Salesforce Experience Cloud, Impartner PRM, Zoho Portals, Magentrix, Allbound, ClientShare, ProjectSend, and Atrium (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted partner portals, open-source client extranets, and community-driven collaboration platforms—ideal for organizations seeking data sovereignty and avoiding per-user community licensing. The open-source landscape splits into **secure file-exchange extranets** (ClientShare, ProjectSend, Atrium) for document collaboration with external parties, and **CRM-based partner workspaces** (Twenty) that can be extended with custom objects for partner relationship management.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Partner Relationship Management (PRM) and Extranet software market is estimated at approximately $3B to $5B for core software solutions (expanding past $15B+ within broader digital workplace and channel enablement ecosystems), expanding at a CAGR of 14%–17%. The sector is **moderately fragmented**: mega-cap enterprise CRM vendors (such as Salesforce) dominate large ecosystems, while specialized pure-play PRM platforms (like Impartner, Magentrix, Channeltivity, and Allbound) fiercely compete alongside self-hosted/open-source portal frameworks for mid-market and niche channel requirements.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits | Description |
|---------|-----------------------------------|------------------|--------------------------|-------------|
| **[Salesforce Experience Cloud](https://www.salesforce.com/products/experience-cloud/)** | ~$200B–$250B Market Cap (~$38B FY25 Rev) | $25/member/month (Partner Community, billed annually) or $10/login | No permanent production free tier. 30-day free trial on CRM parent orgs, or free permanent Developer Edition (capped at 5 MB data storage, 20 MB file storage, and 5,000 API requests/day). | **The enterprise partner portal standard.** Build branded partner communities with deal registration, lead distribution, training materials, and reporting. Requires at least one Enterprise Edition Salesforce license to host. |
| **[Zoho Portals (Creator / CRM)](https://www.zoho.com/)** | ~$12.5B Valuation (~$1.5B FY25 Rev) | $8/user/month (Zoho Creator Standard) + $100/month per block of 250 external portal users | Free forever plan available (capped at 1 app, 1 user, and 5,000 total records); 15-day free trial on paid tiers (unlocked features, no credit card required). | External partner/client access portal capabilities across the Zoho ecosystem (Creator & CRM), enabling custom partner interfaces, record workflows, and role-based permissions. |
| **[Impartner PRM](https://www.impartner.com/)** | ~$35M–$45M ARR ($110M+ Raised) | $2,000/month ($25,000/year billed annually for Emerge tier) | No permanent free tier; 30-day trial available exclusively via partner marketplace programs (HubSpot integration) or custom demo sandboxes upon sales qualification. | **Purpose-built partner relationship management.** Channel enablement, deal registration, partner onboarding, and performance analytics positioned for enterprises with complex channel programs. |
| **[Allbound](https://www.allbound.com/)** | ~$43M Growth Investment (~$7M+ ARR) | $3,495/month (annual commitment) | No free tier and no self-service free trial; product evaluation requires a scheduled sales demonstration. | Partner sales and marketing enablement platform focused on content distribution, deal registration, training, and partner collaboration. |
| **[Magentrix](https://www.magentrix.com/)** | ~$5M ARR (Bootstrapped/Private) | $1,500/month (Essential PRM tier, includes ~100 partner users / 10 partner accounts) | No permanent free tier; 1-month trial option offered upon plan onboarding. | PRM and partner portal platform offering seamless CRM integration (Salesforce/HubSpot), deal registration, content management, and partner training with zero setup fees. |
| **[Channeltivity](https://www.channeltivity.com/)** | ~$1.5M ARR (Private/Bootstrapped) | $1,199/month (Growth tier, billed annually) | No free tier and no free trial; access requires a custom sales consultation and live product demonstration. | PRM platform with deal registration, lead distribution, partner onboarding, and channel marketing tools tailored for mid-market channel programs. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ClientShare](https://github.com/pixelcop/clientshare)** | [![Stars](https://img.shields.io/github/stars/pixelcop/clientshare?style=social&color=white)](https://github.com/pixelcop/clientshare/stargazers) | **The most complete open-source branded client portal for secure file exchange.** **Go + Vue** single deployable service. **Self-hosted by default** with SQLite/local storage, upgradeable to PostgreSQL/MySQL/S3. **Expiring secure links** for controlled external access. **User and role-based access control**. **Client, folder, and file organization** with email-driven invite and password-reset workflows. **Branding controls** for site title, logo, and primary color. Docker Compose quick start . **Best for teams wanting a branded extranet for document exchange** without per-seat SaaS fees . |
| **[ProjectSend](https://github.com/projectsend/projectsend)** | [![Stars](https://img.shields.io/github/stars/projectsend/projectsend?style=social&color=white)](https://github.com/projectsend/projectsend/stargazers) | **The most established open-source client portal for sharing files privately with clients, partners, and teams.** **Self-hosted**—files stay on your server, no third-party service holding client documents, no per-seat pricing. **Two-factor authentication** with TOTP and recovery codes. **REST API** with scoped tokens. **LDAP and SSO** support. **Download limits and storage quotas** with automatic enforcement. **Client portals** with private pages per client. **Comments and file versions** with notifications. **Complete activity trail** for accountability . **Best for organizations wanting a proven, feature-rich file-exchange extranet** with enterprise auth options . |
| **[Atrium](https://hub.docker.com/r/vibralabs/atrium)** | [![Stars](https://img.shields.io/github/stars/vibralabs/atrium?style=social&color=white)](https://github.com/vibralabs/atrium/stargazers) | **Self-hosted client portal for agencies and freelancers with built-in project management.** **PostgreSQL included** in the Docker image—no separate database container. **Project management** with customizable status pipeline per organization. **File sharing** via S3, MinIO, Cloudflare R2, or local storage. **White-label branding** with custom colors and logo. **Role-based access** (owner/admin for your team, member for clients). **Email notifications** via Resend. Single `docker run` command to start . **Best for agencies wanting a combined client portal + project management** without SaaS fees . |
| **[Twenty](https://github.com/twentyhq/twenty)** | [![Stars](https://img.shields.io/github/stars/twentyhq/twenty?style=social&color=white)](https://github.com/twentyhq/twenty/stargazers) | **Modern open-source CRM that can be extended into a partner portal workspace.** **Self-hostable** (Docker-based, or one-click on Railway with PostgreSQL, Redis, and MinIO pre-wired). **Custom objects and fields** can model partners, agencies, deals, and RFP responses. **Role-based permissions** with custom roles. **REST and GraphQL APIs** plus webhooks for integration. **AGPLv3 with MIT for some packages** . **Best for organizations wanting a configurable CRM foundation** to build partner relationship management on top of—not a turnkey portal, but a flexible data layer . |
| **[Zenario](https://github.com/TribalVision/Zenario)** | [![Stars](https://img.shields.io/github/stars/TribalVision/Zenario?style=social&color=white)](https://github.com/TribalVision/Zenario/stargazers) | **Open-source CMS with a fully-fledged extranet system.** **Secure access for authorised users** with self-registration or admin-created accounts. **Organization Manager** models people and their roles in organizations. **Location Manager** with Google Maps integration. **Modular architecture**—extranet functionality is built in, not bolted on. **Scheduled task manager** for cron-like batch jobs . **Best for organizations wanting an extranet integrated into a broader CMS** rather than a standalone portal . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Open Mercato (Partner Portal Module)](https://github.com/open-mercato/open-mercato)** | — | **B2B PRM partner portal module spec** for the Open Mercato platform. Defines **Partner Dashboard** (tier status, KPI summary, RFP inbox), **RFP Response** workflows, **Case Studies** submission, and **Team Management** with partner-specific RBAC (`portal.partner.access`, `portal.partner.kpi.view`, etc.). Includes agency onboarding flow with staff-initiated invites and auto-role assignment . **Best as a reference architecture** for building a structured PRM partner portal—the module is a spec, not a turnkey product . |
| **[OpenG2P Partner Management](https://github.com/OpenG2P/partner-management)** | — | **Partner management service for the OpenG2P government-to-person platform.** Single shared service where all OpenG2P modules fetch partner public keys from one `partner-api`, and admins onboard partners and rotate keys through one staff portal . **Best for public-sector or G2P deployments** needing partner key management—not a general-purpose partner portal . |

**Frameworks for building custom systems**: Choose **ClientShare** or **ProjectSend** for secure file-exchange extranets with branding and access controls , **Atrium** for a combined client portal and project management solution , or **Twenty** as a configurable CRM foundation to build partner relationship objects on top of —all without per-seat community licensing that compounds across partner networks.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Partner portals and extranets handle external user credentials and potentially sensitive commercial documents; enforce strict access controls, expiring links, and audit logging for all partner activity.
- **Salesforce Experience Cloud's pricing is deceptively complex.** The platform **requires at least one Enterprise Edition Salesforce license** to run—you cannot buy community licensing alone. **Community user licensing is separate**: Customer Community ~$5/login or $2/member/month; Customer Community Plus ~$6/login or $15/member . This two-layer cost structure means the "starting price" is misleading if you're not already a Salesforce customer .
- **Open-source partner portals solve different problems.** **ClientShare, ProjectSend, and Atrium** are **file-exchange extranets**—they excel at secure document collaboration with external parties but lack deal registration, lead distribution, or channel marketing features . **Twenty is a CRM**, not a partner portal—it provides the data model and RBAC foundation, but you build partner-specific workflows yourself . **Zenario** provides extranet capabilities within a broader CMS . **Validate whether you need file exchange (ProjectSend), project collaboration (Atrium), a CRM foundation (Twenty), or full PRM features (Impartner, Salesforce)** before committing.

---

**Made for channel managers, partner operations teams, and organizations building external collaboration infrastructure.**  
Let's make extranet and partner portal management more open, secure, and partner-friendly.

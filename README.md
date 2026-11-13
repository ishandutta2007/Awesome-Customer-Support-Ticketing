# Awesome Customer Support Ticketing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of top **Customer Support Ticketing Systems**, **Helpdesk Platforms**, and **Shared Inboxes** across both enterprise SaaS solutions and open-source self-hosted GitHub projects.

Comprehensive guide for customer support managers, IT service desk leads, sysadmins, and software engineers seeking ticket management platforms, SLA monitoring, multi-channel customer communication tools, and data-sovereign helpdesks.

---

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Architecture & Self-Hosting Considerations](#architecture--self-hosting-considerations)
- [How to Contribute](#how-to-contribute)
- [License & Disclaimer](#license--disclaimer)

---

## Sector Overview & Market Dynamics

The global customer support ticketing and helpdesk software market is valued at approximately **$8 billion to $15 billion** (scaling past **$50 billion** when accounting for the broader CRM and customer service software sector), expanding at an estimated **8% to 10% CAGR**. The market structure is **moderately fragmented overall but consolidated at the enterprise tier**: mega-platforms (such as ServiceNow, Atlassian, Zendesk, and Freshworks) dominate large-enterprise spend due to deep ecosystem lock-in, omnichannel voice/chat routing, and proprietary generative AI investments, while a vibrant, fragmented long tail of specialized SaaS and self-hosted open-source software serves SMBs, privacy-conscious teams, and developer-centric organizations seeking data sovereignty.

---

## SaaS & Hosted Platforms

| Product | Company Size (Rev / Valuation) | Pricing (Starting Paid Tier) | Free Tier / Free Trial Limits | Description |
|:---|:---|:---|:---|:---|
| **[ServiceNow CSM](https://www.servicenow.com/)** | ~$15.4B TTM Rev / ~$112B MCap | Standard: **$100/agent/month** (annual contract) | **No free tier**; 14-day guided proof-of-concept trial via enterprise sales. | Enterprise-grade digital workflow engine providing ITIL-aligned case management, omni-channel routing, field service coordination, and AI assist. |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | ~$6.57B FY26 Rev / ~$42B MCap | Standard: **$23.73/agent/month** (billed annually) | **Free plan forever**: up to 3 agents, unlimited customers, 2 GB file storage, and 100 email notifications/day. | Atlassian's ITSM and customer service platform built natively on Jira, featuring incident/problem management, asset tracking, and native Confluence integration. |
| **[Zoho Desk](https://www.zoho.com/desk/)** | ~$1.5B Rev / ~$12B Est. Val | Standard: **$14/agent/month** (billed annually) | **Free plan forever**: up to 3 agents, basic email ticketing, customer management, and private knowledge base. 15-day free trial on paid plans (no credit card required). | Context-aware cloud ticketing system with multi-department support, SLA escalations, Zia AI, and deep integration with the Zoho SaaS suite. |
| **[Zendesk Support](https://www.zendesk.com/)** | ~$2.0B ARR / ~$10.2B Acq. Val | Support Team: **$19/agent/month** (billed annually) | **No free tier**; 14-day full-featured free trial with sample data and test ticketing access (no credit card required). | Industry-benchmark customer service software offering unified ticket queues, multi-channel intake, trigger-based automations, and outcome-based AI. |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | ~$839M Rev / ~$3.3B MCap | Growth: **$29/agent/month** (billed annually) | **No permanent free tier**; 14-day free trial of Enterprise tier (up to 10 agents, includes 500 Freddy AI sessions, no credit card required). | Multi-channel cloud ticketing system featuring Freddy AI automated triage, collision detection, custom ticketing fields, and workflow automations. |
| **[Front](https://front.com/)** | ~$100M ARR / ~$1.7B Val | Starter: **$25/seat/month** (billed annually, min 2 seats) | **No free tier**; 14-day free trial of Professional plan (access to omnichannel integrations and automated rules, no credit card required). | Customer communication hub unifying email, SMS, and live chat into team-shared inboxes with internal comments, collision avoidance, and automated routing. |
| **[Help Scout](https://www.helpscout.com/)** | ~$35M ARR / ~$150M Est. Val | Standard: **$25/user/month** (billed annually) | **Free plan forever**: up to 5 users, 1 shared mailbox, and 1 Docs knowledge base site (available for non-profits & micro-teams). 15-day free trial on paid tiers. | Clean, collaborative shared inbox designed for human-centric customer support with integrated help center docs, live chat beacons, and AI drafting. |
| **[Deskpro](https://www.deskpro.com/)** | ~$10M ARR / ~$25M Funded | Team: **$39/agent/month** (billed annually, min 5 agents) | **No free tier**; 14-day full-featured Cloud free trial (includes live chat, omnichannel ticketing, and reporting, no credit card required). | Flexible multi-channel helpdesk available both as managed cloud SaaS and on-premise deployment with custom ticketing workflows and CRM integrations. |
| **[LiveAgent](https://www.liveagent.com/)** | ~$8M ARR / Profitable Bootstrapped | Small: **$15/agent/month** (billed annually) | **No permanent free tier**; 14-day or 30-day free trial with full access to live chat, ticketing, call center, and customer portals (no credit card required). | Omnichannel helpdesk with live chat, ticket management, built-in call center software, gamification, and BYO-AI provider integration. |
| **[Kayako](https://kayako.com/)** | ~$5M ARR / Acquired (ESW Capital) | Inbox: **$15/agent/month** (or AI-first resolution model at $1/resolution) | **No free tier**; 14-day free trial with access to shared inbox, live chat, and automated conversations (credit card may be required upon signup). | Unified customer service platform linking shared conversations, customer journey timelines, self-service portals, and AI triage. |

---

## Open-Source GitHub Projects

Curated list of production-ready open-source helpdesks, shared inboxes, and ITSM ticketing engines, sorted by GitHub stargazers:

| Project | Stars | Language / Tech Stack | License | Key Highlights |
|:---|:---:|:---|:---|:---|
| **[Chatwoot](https://github.com/chatwoot/chatwoot)** | [![Stars](https://img.shields.io/github/stars/chatwoot/chatwoot?style=social&color=white)](https://github.com/chatwoot/chatwoot/stargazers) | Ruby / Vue.js | MIT | Leading open-source omnichannel customer engagement platform. Unifies live chat, email, WhatsApp, Facebook, Instagram, and Telegram into a real-time conversational inbox with multi-agent collision avoidance and AI assistance. |
| **[UVdesk](https://github.com/uvdesk/community-skeleton)** | [![Stars](https://img.shields.io/github/stars/uvdesk/community-skeleton?style=social&color=white)](https://github.com/uvdesk/community-skeleton/stargazers) | PHP / Symfony | MIT | Modular and extensible enterprise-grade helpdesk system. Features automated email-to-ticket conversion, ticket dispatching workflows, customizable customer portals, and mailbox integrations. |
| **[GLPI](https://github.com/glpi-project/glpi)** | [![Stars](https://img.shields.io/github/stars/glpi-project/glpi?style=social&color=white)](https://github.com/glpi-project/glpi/stargazers) | PHP / MySQL | GPL-3.0 | Comprehensive open-source IT asset management (ITAM) and ITIL Service Desk ticketing platform. Manages complex hardware/software inventories, financial tracking, SLAs, and customer trouble tickets. |
| **[Papercups](https://github.com/papercups-io/papercups)** | [![Stars](https://img.shields.io/github/stars/papercups-io/papercups?style=social&color=white)](https://github.com/papercups-io/papercups/stargazers) | Elixir / TypeScript | MIT | Open-source live chat and conversational support widget designed as an alternative to Intercom and Drift. Features Slack and Mattermost syncing, webhooks, and modern developer APIs. |
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | Ruby on Rails / Elasticsearch | AGPL-3.0 | Modern, full-featured web-based helpdesk closest to commercial SaaS. Provides complete multi-channel ticketing (email, telephone/CTI, chat, social media), ITIL workflows, SLA timers, audit logs, and customer self-service. |
| **[FreeScout](https://github.com/freescout-help-desk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-help-desk/freescout?style=social&color=white)](https://github.com/freescout-help-desk/freescout/stargazers) | PHP / Laravel | AGPL-3.0 | Lightweight, self-hosted shared inbox and helpdesk alternative to Help Scout and Zendesk. Operates efficiently on low-spec hardware (1–2 GB RAM), with conversation threading, push notifications, and modular plugin support. |
| **[osTicket](https://github.com/osTicket/osTicket)** | [![Stars](https://img.shields.io/github/stars/osTicket/osTicket?style=social&color=white)](https://github.com/osTicket/osTicket/stargazers) | PHP / MySQL | GPL-2.0 | Proven, widely deployed open-source customer support ticket system. Routes inquiries created via email, web forms, and phone into a multi-user web interface with auto-responder, SLA management, and internal notes. |
| **[Chaskiq](https://github.com/chaskiq/chaskiq)** | [![Stars](https://img.shields.io/github/stars/chaskiq/chaskiq?style=social&color=white)](https://github.com/chaskiq/chaskiq/stargazers) | Ruby on Rails / React | GPL-3.0 | Full-featured conversational marketing and customer support platform. Combines live web chat widgets, automated conversational bots, newsletters, onboarding tours, and multi-channel messaging. |
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | Python / Frappe / Vue | AGPL-3.0 | Modern open-source helpdesk tool built on the Frappe framework. Delivers clean ticket routing, customer portal, SLA tracking, team assignment, and native two-way synchronization with ERPNext CRM. |
| **[Peppermint](https://github.com/Peppermint-Lab/peppermint)** | [![Stars](https://img.shields.io/github/stars/Peppermint-Lab/peppermint?style=social&color=white)](https://github.com/Peppermint-Lab/peppermint/stargazers) | TypeScript / Node.js | AGPL-3.0 | Modern and fast open-source ticket and issue management system designed as a lightweight self-hosted alternative to Jira Service Desk and Zendesk. |
| **[Libredesk](https://github.com/abhinavxd/libredesk)** | [![Stars](https://img.shields.io/github/stars/abhinavxd/libredesk?style=social&color=white)](https://github.com/abhinavxd/libredesk/stargazers) | Go / SQLite | AGPL-3.0 | Single-binary, self-hosted customer support desk and live chat system written in Go. Minimal resource footprint, zero external database requirements, and rapid deployment. |
| **[Helpy](https://github.com/helpyio/helpy)** | [![Stars](https://img.shields.io/github/stars/helpyio/helpy?style=social&color=white)](https://github.com/helpyio/helpy/stargazers) | Ruby on Rails / PostgreSQL | MIT | Mobile-friendly, modern open-source helpdesk software with integrated knowledge base, multi-lingual support, email ticketing queues, and community discussion boards. |
| **[Trudesk](https://github.com/polonel/trudesk)** | [![Stars](https://img.shields.io/github/stars/polonel/trudesk?style=social&color=white)](https://github.com/polonel/trudesk/stargazers) | JavaScript / Node.js / MongoDB | Apache-2.0 | Clean, real-time open-source helpdesk platform with built-in chat, ticket assignment, dashboard analytics, and notifications via WebSockets. |
| **[iTop](https://github.com/Combodo/iTop)** | [![Stars](https://img.shields.io/github/stars/Combodo/iTop)?style=social&color=white](https://github.com/Combodo/iTop/stargazers) | PHP / MySQL | AGPL-3.0 | ITIL-compliant IT Service Management (ITSM) tool with a comprehensive Configuration Management Database (CMDB), helpdesk ticketing, change management, and service catalog. |
| **[Request Tracker (RT)](https://github.com/bestpractical/rt)** | [![Stars](https://img.shields.io/github/stars/bestpractical/rt?style=social&color=white)](https://github.com/bestpractical/rt/stargazers) | Perl / PostgreSQL / MySQL | GPL-2.0 | Enterprise-grade issue tracking and ticketing system deployed worldwide by Fortune 500s and government entities. Offers fine-grained access control, PGP/S-MIME encryption, and custom workflow scrips. |
| **[OTOBO](https://github.com/RotherOSS/otobo)** | [![Stars](https://img.shields.io/github/stars/RotherOSS/otobo?style=social&color=white)](https://github.com/RotherOSS/otobo/stargazers) | Perl / MariaDB | GPL-3.0 | Enterprise IT service desk and ticket management platform forked from OTRS. Features ITIL-aligned service management, CMDB, customer self-service portal, and OpenID Connect / SAML authentication. |
| **[Helpdock](https://github.com/Docker-Hunterpedia/Helpdock)** | [![Stars](https://img.shields.io/github/stars/Docker-Hunterpedia/Helpdock?style=social&color=white)](https://github.com/Docker-Hunterpedia/Helpdock/stargazers) | TypeScript / Next.js / Docker | MIT | Multi-brand self-hosted support platform featuring AI-assisted ticket resolution, help center CMS, live chat widget, and automated data importers for Zendesk, Freshdesk, and Zoho Desk. |

---

## Architecture & Self-Hosting Considerations

When evaluating self-hosted ticketing systems vs. managed SaaS platforms, consider total cost of ownership (TCO) and operational requirements:

- **Resource Footprint**:
  - *Lightweight (< 2 GB RAM)*: **Libredesk** (single Go binary), **FreeScout** (PHP/Laravel), and **osTicket** run smoothly on low-cost VPS instances or shared hosting.
  - *Mid to Heavy (4–16 GB RAM)*: **Zammad** (requires Elasticsearch + Redis + PostgreSQL/MySQL), **GLPI**, and **OTOBO** demand dedicated resources for indexing, complex search, and asset relationship mapping.
- **Data Sovereignty & Compliance**: Self-hosted solutions provide strict boundary control over Personally Identifiable Information (PII), customer communication archives, and HIPAA/GDPR data residency obligations without vendor lock-in.
- **Email Deliverability**: Ensure proper SPF, DKIM, DMARC, and reverse DNS records are configured when hosting SMTP/IMAP-driven ticket engines.

---

## How to Contribute

Contributions, project suggestions, and documentation fixes are warmly welcomed!

1. Fork this repository.
2. Create a descriptive feature branch (`git checkout -b add-new-ticketing-tool`).
3. Add your suggested SaaS product or open-source repository following the table formatting:
   - For SaaS: Product name, official link, company size (revenue/valuation), specific starting price, exact free tier / trial terms, and concise description.
   - For Open-Source: GitHub repo URL, star badge `[![Stars](https://img.shields.io/github/stars/<owner>/<repo>?style=social&color=white)](https://github.com/<owner>/<repo>/stargazers)`, primary language/stack, license, and key highlights.
4. Verify all markdown links and ensure proper chronological or sorted order.
5. Commit your changes and open a Pull Request.

---

## License & Disclaimer

- Distributed under the [Creative Commons CC0 1.0 Universal](LICENSE) (Public Domain Dedication).
- Pricing figures, trial terms, and market valuations are approximate, compiled from publicly available investor disclosures, corporate filings, and vendor sites as of 2025/2026. Always confirm current rates directly with product vendors prior to commercial procurement.

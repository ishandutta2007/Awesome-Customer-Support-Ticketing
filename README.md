# Awesome-Customer-Support-Ticketing

## Top Customer Support Ticketing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ticket Management, Shared Inboxes & Omnichannel Support*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Support Ticketing**. These tools help support teams capture, organize, and resolve customer requests across email, chat, and web forms—consolidating conversations into a single queue with assignment rules, SLAs, and reporting so nothing falls through the cracks.

**Examples** include Zoho Desk, Zendesk Support, Freshdesk, ServiceNow CSM, Help Scout, Front, Jira Service Management, Kayako, LiveAgent, Deskpro, and open-source alternatives like Chatwoot, Zammad, FreeScout, and Helpdock (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted ticketing systems, open-source shared inboxes, and community-driven helpdesk platforms—ideal for organizations seeking data sovereignty and eliminating per-agent licensing costs. The open-source ticketing landscape is mature and production-ready: **Chatwoot** leads as the omnichannel conversational default (28k+ stars, MIT) , **Zammad** offers the cleanest interface closest to commercial SaaS , **FreeScout** runs on minimal hardware (1–2 GB RAM) , and **Helpdock** provides a modern multi-brand platform with built-in AI and importers for Zendesk, Freshdesk, and Zoho Desk .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Zoho Desk](https://www.zoho.com/desk/)** | Context-aware helpdesk with email ticketing, social channels, SLAs, workflow automation, and Zia AI (on higher tiers). Standard tier supports unlimited agents and adds public self-service, messaging, and Answer Bot . | Standard: **$14/agent/month** (annual); Express: $7; Professional: $23; Enterprise: $40  | **Free**: up to 3 agents, basic email ticketing; **15-day free trial** (auto-downgrades to Free, no credit card)  |
| **[Zendesk Support](https://www.zendesk.com/)** | Industry-standard ticketing platform with mature omnichannel queues and broad integration ecosystem. **Standalone Support Team is $19/agent/month** (annual), distinct from Suite pricing. Zendesk is transitioning to **Outcome AI Platform** with outcome-based pricing (unlimited seats, pay for eligible outcomes) in Early Access . | Support Team: **$19/agent/month** (annual); Suite Team: $55  | No free tier; trial via sales. AI resolution allowances vary by account  |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | Cloud helpdesk with Freddy AI for automated responses, routing, and agent assistance. Growth tier covers core support; Pro adds custom dashboards; Enterprise adds skill-based routing and audit logs . | Growth: **$29/agent/month** (annual); Pro: $79; Enterprise: $119  | No permanent free tier; **14-day trial** (Enterprise plan access). Freddy AI Agent: 500 free sessions, then $49/100  |
| **[Help Scout](https://www.helpscout.com/)** | Shared inbox focused on conversation quality. Standard adds AI Inbox assistant; Plus adds unlimited AI Drafts. **Docs costs $10/user/month extra on Standard**—making Standard+Docs ($35) nearly comparable to Plus ($50) . | Standard: **$25/user/month** (annual); Plus: $50; Pro: $65  | **Free**: 5 users, 1 Inbox, 1 Docs site  |
| **[Front](https://front.com/)** | Collaborative inbox for shared email, chat, and messaging. Starter supports single channel type; Professional adds omnichannel and macros. **14-day trial of Professional** (no credit card) . | Starter: **$25/seat/month**; Professional: $65; Enterprise: $105  | **14-day free trial** of Professional  |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | Atlassian's service management platform. **Free tier: 3 agents, unlimited customers**. Premium adds 24/7 support and advanced automation. Customer Service Management adds **$1 per resolution** on top of agent seats . | Premium: **$55.28/agent/month**  | **Free**: 3 agents, unlimited customers, 2 GB storage, 100 emails/day  |
| **[LiveAgent](https://www.liveagent.com/)** | Helpdesk with universal inbox for tickets, chats, calls, and social. **AI assistants run on your own AI provider account**—LiveAgent does not charge for AI. Starter up to 5 agents; Enterprise flat fee with 80 agents included . | Per-agent plans (Starter/Team/Business); Enterprise flat fee  | Free trial available; no permanent free tier  |
| **[Deskpro](https://www.deskpro.com/)** | Helpdesk with multi-channel support and customizable ticket workflows. Cloud pricing is public: Team **$39/agent/month** (min 5), Professional **$59** (min 10), Enterprise **$99** (min 25) . | Team: **$39/agent/month** (min 5); Professional: $59; Enterprise: $99  | Free trial available  |
| **[Kayako](https://kayako.com/)** | AI-first support platform with **$1 per AI resolution** pricing. No per-seat fees, no upsells. If the AI escalates to a human, you don't pay the $1 . | **$1 per AI resolution**  | No free tier; demo available  |
| **[ServiceNow CSM](https://www.servicenow.com/)** | Enterprise customer service management. **Fulfiller seats roughly $100–$200/user/month** at smallest band, falling above 2,500 seats. Now Assist AI adds $25–$75/fulfiller/month on pre-2026 contracts; April 2026 tiers include AI with assist allocation . | Quote-only; ~$100–$200/fulfiller/month (smallest band)  | No free tier; demo via sales  |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Chatwoot](https://github.com/chatwoot/chatwoot)** | [![Stars](https://img.shields.io/github/stars/chatwoot/chatwoot?style=social&color=white)](https://github.com/chatwoot/chatwoot/stargazers) | **The most adopted open-source customer engagement platform** (~28k stars, MIT). Omnichannel shared inbox covering live chat, email, WhatsApp, Facebook, Instagram, Telegram, and SMS in one queue. Multi-agent conversations, AI Captain for triage, and self-hostable or cloud. **The default pick when your support model is conversational rather than ticket-only** . |
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | **The cleanest open-source ticketing interface, closest to commercial SaaS.** AGPL-3.0, Ruby on Rails. Multi-channel intake (email, phone, chat, social media), ITIL-aligned workflows, time accounting, knowledge base, and SLA management. **No feature paywalls**—SSO, roles, and audit logs included. **Needs 4–8 GB RAM** (Elasticsearch is the main consumer) . |
| **[FreeScout](https://github.com/freescout-help-desk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-help-desk/freescout?style=social&color=white)](https://github.com/freescout-help-desk/freescout/stargazers) | **The best lightweight open-source Help Scout alternative.** PHP/Laravel. Runs on **1–2 GB RAM** and is designed for shared hosting. Shared inbox, conversation threading, customer profiles, knowledge base, customer portal, mobile apps. **Core free; Modules marketplace for advanced features** (WhatsApp, custom fields, etc.) . |
| **[Helpdock](https://github.com/Docker-Hunterpedia/Helpdock)** | [![Stars](https://img.shields.io/github/stars/Docker-Hunterpedia/Helpdock?style=social&color=white)](https://github.com/Docker-Hunterpedia/Helpdock/stargazers) | **Modern multi-brand open-source support platform with built-in AI.** Self-hosted alternative to Zoho Desk/Zendesk. Features ticketing, help center, live chat widget, and grounded AI. **Importers for Zendesk, Freshdesk, and Zoho Desk** with dry-run previews. Multi-brand with row-level security per tenant. SSO over SAML 2.0 and OIDC. Reports on ticket volume, first response, resolution times, SLA compliance, and CSAT. Docker Compose deployment (2 vCPU, 4 GB RAM) . |
| **[osTicket](https://github.com/osTicket/osTicket)** | [![Stars](https://img.shields.io/github/stars/osTicket/osTicket?style=social&color=white)](https://github.com/osTicket/osTicket/stargazers) | **The most established open-source email-to-ticket system.** Deployed since 2013. PHP 8.2–8.4, MySQL. Integrates email, phone, and web forms into a simple multi-user interface. Lightweight (1–2 GB RAM). **Completely free** under GPL2. Best when you need straightforward email ticketing without modern omnichannel complexity . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | Modern ticketing built on Frappe framework (~3.5k stars, AGPL-3.0). SLAs with business hours, auto-assignment by priority/type/team/workload, **unlimited agents with no seat fees**, Google/Microsoft/OIDC sign-in, and **customer sync with ERPNext**. Trade-off: self-hosting means running the full Frappe stack (MariaDB, Redis, bench) . |
| **[OTOBO](https://github.com/rotheross/otobo)** | [![Stars](https://img.shields.io/github/stars/rotheross/otobo?style=social&color=white)](https://github.com/rotheross/otobo/stargazers) | Open-source ticketing and ITSM system forked from OTRS. **ITSM add-on packages are free**. OpenID Connect, LDAP, and RADIUS sign-in included. **Production servers need at least 8 GB RAM** (16 GB recommended). Vendor support from €3,900/year. Best for IT teams wanting OTRS-style service desk without licence fees . |
| **[Request Tracker (RT)](https://github.com/bestpractical/rt)** | [![Stars](https://img.shields.io/github/stars/bestpractical/rt?style=social&color=white)](https://github.com/bestpractical/rt/stargazers) | **Best for complex queues and granular permissions.** Rights per queue, group, and role; asset tracking built in; REST 2 API included. GPL-2.0, Perl. **No official Docker image for production**; SSO needs a web server module . |
| **[UVdesk](https://github.com/uvdesk)** | [![Stars](https://img.shields.io/github/stars/uvdesk?style=social&color=white)](https://github.com/uvdesk/stargazers) | Open-source helpdesk on Symfony/PHP with customer portal and knowledge base. Unlimited agents, teams, and mailboxes in free edition. **No SSO for agents and no audit log**; no new release since September 2025—check recent activity before committing . |
| **[Libredesk](https://github.com/abhinavxd/libredesk)** | [![Stars](https://img.shields.io/github/stars/abhinavxd/libredesk?style=social&color=white)](https://github.com/abhinavxd/libredesk/stargazers) | Open-source customer support inbox for email and live chat, written in Go. **Single Go binary**—significantly simpler deployment than PHP or Ruby stacks. Newer project worth watching for teams wanting minimal infrastructure footprint . |

**Frameworks for building custom systems**: Choose **Chatwoot** for conversational omnichannel support (live chat + messaging apps + email), **Zammad** for the closest commercial SaaS ticketing experience with no feature paywalls, **FreeScout** for lightweight shared-inbox on minimal hardware, **Helpdock** for multi-brand operations with built-in migration importers and AI, and **Frappe Helpdesk** for ERPNext integration—all deployable on a VPS without per-agent licensing .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Ticketing systems handle customer PII and support conversations; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Open-source ticketing TCO is not zero.** Zammad needs 4–8 GB RAM ; OTOBO needs 8–16 GB . Budget infrastructure, admin time, backups, and security hardening. **SaaS pricing is shifting toward AI outcomes.** Kayako charges **$1 per AI resolution** with no seat fees , Zendesk is moving to outcome-based billing with unlimited seats , and Freshdesk includes 500 free Freddy AI sessions before charging $49/100 . Verify current pricing against vendor pages before committing.

---

**Made for support operations managers, helpdesk administrators, IT service teams, and developers building ticketing infrastructure.**  
Let's make customer support ticketing more open, affordable, and agent-friendly.

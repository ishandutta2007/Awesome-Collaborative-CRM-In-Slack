# Awesome-Collaborative-CRM-In-Slack

# Top Collaborative CRM in Slack Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on CRM Workflows, Pipeline Management & Sales Collaboration Inside Slack*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative CRM in Slack**. These tools enable sales teams, RevOps, and customer-facing teams to manage deals, update CRM records, receive pipeline alerts, and collaborate on customer relationships without leaving Slack.

**Examples** include Salesforce Sales Cloud in Slack, Troops.ai (Slack Sales Elevate), Scratchpad, Halp, Wrike for Slack, Asana for Slack, HubSpot Slack Integration, Zoho CRM for Slack, Pipedrive for Slack, Workbot for Slack, and Copper CRM (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom Slack bot integration, and open CRM data processing — ideal for teams seeking transparent, extensible, and vendor-independent sales collaboration solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Sales Cloud in Slack](https://www.salesforce.com/slack/)**  
  Native Slack integration bringing Salesforce CRM data, deal alerts, and record updates directly into Slack channels. Includes Slack Sales Elevate (successor to Troops) for pipeline workflow automation.

- **[Troops.ai / Slack Sales Elevate](https://www.salesforce.com/slack/)**  
  Acquired by Salesforce in 2022. Enables Salesforce record search/edit, deal alerts, and sales workflow automation inside Slack. No longer available to new standalone customers.

- **[Scratchpad](https://scratchpad.com/)**  
  Fast Salesforce update and sales workflow platform in Slack. Provides actionable alerts for stale opportunities, pipeline hygiene, and deal reminders directly in Slack channels.

- **[HubSpot Slack Integration](https://www.hubspot.com/)**  
  CRM notifications, deal updates, and contact management within Slack. Supports lead capture from Slack conversations and bidirectional data sync.

- **[Zoho CRM for Slack](https://www.zoho.com/crm/)**  
  Cost-effective CRM integration for Slack with notifications, task management, record searching, and CRM data sharing. Lead capture from Slack conversations is supported.

- **[Pipedrive for Slack](https://www.pipedrive.com/)**  
  Sales CRM integration allowing users to add people, create deals automatically from Slack, and receive pipeline notifications.

- **[Wrike for Slack](https://www.wrike.com/)**  
  Project management integration enabling task creation from Slack messages, automated updates, and request capture in Slack channels.

- **[Asana for Slack](https://asana.com/)**  
  Create tasks from Slack messages, receive project updates, and manage workflows without context-switching.

- **[Halp](https://www.atlassian.com/software/halp)**  
  (Acquired by Atlassian, now integrated into Jira Service Management). Slack-native ticketing and support workflow tool for internal helpdesk and customer operations.

- **[Workbot for Slack](https://www.workato.com/)**  
  Workato's Slack bot enabling no-code automation between Slack and 400+ business apps, including CRM platforms like Salesforce, HubSpot, and Pipedrive.

- **[Copper CRM](https://www.copper.com/)**  
  Google Workspace-native CRM with Slack integration for deal notifications, contact syncing, and pipeline visibility.

## Open-Source GitHub Projects

- **[Twenty](https://github.com/twentyhq/twenty)**  
  Modern open-source CRM (GPL-licensed) built as an alternative to Salesforce and HubSpot. Features customizable data models, Kanban views, workflow automation, and native Slack integration. Backed by Y Combinator with 53.7k+ GitHub stars.

- **[Horilla CRM](https://github.com/horilla-opensource/horilla)**  
  Free, open-source, self-hosted CRM built on Django (LGPL-2.1). Includes sales pipeline, lead management, forecasting, email sync, and native Slack integration. Docker deployment available.

- **[Customermates](https://github.com/customermates)**  
  Self-hostable open-source CRM (AGPL-3.0) for small B2B teams. Features contacts, deals, pipelines, and a native n8n community node for workflow automation — enabling deal stage notifications to Slack and CRM sync workflows.

- **[OpenCRM](https://github.com/clawnify/OpenCRM)**  
  Lightweight open-source HubSpot alternative for SaaS teams. Manages contacts, companies, deals, and custom attributes with a full REST API and webhook support for Slack and other integrations.

- **[ChatterMate](https://github.com/chattermate/chattermate.chat)**  
  Open-source AI customer support platform (Apache-2.0) with Slack bot integration, human handoff, and CRM sync workers for pushing leads to HubSpot and Pipedrive.

- **[Quix by Clearfeed](https://github.com/clearfeed/quix)**  
  AI-powered Slack agent (Apache-2.0) that interacts with business tools including HubSpot, Jira, and GitHub directly from Slack channels. Natural language CRM queries and updates.

- **[Baserow](https://gitlab.com/baserow/baserow)**  
  Open-source no-code database tool (MIT license) usable as a lightweight CRM backend. Connects to Slack and Discord via APIs for notifications and workflow triggers.

- **[OpenClaw](https://github.com/openclaw)**  
  Open-source AI agent framework connecting Slack, WhatsApp, Discord, and Telegram to CRM systems via webhooks and REST APIs. Classifies intent, extracts structured data, and pushes records to CRM as a side effect of conversations.

### Additional Strong Open-Source Options

- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation with Slack and CRM nodes for custom pipeline alerts and data sync.
- **[Activepieces](https://github.com/activepieces/activepieces)** — Open-source Zapier alternative with Slack + CRM connectors.
- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)** — Mature open-source CRM (AGPL) with webhook support for Slack integration.
- **[EspoCRM](https://github.com/espocrm/espocrm)** — Lightweight open-source CRM with REST API and community Slack connectors.
- **[Krayin CRM](https://github.com/krayin/laravel-crm)** — Laravel-based open-source CRM with extensible API for Slack bots.
- Community **Slack Bolt** projects for building custom CRM bots with Python/Node.js.

**Frameworks for building custom systems**: Combine **Twenty** or **Horilla CRM** as the CRM backend with **Slack Bolt** (Python/Node.js) for bot development, **n8n** or **Activepieces** for workflow automation, and **PostgreSQL** for data persistence — creating a fully self-hosted collaborative CRM in Slack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CRM data in Slack must comply with data protection regulations (GDPR, CCPA, etc.).
- Self-hosted open-source solutions require proper security hardening and maintenance.

---

**Made for sales teams, RevOps professionals, and developers building collaborative CRM solutions.**  
Let's make CRM-in-Slack more open, data-driven, and efficient.
# Awesome-Collaborative-CRM-In-Slack


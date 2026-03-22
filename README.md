# 🧰 Open Source Stack

A curated list of **production-ready open source software** for building, self-hosting, and replacing expensive SaaS.

Every project here is:
- Actively maintained (commits in the last 6 months)
- 1K+ GitHub stars (community-vetted)
- Self-hostable (you own your data)
- Practically useful (solves real business problems)

**Updated daily** via automated discovery.

---

## How to Use This List

**Building a new app?** Check if an open source alternative exists before building from scratch.
**Paying for SaaS?** Find a self-hosted replacement and cut your monthly costs.
**Learning?** Each project links to its repo with full documentation.

---

## Table of Contents

| Category | Projects |
|----------|----------|
| [Scheduling & Booking](#scheduling--booking) | Cal.com |
| [CRM & Sales](#crm--sales) | Twenty |
| [Project Management](#project-management) | Plane |
| [Communication](#communication) | Chatwoot, Fluxer |
| [Analytics & Monitoring](#analytics--monitoring) | Umami, OpenObserve, Web-Check |
| [Content & CMS](#content--cms) | Payload, Directus |
| [E-Commerce](#e-commerce) | Medusa |
| [AI & Machine Learning](#ai--machine-learning) | Dify |
| [DevOps & Infrastructure](#devops--infrastructure) | Dokploy, OpenCTI |
| [Auth & Identity](#auth--identity) | ZITADEL |
| [Forms & Surveys](#forms--surveys) | Formbricks |
| [Email & Marketing](#email--marketing) | Listmonk |
| [Finance & Invoicing](#finance--invoicing) | IDURAR, Invoicerr |
| [Automation & Workflows](#automation--workflows) | n8n |
| [Database & Storage](#database--storage) | Databasus |
| [Developer Tools](#developer-tools) | GitNexus, Yaade |
| [Productivity](#productivity) | AFFiNE, Super Productivity |

---

## Scheduling & Booking

### Cal.com
- **Repo:** [calcom/cal.com](https://github.com/calcom/cal.com)
- **Stars:** 40.5K ⭐
- **Stack:** TypeScript, Next.js, Prisma, PostgreSQL, tRPC, Tailwind CSS
- **License:** AGPLv3 (with commercial license option)
- **What it does:** Open source Calendly alternative. Scheduling infrastructure with full control over data, workflows, and appearance.
- **Key features:**
  - Event types with custom durations, buffers, and limits
  - Team scheduling with round-robin and collective availability
  - Calendar integrations (Google, Outlook, Apple)
  - Payment collection (Stripe)
  - Webhook support and API
  - Embeddable widgets
  - Custom branding
- **Self-host:** Docker, Vercel, Railway — full self-hosting supported
- **Why it's useful:** Replace Calendly/GHL calendars for client booking pages. Already using for Orias bespoke consultations.
- **Added:** 2026-03-14

---

## CRM & Sales

### Twenty
- **Repo:** [twentyhq/twenty](https://github.com/twentyhq/twenty)
- **Stars:** 40.4K ⭐
- **Stack:** TypeScript, NestJS, React, PostgreSQL, Redis, BullMQ, Nx
- **License:** Other (Custom open-source license)
- **What it does:** Modern open-source alternative to Salesforce and HubSpot with full control over customer data and workflows.
- **Key features:**
  - Customizable objects and fields
  - Personalize layouts with filters, sort, group by, kanban and table views  
  - Custom roles and permissions management
  - Workflow automation with triggers and actions
  - Emails, calendar events, and file management
  - GraphQL API and extensible architecture
  - Modern UX inspired by Notion, Airtable, Linear
- **Self-host:** Docker, Kubernetes, or from source with PostgreSQL + Redis
- **Why it's useful:** Perfect Salesforce/HubSpot replacement for agencies needing full data control, customization, and modern UX without vendor lock-in.
- **Added:** 2026-03-14

---

## Project Management

### Plane
- **Repo:** [makeplane/plane](https://github.com/makeplane/plane)
- **Stars:** 46.5K ⭐
- **Stack:** TypeScript, Next.js, Django, PostgreSQL, Redis
- **License:** AGPLv3
- **What it does:** Modern open-source alternative to Jira, Linear, Monday, and ClickUp for issue tracking, sprints, and product roadmaps.
- **Key features:**
  - Issues and task management with rich text editor
  - Sprint cycles and roadmap planning
  - Multiple project views (List, Board, Calendar, Gantt)
  - Custom workflows and automation
  - Team collaboration and mentions
  - Time tracking and estimates
  - File attachments and integrations
- **Self-host:** Docker, Kubernetes, or cloud deployment options
- **Why it's useful:** Replace expensive project management SaaS for agency work. Great Jira alternative with modern UX for managing client projects, sprints, and roadmaps.
- **Added:** 2026-03-14

---

## Communication

### Chatwoot
- **Repo:** [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot)
- **Stars:** 27.9K ⭐
- **Stack:** Ruby on Rails, Vue.js, PostgreSQL, Redis, ActionCable
- **License:** Other (Custom open-source license)
- **What it does:** Open-source omnichannel customer support platform - comprehensive alternative to Intercom, Zendesk, and Salesforce Service Cloud.
- **Key features:**
  - Live chat widget for websites with real-time messaging
  - Multi-channel support (WhatsApp, Facebook, Twitter, Instagram, Email, SMS)
  - Team collaboration with internal notes and mentions
  - Automated workflows and chatbot integration
  - Detailed analytics and reporting dashboard
  - Mobile apps for iOS and Android
  - Custom attributes and conversation labeling
  - API access and webhook integrations
- **Self-host:** Docker, Docker Compose, or Kubernetes with PostgreSQL + Redis
- **Why it's useful:** Essential for agencies providing customer support services to clients. Eliminates expensive monthly fees for Intercom/Zendesk while offering enterprise-grade omnichannel support capabilities.
- **Added:** 2026-03-22

### Fluxer
- **Repo:** [fluxerapp/fluxer](https://github.com/fluxerapp/fluxer)
- **Stars:** 6.7K ⭐
- **Stack:** TypeScript, React, Node.js, Electron
- **License:** AGPL-3.0
- **What it does:** Free and open source instant messaging and VoIP platform built for friends, groups, and communities - alternative to Discord and Slack.
- **Key features:**
  - Real-time messaging and voice/video calls
  - Server and channel organization
  - Custom themes and plugins
  - Cross-platform desktop and mobile apps
  - File sharing and screen sharing
  - Bot support and API access
  - Self-hosted with full data control
- **Self-host:** Docker Compose or from source with Node.js backend
- **Why it's useful:** Perfect Discord/Slack replacement for agencies and teams wanting data sovereignty, custom branding, and no monthly fees. Ideal for client communication hubs.
- **Added:** 2026-03-18

---

## Analytics & Monitoring

### Umami
- **Repo:** [umami-software/umami](https://github.com/umami-software/umami)
- **Stars:** 35.6K ⭐
- **Stack:** TypeScript, Next.js, PostgreSQL, Clickhouse
- **License:** MIT
- **What it does:** Privacy-focused web analytics platform that's a simple, fast alternative to Google Analytics without cookies.
- **Key features:**
  - GDPR, CCPA, and PECR compliant (no cookies)
  - Real-time website analytics and insights
  - Custom events and goal tracking
  - Multiple website management
  - Lightweight tracking script (< 2KB)
  - Beautiful, intuitive dashboard
  - Team sharing and permissions
- **Self-host:** Docker, Docker Compose, or from source with PostgreSQL/MySQL
- **Why it's useful:** Replace Google Analytics for client websites while maintaining privacy compliance and faster page loads. Perfect for agencies managing multiple sites.
- **Added:** 2026-03-14

### OpenObserve
- **Repo:** [openobserve/openobserve](https://github.com/openobserve/openobserve)
- **Stars:** 18.3K ⭐
- **Stack:** TypeScript, Rust, Vue.js, Docker
- **License:** AGPL-3.0
- **What it does:** Open-source observability platform for logs, metrics, traces, and frontend monitoring - cost-effective Datadog/Splunk alternative with 140x lower storage costs.
- **Key features:**
  - Unified logs, metrics, traces, and frontend monitoring
  - Advanced search and query capabilities (SQL + PromQL)
  - Real-time alerting with anomaly detection
  - Stream processing for logs-to-metrics conversion
  - Single binary deployment with no external dependencies
  - Built-in dashboards and visualization
  - Cost-effective storage with compression
- **Self-host:** Single Docker container or Kubernetes deployment
- **Why it's useful:** Perfect Datadog/New Relic replacement for agencies monitoring client applications. Massive cost savings on observability while maintaining enterprise features and performance.
- **Added:** 2026-03-21

### Web-Check
- **Repo:** [Lissy93/web-check](https://github.com/Lissy93/web-check)
- **Stars:** 32.3K ⭐
- **Stack:** TypeScript, Vue.js, Node.js, Docker
- **License:** MIT
- **What it does:** All-in-one OSINT tool for analysing any website - comprehensive security, performance, and infrastructure analysis.
- **Key features:**
  - SSL/TLS certificate analysis and validation
  - DNS records lookup and propagation testing
  - Port scanning and service detection
  - Technology stack identification
  - SEO and accessibility auditing
  - Performance metrics and load time analysis
  - Domain reputation and threat intelligence
  - Whois lookup and domain registration info
- **Self-host:** Docker, Docker Compose, or deploy to Vercel/Netlify
- **Why it's useful:** Essential for website audits, security assessments, and competitive analysis. Perfect for agencies doing technical due diligence and client website evaluations.
- **Added:** 2026-03-19

---

## Content & CMS

### Payload
- **Repo:** [payloadcms/payload](https://github.com/payloadcms/payload)
- **Stars:** 41.2K ⭐
- **Stack:** TypeScript, Next.js, React, MongoDB, PostgreSQL, Express
- **License:** MIT
- **What it does:** Open-source, fullstack Next.js framework giving instant backend superpowers with TypeScript admin panel and headless CMS.
- **Key features:**
  - Next.js native CMS that installs in existing /app folder
  - 100% TypeScript backend and admin panel
  - Works as both app framework & headless CMS
  - Deploy anywhere including serverless on Vercel for free
  - Query database in React Server Components
  - Fully extensible admin and backend
  - No vendor lock-in, self-hosted control
- **Self-host:** Docker, Vercel, Railway, or from source with MongoDB/PostgreSQL
- **Why it's useful:** Perfect modern CMS for client projects. Combines frontend and backend in same codebase, eliminating the need for separate WordPress installations or expensive SaaS CMSs.
- **Added:** 2026-03-16

### Directus
- **Repo:** [directus/directus](https://github.com/directus/directus)
- **Stars:** 34.5K ⭐
- **Stack:** TypeScript, Vue.js, Node.js, SQL databases
- **License:** GPL
- **What it does:** Flexible backend that turns any SQL database into a headless CMS, admin panels, or apps with custom UI and instant APIs.
- **Key features:**
  - Works with existing SQL databases (no migration required)
  - Supports PostgreSQL, MySQL, SQLite, Oracle, MariaDB, MS-SQL
  - Real-time REST & GraphQL APIs
  - Modern Vue.js dashboard for non-technical users
  - Completely white-label and extensible
  - Role-based permissions and authentication
  - File storage and digital asset management
- **Self-host:** Docker, Docker Compose, or from source with any SQL database
- **Why it's useful:** Ideal for agencies working with existing client databases. Can retrofit any legacy database with modern API and admin interface without data migration.
- **Added:** 2026-03-16

---

## E-Commerce

### Medusa
- **Repo:** [medusajs/medusa](https://github.com/medusajs/medusa)
- **Stars:** 32.4K ⭐
- **Stack:** TypeScript, Node.js, React, PostgreSQL, Redis
- **License:** MIT
- **What it does:** Open-source, composable commerce platform with built-in framework for customization - modern alternative to Shopify Plus and Magento.
- **Key features:**
  - Modular architecture with plugins and customizable modules
  - Multi-channel selling (web, mobile, social commerce, marketplaces)
  - Advanced order management and inventory tracking
  - Flexible pricing rules and promotions engine
  - Multi-currency and multi-region support
  - Built-in admin dashboard and customer portal
  - Extensive API for headless commerce setups
  - Integration with payment providers and shipping services
- **Self-host:** Docker, Railway, or deploy to any Node.js hosting provider
- **Why it's useful:** Perfect for building custom e-commerce solutions without the constraints of SaaS platforms. Ideal for agencies creating unique shopping experiences with full control over functionality and data.
- **Added:** 2026-03-19

---

## AI & Machine Learning

### Dify
- **Repo:** [langgenius/dify](https://github.com/langgenius/dify)
- **Stars:** 132.9K ⭐
- **Stack:** TypeScript, Python, Next.js, Flask, PostgreSQL, Redis, Celery
- **License:** Custom open-source (Apache-style with additional terms)
- **What it does:** Production-ready platform for building, deploying, and managing AI applications and agentic workflows with visual canvas.
- **Key features:**
  - Visual workflow builder for AI agent chains
  - Support for 200+ LLM providers (OpenAI, Anthropic, local models)
  - RAG knowledge base with document processing
  - Agent creation with tools and memory
  - API endpoints for AI app integration
  - Model management and prompt engineering
  - Analytics and observability dashboard
- **Self-host:** Docker Compose, Kubernetes, or cloud deployment with PostgreSQL + Redis
- **Why it's useful:** Build AI-powered features for client projects without vendor lock-in. Perfect for creating custom ChatGPT-like apps, knowledge bases, and automated workflows.
- **Added:** 2026-03-16

---

## DevOps & Infrastructure

### Dokploy
- **Repo:** [Dokploy/dokploy](https://github.com/Dokploy/dokploy)
- **Stars:** 31.8K ⭐
- **Stack:** TypeScript, Next.js, Node.js, Docker, PostgreSQL
- **License:** Other (Custom open-source license)
- **What it does:** Open-source deployment platform providing simple PaaS functionality - self-hosted alternative to Vercel, Netlify, and Heroku.
- **Key features:**
  - Git-based deployments with automatic builds
  - Multi-server deployment and management
  - Built-in database support (PostgreSQL, MySQL, MariaDB, MongoDB)
  - Docker Compose and Dockerfile support
  - SSL certificate automation (Let's Encrypt)
  - Real-time deployment monitoring and logs
  - Environment variable management
  - Backup and restore functionality
- **Self-host:** Single Docker container or full installation on VPS with Docker
- **Why it's useful:** Perfect for agencies wanting Heroku-like simplicity without vendor lock-in or monthly costs. Ideal for deploying client applications with full control over infrastructure and zero platform fees.
- **Added:** 2026-03-22

### OpenCTI
- **Repo:** [OpenCTI-Platform/opencti](https://github.com/OpenCTI-Platform/opencti)
- **Stars:** 9.0K ⭐
- **Stack:** TypeScript, React, Python, GraphQL, ElasticSearch, Redis
- **License:** Other (Apache 2.0 style)
- **What it does:** Open cyber threat intelligence platform for managing and analyzing security threats, vulnerabilities, and indicators of compromise.
- **Key features:**
  - STIX 2.1 compliant threat intelligence modeling
  - Real-time data ingestion from multiple threat feeds
  - Interactive knowledge graph visualization
  - Collaborative threat analysis and reporting
  - Automated threat hunting and detection rules
  - Integration with SIEM and security tools via APIs
  - Multi-tenancy and role-based access control
  - Import/export capabilities for threat data sharing
- **Self-host:** Docker Compose with ElasticSearch, Redis, and MinIO
- **Why it's useful:** Essential for agencies handling cybersecurity consulting or managing security infrastructure. Provides enterprise-grade threat intelligence capabilities without expensive commercial tools.
- **Added:** 2026-03-19

---

## Auth & Identity

### ZITADEL
- **Repo:** [zitadel/zitadel](https://github.com/zitadel/zitadel)
- **Stars:** 13.3K ⭐
- **Stack:** Go, TypeScript, Angular, PostgreSQL, gRPC, REST APIs
- **License:** AGPL-3.0 (with Apache 2.0/MIT exceptions)
- **What it does:** Open-source identity and access management platform built for teams needing enterprise-grade authentication with multi-tenancy.
- **Key features:**
  - SSO, MFA, Passkeys (FIDO2), OIDC, SAML, SCIM support
  - Native multi-tenancy with infrastructure-level isolation
  - Comprehensive audit trail with event-driven architecture
  - API-first design with gRPC, connectRPC, and REST
  - Zero-downtime updates and horizontal scalability
  - Custom branding and B2B organization management
  - Actions/webhooks for token enrichment and workflows
- **Self-host:** Docker, Kubernetes, or Docker Compose with PostgreSQL
- **Why it's useful:** Perfect Auth0/Okta replacement for agencies building B2B SaaS. Handles complex multi-tenant authentication, SSO, and identity brokering without vendor lock-in.
- **Added:** 2026-03-20

---

## Forms & Surveys

### Formbricks
- **Repo:** [formbricks/formbricks](https://github.com/formbricks/formbricks)
- **Stars:** 12.0K ⭐
- **Stack:** TypeScript, Next.js, React, Prisma, PostgreSQL, Tailwind CSS
- **License:** Custom open-source (AGPL-style)
- **What it does:** Open source Qualtrics alternative for in-app, website, link and email surveys with privacy-first experience management.
- **Key features:**
  - In-app surveys triggered by user actions
  - Website overlay surveys and popups
  - Email and link surveys with beautiful templates
  - Real-time response analytics and insights
  - GDPR compliant data collection
  - Custom branding and white-label options
  - Webhook integrations and API access
- **Self-host:** Docker, Kubernetes, or from source with PostgreSQL
- **Why it's useful:** Perfect Typeform/Qualtrics replacement for client feedback collection, NPS surveys, and user research. Essential for gathering insights without expensive monthly fees.
- **Added:** 2026-03-16

---

## Email & Marketing

### Listmonk
- **Repo:** [knadh/listmonk](https://github.com/knadh/listmonk)
- **Stars:** 19.3K ⭐
- **Stack:** Go, PostgreSQL, Vue.js
- **License:** AGPL-3.0
- **What it does:** High-performance, self-hosted newsletter and mailing list manager packed into a single binary application.
- **Key features:**
  - Manage millions of subscribers with custom attributes
  - Beautiful responsive email templates
  - Campaign scheduling and automation
  - A/B testing and analytics
  - Bounce and complaint handling
  - Multi-list management with segmentation
  - REST API and webhook support
- **Self-host:** Single binary + PostgreSQL, Docker, or Docker Compose
- **Why it's useful:** Perfect Mailchimp/ConvertKit replacement for client newsletters and email marketing. No monthly fees, full data control, and handles large subscriber lists efficiently.
- **Added:** 2026-03-16

---

## Finance & Invoicing

### IDURAR
- **Repo:** [idurar/idurar-erp-crm](https://github.com/idurar/idurar-erp-crm)
- **Stars:** 8.3K ⭐
- **Stack:** JavaScript, React, Node.js, MongoDB, Express, Ant Design
- **License:** AGPL-3.0
- **What it does:** Comprehensive open-source ERP/CRM system with accounting, invoicing, inventory, and HR management - complete business management solution.
- **Key features:**
  - Integrated CRM with lead and customer management
  - Professional invoicing and quotation system
  - Inventory and warehouse management
  - Accounting and financial reporting
  - HR management with employee records
  - Project management and time tracking
  - Multi-currency and tax support
- **Self-host:** Docker, MERN stack deployment with MongoDB
- **Why it's useful:** All-in-one business management for agencies - replaces multiple SaaS tools with single integrated platform. Perfect for growing businesses needing ERP capabilities without enterprise pricing.
- **Added:** 2026-03-21

### Invoicerr
- **Repo:** [invoicerr-app/invoicerr](https://github.com/invoicerr-app/invoicerr)
- **Stars:** 656 ⭐
- **Stack:** TypeScript, React, NestJS, Prisma, PostgreSQL
- **License:** AGPL-3.0
- **What it does:** Freelance-focused invoicing app that lets you create quotes, generate invoices, track payments, and collect secure signatures.
- **Key features:**
  - Professional quote and invoice creation
  - Digital signature collection
  - Payment tracking and reminders
  - PDF generation and email delivery
  - Client management and contact database
  - Tax calculation and reporting
  - Multi-currency support
- **Self-host:** Docker Compose with PostgreSQL database
- **Why it's useful:** Perfect FreshBooks/QuickBooks alternative for freelance agencies. Eliminate monthly subscription costs while maintaining professional invoicing workflows for client billing.
- **Added:** 2026-03-18

---

## Design & Media

*Coming soon*

---

## Automation & Workflows

### n8n
- **Repo:** [n8n-io/n8n](https://github.com/n8n-io/n8n)
- **Stars:** 179.4K ⭐
- **Stack:** TypeScript, Node.js, Vue.js, SQLite, PostgreSQL
- **License:** Fair-code (sustainable open source)
- **What it does:** Workflow automation platform combining no-code visual interface with full coding capabilities - open source alternative to Zapier, Make, and Microsoft Power Automate.
- **Key features:**
  - 400+ pre-built integrations (Google, Slack, GitHub, AWS, etc.)
  - Visual workflow builder with drag-and-drop interface
  - Write custom JavaScript/Python code when needed
  - Native AI capabilities with LangChain integration
  - Self-hosted with full data control
  - Advanced scheduling and conditional logic
  - Webhook support and REST API access
- **Self-host:** Docker, npm install, or Kubernetes with SQLite/PostgreSQL
- **Why it's useful:** Essential for agency automation - client onboarding, social media posting, data sync between tools, invoice generation. Eliminates expensive Zapier subscriptions while providing more flexibility.
- **Added:** 2026-03-16

---

## Database & Storage

### Databasus
- **Repo:** [databasus/databasus](https://github.com/databasus/databasus)
- **Stars:** 6.1K ⭐
- **Stack:** Go, TypeScript, React, H2, Docker, Kubernetes
- **License:** Apache 2.0
- **What it does:** Free, open-source database backup tool with focus on PostgreSQL, MySQL, MongoDB with smart scheduling and multiple storage options.
- **Key features:**
  - Support for PostgreSQL, MySQL, MariaDB, MongoDB
  - Flexible scheduling (hourly, daily, weekly, monthly, cron)
  - Multiple storage backends (S3, Google Drive, FTP, local, Rclone)
  - Smart retention policies (time-based, count-based, GFS)
  - AES-256-GCM encryption with zero-trust storage
  - Real-time notifications (Email, Telegram, Slack, Discord)
  - Multi-workspace organization with role-based permissions
- **Self-host:** Docker, Docker Compose, or Kubernetes deployment
- **Why it's useful:** Essential for agencies managing client databases. Automated backups with enterprise features, encryption, and notifications - eliminates manual backup processes and reduces data loss risk.
- **Added:** 2026-03-20

---

## Developer Tools

### GitNexus
- **Repo:** [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)
- **Stars:** 16.6K ⭐
- **Stack:** TypeScript, Next.js, React, D3.js, Web Workers
- **License:** Other (Open Source)
- **What it does:** Zero-server code intelligence engine that runs entirely in your browser - drop in a GitHub repo or ZIP file and get an interactive knowledge graph with built-in Graph RAG Agent.
- **Key features:**
  - Client-side knowledge graph generation (no server needed)
  - Interactive code visualization and exploration
  - Built-in Graph RAG Agent for code Q&A
  - Works with GitHub repos or ZIP files
  - Real-time dependency analysis and relationships
  - AI-powered code understanding and navigation
  - Zero data sharing - everything runs locally
- **Self-host:** Deploy static Next.js app to any hosting provider
- **Why it's useful:** Essential for code reviews, onboarding new developers, and understanding large codebases. Perfect for agencies working on complex client projects - no server setup required.
- **Added:** 2026-03-18

### Yaade
- **Repo:** [EsperoTech/yaade](https://github.com/EsperoTech/yaade)
- **Stars:** 2.0K ⭐
- **Stack:** TypeScript, React, Kotlin, H2 Database, Vite
- **License:** MIT
- **What it does:** Open-source, self-hosted, collaborative API development environment - secure Postman alternative with team sharing and authentication.
- **Key features:**
  - Multi-user support with authentication and permissions
  - REST and WebSocket testing with Markdown documentation
  - JavaScript scripting for pre/post request automation
  - Import/export from Postman and OpenAPI collections
  - Browser extension for CORS proxy functionality
  - Single-file data import/export for easy backups
  - Dark mode and responsive design
- **Self-host:** Docker container with H2 database, no external dependencies
- **Why it's useful:** Perfect Postman replacement for agencies wanting data control and team collaboration. Eliminates monthly subscription costs while providing secure API development environment for client projects.
- **Added:** 2026-03-20

---

## Productivity

### AFFiNE
- **Repo:** [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE)
- **Stars:** 66.4K ⭐
- **Stack:** TypeScript, React, Rust, CRDT, Electron
- **License:** Other (Custom open-source license)
- **What it does:** Next-generation knowledge base that combines docs, whiteboards, and databases in one unified workspace - privacy-first alternative to Notion and Miro.
- **Key features:**
  - Block-based document editor with real-time collaboration
  - Infinite canvas whiteboard for visual planning and brainstorming
  - Database views with tables, kanban boards, and galleries
  - Local-first architecture with offline functionality
  - End-to-end encryption and privacy protection
  - Cross-platform apps (Windows, Mac, Linux, Web, Mobile)
  - Plugin system for extensibility and customization
  - Import from Notion, Markdown, and other formats
- **Self-host:** Docker, Kubernetes, or desktop apps with local storage
- **Why it's useful:** Perfect Notion/Miro replacement for agencies wanting data sovereignty and offline capability. Combines documentation, project planning, and visual collaboration without subscription costs or data privacy concerns.
- **Added:** 2026-03-22

### Super Productivity
- **Repo:** [super-productivity/super-productivity](https://github.com/super-productivity/super-productivity)
- **Stars:** 18.1K ⭐
- **Stack:** TypeScript, Angular, Electron, Node.js
- **License:** MIT
- **What it does:** Advanced todo list app with integrated timeboxing, time tracking, and deep work focus - comprehensive productivity suite for individuals and teams.
- **Key features:**
  - Task management with projects, sub-tasks, and tags
  - Built-in Pomodoro timer and time tracking
  - Calendar integration and timeboxing
  - Jira, GitHub, GitLab, and Trello integrations
  - Anti-procrastination features and break reminders
  - Offline-first with sync via Dropbox/WebDAV
  - Completely privacy-focused (no data collection)
- **Self-host:** Desktop apps (Windows, Mac, Linux), web version, or Docker
- **Why it's useful:** Perfect all-in-one productivity solution for agencies and developers. Eliminates need for multiple task management, time tracking, and focus apps. Great for client work tracking and billable hours.
- **Added:** 2026-03-21

---

## Contributing

This list is maintained by HachiPoppo via daily automated discovery. Projects are evaluated on:
- **Stars:** Minimum 1K+ (indicates community trust)
- **Active development:** Recent commits within last 6 months
- **Self-hostable:** Preference for tools we can run ourselves
- **Practical value:** Must solve a real problem for Vendrato or personal use
- **Stack compatibility:** Preference for TypeScript/Node.js/Python ecosystem

---

## Contributing

Found a great open source project? Open a PR or issue with:

1. **Project name** and GitHub link
2. **Stars count** and license
3. **One-line description** of what it does
4. **Why it's useful** — what SaaS does it replace?

### Criteria

- 1K+ GitHub stars
- Active development (commits within last 6 months)
- Self-hostable
- Clear documentation
- Solves a real problem

### What We Don't Include

- Abandoned projects (no commits in 6+ months)
- Libraries/frameworks (this is for end-user applications)
- Projects without self-hosting option
- Crypto/blockchain projects (unless they solve a non-crypto problem)

---

## License

This list is [MIT licensed](LICENSE). The listed projects have their own licenses — check each repo.

---

**Maintained by [Vendrato](https://vendrato.com)** — We use these tools to build digital systems for businesses.

If you find this useful, give it a ⭐

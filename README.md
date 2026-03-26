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
| [Analytics & Monitoring](#analytics--monitoring) | Umami, OpenObserve, Web-Check, Kener |
| [Content & CMS](#content--cms) | Payload, Directus |
| [E-Commerce](#e-commerce) | Medusa |
| [AI & Machine Learning](#ai--machine-learning) | Dify, Mem0, OpenViking |
| [DevOps & Infrastructure](#devops--infrastructure) | Dokploy, Coolify, OpenCTI |
| [Auth & Identity](#auth--identity) | ZITADEL |
| [Forms & Surveys](#forms--surveys) | Formbricks |
| [Email & Marketing](#email--marketing) | Listmonk |
| [Finance & Invoicing](#finance--invoicing) | IDURAR, Invoicerr, TaxHacker, ERPNext |
| [Automation & Workflows](#automation--workflows) | n8n |
| [Database & Storage](#database--storage) | NocoDB, PocketBase, MinIO, Databasus |
| [Developer Tools](#developer-tools) | GitNexus, Yaade, Refine, OpenWork, Gogs, Tabby |
| [Productivity](#productivity) | AFFiNE, Super Productivity, SiYuan |
| [Emergency & Preparedness](#emergency--preparedness) | Project N.O.M.A.D |

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

### Kener
- **Repo:** [rajnandan1/kener](https://github.com/rajnandan1/kener)
- **Stars:** 4.8K ⭐
- **Stack:** Svelte, SvelteKit, Node.js
- **License:** MIT
- **What it does:** Modern self-hosted status page system with beautiful UI - lightweight alternative to StatusPage and Uptime Kuma.
- **Key features:**
  - Beautiful, responsive status page design
  - Real-time monitoring with automated checks
  - Custom domain and branding support
  - Incident management and notifications
  - Historical uptime statistics and reporting
  - Multi-language support
  - API for external integrations
  - Minimal resource usage with fast loading
- **Self-host:** Docker, Node.js, or deploy to Vercel/Netlify
- **Why it's useful:** Perfect for agencies managing multiple client services. Create professional status pages that build customer confidence and reduce support tickets during outages.
- **Added:** 2026-03-24

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

### Mem0
- **Repo:** [mem0ai/mem0](https://github.com/mem0ai/mem0)
- **Stars:** 51.0K ⭐
- **Stack:** Python
- **License:** Apache 2.0
- **What it does:** Universal memory layer for AI agents and assistants, enabling personalized and context-aware AI interactions through intelligent long-term memory management.
- **Key features:**
  - Multi-level memory (user, session, agent-specific)
  - 26% accuracy improvement over OpenAI Memory
  - Hybrid database approach for scalable memory retrieval
  - Cross-platform memory persistence and synchronization
  - Memory analytics with TTL, size, and access tracking
  - SOC 2 & HIPAA compliance with BYOK (Bring Your Own Keys)
  - Integration with major LLM providers
  - Personalized AI experiences without vendor lock-in
- **Self-host:** Python package with local or cloud database backends
- **Why it's useful:** Essential for agencies building personalized AI assistants and chatbots. Eliminates expensive memory-as-a-service costs while providing enterprise-grade memory capabilities for client AI applications.
- **Added:** 2026-03-26

### OpenViking
- **Repo:** [volcengine/OpenViking](https://github.com/volcengine/OpenViking)
- **Stars:** 19.3K ⭐
- **Stack:** Python, FastAPI, PostgreSQL, Redis, Vector databases
- **License:** Apache 2.0
- **What it does:** Open-source context database designed specifically for AI agents, unifying the management of context (memory, resources, and skills) through a file system paradigm.
- **Key features:**
  - File system paradigm for organizing AI agent context and resources
  - Hierarchical context delivery with inheritance and scoping
  - Self-evolving knowledge base with automated context updates
  - Integration with OpenClaw and other AI agent frameworks
  - Multi-modal context storage (text, images, documents, code)
  - Vector-based semantic search and retrieval
  - Plugin system for extending functionality
  - RESTful API for programmatic access and management
- **Self-host:** Docker Compose with PostgreSQL, Redis, and vector database backends
- **Why it's useful:** Perfect for agencies building complex AI agent systems that need persistent context and memory. Eliminates vendor lock-in for AI memory services while providing advanced context management for sophisticated AI workflows.
- **Added:** 2026-03-27

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

### Coolify
- **Repo:** [coollabsio/coolify](https://github.com/coollabsio/coolify)
- **Stars:** 52.1K ⭐
- **Stack:** PHP, Laravel, Livewire, TailwindCSS, Docker, Alpine Linux
- **License:** Apache 2.0
- **What it does:** Open-source, self-hostable PaaS alternative to Vercel, Heroku & Netlify that lets you easily deploy static sites, databases, full-stack applications and 280+ one-click services.
- **Key features:**
  - Deploy from Git repositories with automatic CI/CD pipelines
  - 280+ pre-configured one-click services (WordPress, PostgreSQL, Redis, etc.)
  - Multi-server management with SSH-based deployment
  - Automatic SSL certificate management with Let's Encrypt
  - Built-in monitoring with resource usage tracking
  - Team collaboration with role-based permissions
  - Webhook support for external integrations
  - Docker Compose support with custom configurations
- **Self-host:** Docker installation on any Linux server with SSH access
- **Why it's useful:** More comprehensive than Dokploy with 280+ services and mature ecosystem. Perfect for agencies managing multiple client applications and databases with enterprise-grade features but self-hosted control.
- **Added:** 2026-03-27

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

### TaxHacker
- **Repo:** [vas3k/TaxHacker](https://github.com/vas3k/TaxHacker)
- **Stars:** 2.2K ⭐
- **Stack:** TypeScript, Next.js, Tailwind CSS, OpenAI/Gemini/Mistral APIs
- **License:** MIT
- **What it does:** Self-hosted AI-powered accounting app that automatically extracts data from receipts, invoices, and PDFs for expense and income tracking.
- **Key features:**
  - AI-powered OCR and data extraction from any document format
  - Multi-language and multi-currency support with automatic conversion
  - Custom AI prompts for extracting specific business data
  - Automatic categorization and item splitting
  - Project-based organization with filtering and reporting
  - Excel/CSV import/export for accountants and tax software
  - Support for multiple AI providers (OpenAI, Google, Mistral)
- **Self-host:** Docker Compose or Node.js with local file storage
- **Why it's useful:** Perfect for agencies and freelancers who need automated expense tracking without paying for Receipt Bank or similar SaaS. Eliminates manual data entry while maintaining full control over financial data.
- **Added:** 2026-03-23

### ERPNext
- **Repo:** [frappe/erpnext](https://github.com/frappe/erpnext)
- **Stars:** 32.4K ⭐
- **Stack:** Python, JavaScript, MariaDB/PostgreSQL, Redis, Node.js
- **License:** GPL-3.0
- **What it does:** Comprehensive open-source ERP system covering accounting, inventory, CRM, project management, and HR - complete NetSuite/SAP alternative.
- **Key features:**
  - Integrated accounting with multi-currency and tax support
  - CRM with lead management and sales pipeline tracking
  - Inventory management with warehouse and stock tracking
  - Project management with time tracking and billing
  - HR management with payroll and leave management
  - Manufacturing and production planning
  - Website and e-commerce integration
  - Workflow automation and custom app development
- **Self-host:** Docker, manual installation with Frappe Bench, or cloud hosting
- **Why it's useful:** Perfect all-in-one business management solution for growing agencies. Replaces multiple expensive SaaS tools (QuickBooks + Salesforce + Asana + HR software) with single integrated platform.
- **Added:** 2026-03-24

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

### NocoDB
- **Repo:** [nocodb/nocodb](https://github.com/nocodb/nocodb)
- **Stars:** 62.5K ⭐
- **Stack:** TypeScript, Node.js, Vue.js, MySQL, PostgreSQL, SQLite
- **License:** AGPL-3.0 (with commercial license option)
- **What it does:** Transforms any database into a smart spreadsheet interface - powerful open-source Airtable alternative with API generation.
- **Key features:**
  - Connect to existing MySQL, PostgreSQL, SQL Server, SQLite databases
  - Automatic REST and GraphQL API generation
  - Spreadsheet-like interface with rich field types
  - Form builder with customizable views and sharing
  - Team collaboration with granular permissions
  - Webhook support and third-party integrations
  - Mobile apps for iOS and Android
  - Import from Airtable, CSV, and Excel files
- **Self-host:** Docker, Docker Compose, or npm installation with any SQL database
- **Why it's useful:** Perfect Airtable replacement for agencies managing client data. Eliminates monthly subscription costs while providing database flexibility and API access. Ideal for content management, inventory tracking, and project databases.
- **Added:** 2026-03-25

### PocketBase
- **Repo:** [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase)
- **Stars:** 57.1K ⭐
- **Stack:** Go, JavaScript, SQLite
- **License:** MIT
- **What it does:** Complete backend-as-a-service in a single executable file - open-source Firebase alternative with real-time database, auth, and file storage.
- **Key features:**
  - Embedded SQLite database with real-time subscriptions
  - Built-in authentication with OAuth2 providers
  - File storage with image resizing and optimization
  - Admin dashboard for data management
  - REST and real-time APIs out of the box
  - Custom business logic with JavaScript hooks
  - Single binary deployment with no dependencies
  - Backup and migration tools included
- **Self-host:** Single executable file, Docker, or compiled from source
- **Why it's useful:** Perfect Firebase/Supabase alternative for agencies building modern apps. Eliminates vendor lock-in and monthly costs while providing all essential backend services. Ideal for rapid prototyping and production apps.
- **Added:** 2026-03-25

### MinIO
- **Repo:** [minio/minio](https://github.com/minio/minio)
- **Stars:** 60.5K ⭐
- **Stack:** Go
- **License:** AGPL-3.0 (with commercial license option)
- **What it does:** High-performance, S3-compatible object storage server for massive scale data infrastructure and machine learning workloads.
- **Key features:**
  - 100% S3 API compatibility for drop-in replacement
  - Distributed storage with erasure coding
  - Built-in encryption and immutable object locking
  - Policy-based IAM with fine-grained access control
  - Multi-site replication and versioning
  - Kubernetes native with CSI driver
  - Web console for administration and monitoring
  - Lambda compute for event-driven processing
- **Self-host:** Docker, Kubernetes, or binary deployment with minimal hardware requirements
- **Why it's useful:** Essential S3 replacement for agencies managing large files, backups, and media assets. Eliminates AWS storage costs while maintaining compatibility with existing S3 tools and workflows. Perfect for data lakes and content delivery.
- **Added:** 2026-03-25

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

### Refine
- **Repo:** [refinedev/refine](https://github.com/refinedev/refine)
- **Stars:** 34.3K ⭐
- **Stack:** TypeScript, React, Next.js, Various UI libraries (Ant Design, Material UI, Mantine, Chakra UI)
- **License:** MIT
- **What it does:** React meta-framework for building CRUD-heavy applications like admin panels, dashboards, and B2B internal tools with headless architecture.
- **Key features:**
  - Built-in authentication, access control, and routing
  - Works with any backend (REST, GraphQL, custom APIs)
  - Supports multiple UI frameworks and custom designs
  - Real-time capabilities and i18n internationalization
  - Advanced data provider system with caching
  - Code generation and CLI scaffolding
  - Extensible plugin architecture
- **Self-host:** Deploy anywhere React runs - Vercel, Netlify, Docker, or traditional hosting
- **Why it's useful:** Perfect for agencies building custom admin dashboards and internal tools for clients. Eliminates months of boilerplate development while maintaining full customization control. Great alternative to low-code platforms with developer flexibility.
- **Added:** 2026-03-23

### OpenWork
- **Repo:** [different-ai/openwork](https://github.com/different-ai/openwork)
- **Stars:** 12.2K ⭐
- **Stack:** TypeScript, React, Node.js, Electron, OpenCode
- **License:** Other (Open source with custom terms)
- **What it does:** Open-source AI coworker platform and desktop app - self-hosted alternative to Claude Cowork for teams building agentic workflows.
- **Key features:**
  - Local-first desktop app with instant message processing
  - Agent orchestration with custom skills and MCPs
  - Multi-platform connectors (WhatsApp, Slack, Telegram)
  - Composable architecture - use CLI, desktop, or server mode
  - Shareable workspace instances for team collaboration
  - Built on OpenCode for extensibility and ejectable workflows
  - Support for multiple AI providers and models
- **Self-host:** Desktop app, Docker containers, or npm global install for CLI orchestrator
- **Why it's useful:** Essential for agencies building AI-powered workflows and automation. Provides enterprise-grade AI collaboration without vendor lock-in or monthly fees. Perfect for productizing agentic processes and sharing AI capabilities across teams.
- **Added:** 2026-03-23

### Gogs
- **Repo:** [gogs/gogs](https://github.com/gogs/gogs)
- **Stars:** 47.6K ⭐
- **Stack:** Go
- **License:** MIT
- **What it does:** Painless self-hosted Git service for hosting repositories, managing code, and team collaboration - lightweight GitHub alternative.
- **Key features:**
  - Fast, simple Git repository hosting
  - Web-based repository management interface
  - User and organization management
  - Issue tracking and wiki functionality
  - Webhook support for CI/CD integration
  - LDAP/AD authentication support
  - Cross-platform single binary deployment
  - Low resource requirements
- **Self-host:** Single binary executable, Docker, or from source
- **Why it's useful:** Perfect for agencies wanting private Git hosting without GitHub costs or external dependencies. Ideal for client projects requiring code repository control and team collaboration.
- **Added:** 2026-03-24

### Tabby
- **Repo:** [TabbyML/tabby](https://github.com/TabbyML/tabby)
- **Stars:** 33.1K ⭐
- **Stack:** Rust
- **License:** Other (Custom open-source license)
- **What it does:** Self-hosted AI coding assistant offering open-source alternative to GitHub Copilot with full data control and privacy.
- **Key features:**
  - Code completion and suggestions powered by local LLMs
  - Support for multiple programming languages
  - IDE integrations (VS Code, JetBrains, Vim, Emacs)
  - Repository-aware context and suggestions
  - Team collaboration with shared models and settings
  - Analytics and usage tracking dashboard
  - Custom model fine-tuning capabilities
  - Enterprise-grade security and compliance
- **Self-host:** Docker, Kubernetes, or binary installation with GPU support
- **Why it's useful:** Perfect GitHub Copilot replacement for agencies wanting AI-powered coding assistance without data privacy concerns. Eliminates monthly subscription costs while providing customizable AI coding support for development teams.
- **Added:** 2026-03-26

---

## Emergency & Preparedness

### Project N.O.M.A.D
- **Repo:** [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)
- **Stars:** 13.1K ⭐
- **Stack:** TypeScript, Next.js, Node.js, Offline-first architecture
- **License:** Apache 2.0
- **What it does:** Self-contained, offline survival computer packed with critical tools, knowledge, and AI for emergency preparedness and off-grid scenarios.
- **Key features:**
  - Completely offline operation with local AI models
  - Emergency communication tools and protocols
  - Survival guides and knowledge databases
  - Weather monitoring and alert systems
  - Medical reference and first aid information
  - Food and water safety calculators
  - Power management and battery optimization
  - Portable deployment on Raspberry Pi or laptops
- **Self-host:** Docker, single-board computers (Raspberry Pi), or laptop installation
- **Why it's useful:** Essential for agencies and individuals needing emergency preparedness. Provides critical information and tools when internet/power infrastructure fails. Perfect for remote locations, disaster recovery, and business continuity planning.
- **Added:** 2026-03-24

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

### SiYuan
- **Repo:** [siyuan-note/siyuan](https://github.com/siyuan-note/siyuan)
- **Stars:** 42.1K ⭐
- **Stack:** TypeScript, Go, Electron
- **License:** AGPL-3.0
- **What it does:** Privacy-first, self-hosted personal knowledge management system with block-level reference and Markdown WYSIWYG editing.
- **Key features:**
  - Block-based note-taking with bi-directional linking
  - Markdown WYSIWYG editor with live preview
  - Full-text search with advanced query syntax
  - Data synchronization via S3, WebDAV, or local networks
  - Plugin system for extensibility and customization
  - Multi-platform support (Windows, Mac, Linux, Android, iOS)
  - OCR support for extracting text from images
  - Local-first architecture with offline functionality
- **Self-host:** Desktop applications, Docker, or mobile apps with self-hosted sync
- **Why it's useful:** Perfect Notion/Obsidian alternative for agencies and individuals wanting complete data ownership. Ideal for knowledge management, project documentation, and team collaboration without vendor lock-in or monthly fees.
- **Added:** 2026-03-26

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

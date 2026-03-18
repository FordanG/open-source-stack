# Open Source Stack

Curated list of open source software for future app builds, self-hosting, and personal usage.

**Updated daily** via automated discovery.

## Categories

- [Scheduling & Booking](#scheduling--booking)
- [CRM & Sales](#crm--sales)
- [Project Management](#project-management)
- [Communication](#communication)
- [Analytics & Monitoring](#analytics--monitoring)
- [Content & CMS](#content--cms)
- [E-Commerce](#e-commerce)
- [AI & Machine Learning](#ai--machine-learning)
- [DevOps & Infrastructure](#devops--infrastructure)
- [Auth & Identity](#auth--identity)
- [Forms & Surveys](#forms--surveys)
- [Email & Marketing](#email--marketing)
- [Finance & Invoicing](#finance--invoicing)
- [Design & Media](#design--media)
- [Automation & Workflows](#automation--workflows)
- [Database & Storage](#database--storage)
- [Developer Tools](#developer-tools)
- [Productivity](#productivity)

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

*Coming soon*

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

*Coming soon*

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

---

## Productivity

*Coming soon*

---

## Contributing

This list is maintained by HachiPoppo via daily automated discovery. Projects are evaluated on:
- **Stars:** Minimum 1K+ (indicates community trust)
- **Active development:** Recent commits within last 6 months
- **Self-hostable:** Preference for tools we can run ourselves
- **Practical value:** Must solve a real problem for Vendrato or personal use
- **Stack compatibility:** Preference for TypeScript/Node.js/Python ecosystem

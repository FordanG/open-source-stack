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

*Coming soon*

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

---

## Content & CMS

*Coming soon*

---

## E-Commerce

*Coming soon*

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

*Coming soon*

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

*Coming soon*

---

## Design & Media

*Coming soon*

---

## Automation & Workflows

*Coming soon*

---

## Database & Storage

*Coming soon*

---

## Developer Tools

*Coming soon*

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

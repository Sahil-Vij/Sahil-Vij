# Sahil Vij

Full-stack developer with 3+ years building and running production systems for a group of Indian commerce brands: web and
mobile apps, internal tools, AI assistants and data pipelines. I started in mechanical engineering and moved into software.

## Production work

Most of this is in private company repos, so here's what each system does:

- **AI business assistant:** a company-wide assistant in Slack that answers questions on sales, stock, margin, marketing
  and customers from live warehouse data. Built with a Node/TypeScript orchestrator, Claude tool calling, role-based tool
  access, an append-only audit log, and pgvector search over reviews and policies.
- **Order management system:** a Postgres-backed system and dashboard for booking couriers, tracking shipments, store
  pickup and cancellations, kept in sync with the store and shipping provider. Booking is idempotent, so a retry can't
  charge twice.
- **Customer CRM:** customer profiles, visit history and segments, with search, role-based logins and an outreach
  campaign measured against a holdout group.
- **AI shopping chat:** a streaming storefront assistant live on two stores, with product search, order lookup, human
  handoff and daily spend caps.
- **Marketplace website:** feature work on a server-rendered React marketplace, including buyer-posted project photos with
  AI moderation.
- **Data platform:** pipelines from store, ERP, ads and analytics sources into BigQuery, with AI categorisation of 4,889
  SKUs and KPI dashboards with per-person access.
- **Commerce automation:** traced 410 oversold units to one misconfigured setting, fixed 1,282 variants in bulk with a
  nightly check, and automated refunds for cancelled orders.

## Building in public

**[hookrelay](https://github.com/Sahil-Vij/hookrelay):** a self-hosted webhook inbox with signature checks, deduplication
and retries that survive restarts. A React dashboard is next.

## Stack

- **Frontend and mobile:** React, server-side rendering, Flutter
- **Backend:** Node.js, TypeScript, Express, Python, microservices
- **Data:** PostgreSQL, MySQL, MongoDB, Redis, BigQuery
- **AI:** Claude API, tool calling, RAG, pgvector
- **Infrastructure:** Docker, AWS, Caddy, CI/CD
- **Analytics:** Mixpanel, GA4, RudderStack

## Contact

Open to SDE-2 roles and freelance full-stack work.

[LinkedIn](https://www.linkedin.com/in/sahil-vij-4347b26a/) · er.sahilvij910@gmail.com

# Kaka Alfuna Zhafran

Backend and AI systems engineer. I build LLM features and high-concurrency systems that hold up in production.

Based in Denpasar, Indonesia. [kaka.systemcraft.id](https://kaka.systemcraft.id) · [LinkedIn](https://www.linkedin.com/in/kakaalfuna) · kakaalfuna3@gmail.com

## What I work on

**Monolit Labs** — internal AI tooling and a self-serve diagnostic product. A conversion-audit tool that renders a submitted URL in a pooled Chromium instance, splits it into sections through deterministic DOM analysis, then runs Lighthouse, a structural checker, and one vision-LLM pass over the section screenshots. Redis and BullMQ for the queue. The interesting part is what it refuses to do: when a page loads without its stylesheets, the model pass is skipped entirely rather than analyzing a broken render and reporting it with confidence.

**Systemcraft.id** — my own practice. Client platforms and the infrastructure under them: a campaign platform for a major commercial bank at 100,000 registered users, AWS ECS with auto-scaling sized to burst traffic, and a CMS replatform from Strapi to Drupal 11 where a facade module served the JSON API shape the frontend already expected, so the existing Next.js app switched over by changing one environment variable.

Before that, two years on global ticketing and event platforms across Australia, Singapore, Malaysia and Indonesia, where ticket-war events were losing transactions to race conditions until the custom Redis distributed lock gave way to a MongoDB replica set with native distributed transactions.

## Stack

**Backend** Go, Node.js, Python, REST, gRPC, microservices, event-driven architecture
**Data** MongoDB (replica sets, distributed transactions), Redis (distributed locks, BullMQ), PostgreSQL
**Cloud** AWS (ECS, EC2, auto-scaling), GCP, Cloudflare Workers, Docker, NGINX, GitHub Actions
**AI systems** LLM and vision-LLM pipelines, retrieval, structured output with schema validation, tool calling, eval sets, CatBoost
**Frontend** Next.js, React, Vue.js, Tailwind

# Eduardo Morillo (Maverick) Portfolio

**Name:** Eduardo Morillo (Maverick)  
**GitHub Username:** [iamaverrick](https://github.com/iamaverrick)

This public repository houses a curated collection of production-quality portfolio projects that demonstrate my end-to-end software engineering capabilities. The goal is to give hiring teams direct insight into how I design, build, test, and deploy modern applications across the stack without exposing any private client work.

---

## Portfolio Blueprint

```
portfolio/
├── README.md
├── apps/
│   ├── web/
│   │   ├── landing/            # Marketing and personal storytelling site (Next.js + Tailwind)
│   │   └── projects/           # Feature-rich product demos (React + Remix/Next.js)
│   ├── backend/
│   │   ├── api-gateway/        # Spring Boot services (Java/Kotlin)
│   │   └── analytics/          # Django/DRF microservice with async workers
│   └── mobile/
│       └── showcase/           # React Native app highlighting reusable modules
├── infrastructure/
│   ├── terraform/
│   │   ├── aws/
│   │   ├── azure/
│   │   └── gcp/
│   └── pipelines/              # CI/CD definitions (GitHub Actions, Jenkins, Argo)
├── shared/
│   ├── packages/               # Reusable libraries (UI kit, data models, utilities)
│   └── docs/                   # Architecture decisions, runbooks, tech notes
└── tests/
    ├── integration/
    └── load/
```

Each sub-project includes a dedicated README covering scope, tech stack, architecture, setup instructions, and validation steps so reviewers can clone and run everything quickly.

---

## Project Pillars

- **Practical breadth:** Showcase modern UI (React, Next.js, Tailwind), backend APIs (Django + DRF, Spring Boot), and cloud infrastructure (Terraform on AWS, Azure, and GCP).
- **Production mindset:** Document architecture decisions (ADR), testing strategies, observability plans, and operational runbooks for every service.
- **Automation first:** Provide GitHub Actions workflows, containerized environments, and IaC to demonstrate DevOps fluency.
- **Quality focus:** Include unit, integration, and end-to-end tests; highlight coverage goals, performance benchmarks, and security scans.
- **Business storytelling:** Frame each app as a solution to a real-world scenario, articulating the stakeholder problem and measurable outcomes.

---

## Initial Project Roadmap

1. **Web Landing Site (Next.js + Tailwind):** Personal narrative, project highlights, live demos, resume download, and contact form integrating with serverless backend.
2. **SaaS Analytics Dashboard (Next.js + Django):** Multi-tenant dashboard with role-based auth, async data ingestion, and rich visualization (React charts).
3. **Workflow Automation API (Spring Boot):** Event-driven microservice with message queues, OpenAPI docs, and comprehensive integration tests.
4. **Cloud Infrastructure:** Terraform modules deploying shared networking, managed databases, and pipelines per provider (AWS, Azure, GCP).
5. **Experimentation / Labs:** Space to explore ML prototypes, edge/workers, or tooling experiments that reinforce adaptability.

---

## How to Navigate

- Start with `apps/web/landing` to understand the personal branding and UX tone.
- Explore backend services under `apps/backend` for API design, data modeling, and integration patterns.
- Review `infrastructure/terraform/*` to see environment provisioning, secrets management patterns, and deployment automation.
- Check `shared/docs` for ADRs, architecture diagrams, and decision logs showing my engineering thought process.
- Inspect `tests/` for reusable testing utilities, C4 diagrams, and load test scripts.

---

## Engineering Practices Highlighted

- Monorepo tooling (Nx/Turborepo) to manage shared packages and consistent build pipelines.
- Strict linting, formatting, and type-checking enforced via pre-commit hooks and CI.
- Containerized dev environments (Docker Compose) and reproducible local setups.
- Observability baked in: distributed tracing, structured logging, metrics dashboards.
- Secure coding: automated dependency scanning, secrets detection, and threat modeling checklists.

---

## Professional Story

> I'm a self-taught full-stack engineer currently working in a craft union role with AT&T. This portfolio demonstrates the depth and polish I bring to software projects—showing how I transform ambiguous problems into reliable, scalable products. By publishing selected, high-quality builds here, I can protect client confidentiality while giving hiring teams proof of execution across frontend, backend, and DevOps domains.

---

## Next Steps & Contact

- Track progress with GitHub Projects/Issues linked per sub-app.
- Record demo walkthrough videos or animated GIFs for each major feature set.
- Publish writeups on architectural tradeoffs, performance improvements, and lessons learned.

**Reach out:**  
Email: [contactme@maverrick.network](mailto:contactme@maverrick.network) *(update with preferred contact)*  
LinkedIn: [linkedin.com/in/maverrick](https://www.linkedin.com/in/maverrick) *(update as needed)*

---

> _"Build with empathy, ship with confidence, document the journey."_ — Maverick

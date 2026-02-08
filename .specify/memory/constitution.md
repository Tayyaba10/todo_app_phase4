<!-- SYNC IMPACT REPORT:
Version change: 3.0.0 → 4.0.0
Modified principles: Added Reproducibility Rule, Governance Enforcement, and Progressive Learning Principle sections
Added sections: Reproducibility Rule, Governance Enforcement, Progressive Learning Principle
Removed sections: None
Templates requiring updates: ✅ .specify/templates/plan-template.md, ✅ .specify/templates/spec-template.md, ✅ .specify/templates/tasks-template.md, ✅ .specify/templates/commands/*.md, ✅ README.md
Follow-up TODOs: None
-->
# Phase IV Todo Chatbot Constitution

## 1️⃣ Project Purpose
Deploy the Phase-3 Todo Chatbot on **local Kubernetes** using **Minikube, Helm Charts, Docker AI, kubectl-ai, and Kagent**, following **spec-driven infrastructure automation** principles.
**Goals:**
- Containerized frontend & backend
- AI-assisted deployment & scaling
- Blueprint-driven, reusable infrastructure
- Observability & health monitoring
- Zero manual coding for deployment
---
## 2️⃣ Governance Principles
1. **Spec-Driven Development:** All infrastructure, deployment, and scaling operations originate from formal specs executed by AI agents.
2. **Agent-Centric Operations:** Each action is performed by a clearly defined agent with specific skills.
3. **Immutable Secrets Policy:** No API keys or secrets in Git history; `.env.example` files use placeholders.
4. **Observability First:** Every deployed service must expose logs and health metrics; agents monitor cluster health.
5. **Reproducibility:** Deployments must be reproducible on any local machine with Docker Desktop + Minikube. Helm charts and blueprints are version-controlled.
---
## 3️⃣ Agents & Responsibilities
| Agent | Responsibilities | Skills |
|-------|-----------------|--------|
| **DevOps Agent** | Kubernetes management, deployment orchestration | `k8s-local-deployment`, `helm-chart-generation`, `ai-k8s-operations` |
| **Docker Agent** | Containerization, Docker AI optimization | `containerize-frontend-backend`, `docker-ai-optimization`, `local-docker-testing` |
| **Infrastructure Agent** | Spec-driven automation, blueprint creation | `spec-driven-infra`, `infra-blueprint-design` |
| **Monitoring Agent** | Observability, logging, health checks | `k8s-health-monitoring`, `observability-basics` |
---
## 4️⃣ Skills Constitution
1. **`k8s-local-deployment`** — Deploy frontend/backend to Minikube, manage replicas & services.
2. **`helm-chart-generation`** — Generate reusable Helm charts, configure `values.yaml`, support rollbacks.
3. **`ai-k8s-operations`** — Pod failure diagnosis, scaling recommendations, service exposure.
4. **`containerize-frontend-backend`** — Generate Dockerfiles for frontend/backend, production-ready multi-stage builds.
5. **`docker-ai-optimization`** — Optimize image size & caching, apply security best practices.
6. **`local-docker-testing`** — Validate containers before Kubernetes deployment.
7. **`spec-driven-infra`** — Translate spec to deployment blueprint, Claude Code powered execution.
8. **`infra-blueprint-design`** — Create reusable Kubernetes + Helm templates, enforce spec compliance.
9. **`k8s-health-monitoring`** — Pod readiness & liveness checks, node resource usage.
10. **`observability-basics`** — Log collection, error tracking, metrics reporting.
---
## 5️⃣ Operating Rules
1. **Skill Execution Rule:** Tasks must execute via AI agent using its designated skill. Manual CLI only as fallback.
2. **Spec Compliance Rule:** Deployments must match spec definitions; specs are versioned & auditable.
3. **Error Handling Rule:** AI agents log and report all errors; monitoring agent reviews post-deployment health.
4. **Secrets Handling Rule:** Secrets must never be committed to Git; use `.env` at runtime and `.env.example` placeholder.
5. **Reproducibility Rule:** All Helm charts, Docker images, and blueprints must be portable for local deployment.
---
## 6️⃣ Governance Enforcement
- **Agent Hierarchy:**
  - DevOps & Docker agents execute deployments
  - Infrastructure agent validates specs & blueprints
  - Monitoring agent ensures cluster stability

- **Audit:** Every skill execution logged; errors trigger automated alerts.
- **AI-Assisted Automation:** kubectl-ai, kagent, Gordon AI enforce zero-manual deployment.

---
## 7️⃣ Progressive Learning Principle
Every deployment iteration captures:
- AI decisions & prompts
- Spec changes & blueprint updates
- Metrics from monitoring agent

Ensures **continuous learning** and **infrastructure reliability**.

**Version**: 4.0.0 | **Ratified**: 2026-01-23 | **Last Amended**: 2026-02-05
# AI Infrastructure Career Transformation Roadmap

**For:** Balvanth Reddy Gandra — Senior Cloud DevOps Engineer (7+ yrs, CDC/federal, T2 Public Trust)
**Created:** July 11, 2026 · **Pace:** 15–20 hrs/week · **Market:** US (commercial + cleared as edge) · **Status:** Employed, applying ASAP

---

## 1. Executive Summary

You are **not** starting from zero — you're starting from about 70%. Your resume already positions you as "AI-enabled," you hold a T2 clearance (a genuine differentiator for cleared AI-infra roles that pay a premium with far less competition), you have tri-cloud experience, and you already have **8 portfolio repos** in `~/Projects/devops-learning/` that map almost 1:1 to the target skill set:

| Existing repo | Maps to target skill |
|---|---|
| `aiops-remediation-engine` | AIOps auto-remediation (flagship #1) |
| `runbook-rag` (on GitHub) | RAG infrastructure assistant (flagship #2) |
| `kube-triage` | K8s incident triage with AI |
| `llm-serving-bench` | LLM serving / inference benchmarking |
| `ai-platform-k8s` | Kubernetes for AI platforms |
| `multicloud-model-gateway` | Multi-cloud AI architecture |
| `tf-risk-review` (on GitHub) | Terraform + AI automation |
| `tokenmeter` | LLM cost optimization / metering |

**The plan in one paragraph:** Over 12 weeks you will (a) deepen and productionize these repos into 2 flagship + 4 supporting projects instead of building new ones, (b) close the real gaps — production LLM serving, vector databases, agent frameworks, GitOps, Prometheus/Grafana, LLM security — through hands-on labs, (c) apply to jobs from **week 2** (your resume is already good enough to start), and (d) publish weekly on GitHub/LinkedIn so recruiters find you. By month 3 you interview as a credible **AIOps / AI Platform Engineer**; by month 6–12 you're competitive for senior AI Infrastructure roles.

**Biggest risks to manage:** (1) breadth — you listed ~19 topic areas; this plan cuts that to one spine (agentic AIOps) with everything else supporting it; (2) resume inflation — a few bullets claim more AI depth than the repos currently prove, so the projects must catch up to the resume fast.

---

## 2. Best Career Path Recommendation

**Primary path: Agentic AIOps / AI-powered Platform Engineering** — AI agents that operate cloud infrastructure (detect, triage, remediate, review, provision).

**Why this and not the alternatives:**

- **AIOps + Agentic AI for DevOps (CHOSEN):** This is your shortest bridge. Your 7 years are *operations* — incident response, Splunk, Lambda auto-remediation, MTTR reduction. Adding LLM agents to that story is an upgrade, not a pivot. It's also where the market is moving (every observability and platform vendor is shipping AI SRE features) and your existing repos already point here.
- **MLOps (secondary, not primary):** Classic MLOps (feature stores, training pipelines, model registries) is a crowded field full of ex-data-engineers, and you'd compete without ML modeling depth. Learn the fundamentals (MLflow, model serving) because job descriptions mix them in, but don't lead with it.
- **AI Infrastructure (GPU/training clusters):** Highest ceiling, but hard to break into without hands-on GPU fleet experience that's difficult to self-teach cheaply. Approach it via inference (vLLM, GPU scheduling on K8s) — that's learnable on rented spot GPUs and covers 80% of "AI Infrastructure Engineer" job posts, which are mostly inference/platform, not training.
- **Cloud AI Architect:** A title you grow into after 1–2 years of hands-on AI infra delivery; targeting it now reads as hand-wavy.
- **Platform Engineering for AI workloads:** This is effectively the same as the chosen path viewed from the hiring manager's side — you'll qualify for these titles automatically.

**Positioning sentence** (use everywhere): *"I build AI agents and platforms that operate cloud infrastructure — AIOps incident remediation, LLM serving on Kubernetes, and AI-assisted IaC — with 7 years of federal-grade DevOps behind it."*

---

## 3. Resume Gap Analysis

### Strengths (keep leading with these)
- 7+ years uninterrupted CDC mission delivery; **T2 Public Trust clearance** (cleared AI roles: less competition, comp premium, your fallback channel).
- Tri-cloud: AWS (deep, incl. GovCloud), Azure (Databricks, Entra ID, Functions), GCP (certified).
- Real IaC depth: Terraform modules, CloudFormation, ARM; CI/CD (Jenkins/Groovy, GitLab, CodePipeline).
- Python/Boto3 automation with measurable ops outcomes (MTTR, drift elimination).
- Observability breadth: Splunk, CloudWatch, New Relic, ELK, X-Ray, OpenTelemetry patterns.
- Security/compliance story: Palo Alto, WAF, NIST alignment, RBAC governance — maps directly to AI governance work.
- Certs: GCP Professional Cloud DevOps, AZ-104, AZ-400, AWS Developer Associate.

### Gaps (in priority order)
1. **Production LLM serving** — no vLLM, TGI, KServe, Triton, GPU scheduling, quantization, batching. This is the #1 differentiator between "DevOps who read about AI" and "AI infra engineer."
2. **Agent frameworks** — resume says "AI-assisted automation" but names no framework (Claude API tool use, LangGraph, MCP, function calling patterns, guardrails/HITL approval gates).
3. **Vector databases in production** — pgvector/Qdrant/OpenSearch: ingestion pipelines, index tuning, hybrid search — not just "RAG-pattern concepts."
4. **GitOps tooling** — "GitOps principles" is a red flag phrase; you need ArgoCD or Flux hands-on.
5. **Prometheus/Grafana** — the de-facto modern stack; you have everything *except* the one every K8s job post lists.
6. **LLMOps/evals** — Langfuse or LangSmith tracing, prompt versioning, eval harnesses, token/cost telemetry.
7. **Kubernetes credential** — experience is real but unverifiable; CKA closes it cheaply.
8. **AI security** — OWASP LLM Top 10, prompt injection defenses, NIST AI RMF (huge for your federal edge).

### Missing ATS keywords
`vLLM · GPU · inference · model serving · KServe · Ray · LangGraph / LangChain · MCP (Model Context Protocol) · function calling · embeddings · pgvector / Qdrant / Pinecone · RAG (production) · Amazon Bedrock / SageMaker · Azure OpenAI / AI Foundry · ArgoCD · Flux · Prometheus · Grafana · Karpenter · OPA / policy-as-code · MLflow · model registry · LLMOps · evals · Langfuse · prompt injection · NIST AI RMF · FinOps for AI · EKS / AKS / GKE (name the managed services explicitly)`

### Roles: now → 6 months → 12 months
- **Closest now:** Senior Cloud/DevOps Engineer (AI-focused teams), Platform Engineer, Cloud Engineer – AI/ML adjacency, **cleared** DevOps/AI-enablement roles (apply immediately).
- **After ~3–6 months (this plan):** AIOps Engineer, AI Infrastructure Engineer (inference/platform), LLMOps Engineer, Platform Engineer – AI/ML workloads, DevOps Engineer – GenAI.
- **After 12 months:** Senior AI Infrastructure Engineer, Senior AI Platform Engineer, Staff Platform Engineer (AI), Lead AIOps/SRE-AI, Cloud AI Architect track.

### Projects/achievements to add (from work you can truthfully claim)
- Quantified Databricks automation (clusters provisioned/week, hours saved).
- The Kinesis/Lambda streaming pipeline → frame throughput and event volume.
- Foundation-model log-triage Lambda → name the model API, quantify alert noise reduction.
- Then progressively add the portfolio flagships as they mature (see §8).

---

## 4. Target Role Roadmap

| Phase | Weeks | You can credibly claim | Apply for |
|---|---|---|---|
| Bridge | 1–2 | Everything current + GitHub portfolio live | Senior DevOps/Platform (AI-adjacent), cleared roles — **start now** |
| Core AI infra | 3–6 | RAG + vector DBs + LLM serving + LLMOps observability | DevOps w/ AI, LLMOps-curious platform roles |
| Agentic | 7–9 | AI agents with guardrails operating infra; AIOps remediation | AIOps Engineer, AI Platform Engineer |
| Production | 10–12 | K8s AI platform, GitOps, AI security, cost governance | AI Infrastructure Engineer, Platform Engineer – AI |
| Months 4–6 | — | CKA + depth, open-source contributions, GPU inference tuning | Senior AI Infrastructure Engineer |

---

## 5. 3-Month Learning Plan (summary — full daily detail in the dashboard)

> **Weekly rhythm (15–20 hrs):** Mon–Fri ≈ 1.5–2 hrs/evening (study + small lab) · Sat ≈ 4–6 hrs (build block) · Sun ≈ 2 hrs (document, publish, apply). Every week ships something public.

### Month 1 — LLM Infrastructure Core
- **W1 – Foundation + launch:** How LLMs actually work (tokens, context, embeddings, inference costs); modern K8s refresh (EKS, Karpenter basics); set up GitHub profile + push all repos; resume v2 out; **start applying to bridge roles.**
- **W2 – LLM serving:** Run models locally (Ollama) and properly (vLLM); understand continuous batching, PagedAttention, quantization (GGUF/AWQ), GPU memory math; benchmark with `llm-serving-bench`; managed alternatives (Bedrock, Azure OpenAI).
- **W3 – RAG + vector databases:** Embeddings, chunking, hybrid search, reranking; pgvector and Qdrant hands-on; productionize `runbook-rag` (eval set, ingestion pipeline, citations).
- **W4 – LLMOps + observability:** Langfuse tracing, prompt versioning, eval harnesses (promptfoo), token/cost telemetry; Prometheus + Grafana properly; wire `tokenmeter` into a real dashboard.
- **Outcome:** You can deploy, serve, retrieve-augment, evaluate, and monitor an LLM system. 2 repos production-grade.

### Month 2 — Agentic AI + AIOps
- **W5 – AIOps foundations:** Anomaly detection on metrics, alert correlation, event-driven remediation patterns; Prometheus alert rules → webhook pipelines; upgrade `kube-triage`.
- **W6 – AI agents:** Claude API tool use / function calling from first principles; agent loops, MCP servers, structured outputs; build a small infra agent (read-only diagnoser) before any write actions.
- **W7 – Agentic remediation (flagship):** `aiops-remediation-engine` v2 — detect → diagnose (agent) → propose fix → **human approval gate** → execute → verify → post-mortem write-up. Guardrails, audit log, rollback.
- **W8 – Terraform + AI + policy:** `tf-risk-review` v2 — AI plan review in CI, OPA/Conftest policy-as-code, cost estimation (Infracost); GitOps with ArgoCD.
- **Outcome:** Flagship #1 demo-able. You speak fluently about agent guardrails, HITL, and blast-radius control — the #1 interview topic for agentic infra.

### Month 3 — Production AI Platform
- **W9 – K8s for AI workloads:** GPU scheduling (device plugin, time-slicing/MIG concepts), KServe or vLLM-on-K8s, autoscaling inference (KEDA/HPA on custom metrics); `ai-platform-k8s` becomes flagship #2 substrate.
- **W10 – CI/CD + GitOps for AI:** Model/prompt deployment pipelines (GitHub Actions → ArgoCD), canary for models, eval-gated deploys; MLflow registry fundamentals.
- **W11 – AI security + governance + cost:** OWASP LLM Top 10, prompt-injection defenses, secrets/identity for agents, NIST AI RMF (federal edge!); FinOps for AI — `tokenmeter` + `multicloud-model-gateway` cost routing.
- **W12 – Capstone + interview blitz:** Polish both flagships, record demos, final resume versions, mock interviews, system-design reps.
- **Outcome:** Full portfolio, interviewing actively for AIOps/AI-infra titles.

### Certifications (only what's worth it)
1. **CKA** (~$395, take in month 4) — highest ROI unverified-skill fixer.
2. **AWS Certified AI Practitioner** (~$100, optional, month 3–4) — cheap ATS keyword coverage; skip if interviews are already flowing.
3. Skip for now: SageMaker specialty, Azure AI Engineer, Terraform Associate (your experience already reads senior).

### Key resources (all free unless noted)
- **LLMs:** Karpathy "Intro to LLMs" + "Let's build GPT" (YouTube); 3Blue1Brown Transformers series.
- **Serving:** vLLM docs; Ollama; Hugging Face inference docs.
- **RAG/vectors:** pgvector README; Qdrant docs + tutorials; Anthropic docs on embeddings/RAG.
- **Agents:** Anthropic "Building Effective Agents" essay; Claude API tool-use docs; MCP docs (modelcontextprotocol.io); LangGraph tutorials.
- **K8s/GitOps:** kubernetes.io; ArgoCD docs; KServe docs; Karpenter docs; killercoda free labs; CKA curriculum.
- **Observability:** Prometheus/Grafana docs; Langfuse docs; promptfoo docs.
- **Security:** OWASP LLM Top 10 (genai.owasp.org); NIST AI RMF; Anthropic usage policies.
- **Paid worth it:** KodeKloud CKA course (~$15–25/mo) or Mumshad's Udemy CKA (~$15 on sale); ~$30–60 total cloud/GPU spend across 3 months (spot GPU rentals via RunPod/Lambda Labs for vLLM labs).

---

## 6. 6-Month Advanced Plan (months 4–6)

- **Month 4:** CKA exam. GPU inference depth — rent A10/A100 spot instances, tune vLLM (tensor parallelism, quantized vs full precision benchmarks, publish results in `llm-serving-bench`). Start open-source contributions.
- **Month 5:** Multi-cloud + hybrid depth — finish `multicloud-model-gateway` (Bedrock + Azure OpenAI + self-hosted vLLM behind one API with cost-aware routing and failover). On-prem story: k3s cluster on your Mac/mini-PC running the same stack — talk track for "hybrid AI."
- **Month 6:** Scale interview prep for senior roles: AI-platform system design (design an internal LLM platform, design an AIOps pipeline for 10k services), staff-level behavioral stories, negotiate offers.
- **Open-source strategy (start month 4):** Pick 2 projects you actually use — recommended: **vLLM** (docs/benchmarks/good-first-issues), **Langfuse or promptfoo** (integrations), or **ArgoCD** (docs). Path: use it in your projects → file quality bug reports with repro → fix docs → small features. 3–5 merged PRs by month 6 beats any cert for senior credibility.

---

## 7. Weekly Execution Schedule

Full day-by-day plan with links and checkboxes lives in the **dashboard** (`dashboard/index.html`). The invariant weekly template:

| Day | Time | What |
|---|---|---|
| Mon | 1.5–2h | New topic: read/watch + notes |
| Tue | 1.5–2h | Lab: follow-along hands-on |
| Wed | 1.5–2h | Lab: rebuild without the tutorial |
| Thu | 1.5–2h | Project: apply the week's topic to your repo |
| Fri | 1–1.5h | Flashcards + 3 interview questions + tidy code |
| Sat | 4–6h | **Build block:** the week's project milestone |
| Sun | 2h | Write README/blog notes · LinkedIn post · **5–10 job applications** · plan next week |

---

## 8. Hands-On Project Portfolio

Strategy: **upgrade what exists** (recruiters can't tell a 3-month-old repo from a new one, but they can tell depth from a hollow tutorial). Each project below lists its resume bullet once it reaches the described state.

### Beginner→Intermediate (weeks 1–5)

**P1 · `runbook-rag` — RAG Infrastructure Assistant** *(exists, on GitHub)*
- **Problem:** On-call engineers lose 20+ min hunting runbooks during incidents.
- **Build to:** FastAPI + pgvector/Qdrant; ingestion pipeline (chunking, metadata); hybrid search + citations; eval set of 25 Q/A pairs with promptfoo scoring; Dockerized; CI running evals on PR.
- **Resume bullet:** "Built a RAG-based runbook assistant (FastAPI, Qdrant, Claude API) with hybrid search and CI-gated retrieval evals, answering on-call queries with cited sources at >85% eval accuracy."
- **LinkedIn angle:** "I gave my runbooks a brain — here's what broke first" (chunking failures make great content).

**P2 · `tokenmeter` — LLM Cost & Usage Telemetry** *(exists)*
- **Problem:** Teams ship LLM features with zero cost visibility; bills surprise everyone.
- **Build to:** Proxy/middleware capturing tokens per request → Prometheus metrics → Grafana dashboard (cost per feature/model/user); budget alert rules.
- **Resume bullet:** "Engineered LLM cost telemetry (Prometheus/Grafana) tracking per-route token spend across providers, with budget alerting — pattern adopted for FinOps-style AI cost governance."

**P3 · `kube-triage` — AI-Assisted K8s Incident Triage** *(exists)*
- **Problem:** First 15 minutes of a K8s incident is repetitive evidence-gathering.
- **Build to:** CLI/bot that collects pod events, logs, restarts, node pressure → LLM produces ranked hypotheses + next diagnostic step; read-only by design; test against 5 seeded failure scenarios (CrashLoopBackOff, OOMKilled, bad image, PVC pending, DNS).
- **Resume bullet:** "Built an AI triage assistant for Kubernetes that auto-collects incident evidence and generates ranked root-cause hypotheses, cutting time-to-first-hypothesis from ~15 min to under 2."

### Advanced (weeks 5–10)

**P4 · `tf-risk-review` — AI Terraform Plan Reviewer** *(exists, on GitHub)*
- **Build to:** GitHub Action: `terraform plan` JSON → OPA/Conftest policy checks + LLM risk narrative (blast radius, security, cost via Infracost) → PR comment; severity gate blocks merge on critical.
- **Resume bullet:** "Shipped an AI-powered Terraform review pipeline (GitHub Actions, OPA, Claude API, Infracost) that annotates every PR with risk analysis and blocks critical misconfigurations pre-merge."

**P5 · `llm-serving-bench` — Inference Benchmarking Harness** *(exists, has Terraform infra)*
- **Build to:** Terraform spins up GPU spot instance → deploys vLLM + Ollama → load-tests (k6/locust) across models/quantizations → publishes latency/throughput/cost-per-1M-tokens tables. This repo is your "I understand GPUs" proof.
- **Resume bullet:** "Benchmarked self-hosted LLM inference (vLLM, quantization variants) on GPU spot infrastructure via Terraform, publishing latency/throughput/cost analyses that inform build-vs-API decisions."

**P6 · `multicloud-model-gateway` — Multi-Cloud LLM Gateway** *(exists)*
- **Build to:** One OpenAI-compatible API fronting Bedrock + Azure OpenAI + self-hosted vLLM; cost-aware routing, failover, rate limits, per-tenant keys, full token telemetry (reuse P2).
- **Resume bullet:** "Designed a multi-cloud LLM gateway (Bedrock, Azure OpenAI, vLLM) with cost-aware routing, failover, and per-tenant usage metering behind a single OpenAI-compatible API."

### Flagships (weeks 7–12, these headline the resume)

**F1 · `aiops-remediation-engine` — Agentic AIOps Remediation** *(exists)*
- **Problem:** Alert → page → human runs the same 6 commands at 3am.
- **Architecture:** Prometheus alerts → webhook → orchestrator → **diagnostic agent** (read-only tools: kubectl, logs, metrics) → remediation proposal → **Slack approval gate** → executor (allow-listed actions only) → verification loop → auto-generated incident report. Audit log of every agent action. Kill switch.
- **Demo:** Seeded chaos (kill a deployment, fill a disk) → watch the agent diagnose, propose, get approval, fix, verify — recorded as a 3-min video.
- **Resume bullet:** "Architected an agentic AIOps remediation system: LLM agents diagnose Prometheus alerts via read-only tooling, propose fixes through human-approval gates, execute allow-listed remediations, and verify recovery — with full audit trails and rollback."

**F2 · `ai-platform-k8s` — Internal AI Platform on Kubernetes** *(exists)*
- **Problem:** Every team wants "an LLM app"; platform team needs paved road, not chaos.
- **Architecture:** EKS/k3s + ArgoCD (GitOps) hosting: vLLM inference service (autoscaled), the RAG service (P1), the gateway (P6), Langfuse, Prometheus/Grafana, secrets via External Secrets, network policies, OWASP-LLM-aligned controls documented against NIST AI RMF.
- **Demo:** `git push` → ArgoCD deploys a new model config → eval gate → canary → dashboards. Architecture diagram in README.
- **Resume bullet:** "Built a GitOps-managed AI platform on Kubernetes (ArgoCD, vLLM, KServe patterns, Langfuse, Prometheus) providing paved-road LLM serving, RAG, observability, and NIST-AI-RMF-aligned security controls."

Every repo gets: architecture diagram (Mermaid), README (problem → architecture → demo GIF → quickstart → design decisions → roadmap), tests, CI badge, MIT license, topics/tags.

---

## 9. GitHub Portfolio Strategy

- **Profile README** (`balvanthreddy/balvanthreddy`): headline = the positioning sentence; pinned 6 = F1, F2, P1, P4, P5, P6; "currently building" section updated monthly; contact + LinkedIn.
- **Repo hygiene:** every repo has description + topics (`aiops`, `llmops`, `kubernetes`, `terraform`, `ai-agents`); badges (CI status, license, language); demo GIF above the fold (use `vhs` or a screen recording); a `docs/decisions.md` with 3–5 real trade-off write-ups — **this is what separates engineers from tutorial-followers.**
- **Commit strategy:** small, real commits with imperative messages ("add approval gate timeout", not "update"); 3–5 commits/week minimum so the contribution graph shows a living engineer; never squash 3 weeks into one "initial commit."
- **Proof of real ability (vs. tutorials):** eval numbers and benchmark tables in READMEs; failure-mode sections ("what broke and why"); issues you file on yourself and close; design-decision docs; a recorded demo. Push the 6 local-only repos to GitHub in week 1 (per your own note, only `runbook-rag` and `tf-risk-review` are pushed — **ask before pushing, per your global preference, but do it**).

---

## 10. LinkedIn Strategy

- **Headline:** `AI Infrastructure & AIOps Engineer | LLM Serving · AI Agents for Cloud Ops · Kubernetes · Terraform | 7+ yrs AWS/Azure/GCP | T2 Public Trust`
- **About (skeleton):** Para 1 — positioning sentence + 7 yrs CDC-scale ops. Para 2 — what you build now (agentic remediation, RAG assistants, LLM platforms) with 2 concrete metrics. Para 3 — clearance + open to AIOps/AI-infra roles. Keyword block at the end.
- **Featured:** F1 demo video, F2 architecture post, GitHub profile, resume.
- **Posting cadence (Sundays, from week 2):** 1 post/week. Month 1 theme: "DevOps engineer learns LLM infra — honestly" (benchmarks, costs, what broke). Month 2: "Agents operating infrastructure" (approval gates, guardrails — spicy, gets engagement). Month 3: "Production AI platform" (architecture diagrams, security). Formula per post: hook (problem) → what you built → 1 surprising number → diagram/GIF → repo link.
- **Recruiter attraction:** turn on Open-to-Work (recruiters only) for the exact target titles; the keyword-loaded headline + weekly posts do most of the work. Engage (comment substantively) on 3–5 posts/week in the AIOps/platform-engineering space.

---

## 11. Resume Rewrite Suggestions

Your current resume is already well-positioned — 80% there. Changes:

- **Summary:** lead with the positioning sentence; drop "Actively implementing AI/ML concepts" (reads as aspirational) in favor of concrete claims once projects mature.
- **Skills — add a dedicated first line:** `AI Infrastructure & LLMOps: vLLM, Amazon Bedrock, Azure OpenAI, RAG (Qdrant/pgvector), LangGraph, MCP, Claude/OpenAI APIs, Langfuse, promptfoo, GPU inference, KServe` and add `ArgoCD, Prometheus, Grafana, OPA, Karpenter` to the DevOps line. Only list what you've actually touched by then — the 12-week plan covers all of these.
- **Experience bullets:** quantify the Databricks and log-triage bullets (numbers, model names). Keep federal/security bullets — they're your differentiator.
- **Projects section:** replace the current three with F1, F2, and P4/P5 as they mature (bullets provided in §8).

**Four role-targeted variants** (same core, reordered emphasis):
1. **AIOps Engineer:** lead with incident/MTTR/observability bullets + F1; keywords: anomaly detection, alert correlation, auto-remediation, SLO, Prometheus.
2. **AI Infrastructure Engineer:** lead with P5/F2, GPU/vLLM/serving keywords, Kubernetes depth, Karpenter, KServe.
3. **DevOps w/ AI specialization:** current resume + new skills line + P4 (Terraform AI review) prominent — lowest-friction variant, use for bridge applications now.
4. **Cloud AI Platform Engineer:** lead with F2 + gateway (P6) + governance/NIST AI RMF; multi-cloud emphasis.

---

## 12. Interview Preparation Plan

(Full Q&A bank + flashcards are in the dashboard.)

- **Technical to master:** K8s (scheduling, autoscaling, networking, debugging — CKA level), Terraform (state, modules, drift, workspaces), LLM serving (batching, KV cache, quantization, GPU memory math), RAG (chunking, hybrid search, eval), agents (tool use, guardrails, MCP), observability (Prometheus/PromQL basics, SLOs, tracing).
- **System design (practice out loud, 4 scenarios):** design an internal LLM platform for 50 teams; design an AIOps auto-remediation pipeline (safety story is the whole answer); design a RAG system over 1M docs; design multi-region model serving with cost controls.
- **Agentic AI architecture questions to expect:** How do you stop an agent from destroying prod? (allow-lists, approval gates, read-only default, audit, blast radius) · How do you evaluate agent reliability? · When agent vs. plain automation? (Answer: deterministic runbook → script; ambiguous diagnosis → agent.)
- **Behavioral:** 8 STAR stories from CDC work (major incident, migration, security finding, cross-team conflict, automation win, failure, mentoring, ambiguity). Write them down in week 10.
- **Take-home patterns:** "Build a service that summarizes alerts" · "Deploy this model on K8s with monitoring" · "Write Terraform for X with CI" — your P1–P6 are literally rehearsals for these.

---

## 13. Job Search Strategy

- **Start applying: week 2** (bridge roles), week 6+ (AIOps/AI-infra titles). You're employed — volume can be moderate but *consistent*: **5–10 tailored applications every Sunday.**
- **Search keywords:** "AIOps", "LLMOps", "AI infrastructure", "ML platform", "GenAI platform engineer", "LLM serving", "AI enablement" + "DevOps AI", and separately on cleared boards: "AI" + "Public Trust".
- **Company tiers:** (1) AI-native infra (Anthropic, OpenAI, Together, Fireworks, Modal, Anyscale — stretch, months 4+); (2) observability/DevOps vendors shipping AI (Datadog, Grafana Labs, PagerDuty, Harness, HashiCorp); (3) cloud providers (AWS, Azure, GCP — solutions/infra roles); (4) AI-adopting enterprises (finserv, health — your CDC health-data story lands well); (5) **federal/GovCon AI** (Booz Allen, Leidos, GDIT, Accenture Federal, Palantir-adjacent) — highest conversion given clearance.
- **Tailoring:** mirror the JD's exact phrases in your top skills line + swap the resume variant; 15 min per application, never spray identical resumes.
- **Networking:** for every application, message 1 engineer or EM at the company (not just recruiters): short, specific, reference their tech ("Saw you run vLLM on EKS — I benchmarked spot-GPU inference recently, wrote it up here"). Recruiter DM template: 2 sentences — positioning sentence + "open to X roles, resume attached, portfolio: link."
- **Transition narrative (rehearse it):** "I've automated cloud operations for 7 years. The tooling changed — the job of making infrastructure reliable and self-healing didn't. I now build that automation with LLM agents, and here's a demo." Never say "pivoting" or "transitioning" — say **"upgrading the same job."**
- **Tracking:** simple sheet (company, role, variant sent, date, contact, status, follow-up date); follow up once at day 7.

---

## 14. Final 30-Day Action Plan

| Days | Actions |
|---|---|
| 1–3 | Push all 6 local repos to GitHub (confirm first) · create profile README · pin repos · LinkedIn headline/About updated |
| 4–7 | Week 1 curriculum (LLM fundamentals + K8s refresh) · resume variant #3 finalized · job-tracking sheet created |
| 8–10 | **First 5–10 applications (bridge roles)** · first LinkedIn post |
| 11–17 | Week 2: vLLM + Ollama labs, GPU memory math · `llm-serving-bench` first benchmark run · post #2 · 5–10 applications |
| 18–24 | Week 3: RAG + Qdrant · `runbook-rag` productionization begins · post #3 · applications |
| 25–30 | Week 4: Langfuse + promptfoo + Prometheus/Grafana · `tokenmeter` dashboard live · post #4 · applications · month-1 retro against dashboard progress |

---

*Track everything in the dashboard: `dashboard/index.html` — weekly tabs, daily topics, links, completion tracking, interview Q&A, and flashcards.*

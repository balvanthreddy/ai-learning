# FAQ

**Who is this for?**
Cloud/DevOps/platform engineers (roughly 2+ years: comfortable with a cloud provider, Docker, some Kubernetes and Terraform) who want to move into AI infrastructure, AIOps, or platform engineering for AI. It is *not* an intro to programming, Kubernetes, or machine learning theory.

**Do I need ML/math background?**
No. This is infrastructure, not model training. You need to understand how models *behave* in production (memory, latency, cost, failure modes) — the 🧠 blocks in [PROJECTS.md](PROJECTS.md) teach exactly that, by analogy to ops concepts you already know.

**How much time?**
15–20 hrs/week for 12 weeks. Less time = stretch the calendar, don't skip builds. Weeks 2, 3, 6, 7 are load-bearing; week 7 is the flagship — never skip it.

**How much money?**
$10–30 total (API calls + ~3 GPU rental hours). See [SETUP.md](SETUP.md). Everything else is free/open source.

**Only know AWS (or only Azure)?**
Fine. The projects are cloud-agnostic (local k3d + Docker) except the multi-cloud gateway week, where you can substitute any two providers you have access to — or one provider + local Ollama.

**Claude API vs OpenAI vs local models?**
The guide uses the Claude API for agent/tool-use labs, but every project speaks OpenAI-compatible APIs too — swap in whatever you have. Local Ollama covers most labs for free.

**No GPU?**
See the bottom of [SETUP.md](SETUP.md) — CPU + small models covers ~95% of the course.

**How do I track progress?**
Use the [live dashboard](https://balvanthreddy.github.io/ai-learning/dashboard/) — progress saves in *your* browser, so anyone can use it. Or fork this repo and host your own copy with GitHub Pages (it's one static file in `dashboard/`).

**Is there a certificate?**
No. The certificate is your GitHub: 6 repos with working demos, benchmark numbers, and a dated journal. In interviews that beats any PDF.

**Something's wrong / I'm stuck / I have a better resource.**
Open an [issue or discussion](../../discussions). PRs welcome.

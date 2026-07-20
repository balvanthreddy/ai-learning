# Setup

Get this done before Week 1. Budget: 1–2 hours.

## You need

| Thing | Why | Cost |
|---|---|---|
| macOS/Linux (or WSL2 on Windows) | all commands assume a unix shell | free |
| Docker Desktop (or Podman) | every project runs in containers | free |
| Python 3.11+ | all project code | free |
| Git + a GitHub account | you'll publish everything you build | free |
| Anthropic API key ([console.anthropic.com](https://console.anthropic.com)) | agents, RAG, triage — the LLM behind everything | ~$5–15 total over 12 weeks |
| k3d (`brew install k3d` / [k3d.io](https://k3d.io)) | local Kubernetes, weeks 5–12 | free |
| RunPod or Lambda Cloud account | ~3 hours of GPU rental, weeks 2 and 9 | ~$2–10 total |
| Ollama ([ollama.com](https://ollama.com)) | free local models, no GPU needed | free |

**Total out-of-pocket for 12 weeks: roughly $10–30.** Set a spend limit on your API key day one — Week 4 teaches you to build the cost dashboard so it never surprises you again.

## Verify

```bash
docker run hello-world
python3 --version          # 3.11+
k3d cluster create test && kubectl get nodes && k3d cluster delete test
ollama run llama3.2:3b "say hi"
```

## API key hygiene

```bash
# in ~/.zshrc — never in a repo
export ANTHROPIC_API_KEY=sk-ant-...
```
Add `.env` to every `.gitignore` before your first commit. Week 11 covers why this matters more for AI systems, not less.

## No GPU?

Fine. Everything runs CPU-only with small models except two optional labs (weeks 2, 9) that use ~$5 of rented spot GPU. The course teaches the GPU *concepts* either way.

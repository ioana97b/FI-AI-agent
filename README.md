# FI - AI Agent

Comparison of 3 approaches to building an AI agent, developed in parallel by separate pairs.

**Deadline:** 31 January 2027

---

## Approaches

| Folder | Approach | Team |
|--------|----------|------|
| `agent-1/` | Joule Web | Ionela, Silvia |
| `agent-2/` | Joule CLI | Andrei, Ioana |
| `agent-3/` | Claude Code | Adrian, Laura |

---

## Repository Structure

```
FI-AI-agent/
├── README.md
├── agent-1/        # Joule Web
├── agent-2/        # Joule CLI
└── agent-3/        # Claude Code
```

---

## Git Workflow

### Branches

| Branch | Purpose |
|--------|---------|
| `main` | Stable, reviewed code only — no direct commits |
| `agent-1` | Integration branch for Joule Web pair |
| `agent-2` | Integration branch for Joule CLI pair |
| `agent-3` | Integration branch for Claude Code pair |

### Day-to-day for each person

1. Always branch off your pair's branch (not `main`):
   ```bash
   git checkout agent-1
   git pull
   git checkout -b agent-1/your-feature
   ```

2. Work and commit regularly:
   ```bash
   git add .
   git commit -m "short description of what you did"
   git push origin agent-1/your-feature
   ```

3. Open a Pull Request from `agent-1/your-feature` → `agent-1` on GitHub and ask your pair to review.

4. Once your approach is complete and tested, open a final PR from `agent-1` → `main` for the team leader to review.

### Rules

- Never commit directly to `main`
- Each PR needs at least 1 approval before merging
- Keep your pair's branch up to date: pull from it regularly to avoid conflicts

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/<your-username>/FI-AI-agent.git
cd FI-AI-agent

# Switch to your pair's branch
git checkout agent-1   # or agent-2 / agent-3
```

---

## Questions?

Reach out to the team leader or open a GitHub Issue in this repo.

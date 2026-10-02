## Hi, I'm Javier

I like taking messy, real-world work and turning it into simple systems that people actually use.

Most of my career has been on the people side of technology. At ServiceNow I helped more than 80 enterprise accounts across the U.S. and Latin America adopt AI. A lot of that job was listening: sitting with teams, understanding how they really work, and finding the places where automation would genuinely make their day better.

Today I learn by building. I use Claude every day, write Python and TypeScript, and connect tools through APIs and no-code automation. Some of what I build is for work, like the projects below. Some of it is just for the people I love, like a [pixel-art game](https://github.com/JavierMonestel/cata-y-andres) I made for my family.

I work in both English and Spanish, and I'm happiest when a tool I built quietly saves someone an hour.

---

### 🧭 Founder OS: a portfolio series

Tools for the chief-of-staff layer of an early-stage health-tech company running **two business lines** (clinical and performance/wellness). Each project is live, tested, and built so the AI is useful *and* checkable.

| Project | What it does | Stack | Try it |
|---|---|---|---|
| **[Founder Command Center](https://github.com/JavierMonestel/founder-command-center)** | One view across both business lines: OKRs vs. cycle timeline, follow-ups that can't fall through the cracks, a decision queue, blockers, and an **AI daily brief**. Quick Capture turns notes into owned, dated tasks. | Next.js 16 · TypeScript · SQLite · Claude | [Live demo ↗](https://founder-command-center-demo.vercel.app) |
| **[Meeting Action Router](https://github.com/JavierMonestel/meeting-action-router)** | Grain-style transcript in → decisions, open questions and **evidence-backed follow-ups** routed to **Linear, Attio, Notion or Calendar**, with the exact API request shown and a human review step. Ships with **evals** (dev + held-out set). | Python · FastAPI · HTMX · Claude | [Live demo ↗](https://meeting-action-router.vercel.app) |
| **[OKR → Linear Planner](https://github.com/JavierMonestel/okr-to-linear)** | Monthly goals → Linear projects and issues with estimates, owners, cycles and dependencies. **Capacity check, bottleneck detection, auto-balance**, then push via the Linear GraphQL API. | Next.js 16 · TypeScript · Linear API · Claude | [Live demo ↗](https://okr-to-linear.vercel.app) |
| **[Calendar Guardian](https://github.com/JavierMonestel/founder-calendar-guardian)** | Audits the founder's week against **operating rules** (focus blocks, meeting caps, buffers, time per business line), scores it, **fixes it in one click**, and finds meeting times **across time zones** with an email draft in the guest's zone. | Next.js 16 · TypeScript · Luxon · Claude | [Live demo ↗](https://founder-calendar-guardian.vercel.app) |
| **[Automation Library](https://github.com/JavierMonestel/founder-os-automations)** | The no-code layer: **6 importable n8n workflows** (Grain → Claude → Linear/Attio/Notion/Slack, daily brief, follow-up radar, investor update, travel), a **one-command Notion company OS**, and a tested prompt library. CI imports every workflow into a real n8n. | n8n · Notion API · Claude · Python | [Catalog ↗](https://founder-os-automations.vercel.app) |
| **[Discovery to Spec](https://github.com/JavierMonestel/discovery-to-spec)** | Customer discovery call → product brief + a ready-to-build Claude skill, with every conclusion backed by a word-for-word quote and **7 automated eval checks**. | Python · Flask · Claude Agent Skills · Slack | [Demo video ↗](https://www.loom.com/share/5ce0f681ca184281bce1251e44b5cc95) |

### 🛠️ How I build

- **Systems over tasks.** If I do something twice, it becomes a workflow, a template, or a tool.
- **Evidence over vibes.** AI output links back to the source quote. Extraction quality is measured with evals, including a held-out set I never tune on.
- **Humans approve, machines type.** Automations dry-run and show exactly what they will send before they touch a real workspace.
- **Single source of truth.** Everything lands in the system the team already lives in: Notion for docs, Linear for work, Attio for relationships.
- **Documented by default.** Every project has a README a teammate can run in five minutes.

### 🧰 Toolstack

**AI:** Claude (API, Claude Code, Agent Skills), prompt design, structured outputs, evals<br>
**Ops stack:** Notion · Linear · Attio · Grain · Slack · Google Workspace<br>
**Automation:** Zapier · Make · n8n · webhooks · REST & GraphQL APIs<br>
**Build:** Python (FastAPI, Flask) · TypeScript (Next.js, React) · SQLite · Vercel · GitHub Actions

---

📫 Open to **AI-native executive assistant, chief-of-staff and AI-operations roles** (remote, U.S. business hours). Bilingual: English / Spanish.

### Hi, I'm Dean 👋

CPA turned software engineer. My background is public accounting and tax (PwC, then CPA consulting). Now I build the tools, and increasingly the *services*, I used to wish existed.

## 🏛️ DCB, an AI-Native Service Company

Not software that *helps* people do the work. Instead, agents that **do the work**, proposing reviewable, deterministic changes a human approves. The thesis: the spend on services dwarfs the spend on software, so the bigger opportunity is to **deliver the service, not sell the tool**. The suite:

- **DCB Practice:** an AI-native accounting firm. Agents run the repetitive firm work (tax prep, bookkeeping, document collection, cleanup, review, close) end to end, humans review and approve. The service, delivered as software.
- **DCB Copilot:** a screen-aware desktop overlay that reads whatever accounting software is on screen and answers in context.
- **DCB Research:** a research platform over SEC filings, XBRL, and federal/state tax sources, the source-data backbone **DCB Public** distills from.
- **DCB Public:** a vetted money & investing knowledge base with a citation-grounded AI advisor.

🛠️ **Stack I reach for**
- **Languages:** TypeScript, Python, Java, Ruby
- **Frontend:** React, Next.js, Vue, Tailwind, Vite
- **Backend:** FastAPI, Flask, Express, Spring Boot, Rails · PostgreSQL, Redis, SQLAlchemy
- **Cloud / infra:** AWS (EC2, RDS, S3, Lambda, VPC), Docker, GitHub Actions, Nginx
- **AI:** LLM agents, tool use, RAG, deterministic pipelines

🎓 M.S. Computer Science, Georgia Tech (OMSCS) · B.S. Accounting (SUNY Binghamton)

🎮 **Between builds:** hacking on a [Castlevania-style HTML-canvas game](https://dingtianding.github.io/Castlevania97/).

📫 **Reach me:** [dingtian.ding@gmail.com](mailto:dingtian.ding@gmail.com) · [LinkedIn](https://linkedin.com/in/deanding) · [Portfolio](https://dingtianding.github.io)

---

## 🗓️ Weekly standup
_Week of Jul 13, 2026_

**Last week**
- **DCB Practice: agents now run unattended and surface work for a human to approve.** Shipped a supervised async agent-job worker (jobs run on their own and propose changes you approve or decline with full trace and replay), then **five jobs** on top of it: missing-document detection, capacity-aware assignment, the **Firm Memory** learning job that turns approved work into reusable know-how (the moat), Client Success follow-up drafts, and a firm-status Operations morning briefing.
- **Filled out the practice-management surface** the agents operate over: client-intake organizers, recurring engagements with a due-runner, a statutory deadline engine, practice analytics, an IRS-notice / tax-resolution workflow, and the Business Formation assistant (EIN/SS-4 drafts, ownership mapper, filing packet). Plus deploy scaffolding (Render blueprint, Docker) and backend + web e2e tests.
- **Relaunched the portfolio (public):** rebuilt dingtianding.github.io with per-product DCB system-design and workflow diagrams and **/ask**, a live "grounded vs guessed" demo of the DCB Public thesis. Shipped **Tape**, a new Angular 19 / RxJS live-markets dashboard.

**This week**
- Take **DCB Public** live on Render and verify the go-live path (carried from last week).
- Grow the **DCB Research** corpus and harden retrieval, the source-data backbone DCB Public distills from.
- Keep feeding **Firm Memory** with real approved sessions now that the learning job is in.
- Dogfood **DCB Copilot** to build up session data.

**Blockers**
- The imitation agent (one that clones how I approach problems) still needs a body of real recorded sessions. The Firm Memory learning job shipped this week is the mechanism, but the training data only accrues with use.

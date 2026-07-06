### Hi, I'm Dean 👋

CPA turned software engineer. My background is public accounting and tax (PwC, then CPA consulting) — now I build the tools, and increasingly the *services*, I used to wish existed.

## 🏛️ DCB — an AI-Native Service Company

Not software that *helps* people do the work — agents that **do the work**, proposing reviewable, deterministic changes a human approves. The thesis: the spend on services dwarfs the spend on software, so the bigger opportunity is to **deliver the service, not sell the tool**. The suite:

- **DCB Practice** — an AI-native accounting firm: agents run the repetitive tax and accounting work end to end, humans review and approve. The service, delivered as software.
- **DCB Copilot** — a screen-aware desktop overlay that reads whatever accounting software is on screen and answers in context.
- **DCB Research** — a research platform over SEC filings, XBRL, and federal/state tax sources; the source-data backbone **DCB Public** distills from.
- **DCB Public** — a vetted money & investing knowledge base with a citation-grounded AI advisor.

## 🗓️ Weekly standup
_Week of Jul 6, 2026_

**Last week**
- Stood up **DCB Research** — renamed from FilingLens into a working corpus platform: semantic search over SEC filings + a federal/state tax corpus, cited summaries on the document detail pane, and an "Ask the corpus" RAG endpoint, with Claude and real embeddings wired behind a BYOK seam.
- Took **DCB Practice** billing-complete — Time & billing shipped end-to-end (time tracking + budgets, invoices/payments, portal billing, invoice-from-logged-time, client retainers), plus a capacity dashboard, engagement-letter proposals with in-app e-signature, and a portal client↔firm secure-message thread; kicked off the **Business Formation Workflow Assistant** (entity intake → EIN → filing packet).
- Got **DCB Public** deploy-ready — Render blueprint + DEPLOY.md, an LLM answer cache and per-user rate limiting, full-text library search, saved question history, and prior-revision history for canonical entries.

**This week**
- Ship **DCB Public** live on Render and verify the go-live path.
- Build out the **Business Formation Workflow Assistant** (open-item tracker, EIN assistant, bilingual client-message generator, filing packet).
- Grow the **DCB Research** corpus and harden retrieval — it's the source-data backbone DCB Public distills from.
- Dogfood **DCB Copilot** to accumulate real session data.

**Blockers**
- The imitation agent (an agent that clones how I approach problems) is gated on accumulating enough real recorded sessions first — no shortcut to the training data.

🛠️ **Stack I reach for**
- **Languages:** TypeScript, Python, Java, Ruby
- **Frontend:** React, Next.js, Vue, Tailwind, Vite
- **Backend:** FastAPI, Flask, Express, Spring Boot, Rails · PostgreSQL, Redis, SQLAlchemy
- **Cloud / infra:** AWS (EC2, RDS, S3, Lambda, VPC), Docker, GitHub Actions, Nginx
- **AI:** LLM agents, tool use, RAG, deterministic pipelines

🎓 M.S. Computer Science, Georgia Tech (OMSCS) · App Academy · B.S. Accounting (SUNY Binghamton)

🏆 1st place, App Academy 2024 Hackathon (Aurora, an AI wellness app) · built Fire Drill XR at MIT Reality Hack 2024

🎮 **Between builds:** hacking on a [Castlevania-style HTML-canvas game](https://dingtianding.github.io/Castlevania97/), and a Kalshi-flavored prediction-market / sports-betting clone.

📫 **Reach me:** [dingtian.ding@gmail.com](mailto:dingtian.ding@gmail.com) · [LinkedIn](https://linkedin.com/in/deanding) · [Portfolio](https://dingtianding.github.io)

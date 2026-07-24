### Hi, I'm Dean 👋

CPA turned software engineer. My background is public accounting and tax (PwC, then CPA consulting). Now I build the tools, and increasingly the *services*, I used to wish existed.

🛠️ **Stack I reach for**
- **Languages:** TypeScript, Python, Java, Ruby
- **Frontend:** React, Next.js, Vue, Tailwind, Vite
- **Backend:** FastAPI, Flask, Express, Spring Boot, Rails · PostgreSQL, Redis, SQLAlchemy
- **Cloud / infra:** AWS (EC2, RDS, S3, Lambda, VPC), Docker, GitHub Actions, Nginx
- **AI:** LLM agents, tool use, RAG, deterministic pipelines

🎓 M.S. Computer Science, Georgia Tech (OMSCS) · B.S. Accounting (SUNY Binghamton)

🧠 **Also building:** [DD-KB](https://github.com/dingtianding/DD-KB-App), an Obsidian personal knowledge base with a dependency-free local RAG engine (BM25 retrieval, cited answers, and an Obsidian sidebar plugin).

🎮 **Between builds:** hacking on a [Castlevania-style HTML-canvas game](https://dingtianding.github.io/Castlevania97/).

📫 **Reach me:** [dingtian.ding@gmail.com](mailto:dingtian.ding@gmail.com) · [LinkedIn](https://linkedin.com/in/deanding) · [Portfolio](https://dingtianding.github.io)

---

## 🏛️ DCB, an AI-Native Service Company
_🚧 What I'm currently working on._

Not software that *helps* people do the work. Instead, agents that **do the work**, proposing reviewable, deterministic changes a human approves. The thesis: the spend on services dwarfs the spend on software, so the bigger opportunity is to **deliver the service, not sell the tool**. The suite:

- **DCB Practice:** an AI-native accounting firm. Agents run the repetitive firm work (tax prep, bookkeeping, document collection, cleanup, review, close) end to end, humans review and approve. The service, delivered as software.
- **DCB Copilot:** a screen-aware desktop overlay that reads whatever accounting software is on screen and answers in context.
- **DCB Research:** a research platform over SEC filings, XBRL, and federal/state tax sources, the source-data backbone **DCB Public** distills from.
- **DCB Public:** a vetted money & investing knowledge base with a citation-grounded AI advisor.

## 🗓️ Weekly standup
_Week of Jul 20, 2026_

**Since the last standup**
- Turned **DCB Practice** from a broad practice-management app into a supervised agent workspace: scheduled deadline, missing-document, capacity-assignment, Firm Memory, client-success, intake, and operations jobs now surface reviewable proposals; an iterative goal-directed loop advances only through the existing approve → execute → audit gate. Added recurring work, organizers, deadlines, notices, reporting, monitoring, staff administration, browser E2E coverage, and separate demo/production deployment paths.
- Made **DCB Research** the suite's shared evidence layer: shipped a versioned, service-authenticated grounding contract with real excerpt citations and PII-safe consumer boundaries, plus company briefs consumed by Public. An eval-gated agentic research loop now reaches **100% retrieval coverage@5 vs. 83% for single-shot RAG** on the same evidence budget.
- Hardened **DCB Copilot** as a native, privacy-conscious CPA overlay: macOS permission and Keychain handling, a PII-safe workpaper fixture, frontend/Rust CI, capture-scaling tests, and authoritative tax grounding from DCB Research instead of rebuilding the corpus locally.
- Advanced **DCB Public** from deploy-ready to a fuller subscription product: permanent shared answers, advisor credits, lead capture, Research-backed market briefs, annual pricing, and Stripe-sourced price display.
- Rebuilt the **portfolio** around the DCB thesis: live `/ask`, a suite one-pager, individual case studies and system diagrams for all four products, clearer privacy/review boundaries, and DD-KB as the supporting Obsidian + local-RAG knowledge system.

**Now**
- Build one end-to-end proof across the suite: Research supplies cited authority → Copilot interprets a fabricated workpaper → Practice receives a proposed review action → a human approves or rejects it with an audit trail.
- Expand Research's gold set beyond the current SEC fixture into tax questions, refusals, freshness, and claim-to-citation checks; deploy it with production embeddings while preserving the deterministic CI baseline.
- Record the 60–90 second Copilot demo and expose observed facts, retrieved authority, model inference, and uncertainty as separate evidence layers.
- Close the Public editorial loop: content-gap question → Research evidence packet → human-reviewed canonical explanation → retrieval regression test.

**Blockers**
- Copilot's imitation agent remains gated on enough real, labeled work sessions; reviewed traces come before training.
- Research generation-quality scoring needs a configured model key, while the retrieval tier remains deterministic and key-free.

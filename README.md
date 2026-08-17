## Jie Sheng Ooi

AI engineer. I ship LLM systems into production and own the data infrastructure underneath them.

**Day job** — I designed, built and operate a multi-channel e-commerce analytics platform: Linnworks → BigQuery pipelines across 7 sales channels, 40,000+ SKUs and 200+ orders a day, feeding a React/Express operations dashboard on Google Cloud Run. Sole engineer on it. Dynamic pricing runs on Vertex AI.

**What I actually care about** — making AI systems that fail honestly.

- **Eval-driven development.** My trading agents are scored by a Postgres-backed harness against golden expectations, and a CI gate blocks any regression below 80%. If a prompt change makes the model worse, the build goes red.
- **Fail-closed data paths.** When a market feed is stale or a field is missing, the analysis stops and names the producer that failed. It does not degrade quietly into a confident wrong answer.
- **Multi-agent orchestration** over a shared state, producing a weighted conviction score rather than a vibe.

### Selected work

| | |
|---|---|
| **AI Market Dashboard** | Multi-agent trading SaaS. Fundamental + technical agents over shared state, LLM-authored daily brief, Neon-backed eval harness with an 80% CI quality gate, live broker feeds behind a fail-closed freshness guard. Private beta — walkthrough on request. |
| **MacroSnap** | Photo-to-macros food tracker. Gemini vision → structured JSON, with a provider-agnostic safety layer that re-checks the 4/4/9 energy identity and downgrades confidence when the model contradicts itself. |
| **[Malaysia SME E-Invoicing Sandbox](https://github.com/js9726/sme-e-invoicing-sandbox)** | Mobile-first LHDN MyInvois compliance flow for micro-SMEs — plain-language templates instead of accounting fields, personal-seller mode for users without SSM registration. |
| **[E-Commerce Ops Dashboard](https://ecommerce-ops-demo.vercel.app)** | Public demo of the operations dashboard, running entirely on synthetic data. |
| **Trading Assistant Skill Suite** | RAG over a 120-page maintained knowledge base, MCP servers, live broker integration. Portable across two different agent harnesses from one authoring source. |

### Stack

`TypeScript` `Python` `SQL` · `Next.js` `React` `Node/Express` `Django` `Flask` · `PostgreSQL` `Prisma` `BigQuery` · `Google Cloud Run` `Vertex AI` `Vercel` `Docker` `GitHub Actions` · `MCP` `RAG` `multi-agent orchestration` `eval harnesses`

📄 **[jiesheng.vercel.app](https://jiesheng.vercel.app)** · 📫 [jiesheng2697@gmail.com](mailto:jiesheng2697@gmail.com)

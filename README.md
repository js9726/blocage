## Jie Sheng Ooi

AI engineer. I build production LLM-assisted systems and own the data infrastructure underneath them.

**Day job** — I designed, built and operate a multi-channel e-commerce analytics platform: Linnworks → BigQuery pipelines across 7 sales channels, 40,000+ SKUs and 200+ orders a day, feeding a React/Express operations dashboard on Google Cloud Run. Sole engineer on it. I use Vertex AI to support dynamic-pricing decisions.

**What I actually care about** — making AI systems that fail honestly.

- **Eval-driven development.** A Neon export path prepares real analysis rows for review, while CI deterministically scores versioned evaluation results and fails below an 80% quality threshold.
- **Fail-closed data paths.** When a market feed is stale or a field is missing, the analysis stops and names the producer that failed. It does not degrade quietly into a confident wrong answer.
- **Role-based analysis pipelines** combine deterministic data/risk checks with LLM-generated analysis to produce a weighted conviction score rather than a vibe.

### Selected work

| | |
|---|---|
| **AI Market Dashboard** | Role-based trading analysis SaaS. Deterministic data/risk checks, LLM-authored daily brief, Neon evaluation-data export, versioned 80% CI quality gate, and live broker feeds behind a fail-closed freshness guard. Private beta — walkthrough on request. |
| **MacroSnap** | Photo-to-macros food tracker. Gemini vision → structured JSON, with a provider-agnostic safety layer that re-checks the 4/4/9 energy identity and downgrades confidence when the model contradicts itself. |
| **[Malaysia SME E-Invoicing Sandbox](https://github.com/js9726/sme-e-invoicing-sandbox)** | Mobile-first LHDN MyInvois compliance flow for micro-SMEs — plain-language templates instead of accounting fields, personal-seller mode for users without SSM registration. |
| **[E-Commerce Ops Dashboard](https://ecommerce-ops-demo.vercel.app)** | Public demo of the operations dashboard, running entirely on synthetic data. |
| **Trading Assistant Skill Suite** | Knowledge-grounded trade analysis over a maintained wiki, with live OpenD broker integration. Portable across Claude Code and Codex from one authoring source. |
| **Malaysia Auction Property Rental-Yield Screener** | Private Python/Selenium research workflow that compares auction properties with rental listings and flags estimated gross yields above 7% for manual review. |

### Stack

`TypeScript` `Python` `SQL` · `Next.js` `React` `Node/Express` `Django` `Flask` · `PostgreSQL` `Prisma` `BigQuery` · `Google Cloud Run` `Vertex AI` `Vercel` `Docker` `GitHub Actions` · `knowledge-grounded LLM workflows` `role-based AI pipelines` `eval harnesses`

📄 **[jiesheng.vercel.app](https://jiesheng.vercel.app)** · 📫 [jiesheng2697@gmail.com](mailto:jiesheng2697@gmail.com)

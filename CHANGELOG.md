# Changelog

## 2.2.0 — 2026-07-19

**Enterprise-grade expansion: strategy frameworks, MarTech architecture, full org-chart
orchestration.**

### Added
- `references/strategy-frameworks.md` — Go-to-Market 5-step framework, Account-Based
  Marketing tiers (1:1 / 1:few / 1:many with air-cover + ground-game doctrine),
  Product-Led Growth and growth loops (viral/content/paid/data), business-model mechanics
  table (B2C impulse → enterprise ABM → marketplace), and customer intelligence (persona
  generation with verbatim-quote rule, segmentation schemes, cohort analysis, health
  scores, identity resolution, Voice-of-Customer mining).
- `references/enterprise-martech.md` — MarTech stack blueprint sized by client tier
  (tag/analytics/CRM/CDP/consent layers; CRM vs CDP vs DMP distinctions), event-tracking
  architecture rules, programmatic advertising plumbing (DSP → exchange/OpenRTB → SSP,
  PMP, header bidding, contextual, CTV, when-it's-worth-it thresholds), retail media
  (Amazon, Walmart Connect, Flipkart, Shopify Audiences), analytics tool map, and a CRO
  deep-dive (research stack, ICE prioritization, LP/form/checkout/offer test playbook).
- Agent orchestrator expanded to the full enterprise org chart (GTM/ABM strategy, customer
  intelligence, MarTech architecture, programmatic & retail media, CRO, social/influencer,
  continuous learning) and **advanced reasoning techniques** (ReAct, tree-of-thought for
  irreversible calls, self-critique, retrieval-before-reasoning, long-term client-playbook
  memory, parallel decomposition).

## 2.1.1 — 2026-07-19

### Added
- **Claude Code plugin marketplace support**: `.claude-plugin/marketplace.json` (repo root)
  and `ad-campaign-director/.claude-plugin/plugin.json`. Install is now:
  `/plugin marketplace add rghrmkr1993/ad-campaign-skills` then
  `/plugin install ad-campaign-director@ad-campaign-skills`.
- README install section updated with the marketplace option.

## 2.1.0 — 2026-07-19

**The AI-marketing-agent brain: five new knowledge layers + orchestrator architecture.**

### Added
- `references/marketing-foundations.md` — 28-discipline map, customer-journey models
  (AIDA, TOFU/MOFU/BOFU, Flywheel, AARRR, See-Think-Do-Care, RACE), objective-selection
  matrix (the objective IS the instruction to platform AI).
- `references/creative-psychology.md` — 10-point creative scoring rubric, 12 copywriting
  frameworks (PAS, BAB, FAB, 4P, QUEST, StoryBrand, PASTOR…), Cialdini principles +
  cognitive biases with application rules and explicit ethical lines.
- `references/platform-ai-internals.md` — how Meta (Andromeda retrieval + GEM ranking,
  auction Total Value math) and Google (Ad Rank, Smart Bidding auction-time signals)
  actually decide, the steering doctrine that follows, and objective maps for 8 secondary
  platforms (Microsoft, LinkedIn, TikTok, Pinterest, Snapchat, Reddit, Amazon, X).
- `references/measurement-science.md` — metric health logic, 9 attribution models
  (first/last/linear/time-decay/position/DDA/Markov/Shapley/incrementality), experiment
  designs (A/B, Bayesian, geo, lift, holdouts, budget stair-steps), honest forecasting/MMM.
- `references/optimization-automation.md` — the agent's own decision algorithms: marginal
  budget allocation, explore/exploit splits, bidding selection tree, creative-bandit
  rotation, scale/kill thresholds, lifecycle automation, ecommerce feed intelligence.
- Agent: **Orchestrator model** (enterprise sub-agent functions mapped to real execution)
  and **Reasoning protocol** (plan → act → measure → reflect → escalate).

## 2.0.0 — 2026-07-18

**Global generalization + architecture docs. Repo renamed to `ad-campaign-skills`.**

### Changed
- **Any region:** `geo-playbooks.md` rebuilt around a 7-question **Geo Framework** that
  produces a playbook for any market, with regional quick guides for North America, Latin
  America, Europe, Middle East & GCC, Africa, South Asia, Southeast Asia, East Asia, and
  Oceania. The original six markets (India/South India, Sri Lanka, Malaysia, Singapore, US,
  UK) remain as full-depth worked examples.
- **Any industry:** `vertical-playbooks.md` rebuilt around a 6-question **Vertical
  Framework**, with quick guides for 12 industries (F&B, health & wellness, finance, real
  estate, education, travel, automotive, gaming/apps, B2B/SaaS, local services,
  luxury/jewelry, electronics). The original four verticals (skincare/beauty, fashion,
  film/entertainment, tech) remain as full-depth worked examples.
- Agent and skill descriptions generalized from a fixed geo/vertical list to
  any-region/any-industry, with per-geo platform-availability checks made a first-class
  rule.
- Root README rewritten as detailed public documentation with **Mermaid architecture and
  workflow diagrams**, install for macOS/Linux/Windows, multi-region usage examples, safety
  design table, contributing guide, and FAQ.
- Repo renamed: `claude-agents` → **`ad-campaign-skills`**.

### Added
- `CHANGELOG.md` (this file).
- Agent-level detailed README with mental model, phase table, and FAQ.

## 1.0.0 — 2026-07-18

Initial release: `ad-campaign-director` agent + `ads-agency-pro` skill (2026 platform
doctrine for Meta/Google/YouTube/TikTok, six-market geo playbooks, four vertical playbooks,
client dashboard spec).

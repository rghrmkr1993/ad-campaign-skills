# Changelog

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

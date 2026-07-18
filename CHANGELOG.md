# Changelog

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

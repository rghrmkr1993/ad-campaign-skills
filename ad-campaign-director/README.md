# Ad Campaign Director — Claude Code Agent + Agency Playbook Skill

A veteran paid-media **campaign director agent** and a 2026 **agency playbook skill** for
[Claude Code](https://claude.com/claude-code). Give the agent a four-line client brief —
client name, budget, geo, nature of business — and it plans and executes a complete paid-media
campaign: research → strategy → tracking → build → launch (human-gated) → daily optimization →
a daily client results dashboard.

Built for agencies and freelancers running Meta (Facebook/Instagram), Google, YouTube, and
TikTok campaigns — with deep playbooks for **India (especially South India), Sri Lanka,
Malaysia, Singapore, the US, and the UK**, and vertical guides for **skincare/beauty,
clothing/fashion, film/entertainment, and tech**.

## What's inside

```
agents/
  ad-campaign-director.md        # The agent: 30-yr-veteran persona, full workflow, hard gates
skills/
  ads-agency-pro/
    SKILL.md                     # Agency OS: doctrine, quick sheets, workflow, guardrails
    references/
      platforms-2026.md          # Meta Andromeda, Google Power Pack, YouTube, TikTok Smart+/GMV Max
      geo-playbooks.md           # India/South India (languages, festivals, CPM calendar), SL, MY, SG, US, UK
      vertical-playbooks.md      # Skincare compliance, fashion benchmarks, film release arc, tech/B2B
      client-dashboard-spec.md   # Daily client dashboard: layout, metric rules, narrative style
```

## Highlights

- **2026 doctrine:** creative-is-the-targeting (Meta Andromeda entity-ID mechanics), Google
  Power Pack budget splits (PMax / AI Max / Demand Gen), YouTube Shorts + CTV strategy,
  TikTok Smart+ and GMV Max.
- **South Asia expertise rarely found in public playbooks:** Tamil/Telugu/Kannada/Malayalam
  language strategy, festival CPM calendar (Pongal → Onam → Diwali), UPI/COD commerce
  mechanics, the Tamil diaspora chain (TN → SL/MY/SG → UK/US), and the hard fact that
  **TikTok is banned in India** (bake it into your media plans).
- **Compliance built in:** ASCI (India) influencer/claims rules, Meta before/after policies,
  UK ASA/CAP beauty rules, GDPR/DPDP/PDPA lead-form notes.
- **Human-gated spend:** the agent never activates campaigns, raises budgets, or touches
  billing without explicit approval. Everything builds in PAUSED state first.
- **Honest reporting doctrine:** misses reported as misses; the dashboard spec supports both
  full-transparency and fixed-fee reporting models — **the client contract always wins**.

## Install

Copy into your Claude Code user directory:

```bash
# agent
cp agents/ad-campaign-director.md ~/.claude/agents/

# skill
cp -r skills/ads-agency-pro ~/.claude/skills/
```

(Windows: `%USERPROFILE%\.claude\agents\` and `%USERPROFILE%\.claude\skills\`.)

Optional but recommended companions:
- [claude-ads](https://github.com/AgriciDaniel/claude-ads) — structured audits + gated account ops across 12 platforms
- A Meta Ads MCP connector for direct API access
- Marketing skill packs (copywriting, CRO, analytics)

## Use

Start a Claude Code session and give it a brief:

```
Run ads for: GlowLeaf Skincare • ₹1.5L/month • Tamil Nadu + Kerala • ayurvedic skincare D2C
```

The agent researches, plans, builds paused campaigns, and asks for one explicit approval
before any money moves. During live flights, schedule a daily run:

```
daily update for GlowLeaf
```

…and it refreshes the client dashboard and flags anomalies.

## Customize

1. Fill in the **account registry** table in `skills/ads-agency-pro/SKILL.md` with your own
   ad accounts.
2. Adjust geo/vertical files for your markets — the structure is meant to be forked.
3. Platform numbers are research-dated **July 2026**; algorithms drift — refresh
   `platforms-2026.md` periodically.

## Disclaimers

- Not affiliated with Meta, Google, TikTok, or any platform. Platform policies and benchmark
  figures change — verify against official documentation before spending real money.
- Nothing here is financial, legal, or compliance advice. Regulated-category advertisers
  (health claims, finance, etc.) should get professional review.
- You are responsible for how campaigns run in your accounts. The agent's hard gates help,
  but the human approving the spend owns the outcome.

## License

MIT — see [LICENSE](LICENSE).

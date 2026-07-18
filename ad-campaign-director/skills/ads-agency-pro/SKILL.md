---
name: ads-agency-pro
description: Advanced paid-media agency playbook for running client ad campaigns on Meta (Facebook/Instagram), Google, YouTube, and TikTok for tech, skincare/beauty, film/entertainment, and clothing/fashion clients across India (especially South India), Sri Lanka, Malaysia, Singapore, US, and UK. Use for ANY client campaign work — strategy, media planning, audits, campaign builds, budgets, creative strategy, benchmarks, geo/vertical questions, or platform best practices. Layers 2026 platform doctrine (Meta Andromeda, Google Power Pack, TikTok Smart+/GMV Max), regional playbooks, and vertical compliance.
---

# Ads Agency Pro — 2026 Client Campaign Playbook

Agency operating system for running paid media for clients. This skill is the
**strategy + regional + vertical layer**. It pairs well with:

- **`ads` skill ([claude-ads plugin](https://github.com/AgriciDaniel/claude-ads))** — optional
  but recommended: structured audits, deterministic scoring, JSON reports, capability-gated
  account changes. Use it for the mechanics; use THIS skill for what to actually do in these
  markets and verticals.
- **Meta Ads MCP tools** (`ads_*`) if connected — direct API access to campaigns, ad sets,
  creatives, audiences, insights, A/B and lift tests.
- **Browser automation** — Google Ads, YouTube Studio, GA4, TikTok Ads Manager.
- **Your creative stack** — AI video/UGC generation skills, Canva MCP, ad-copy skills,
  landing-page skills.

## Account registry (maintain your own — TEMPLATE)

Keep this table updated with YOUR accounts. Verify the right account before every action.

| Platform | Account | Login | Notes |
|---|---|---|---|
| Google Ads | `XXX-XXX-XXXX` | `your-ads-login@example.com` | Billing model, tax status |
| Meta | Business Manager + ad account per client | — | Never run client work on a personal ad account. Pixel + CAPI per client. |
| TikTok | Per-client | — | **India: TikTok is BANNED (since 2020, still banned 2026). Never plan TikTok for India geos.** |

## 2026 core doctrine (applies to every campaign)

1. **Creative is the targeting.** Meta Andromeda and TikTok Smart+ retrieve ads by creative
   signal, not audience settings. Budget creative volume before budgeting media: 10-15
   conceptually distinct concepts per campaign, 20+ new ads/month for active accounts.
2. **Concepts, not variations.** Similar ads collapse into one Entity ID on Meta — 30 lookalike
   ads = 1 ad to the algorithm. Diversify angle, emotion, format, and creator, not just colors.
3. **Consolidate structure.** 1-3 ad sets per campaign max. Advantage+ Shopping / PMax as
   workhorses. Fragmented structures starve the learning phase.
4. **Broad beats narrow.** Lookalikes and interest stacks are legacy. Go broad + let creative
   segment. Exception: genuine niche B2B and film fan-bases.
5. **Signal quality is the moat.** Pixel + CAPI together, Event Match Quality ≥ 7, GA4 +
   enhanced conversions on Google, offline conversion import for lead-gen. No launch without
   conversion tracking verified end-to-end.
6. **Video-first everywhere.** 9:16 native vertical for Reels/Shorts/TikTok. Hook < 2s,
   brand < 3s, text overlays for sound-off. UGC-style outperforms studio polish (24% higher
   ROAS, ~47% lower CPM on Meta).
7. **Patience windows.** Let algorithms learn 7-10 days before judging. Expect ad fatigue at
   2-3 weeks — plan refresh cadence (25-30% of assets every 2 weeks at scale).

## Platform quick sheet

| Platform | 2026 play | Detail |
|---|---|---|
| Meta | Andromeda era: A+SC primary, creative volume, EMQ ≥ 7 | [references/platforms-2026.md](references/platforms-2026.md) |
| Google | Power Pack: PMax (50-60% ecom budget) + AI Max Search (30-40%) + Demand Gen (10-20%) | same |
| YouTube | Shorts ≥ 20-30% of YT spend for <35 audiences; CTV for premium brand | same |
| TikTok | Smart+ for web, GMV Max default for TikTok Shop; SEA CPMs $1-5 | same |

## Geo quick sheet

| Market | Platform mix | Key facts | Detail |
|---|---|---|---|
| India / South India | Meta + Google + YT (NO TikTok) | Regional language creative outperforms English for tier-2/3; 73% consume regional content; UPI + COD; festival CPM spikes | [references/geo-playbooks.md](references/geo-playbooks.md) |
| Sri Lanka | Facebook-first (9M users) + YT (8.8M) | FB = the internet for mass market; WhatsApp/IG social commerce >25% of online sales | same |
| Malaysia | Meta + TikTok Shop + Google | Bahasa/English/Chinese/Tamil; Raya mega-season; Touch 'n Go | same |
| Singapore | Meta + Google + TikTok | Premium CPMs, 98% penetration, English-first, PDPA | same |
| US | Meta + Google/YT + TikTok | Highest CPMs, CTV big, state privacy laws | same |
| UK | Meta + Google/YT + TikTok | ASA/CAP code (strict on beauty claims), GDPR | same |

## Vertical quick sheet

| Vertical | Core play | Compliance hot zone | Detail |
|---|---|---|---|
| Skincare/beauty | UGC + A+SC; "helps/visibly reduces" language | ASCI (India), Meta before/after rules, no treatment claims | [references/vertical-playbooks.md](references/vertical-playbooks.md) |
| Clothing/fashion | 70% catalog (A+SC) / 30% hero drops; 21+ creatives/month | Sizing/returns clarity; median ROAS 2.18x, top-10% 6.0x | same |
| Film/entertainment | Music-first, meme + creator seeding, phase-gated | Certification marks (India), spoiler windows | same |
| Tech/B2B | Search intent + Demand Gen; offline conversion feedback | Data claims, GDPR/DPDP for lead forms | same |

## Standard engagement workflow (new client)

1. **Intake** — business goal, AOV/LTV, margins, target ROAS/CPA ceiling, geo list, languages,
   existing assets/accounts. Get Business Manager / Google Ads access via proper partner
   delegation (never passwords).
2. **Audit** — invoke the `ads` skill for a source-grounded audit if account has history;
   otherwise baseline: tracking, feeds, past creative, competitor scan (Meta Ads Library;
   Google Ads Transparency Center).
3. **Measurement first** — pixel + CAPI (Meta), Google tag + enhanced conversions, GA4,
   catalog/feed health. Verify test events BEFORE any spend.
4. **Structure** — per doctrine above. One prospecting (broad) + one retargeting + optional
   test campaign per platform. Name convention: `{CLIENT}-{GEO}-{OBJ}-{YYYYMM}`.
5. **Creative sprint** — 10-15 concepts across angles (problem, desire, social proof, founder,
   demo, UGC, meme where fit). Localize per language market — separate ad groups/ad sets per
   language, never mixed.
6. **Launch small, scale on signal** — 7-10 day learning window, then scale winners 20-30%
   per step; kill losers at concept level, not variation level.
7. **Report** — weekly: spend, ROAS/CPA vs target, creative leaderboard, next tests.
8. **Client dashboard** — daily results dashboard per
   [references/client-dashboard-spec.md](references/client-dashboard-spec.md).

## Guardrails

- Never launch, edit budgets, or change live campaigns without explicit owner approval.
- Never plan TikTok spend for India. Redirect that budget to Reels + Shorts (+ Moj/ShareChat
  via managed buys for deep tier-2/3 regional reach).
- Festival calendars drive CPM inflation in India (Diwali window CPMs can run 2-3x) — book
  creative and lock budgets 4-6 weeks ahead.
- Every regulated-vertical ad (skincare claims, finance, health) passes the compliance checks
  in [references/vertical-playbooks.md](references/vertical-playbooks.md) before submission.
- Currency/billing: Indian accounts commonly run prepaid (UPI) with GST invoicing — check the
  billing threshold model per market before launch week.

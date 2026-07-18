# Claude Agents

Production-grade agents and skills for [Claude Code](https://claude.com/claude-code) —
built from real agency and client work, released for anyone to use and fork.

## Agents

| Agent | What it does |
|---|---|
| [ad-campaign-director](ad-campaign-director/) | Veteran paid-media campaign director: give it a 4-line client brief (client, budget, geo, business) and it runs a complete campaign — research → strategy → tracking → build → human-gated launch → daily optimization → daily client results dashboard. Ships with the `ads-agency-pro` skill: 2026 platform doctrine (Meta Andromeda, Google Power Pack, TikTok Smart+/GMV Max), geo playbooks for India/South India, Sri Lanka, Malaysia, Singapore, US, UK, and vertical playbooks for skincare, fashion, film, and tech. |

*More agents coming.*

## Install

Each agent folder has its own README with install steps. General pattern:

```bash
cp <agent>/agents/*.md ~/.claude/agents/
cp -r <agent>/skills/* ~/.claude/skills/
```

(Windows: `%USERPROFILE%\.claude\agents\` and `%USERPROFILE%\.claude\skills\`.)

## Design principles

- **Human-gated actions:** agents never spend money, publish, or mutate accounts without
  explicit approval.
- **Evidence over vibes:** benchmarks cited, platform mechanics dated, honest reporting
  doctrine (misses reported as misses).
- **Fork-friendly:** playbooks are structured to be edited for your markets and clients.

## License

MIT — see [LICENSE](LICENSE).

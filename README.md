# Kasulik AI Plugins

24 AI skills packaged into 3 plugins for small and medium businesses. Install them in [Claude](https://claude.ai) via Cowork or Claude Code.

**Uus kasutaja?** Loe kõigepealt [KIIRSTART-JUHEND.md](KIIRSTART-JUHEND.md) ja [TURVALISUS-JUHEND.md](TURVALISUS-JUHEND.md).

## Quick Start

```
/plugin marketplace add kasulik-ai/plugins
/plugin install kasulik-tööruum@kasulik-ai-plugins
/plugin install kasulik-turism@kasulik-ai-plugins
/plugin install kasulik-ettevõtlus@kasulik-ai-plugins
```

Then run `/alusta` to set up your workspace.

## What's Inside

### kasulik-tööruum (7 skills)
AI workspace setup, coaching, and productivity tools.

| Skill | What It Does |
|-------|-------------|
| /alusta | Smart entry point — detects existing setup, guides new or returning users |
| /agendid | Creates personalized AI assistant: interview → CLAUDE.md + memory/ + exports |
| /ai-coach | Finds the right skill for any task, suggests workflows, teaches prompting |
| /töövood | 12 pre-built multi-skill workflows for common business tasks |
| /ülevaade | Weekly structured reflection: wins, struggles, discovery, next week |
| /tabel | Excel and CSV data analysis |
| /wordpress | WordPress integration guide |

### kasulik-ettevõtlus (8 skills)
Daily business operations — marketing copy, email campaigns, client communication, processes, reports, and strategy.

| Skill | What It Does |
|-------|-------------|
| /kontekst | Sets up marketing context (positioning, ICP, competitors, brand voice) |
| /tekst | Marketing copy — website, ads, blog posts, social media |
| /meilid | Email campaigns — welcome sequences, newsletters, follow-ups |
| /kõnekokkuvõte | Call notes → action items, follow-up email, internal summary |
| /klient | Client communication — inquiries, complaints, FAQ articles |
| /protsess | Process documentation — SOP, RACI matrix, optimization |
| /aruanne | Reports — weekly, monthly, board, team updates |
| /plaan | Strategic plans — SWOT, competitive analysis, action plans |

### kasulik-turism (9 skills)
Tourism-specific skills for hospitality and destination businesses.

| Skill | What It Does |
|-------|-------------|
| /turism | Main entry point — routes to the right tourism skill |
| /strateegia | Strategy: value proposition, SWOT, competitive analysis, expansion |
| /turundus-sisu | Marketing: social media, SEO, blog, newsletters, brand storytelling |
| /müük-kliendid | Sales: segmentation, funnel, objections, follow-ups, loyalty |
| /külastuskogemus | Guest experience: customer journey, packages, guides, FAQs |
| /analüütika | Analytics: KPIs, pricing, customer behavior, channel effectiveness |
| /hooaeg | Seasonal planning: high, shoulder, and low season strategies |
| /arvustus | Review responses: Google, Booking, TripAdvisor, Facebook |
| /külastaja | Visitor journey optimization: pre-booking to post-visit |

## How It Works

1. **Install all 3 plugins** (they work best together)
2. **Run `/alusta`** — detects your setup state and guides you
3. **Run `/agendid`** to create a personalized AI assistant
4. **Run `/kontekst`** to set your marketing context
5. **Just describe what you need** — skills trigger automatically
6. **Schedule `/ülevaade` weekly** to improve your workspace

## Estonian Commands Reference

| Käsk | Plugin | Kirjeldus |
|------|--------|-----------|
| `/alusta` | tööruum | Tark alguspunkt — seadistamine, parendamine või coaching |
| `/agendid` | tööruum | AI assistendi loomine intervjuu ja skaneerimise kaudu |
| `/töövood` | tööruum | Eelseadistatud mitmeskillsed töövood |
| `/ülevaade` | tööruum | Iganädalane AI kasutuse ülevaade |
| `/tabel` | tööruum | Exceli ja CSV failide analüüs |
| `/wordpress` | tööruum | WordPress MCP integreerimise juhend |
| `/kontekst` | ettevõtlus | Turunduskonteksti seadistamine |
| `/tekst` | ettevõtlus | Turunduskopii ja sisuloome |
| `/meilid` | ettevõtlus | E-posti kampaaniad ja jadad |
| `/kõnekokkuvõte` | ettevõtlus | Kõne kokkuvõte ja järeltegevused |
| `/klient` | ettevõtlus | Kliendikommunikatsioon |
| `/protsess` | ettevõtlus | Protsesside dokumenteerimine |
| `/plaan` | ettevõtlus | Strateegilised plaanid |
| `/aruanne` | ettevõtlus | Aruanded ja ülevaated |
| `/turism` | turism | Turismiettevõtte AI abiline |
| `/hooaeg` | turism | Hooajaplaneerimine |
| `/arvustus` | turism | Arvustustele vastamine |
| `/külastaja` | turism | Külastaja teekonna optimeerimine |
| `/strateegia` | turism | Positsioneerimine ja strateegia |
| `/turundus-sisu` | turism | Turundussisu ja sotsiaalmeedia |
| `/müük-kliendid` | turism | Müük ja kliendisuhtlus |
| `/külastuskogemus` | turism | Külastuskogemuse arendamine |
| `/analüütika` | turism | KPI-d ja analüütika |

## Additional Guides

- [KIIRSTART-JUHEND.md](KIIRSTART-JUHEND.md) — Pre-training setup guide (Estonian)
- [TURVALISUS-JUHEND.md](TURVALISUS-JUHEND.md) — AI security and privacy cheat sheet (Estonian)

## Architecture (v3.0)

v3.0 removed 31 English-language skills that duplicated Anthropic's official plugins (marketing, sales, operations, customer-support, etc.). The remaining 24 skills are Estonian-language entry points enriched with English framework content inside. This eliminates trigger collisions when users have both Kasulik and Anthropic plugins installed.

## Sources

This collection curates selected frameworks from:

- **Corey Haines / Marketing Skills** — SaaS marketing frameworks (copywriting, email, CRO). Open-source.
- **Anthropic Official Plugins** — Framework patterns adapted into Estonian wrapper skills.
- **Kasulik AI (Original)** — Workspace plugin (alusta, ai-coach, ülevaade, agendid), entire Tourism plugin, and all Estonian business skills are 100% original.

All curated content is used in accordance with respective licenses.

## About

Built by [Kasulik AI](https://kasulik.ai) — practical AI training for businesses. Founded by Kristo Peterson.

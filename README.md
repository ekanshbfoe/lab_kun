# lab_kun — Competitive Research for Manga/Comic Localization in Indian Languages

**Research for:** A service that translates manga (Japan), manhwa (Korea), and manhua (China) into natural, casual Hindi (Hinglish) with per-bubble font matching, tone adaptation from user samples, and chapter-aware workflow.

---

## Repository Structure

```
lab_kun/
├── README.md                           # This file
└── research/
    ├── setup_report.md                 # Initial tool audit & capability verification
    ├── stage1_player_list.md           # 100-player landscape across 8 categories
    ├── stage2_batch1_deepdive.md       # 5 commercial AI SaaS: Mantra, PicTranslate, AI Manga Translator, PanelFont, MangaTranslate
    ├── stage2_batch2_deepdive.md       # 5 scanlation/platform/dub: Otaku Nadu, AnimeMirchi, Toonsutra, INKR/GlobalComix, Muse India
    ├── stage3_cross_analysis.md        # Master comparison, pricing patterns, business model taxonomy, feature gap map
    ├── stage4_gap_analysis.md          # 10 gaps scored (Market Pain × Tech Feasibility × Moat × Revenue)
    ├── stage5_final_positioning.md     # Positioning, pricing, GTM, architecture, risk register
    ├── stage6_corrections.md           # Corrections pass: live-test limits, font reality, verified pricing, bottom-up market sizing
    └── test_images/                    # Test PNGs used for Hindi translation attempts (harmless)
```

---

## Recommended Reading Order

| Order | File | Purpose |
|-------|------|---------|
| 1 | `setup_report.md` | Tool audit — what's working, what's not |
| 2 | `stage1_player_list.md` | Full 100-player landscape (8 categories) |
| 3 | `stage2_batch1_deepdive.md` | Deep-dive: 5 commercial AI translation SaaS |
| 4 | `stage2_batch2_deepdive.md` | Deep-dive: 5 scanlation groups, Indian platforms, anime Hindi dub |
| 5 | `stage3_cross_analysis.md` | Cross-player comparison, pricing patterns, business models, feature gaps |
| 6 | `stage4_gap_analysis.md` | Top 10 gaps scored and detailed specs |
| 7 | `stage5_final_positioning.md` | Positioning, pricing (₹199/₹599), GTM, tech architecture, risks |
| 8 | `stage6_corrections.md` | **Critical corrections** — font matching reality, verified pricing, bottom-up market sizing, funding reconciliation |

> **Start with `stage6_corrections.md`** if you want the final validated numbers — it corrects several claims from earlier stages.

---

## Key Findings Summary

| Area | Finding |
|------|---------|
| **Hindi/Hinglish demand** | 8/10 Reddit posts explicitly about manga/comics (not anime) demand casual Hinglish; formal "Shudh Hindi" called "cringy" |
| **Font matching** | **No competitor achieves per-bubble automatic font matching** — Alibaba hands-on test of 17 tools × 42 titles confirms best tools (ComicAI, DeepL Manga Pro) require manual font upload + weight assignment per bubble type |
| **AI tool pricing** | Median **$0.0035/page** (MangaTranslate yearly, PanelFont add-ons); range $0.001–0.01/page |
| **Human pricing** | $5–7/page (translation + lettering); $1–2/page low-end freelancers |
| **Market size (SAM)** | **₹5–11Cr ARR ($600K–1.3M)** at maturity — bottom-up from 18K reachable customers (scanlation groups, indie creators, publishers, platforms) |
| **Toonsutra funding** | Pre-seed $1.1M + Seed $3.2M = $4.3M committed; total $5.9M with angels (Google, Sony, Holtzbrinck, Gen Fukunaga, etc.) |
| **Your wedge** | Hinglish tone adaptation (sample-based) + per-bubble font matching + chapter workflow + Indian pricing (₹199/mo) + legal-safe local-first |

---

## Research Methodology

- **Stage 1:** Broad landscape mapping (web search, GitHub, Product Hunt, Reddit, company sites)
- **Stage 2:** 10 deep-dives (5 commercial SaaS + 5 scanlation/platform/dub) with cited sources
- **Stage 3:** Cross-analysis with master comparison table, pricing taxonomy, business model map
- **Stage 4:** Gap scoring (Market Pain × Tech Feasibility × Moat × Revenue)
- **Stage 5:** Positioning, pricing, GTM, architecture, risk register
- **Stage 6:** Corrections pass — live-test attempts, independent font-test evidence, verified pricing tables, bottom-up market sizing, missing player deep-dives (Pratilipi, Dashtoon)

---

## No Secrets

This repository contains **no API keys, tokens, .env files, or credentials**. All research is based on public sources (company websites, pricing pages, news articles, Reddit, GitHub, industry reports).

---

## License

Research for internal use. No license granted for redistribution.
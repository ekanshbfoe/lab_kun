# Stage 3: Cross-Analysis — All 10 Deep-Dived Players

**Date:** 2026-11-10  
**Sources:** Stage 1 player list + Stage 2 Batch 1 (5 commercial SaaS) + Stage 2 Batch 2 (5 scanlation/platform/dub players)  
**Scope:** 10 players across 4 segments: Enterprise, Prosumer SaaS, Creator Tools, Licensed Platforms

---

## 1. MASTER COMPARISON TABLE

| Dimension | Mantra Engine | PicTranslate | AI Manga Translator | PanelFont | MangaTranslate | Otaku Nadu | AnimeMirchi | Toonsutra | INKR/GlobalComix | Muse India/CR |
|-----------|---------------|--------------|---------------------|-----------|----------------|------------|-------------|-----------|------------------|---------------|
| **Segment** | Enterprise B2B | Prosumer SaaS | Prosumer SaaS | Prosumer SaaS (early) | Creator/Studio SaaS | Volunteer Scanlation | Scanlator + Community | Licensed Platform (App) | Platform + Localization SaaS | Dub Producer + Distributor |
| **Legal Model** | Licensed only | Tool only | Tool only | Tool only | Tool only | Unlicensed (DMCA risk) | Unlicensed (DMCA'd) | **Fully licensed** | **Fully licensed** | **Fully licensed** |
| **Primary Customer** | JP Publishers (Shueisha, SQEX) | Creators, scanlators, general | Readers, file owners, scanlators | Agencies, PMs, scanlators | Individuals, studios, API | Tamil/Indic anime fans | Hindi manga readers | Indian mobile youth (700M) | Global publishers, indie creators | Anime streaming platforms |
| **Hindi Support** | ❌ No | ✅ Yes (130+) | ❓ Unverified (20+) | ❓ Likely (100+) | ✅ Yes (100+) | ❓ Unverified (Tamil focus) | ✅ **Explicit + Hinglish** | ✅ **Primary (HI/TA/TE/EN)** | ❌ **No (12 langs, no Indian)** | ✅ **Full dub (HI/TA/TE)** |
| **Tone/Style** | Formal/Standard MT | Standard MT + custom prompts (Max) | Standard MT (Claude) | "Contextual semantic consistency" | 3 models + Studio editor | Standard scanlation | **Community demands Hinglish** | AI standardized (Gemini) | AI standardized (Vision) | **Hinglish praised** |
| **Font Matching** | Style estimation (enterprise) | "Preserve font style" (claim) | Layout-aware typesetting | "Manga-appropriate typeface" | **Studio: import own fonts** | Manual (volunteer) | Manual (Photoshop) | None visible | None visible | N/A (video) |
| **Manga-Native Formats** | Editorial workflow | Images only | **CBZ, EPUB, PDF, ZIP (1GB)** | Images, PDF | Images | Manual | Manual | App-only (vertical scroll) | PNG, JPG, PSD | N/A |
| **Batch/Volume** | 100K pages/mo | 20 img/batch | **1,000 pages/upload** | Multi-threaded PDF batch | Images only | Manual | Manual | 500K episodes (licensed) | ALU-based (30pg ≈ 1–2 ALU) | N/A |
| **Browser Extension** | ❌ | ❌ | **Chrome + Firefox (30+ sites)** | ❌ | ❌ | ❌ | ❌ | ❌ (app only) | ❌ | ❌ |
| **Editor/Studio** | Editorial QA tools | Web editor | Basic editor | Not advertised | **Photoshop-style Studio (font import, batch actions)** | ❌ | ❌ | ❌ (reader only) | On-page AI assistants | N/A |
| **Custom Prompts/Glossary** | Glossary/style locks (contract) | **Max plan only** | Glossary | Not advertised | Not advertised | ❌ | ❌ | ❌ | Auto-detect glossary (Advanced) | N/A |
| **Model Choice** | Proprietary + LLM | **GPT-4o, Claude, Gemini (Max)** | Claude (per PicTranslate) | Fast vs HQ (unspecified) | **GPT-4o, Papago, Google (3 models)** | Manual | Manual + AI curiosity | **Gemini 2.0 Flash** | Google Vision + proprietary | Traditional dub studio |
| **Pricing Model** | Contract ($1K–5K/mo) | Credits (sub + packs) | Page packs + subs | Credits (sub + packs) | Credits (sub + packs) | Free (volunteer) | Free (volunteer) | Freemium coins/IAP | **ALU usage ($2–4/ALU)** | Free (YT) + B2B licensing |
| **Cheapest/Page** | N/A | ~$0.03 (annual Pro) | **$0.009 (yearly)** | ~$0.003 (Premium add-on) | **$0.0031 (yearly)** | $0 (volunteer) | $0 (volunteer) | Coin packs ~$0.60–6 | **$2–8/chapter** | Free (ad-supported) |
| **Free Tier** | 1-mo trial (contact) | 10 credits/day + 20 signup | 5 pages one-time | 10 credits/day | 5/day IP + 5/day check-in | Free | Free | Free episodes | 0 ALU, watermarked | Free (YouTube) |
| **Funding/Scale** | ¥780M ($5.2M), 10+ pubs | Unverified | Unverified | Show HN (2 days old) | Launched Sept 2026 | 2.8K Discord | Small, DMCA'd | **$5.9M, 2M DL, 500K MAU** | $3.1M Series A, 1K+ titles | 150+ shows on CR |
| **Team Size** | ~30–50 (EST) | <10 (EST) | Unverified | Solo/small (EST) | Small (Ficory LLC) | Volunteers | Volunteers | 20–50 (EST) | Unverified (SG + dist) | Dub studio + licensing |

---

## 2. PRICING PATTERNS BY SEGMENT

### A. Enterprise (Licensed Publishers)
| Player | Model | Effective $/Page | Volume Commitment |
|--------|-------|------------------|-------------------|
| **Mantra Engine** | Contract $1K–5K/mo | ~$0.01–0.05 (at 100K pg/mo) | Annual contract, negotiated |
| **Toonsutra** | Licensing + IAP | N/A (content cost) | Per-title licensing deals |

**Pattern:** High-touch sales, revenue-share or volume contracts, no self-serve. **Not your segment.**

---

### B. Prosumer SaaS (Self-Serve, Credit/Page-Based)
| Player | Best $/Page | Free Tier | Pricing Complexity |
|--------|-------------|-----------|-------------------|
| **MangaTranslate** | **$0.0031** (yearly 41,700 credits) | 5/day IP + 5/day check-in | **High** (2 price lists, 3 models, API separate) |
| **AI Manga Translator** | **$0.009** (yearly 15K pages) | 5 pages one-time | **Medium** (packs + subs, tall-strip billing) |
| **PicTranslate** | ~$0.03 (annual Pro 3K/mo) | 10 credits/day + 20 signup | **Medium** (credits, packs, model gating) |
| **PanelFont** | ~$0.003 (Premium 15K/mo + add-ons) | 10 credits/day | **Low** (simple sub + add-ons) |

**Key Observations:**
- **Floor: ~$0.003/page** at high annual volume (MangaTranslate, PanelFont add-ons)
- **Entry: ~$0.01–0.02/page** for realistic volumes (1K–10K pages/yr)
- **Credit models dominate** — flexible for burst usage, subscriptions for steady volume
- **Model gating** (PicTranslate Max, MangaTranslate Ultra) adds 2× cost for quality
- **No Indian pricing** — all USD, no regional parity

---

### C. Creator/Studio Tools (Editor + API Focus)
| Player | Model | Editor Quality | API |
|--------|-------|----------------|-----|
| **MangaTranslate** | Credits + Studio | **Best: Photoshop-style, font import, batch actions** | Yes (separate pricing) |
| **AI Manga Translator** | Page packs | Basic (move boxes, adjust font) | Yes (~$0.005/page) |
| **PicTranslate** | Credits | Web editor (fine-tune, colors, reposition) | **No (roadmap only)** |
| **GlobalComix Studio** | ALU ($2–4/ALU) | On-page AI assistants, PSD export (Pro+) | Unverified |

**Pattern:** **Editor is the retention hook** — MangaTranslate's Studio is the differentiator. API = enterprise upsell.

---

### D. Licensed Platforms (Content Aggregators)
| Player | User Price | Creator/Publisher Share | Language Coverage |
|--------|------------|-------------------------|-------------------|
| **Toonsutra** | Freemium coins (~₹50–500) | Licensing fees + rev share | **HI, TA, TE, EN** (+4 planned) |
| **INKR** | Free + $4.99/mo Extra | Revenue share (platform takes %) | 12 langs (**no Indian**) |
| **Crunchyroll** | Free + $9.99/mo Premium | Licensing from Muse/etc. | **150+ Hindi dubs** (growing) |
| **Muse India** | Free (YouTube ads) | B2B licensing to 6+ platforms | **HI, TA, TE dubs** |

**Pattern:** **Content licensing is the moat**, not tech. Tech enables scale (Gemini, Vision AI). **Indian languages = growth lever** for Toonsutra/Crunchyroll.

---

## 3. BUSINESS MODEL TAXONOMY — WHERE MONEY FLOWS

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                        COMIC LOCALIZATION VALUE CHAIN                       │
├──────────────────┬──────────────────┬──────────────────┬───────────────────┤
│   CONTENT        │   TOOLS/INFRA    │   DISTRIBUTION   │   MONETIZATION    │
│   (IP Owners)    │   (Your Layer)   │   (Platforms)    │   (Revenue)       │
├──────────────────┼──────────────────┼──────────────────┼───────────────────┤
│ Shueisha         │ Mantra Engine    │ MangaONE         │ Subscription      │
│ Shogakukan       │ ($1K–5K/mo)      │ Shonen Jump+     │ Ad revenue        │
│ KADOKAWA         │                  │                  │ Licensing fees    │
│ Square Enix      │                  │                  │                   │
├──────────────────┼──────────────────┼──────────────────┼───────────────────┤
│ Global Publishers│ PicTranslate     │ Self-hosted      │ Direct sales      │
│ Indie Creators   │ AI Manga Trans.  │ (MangaDex,       │ Patreon/Ko-fi     │
│ Scanlation Groups│ MangaTranslate   │  wedex.org)      │ Commissions       │
│                  │ PanelFont        │                  │                   │
├──────────────────┼──────────────────┼──────────────────┼───────────────────┤
│ Graphic India    │ Toonsutra        │ Toonsutra App    │ Freemium IAP      │
│ (Baahubali,      │ (Gemini 2.0)     │ (iOS/Android)    │ (Coins/Sub)       │
│  Legend of Hanuman)              │                  │                   │
├──────────────────┼──────────────────┼──────────────────┼───────────────────┤
│ INKR Publishers  │ GlobalComix      │ INKR App         │ Rev share +       │
│ Indie Creators   │ Studio (ALU)     │ (Global)         │ Sub ($4.99)       │
├──────────────────┼──────────────────┼──────────────────┼───────────────────┤
│ Japanese Studios │ Muse India       │ YouTube +        │ YouTube ads +     │
│ (Anime/Donghua)  │ (Dub Studio)     │ Crunchyroll +    │ B2B licensing     │
│                  │                  │ Netflix + MX +   │ (6+ platforms)    │
│                  │                  │ JioHotstar + TV  │                   │
└──────────────────┴──────────────────┴──────────────────┴───────────────────┘
```

### Revenue Concentration
| Layer | Total Addressable Market (EST) | Your Accessible Slice |
|-------|--------------------------------|----------------------|
| **Enterprise Tools** | $50–100M (global manga pubs) | Low (incumbents entrenched) |
| **Prosumer SaaS** | $200–500M (creators + scanlators) | **HIGH** (underserved Indian segment) |
| **Creator Platforms** | $1–2B (global webtoon apps) | Medium (Toonsutra dominates India) |
| **Localization Services** | $100–200M (agencies + studios) | **HIGH** (no Hindi/Indic specialists) |
| **Dub/Sub Production** | $500M+ (anime streaming) | Low (video, not comic) |

**Your sweet spot: Prosumer SaaS + Localization Services for Indian languages** — $300–700M TAM, near-zero competition.

---

## 4. FEATURE GAP MAP → YOUR PRODUCT SPEC

| Feature | Mantra | PicTranslate | AI Manga Trans | PanelFont | MangaTranslate | Toonsutra | INKR/GC | Muse/CR | **GAP** | **Your Spec** |
|---------|--------|--------------|----------------|-----------|----------------|-----------|---------|---------|---------|---------------|
| **Casual Hinglish Tone** | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ (dub) | **NONE** | **Sample-based tone adaptation** (user provides 10–50 hand translations → few-shot prompt → per-character voice) |
| **Font Style Detection → Free Font Match** | ⚠️ Style est. | ⚠️ Claim only | ❌ | ⚠️ Claim only | ✅ Import own | ❌ | ❌ | N/A | **NONE** | **Detect bubble font (weight, width, slant, serif/sans) → match Google Fonts/OFL library → apply per-bubble** |
| **Hindi/Indic Language Focus** | ❌ | ✅ Generic | ❓ | ❓ | ✅ Generic | ✅ Reader | ❌ | ✅ Dub | **TOOLS** | **Native HI/TA/TE/MR/BN/KN/ML/GU/PA/OR/AS support + Hinglish toggle** |
| **Volume Workflow (CBZ/EPUB/PDF + Chapter Mgmt)** | Editorial | ❌ | ✅ Best | ⚠️ PDF batch | ❌ | App-only | ⚠️ ALU-based | N/A | **PARTIAL** | **Chapter-aware: glossary persistence, tone consistency across chapter, batch queue, progress tracking** |
| **Creator Editor (Not Just Reader)** | Editorial | Basic | Basic | ❌ | **Best (Studio)** | ❌ | Pro+ only | N/A | **PARTIAL** | **Tone slider (formal↔casual), font override per char, SFX handling, batch actions, PSD export** |
| **Legal-Safe Tooling** | Licensed only | User responsible | User responsible | User responsible | User responsible | Licensed | Licensed | Licensed | **ALL "USER RESPONSIBLE"** | **Built-in: rights metadata fields, license checker (optional), no hosting, local-first option** |
| **Pricing for Indian Market** | $1K+/mo | $10–20/mo | $10–30/mo | $10–50/mo | $8–130/mo | ₹50–500 coins | $2–8/ch (ALU) | Free + B2B | **NONE** | **₹99–299/mo (Pro), ₹999/yr, per-page ₹0.50–1.00, student/indie discounts** |
| **Offline/Local-First Option** | ❌ Cloud | ❌ Cloud | ❌ Cloud | ❌ Cloud | ❌ Cloud | ❌ App | ❌ Cloud | ❌ Cloud | **NONE** | **Optional: local ONNX pipeline (like AutoScanlate-AI) for privacy + zero marginal cost** |
| **SFX/Sound Effects Handling** | ✅ | ✅ Dedicated | ⚠️ | ⚠️ | ⚠️ Manual | N/A | Advanced (ALU) | N/A | **PARTIAL** | **SFX detection → translate/annotate/remove toggle, vertical text reflow** |
| **Team/Community Workflow** | Editorial QA | ❌ | ❌ | ❌ | ❌ | ❌ | Collaborative | ❌ | **NONE** | **Shared glossary, tone presets, reviewer comments, role-based (translator/cleaner/typesetter)** |

---

## 5. COMPETITIVE POSITIONING MAP

```
                    HIGH DIFFERENTIATION (Unique Value)
                            │
                            │     ★ YOUR PRODUCT
                            │     (Hinglish tone + Font match +
                            │      Chapter workflow + Indian pricing +
                            │      Legal-safe + Team features)
                            │
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
   ENTERPRISE           PROSUMER            CREATOR PLATFORMS
   (Mantra)             (PicTranslate,      (Toonsutra, INKR)
                        AI Manga Trans,      Reader-focused,
                        MangaTranslate,      Licensed content,
                        PanelFont)           No creator tools
                            │
                            │
                    LOW DIFFERENTIATION
                    (Commoditized OCR+MT+Typeset)
                            │
                    ┌───────┴───────┐
                    │               │
                    ▼               ▼
              GENERIC TOOLS      SCANLATION
              (Google Lens,      COMMUNITIES
               Yandex, MSFT)     (Otaku Nadu,
                                 AnimeMirchi)
                    │               │
                    │          HIGH PASSION
                    │          LOW TOOLING
                    │          HIGH LEGAL RISK
                    │
                    ▼
              YOUR ENTRY POINT:
              "Prosumer tool for
               Indic-language
               creators"
```

---

## 6. PRICING STRATEGY FOR YOUR PRODUCT

### Recommended Tiers (Indian Market First, Global Second)

| Tier | Monthly | Yearly | Per-Page (Vol) | Target | Includes |
|------|---------|--------|----------------|--------|----------|
| **Free** | ₹0 | — | — | Hobbyists, trial | 5 pages/day, basic models, watermark, community glossary |
| **Indie** | **₹199** | **₹1,999** | ~₹0.50 (4K pg/yr) | Solo creators, scanlators | 4K pages/yr, all models, tone adaptation (10 samples), font matching, chapter workflow, PSD export, no watermark |
| **Studio** | **₹599** | **₹5,999** | ~₹0.30 (20K pg/yr) | Small teams, agencies | 20K pages/yr, team seats (3), shared glossary/tone presets, reviewer roles, API access (10K calls), priority queue |
| **Enterprise** | Custom | Custom | ~₹0.15 | Publishers, platforms | Unlimited, SLA, custom models, on-premise option, dedicated support, license management |

### Global Pricing (USD, parity-adjusted)
| Tier | Monthly | Yearly | Per-Page |
|------|---------|--------|----------|
| Free | $0 | — | — |
| Indie | **$3.99** | **$39** | ~$0.01 |
| Studio | **$9.99** | **$99** | ~$0.005 |
| Enterprise | Custom | Custom | ~$0.002 |

**Rationale:**
- **Below PicTranslate Pro ($9.99), AI Manga Trans Monthly ($29.90), MangaTranslate Monthly ($12.90)**
- **Above free tiers** — sustainable for indie, beats GlobalComix ALU ($2–8/ch = ₹160–640/ch)
- **Per-page at volume beats Mantra contract** for non-publishers
- **Regional parity** — ₹199 ≈ $2.40 (vs $3.99 global) reflects purchasing power

---

## 7. TOP LEGAL & BUSINESS RISKS

### Legal Risks (Priority Order)

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| **Copyright infringement liability** (user uploads licensed manga) | **HIGH** | **CRITICAL** | **Tool-only architecture**: no hosting, no distribution, local processing option, clear ToS, DMCA agent, rights metadata fields |
| **Font licensing** (commercial manga fonts: Wild Words, Badaboom BB, CC Wild Words) | **HIGH** | **HIGH** | **Free-font-only default** (Google Fonts/OFL: Noto, Komika, Roboto). Warn on commercial font upload. Partner with font foundries for optional licensed packs. |
| **DMCA takedowns on output hosting** (if you ever host) | **MEDIUM** | **HIGH** | **Never host user output**. 10-day cache max (like AI Manga Translator). User downloads, owns responsibility. |
| **Patent/IP on manga-specific OCR/typesetting** | **LOW** | **MEDIUM** | Use open-source components (manga-ocr, comic-text-detector, LaMa) with MIT/Apache licenses. Avoid Mantra's proprietary "typesetting spec" patent area. |
| **Data privacy (user uploads, samples)** | **MEDIUM** | **MEDIUM** | Local-first option. Zero-retention policy. GDPR/India DPDP compliance. No training on user data. |

### Business Risks

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| **Toonsutra/INKR build creator tools** | **MEDIUM** | **HIGH** | **Speed to market**: ship MVP in 3–4 months. **Moat**: Hinglish tone + font matching + community workflow — hard to retrofit. |
| **Google/Meta release free manga translation** | **LOW** | **HIGH** | **Niche focus**: Indic languages + Hinglish + font matching + chapter workflow. General tools won't specialize. |
| **Scanlation community rejects paid tool** | **MEDIUM** | **MEDIUM** | **Free tier generous** (5 pg/day). **Community features** (shared glossary, tone presets). **Discord integration**. |
| **Indian payment infrastructure (UPI, GST)** | **HIGH** | **MEDIUM** | Use Razorpay/Stripe India. GST-compliant invoicing. INR pricing avoids FX friction. |
| **Talent acquisition (Indic NLP, font tech)** | **MEDIUM** | **HIGH** | Partner with IIIT/Hindi NLP researchers. Use open-source base (manga-ocr, IndicTrans2). Hire 1–2 ML engineers early. |

---

## 8. GO-TO-MARKET SEQUENCE

### Phase 1: MVP (Months 1–4) — "Scanlation Tool for Indic Languages"
- **Core:** OCR (manga-ocr + PaddleOCR) → MT (IndicTrans2 + Gemini) → Inpaint (LaMa) → Typeset (font match + tone)
- **Languages:** Hindi, Tamil, Telugu, Marathi, Bengali (Hinglish toggle)
- **Formats:** JPG/PNG/CBZ/PDF → translated CBZ/PDF
- **Editor:** Tone slider, font override, glossary, batch export
- **Distribution:** GitHub (open core), Discord community, Product Hunt, r/mangaindia, r/animeindian
- **Price:** Free (open core) + ₹199/mo cloud (GPU, models, storage)

### Phase 2: Community & Workflow (Months 4–8)
- **Team features:** Shared glossary, reviewer roles, tone presets per series
- **Chrome extension:** Translate on MangaDex, Pixiv, Toonsutra (if allowed)
- **API:** For studios/agencies (₹599/mo tier)
- **Partnerships:** Otaku Nadu, AnimeMirchi, Indian creator Discords
- **Content:** Tutorial videos (Hindi/English), template glossaries for popular series

### Phase 3: Platform & Scale (Months 8–18)
- **Local-first desktop app** (Electron + ONNX) — zero marginal cost for power users
- **Enterprise features:** License metadata, audit logs, SSO, on-premise
- **Regional expansion:** Gujarati, Kannada, Malayalam, Odia, Punjabi, Assamese
- **Donghua/Manhua pipeline:** Vertical scroll, colorization, audio narration (Lyria-style)
- **Revenue target:** ₹50L ARR (≈$60K) by Month 12, ₹5Cr ARR (≈$600K) by Month 24

---

## 9. SUCCESS METRICS

| Metric | Phase 1 (M4) | Phase 2 (M8) | Phase 3 (M18) |
|--------|--------------|--------------|---------------|
| **Active Users (MAU)** | 500 | 3,000 | 20,000 |
| **Paid Subscribers** | 50 | 300 | 2,000 |
| **Pages Translated/Month** | 10K | 100K | 1M |
| **Languages Supported** | 5 | 8 | 12 |
| **Community Glossaries** | 10 | 100 | 500 |
| **ARR** | ₹6L ($7K) | ₹36L ($43K) | ₹5Cr ($600K) |
| **NPS** | >30 | >50 | >60 |

---

## 10. FINAL RECOMMENDATION SUMMARY

### **Build This:**
1. **Hinglish-first tone engine** (sample-based few-shot, per-character)
2. **Font style detection → OFL font matching** (per-bubble, visual parity)
3. **Chapter-aware workflow** (CBZ/EPUB/PDF → glossary persistence → tone consistency)
4. **Indian pricing** (₹199/mo indie, ₹599/mo studio) + generous free tier
5. **Legal-safe by design** (local-first option, no hosting, rights metadata)
6. **Community-native** (Discord bot, shared glossaries, reviewer roles)

### **Don't Build (Yet):**
- Video/dubbing (Muse India owns this)
- Reader app (Toonsutra owns this)
- Enterprise editorial QA (Mantra owns this)
- General image translation (PicTranslate/ImageTranslate own this)
- Japanese-only OCR (manga-ocr is better, contribute upstream)

### **Partner With:**
- **Otaku Nadu / AnimeMirchi** — early adopters, feedback, community trust
- **Indian font foundries** — licensed manga font packs (optional paid add-on)
- **IIIT/Indic NLP researchers** — Hinglish tone models, evaluation benchmarks
- **Toonsutra (long-term)** — creator tool ecosystem, not competitor

### **Exit/Scale Options:**
- **Acquisition:** Toonsutra, INKR, GlobalComix, Google (AI Futures), Kakao/Naver (India entry)
- **Platform:** Become "GlobalComix for Indic Languages" — localization infra for Indian publishers
- **Vertical:** Expand to light novels, web novels, manhua, donghua comics

---

**Files Created:**
- `C:\Users\welcome\research\stage1_player_list.md` (100 entities)
- `C:\Users\welcome\research\stage2_batch1_deepdive.md` (5 commercial SaaS)
- `C:\Users\welcome\research\stage2_batch2_deepdive.md` (5 scanlation/platform/dub)
- `C:\Users\welcome\research\stage3_cross_analysis.md` (this file)

**Next:** Stage 4 (Gap Analysis) + Stage 5 (Detailed Pricing/Positioning/Risks) — or proceed to implementation planning?
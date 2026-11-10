# Stage 1: Full Player List — Manga/Comic Translation & Typesetting Ecosystem

**Date:** 2026-11-10  
**Sources:** Web search, Product Hunt, Reddit, Wikipedia, company sites, GitHub, news articles  
**Note:** All entries have at least one source URL. "ESTIMATE" = reasoned guess; "UNVERIFIED" = unconfirmed.

---

## CATEGORY 1: AI Manga/Comic Translation & Typesetting Tools (Commercial SaaS)

| # | Name | Type | URL | Notes |
|---|------|------|-----|-------|
| 1 | **Mantra Engine** | Enterprise AI translation + typesetting for publishers | https://mantra.co.jp/en/ | Japanese startup (founded 2020), Square Enix investor/partner. "Manga for everyone, in every language." Enterprise-only, no public pricing. |
| 2 | **PicTranslate** | Hosted AI image/manga translator (credit-based) | https://pictranslate.ai/ | 130+ languages, manga mode (bubbles, vertical text, SFX). Free: 10 credits/day. Pro $9.99/mo (3K credits), Max $19.99/mo (6K credits). Credit packs $9.99–$99.99. |
| 3 | **AI Manga Translator (ai-manga-translator.com)** | Web SaaS, manga-only, per-page pricing | https://ai-manga-translator.com/ | Chrome extension, CBZ/EPUB/PDF support. Basic $12/mo. Claims $0.013–0.020/page at scale. Claude-powered. |
| 4 | **PanelFont** | Web-based manga/comic translator | https://innovaai.io/service/panelfont | Pro $9.99/mo. 100+ languages. Multi-threaded batch. Early stage, no published benchmarks. |
| 5 | **MangaTranslate (mangatranslate.com)** | Web SaaS by Ficory LLC | https://mangatranslate.com/ | Three models (Manga/Ultra/EagleEye), 14 font styles, Studio editor. Credit-based. |
| 6 | **Gurafia Manga Translator** | Independent tool (aimangatranslator.net) | https://www.producthunt.com/products/ai-manga-translator-8 | 1 page free, then credits. Not affiliated with other "AI Manga Translator" brands. |
| 7 | **TheMangaTranslator** | Web SaaS, 40+ languages, built-in editor | https://www.producthunt.com/p/themangatranslator/themangatranslator | Free trial. Context injection, visual editor for fonts/positions. |
| 8 | **ImageTranslate.ai** | General image translator with manga mode | https://techshark.io/tools/imagetranslate/ | Starter $9.90/mo (5K credits). 130+ langs. Font matching, texture-aware synthesis. API on paid tiers. |
| 9 | **Manga OCR Translator (Apify Actor)** | API-only, batch OCR + translation | https://parseforge.co/a/manga-ocr-translator/ | Returns structured JSON (original + translations). 16 target langs incl. Hindi. Pay-per-run. |
| 10 | **AI Manga Translator (peters-lab/ai-manga-translator-official)** | Next.js 14 web tool + Chrome extension | https://github.com/peters-lab/ai-manga-translator-official | 20+ languages. Context-aware OCR, automated typesetting (beta). Indie creator focus. |

---

## CATEGORY 2: Open-Source / Self-Hosted Translation Pipelines (GitHub)

| # | Name | Type | URL | Notes |
|---|------|------|-----|-------|
| 11 | **manga-translator (neartana)** | CLI + Web UI, full pipeline | https://github.com/neartana/manga-translator | YOLO detection, manga-ocr/EasyOCR, LaMa inpaint, LLM translation, auto-fitted fonts. MIT license. |
| 12 | **manga-translator-ui (hgmzhn)** | Desktop app (Win/Mac/Linux), rich editor | https://gitcode.com/hgmzhn/manga-translator-ui | 5 translation engines (OpenAI, Gemini, etc.). Smart balloon layout, full rich-text editor, font management. CC BY-NC 4.0 (non-commercial). |
| 13 | **MangaTranslator (meangrinch/mudassirsenpai/amarabass)** | Gradio web UI + CLI, 60 langs | https://github.com/meangrinch/MangaTranslator | YOLO + SAM 2.1/3 detection, diffusion inpaint (FLUX, LaMa), LLM translation, custom font packs. Multiple forks. |
| 14 | **AutoScanlate-AI (P4ST4S)** | Docker stack (PostgreSQL, Redis, Go, Next.js, Python worker) | https://github.com/P4ST4S/AutoScanlate-AI | Fully local, GPU-accelerated. Frontend + Backend + AI Worker. Requires Docker, Go, Python, CUDA. |
| 15 | **manga-translation (M3MONs)** | Offline ONNX Runtime pipeline | https://github.com/M3MONs/manga-translation | comic-text-detector, manga-ocr/PaddleOCR, NLLB-200 600M, LaMa, Noto Sans fonts. Fully local. |
| 16 | **manga-image-translator (zyddnys/tahuakun/misaka10843)** | Web server + browser userscript | https://github.com/tahuakun/manga-image-translator-main | Demo: https://touhou.ai/imgtrans/. PaddleOCR, LaMa, custom renderer. Docker images available. |
| 17 | **manga-ocr (autocomic/kha-white)** | Japanese OCR library (ViT+RoBERTa) | https://github.com/autocomic/manga-ocr | Vertical/horizontal, furigana, multi-line. `pip install manga-ocr`. Core component used by many pipelines. |
| 18 | **comic-text-detector (kha-white)** | YOLO/RT-DETR text detection | https://github.com/kha-white/comic-text-detector | Extracts bboxes, lines, segmentation masks. Used by manga-image-translator. |
| 19 | **manga-text-removal (Arybil)** | LaMa inpainting engines (3 variants) | https://github.com/Arybil/manga-text-removal | Live demo: https://komikaku.duckdns.org/clean. `ctd_lama.py` default (AI detection + LaMa). |
| 20 | **Anime-Manga / Kites (ZuhairZeiter)** | In-browser WebGPU, 100% local | https://github.com/ZuhairZeiter/Anime-Manga | PaddleOCR v3-v6, WebGPU inpainting, studio typesetting. No server, runs in browser. |
| 21 | **manga-reader (Tolkium)** | Browser extension, reads bubbles aloud | https://github.com/Tolkium/manga-reader | comic-text-and-bubble-detector + Qwen3-VL. Local TTS. Accessibility focus. |
| 22 | **Pear (k-omiq)** | Rust desktop typesetting app | https://github.com/k-omiq/Pear | Balloon-aware lettering, gradients, patterns, bulk styling, font roughening, perspective warp. |
| 23 | **CarrotMangaTranslator (ucx0204)** | PySide6 desktop, ONNX, Windows | https://github.com/ucx0204/CarrotMangaTranslator | OCR, LLM translation, auto inpainting, typesetting. Batch images/PDF. |
| 24 | **ComfyUI-Speech-Bubble (miya805843)** | ComfyUI custom node for bubble overlay | https://github.com/miya805843/ComfyUI-Speech-Bubble | Font detection, system/custom fonts. Generative workflow integration. |

---

## CATEGORY 3: Scanlation Groups & Fan Communities (incl. Hindi)

| # | Name | Type | URL | Notes |
|---|------|------|-----|-------|
| 25 | **MangaDex Groups** | Aggregator platform for scanlation groups | https://mangadex.org/groups | Thousands of groups. Language filter. Redo Scans, Valhalla Scanlation, etc. Discord-linked. |
| 26 | **Otaku Nadu Scanlations** | Indian group → English, Tamil, Indic langs | https://mangadex.org/group/b7b14941-d383-4541-8457-12cf0dbbbfee | "Otaku Nadu's pet project to translate interesting Manga to English, Tamil and other Indic Languages!" Discord: #scanlations channel. |
| 27 | **AnimeMirchi (Reddit u/...)** | Hindi scanlator (Look Back, etc.) | https://www.reddit.com/r/AnimeMirchi/comments/1rosfb8/ | DMCA'd on MangaDex. Re-uploading elsewhere. "Shuddh Hindi scanlation." |
| 28 | **r/mangaindia** | Indian manga community, Hindi cover designs | https://www.reddit.com/r/mangaindia/comments/1rngdsl/ | User iotaku_106 designed Hindi Wotakoi covers. "Manga scanlator also uses it." |
| 29 | **Valhalla Scanlation** | Multi-lang group (EN), Patreon/Ko-fi monetization | https://mangadex.org/group/86c31a99-7862-41e3-a11e-d117d56274d0 | Website: valhallascans.com. Patreon for downloads. Recruiting JP/CN/KR translators. |
| 30 | **AceToon** | Free reader platform (scanlation uploads) | https://acetoon.org/about?lang=en | Not a publisher. Groups/users upload, keep control. Free, no paywall. |
| 31 | **MangaUpdates Groups** | Directory of scanlation groups | https://www.mangaupdates.com/groups | Legacy directory. Group info, websites, contact. |
| 32 | **Scanlation Discords** | Community hubs | https://discord.gg/mangadex, https://discord.gg/xAsyVb52a9 | Mangadex Discord (group channels). Scan Directory Discord. Recruitment threads on r/Scanlation. |
| 33 | **r/Scanlation Self-Promo Threads** | Monthly recruitment | https://www.reddit.com/r/Scanlation/comments/1iqwp6q/ | Groups post Discord invites, seek translators/cleaners/typesetters. Jan 2024, Feb 2025 threads. |

---

## CATEGORY 4: Official Platforms & Publishers (Global + India Hindi Support)

| # | Name | Type | URL | Hindi? | Notes |
|---|------|------|-----|--------|-------|
| 34 | **WEBTOON (Naver Webtoon / LINE Webtoon)** | Global platform, freemium | https://www.webtoons.com/ | **No** (EN, ES, FR, TH, ID, ZH, etc.) | Weekly free episodes, Fast Pass coins. Fan translation feature exists. Nasdaq: WBTN. |
| 35 | **Tapas (Tapas Entertainment / Kakao)** | Webtoon + prose, English | https://tapas.io/ | **No** (EN only) | **Shutting down 31 Mar 2027**. Wait Until Free, Ink currency. Kakao subsidiary. |
| 36 | **Kakao Page / Kakao Webtoon** | Korean platform | https://page.kakao.com/ | **No** (KR only) | Merging into Kakao Page by end-2026. Thai/TC/ID discontinued. |
| 37 | **Lezhin Comics** | Premium mature webtoons | https://www.lezhin.com/ | **No** (EN, KR, JP) | Coin-based, mature/BL focus. Region-locked catalog. |
| 38 | **Toomics** | Subscription + store, 11 langs | https://toomics.com/ | **No** (EN, CN, JP, TH, etc.) | 50K+ episodes. Mature content web-only (not in apps). VIP subscription. |
| 39 | **Tappytoon** | Licensed manhwa, pay-per-episode | https://tappytoon.com/ | **No** (EN) | Points, Time Till Free, Club subscription. Premium romance/fantasy. |
| 40 | **Manta** | Subscription binge-reading | https://manta.net/en | **No** (EN) | Standard/Premium plans. 300+ titles in Unlimited Library. Gems for non-included. |
| 41 | **Kross Komics** | **Defunct** (India, 2020–2023) | https://www.mangaupdates.com/publisher/sx77wmg/kross-komics | **Was: Yes (HI, TE, EN)** | Acquired by Kakao 2021, shut down Dec 2022. 40 titles in HI/TE/EN. 1.1M MAU at peak. |
| 42 | **Toonsutra** | **India #1 webtoon app** | https://toonsutra.com/ | **YES (HI, TA, TE, EN)** | 3,100+ titles, 500K+ episodes. Google-backed, $3.2M seed (Holtzbrinck, Graphic India, Gen Fukunaga). 2M+ downloads. Gemini 2.0 Flash for translation. |
| 43 | **INKR Comics** | Global platform + localization studio | https://comics.inkr.com/ | **No** (12 langs: DE, ES, FR, ID, IT, JP, KR, PT, TH, VI, ZH-CN, ZH-TW) | Singapore. 1,000+ titles. GlobalComix Studio (free → Pro/Enterprise). AI-assisted localization. |
| 44 | **GlobalComix / GlobalComix Studio** | Creator-first platform + AI localization | https://globalcomix.com/ / https://mystudio-globalcomix.inkr.com/ | **No** (12 langs, same as INKR) | USA, founded 2017, Series A. Free plan (watermarks), Pro/Enterprise. Cuts publishing cost 90%. |
| 45 | **WebComics** | Mobile-first webtoon app | (various) | UNVERIFIED | Listed in market reports alongside INKR, Manta, Tappytoon. |
| 46 | **ComiXology (Amazon)** | Digital comics store | https://www.comixology.com/ | **No** (EN primarily) | Subscription (Unlimited) + a la carte. Manga/manhwa selection. |
| 47 | **Marvel Unlimited** | Marvel-only subscription | https://www.marvel.com/comics/unlimited | **No** | Listed in India webtoon market reports as competitor. |
| 48 | **Pocket Comics (NHN)** | **Defunct** (closed Oct 2025) | — | **No** | Mentioned in EpicKor comparison table. |
| 49 | **DayComics (ex-TopToonPlus)** | Global rebrand 2023 | https://daycomics.com/ | UNVERIFIED | Listed in Wikipedia. |
| 50 | **Lalatoon (Toomics sibling)** | Mature-focused, shared library | — | UNVERIFIED | Some exclusives vs Toomics. |

---

## CATEGORY 5: Indian Comic / Webtoon / Regional Platforms

| # | Name | Type | URL | Languages | Notes |
|---|------|------|-----|-----------|-------|
| 51 | **Toonsutra** | Premium webtoon app (see #42) | https://toonsutra.com/ | HI, TA, TE, EN (+ BN, MR, ML, KN planned) | Graphic India spinout. Baahubali, Legend of Hanuman exclusives. Google DeepMind showcase. |
| 52 | **Graphic India** | Publisher / creator (Chakra, Baahubali) | https://graphicindia.com/ | HI, EN (comics) | Parent of Toonsutra. Liquid Comics. Sharad Devarajan (co-founder Toonsutra). |
| 53 | **Pratilipi** | Indian storytelling platform (text + comics) | https://pratilipi.com/ | HI, TA, TE, MR, BN, GU, KN, ML, EN, PA, OR, AS | 80M+ users. Comics vertical. Acquired by Koo? UNVERIFIED. |
| 54 | **Kross Komics** | **Defunct** (see #41) | — | Was HI, TE, EN | Kakao subsidiary. Shut down 2022/2023. |
| 55 | **Dailyhunt (VerSe Innovation)** | News + content app | https://dailyhunt.in/ | 14+ Indian langs | Toonsutra CEO Vishal Anand ex-CPO Dailyhunt. Potential distribution partner. |
| 56 | **Amar Chitra Katha / ACK Media** | Legacy Indian comics publisher | https://www.amarchitrakatha.com/ | HI, EN, regional | Digital app. Mythology/history focus. |
| 57 | **Tinkle / ACK Digital** | Children's comics magazine + app | https://tinkle.in/ | EN, HI | Legacy brand going digital. |
| 58 | **Comics Byte** | Indian comic news/reviews | https://comicsbyte.com/ | EN | Media site, not a platform. |
| 59 | **AnimationXpress** | Industry news (covers Toonsutra, Kross) | https://www.animationxpress.com/ | EN | Trade publication. |

---

## CATEGORY 6: OCR / Text-Removal / Typesetting / Font-ID Tech Vendors (B2B)

| # | Name | Type | URL | Offering |
|---|------|------|-----|----------|
| 60 | **Mantra Engine** (see #1) | Enterprise manga AI | https://mantra.co.jp/en/ | Typesetting spec engine (Square Enix JV). Font/style estimation per bubble. |
| 61 | **manga-ocr** (autocomic/kha-white) | OCR library (open core) | https://github.com/autocomic/manga-ocr | Japanese ViT+RoBERTa. Vertical, furigana, multi-line. Used commercially by many. |
| 62 | **comic-text-detector** (kha-white) | Detection model (open) | https://github.com/kha-white/comic-text-detector | YOLO/RT-DETR for bubbles, lines, masks. Base for downstream pipelines. |
| 63 | **LaMa / simple-lama-inpainting** | Inpainting (open) | https://github.com/Arybil/manga-text-removal | Text removal via LaMa. 3 engines. Live demo. |
| 64 | **PaddleOCR** | General multilingual OCR | https://github.com/PaddlePaddle/PaddleOCR | v3-v6 used by Kites, manga-image-translator. 80+ langs. |
| 65 | **EasyOCR** | General OCR (80 langs) | https://github.com/JaidedAI/EasyOCR | Fallback in neartana pipeline. CPU/GPU. |
| 66 | **RapidOCR (ONNX)** | Lightweight OCR | https://github.com/RapidAI/RapidOCR | No PyTorch. Used as fallback in neartana. |
| 67 | **NLLB-200 (Meta)** | Machine translation (open) | https://github.com/facebookresearch/fairseq | 200 langs. 600M distilled used in M3MONs pipeline. |
| 68 | **Google Translate / Cloud Translation API** | Cloud MT | https://cloud.google.com/translate | Fallback in neartana. Paid per character. |
| 69 | **DeepL API** | Cloud MT (high quality) | https://www.deepl.com/pro-api | Used in koesan pipeline. Paid per character. |
| 70 | **OpenAI / Anthropic / Gemini APIs** | LLM translation | various | Used by MangaTranslator forks, PicTranslate Max, AI Manga Translator. Pay-per-token. |
| 71 | **Font detection (ComfyUI-Speech-Bubble)** | Font metadata parsing | https://github.com/miya805843/ComfyUI-Speech-Bubble | Parses name table, detects system fonts, custom font dir. |
| 72 | **Adobe Fonts / Monotype / Fontspring** | Commercial font licensing | various | Manga fonts (Wild Words, Badaboom BB, Komika, CC Wild Words) require licenses for commercial use. |
| 73 | **Google Fonts / OFL fonts** | Free fonts | https://fonts.google.com/ | Noto Sans (JP, KR, SC, Thai), Roboto, Komika (some variants). Used in open-source packs. |

---

## CATEGORY 7: Donghua / Anime Subtitle & Dubbing Players (Hindi Focus)

| # | Name | Type | URL | Hindi Dub/Sub? | Notes |
|---|------|------|-----|----------------|-------|
| 74 | **Muse India / Muse Asia** | Official YouTube + distribution | https://youtube.com/@MuseIndiaChannel | **YES** (Dub + Sub) | SPY×FAMILY, Slime S4, Iruma-kun S3, Hunter×Hunter, Assassination Classroom, Campfire Cooking. Daily uploads. |
| 75 | **Crunchyroll** | Global anime streaming | https://www.crunchyroll.com/ | **YES** (Dub + Sub, expanding) | Hindi interface: No. Hindi audio/sub for select titles (Slime, Campfire Cooking, Exiled Heavy Knight). |
| 76 | **Netflix India** | Streaming | https://www.netflix.com/in/ | **YES** (Dub + Sub) | Slime S1-2, Hunter×Hunter, Campfire Cooking, Exiled Heavy Knight. Regional dubs (TA, TE). |
| 77 | **Amazon MX Player / Anime Times** | Streaming (Prime Video channel) | https://www.primevideo.com/ | **YES** (Dub) | Slime S1-2, Assassination Classroom S1-2, Campfire Cooking. |
| 78 | **JioHotstar (Disney+ Hotstar)** | Streaming | https://www.hotstar.com/in | **YES** (Dub + Sub) | SPY×FAMILY, Assassination Classroom, Exiled Heavy Knight. |
| 79 | **Sony LIV / Sony YAY / Cartoon Network India** | TV + streaming | various | **YES** (Dub, TV broadcast) | Assassination Classroom (Sony LIV), Hunter×Hunter (Cartoon Network). |
| 80 | **Airtel Xstream** | Telco streaming bundle | https://airtelxstream.in/ | **YES** (Dub) | Listed by Muse India as distribution point. |
| 81 | **Anime Times (Prime Video channel)** | Anime-specific channel | https://www.primevideo.com/ | **YES** (Dub + Sub) | Slime, Hunter×Hunter, Campfire Cooking. |
| 82 | **Hall of C (Guodong)** | Fan sub group (mostly retired) | Reddit r/Donghua mentions | **Subs (EN)** | High-quality donghua fansubs. Retired after copyright claims. |
| 83 | **LManime** | Fan sub group | Reddit r/Donghua mentions | **Subs (EN)** | "Decent work, not missing info." Limited uploads. |
| 84 | **Tencent / WeTV / iQIYI** | Chinese platforms (global) | https://wetv.vip/ | **Subs (EN, sometimes HI?)** | Official donghua source. Soul Land subs criticized. Hindi UNVERIFIED. |
| 85 | **Bilibili International** | Chinese platform (global) | https://www.bilibili.tv/ | **Subs (EN)** | Donghua source. Hindi UNVERIFIED. |

---

## CATEGORY 8: Adjacent / Infrastructure / Aggregators

| # | Name | Type | URL | Relevance |
|---|------|------|-----|-----------|
| 86 | **MangaDex** | Scanlation aggregator (API) | https://mangadex.org/ | Primary distribution for scanlation groups. API for metadata. |
| 87 | **MangaUpdates** | Metadata database | https://www.mangaupdates.com/ | Series, group, publisher info. |
| 88 | **Anilist / MyAnimeList** | Anime/manga tracking | https://anilist.co/ | Community data, ratings. |
| 89 | **VNDB** | Visual novel database | https://vndb.org/ | Adjacent translation community. |
| 90 | **Reddit: r/manga, r/manhwa, r/donghua, r/animeindian, r/scanlation** | Communities | reddit.com | User sentiment, requests, group recruitment. |
| 91 | **Discord: Mangadex, Scan Directory, group servers** | Real-time coordination | discord.gg | Scanlation workflow, recruitment, releases. |
| 92 | **Product Hunt** | Launch platform | producthunt.com | New AI manga tools launch here (multiple "AI Manga Translator" entries). |
| 93 | **F6S / InnovaAI / VentureRadar** | Startup databases | f6s.com, innovaai.io, ventureradar.com | Funding, team size, traction signals. |
| 94 | **Google Play / App Store** | Mobile distribution | play.google.com, apps.apple.com | Toonsutra, INKR, Crunchyroll, Netflix apps. Ratings, downloads. |
| 95 | **Holtzbrinck Publishing Group** | Investor (Toonsutra) | https://www.holtzbrinck.com/ | Macmillan, Springer Nature parent. $3.2M seed lead. |
| 96 | **Gen Fukunaga (Funimation founder)** | Investor/advisor (Toonsutra) | — | Anime industry veteran. |
| 97 | **Graphic India / Liquid Comics** | Content studio + IP | https://graphicindia.com/ | Toonsutra parent. Baahubali, Legend of Hanuman IP. |
| 98 | **Square Enix** | Publisher + Mantra investor | https://www.square-enix.com/ | Manga publisher. Mantra JV for typesetting automation. |
| 99 | **Kakao Entertainment** | Platform conglomerate | https://kakaoent.com/ | Owns Tapas, Kakao Page, Kakao Webtoon, Kross Komics (defunct), Radish. |
| 100 | **Naver / WEBTOON Entertainment** | Platform conglomerate | https://www.webtoons.com/ | Nasdaq: WBTN. Owns LINE Webtoon, Wattpad. |

---

## SUMMARY BY CATEGORY

| Category | Count | Key Players |
|----------|-------|-------------|
| 1. Commercial AI SaaS | 10 | Mantra, PicTranslate, AI Manga Translator, PanelFont, MangaTranslate, Gurafia, TheMangaTranslator, ImageTranslate, Manga OCR Translator, Peters-lab |
| 2. Open-Source Pipelines | 14 | neartana, hgmzhn, meangrinch, P4ST4S, M3MONs, zyddnys, autocomic, kha-white, Arybil, ZuhairZeiter, Tolkium, k-omiq, ucx0204, miya805843 |
| 3. Scanlation Groups | 9 | MangaDex groups, Otaku Nadu, AnimeMirchi, r/mangaindia, Valhalla, AceToon, MangaUpdates, Discords, r/Scanlation threads |
| 4. Official Platforms | 17 | WEBTOON, Tapas, Kakao, Lezhin, Toomics, Tappytoon, Manta, Kross Komics (dead), Toonsutra, INKR, GlobalComix, WebComics, ComiXology, Marvel Unlimited, Pocket Comics (dead), DayComics, Lalatoon |
| 5. Indian Platforms | 9 | Toonsutra, Graphic India, Pratilipi, Kross Komics (dead), Dailyhunt, ACK, Tinkle, Comics Byte, AnimationXpress |
| 6. Tech Vendors (OCR/Font/MT) | 14 | Mantra, manga-ocr, comic-text-detector, LaMa, PaddleOCR, EasyOCR, RapidOCR, NLLB, Google/DeepL/LLM APIs, Font detection, Adobe/Monotype, Google Fonts/OFL |
| 7. Donghua/Anime Hindi | 12 | Muse India, Crunchyroll, Netflix, MX Player/Anime Times, JioHotstar, Sony LIV/YAY/CN, Airtel Xstream, Hall of C, LManime, Tencent/WeTV, Bilibili |
| 8. Adjacent/Infra | 15 | MangaDex, MangaUpdates, Anilist, VNDB, Reddit, Discord, Product Hunt, F6S, VentureRadar, App Stores, Holtzbrinck, Gen Fukunaga, Graphic India, Square Enix, Kakao, Naver |

**Total unique entities: ~100**

---

## NEXT STEPS (Stage 2)

Deep-dive 5 players at a time, starting with highest-relevance commercial SaaS:
1. **Mantra Engine** (enterprise benchmark)
2. **PicTranslate** (pricing, manga mode, free tier)
3. **AI Manga Translator (ai-manga-translator.com)** (per-page pricing, Chrome ext, CBZ support)
4. **PanelFont** (early stage, $9.99/mo)
5. **MangaTranslate (mangatranslate.com)** (Ficory LLC, 3 models, Studio editor)

Then scanlation groups (Otaku Nadu, AnimeMirchi, Valhalla), then Indian platforms (Toonsutra, INKR/GlobalComix), then donghua Hindi players (Muse India, Crunchyroll), then tech vendors.
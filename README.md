<div align="center">

![Awesome Kling 4.0 prompt library hero](assets/images/hero-kling-prompt-cinema.png)

# Awesome Kling 4.0 Prompts

### A production-ready AI video prompt library for cinematic stories, product ads, UGC, dialogue, VFX, anime, food, travel, education and social video.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-5b8cff.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/original_prompts-24-ff9f43.svg)](prompts/README.md)
[![Languages](https://img.shields.io/badge/languages-5-38c172.svg)](#languages)
[![Status](https://img.shields.io/badge/Kling_4.0-community_preview-f5c542.svg)](#model-status-read-this-first)

**English** · [简体中文](README.zh-CN.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Español](README.es-ES.md)

[Browse all prompts](prompts/README.md) · [Prompting guide](docs/PROMPT-GUIDE.md) · [Multilingual audio](docs/MULTILINGUAL-AUDIO.md) · [Contribute](CONTRIBUTING.md)

</div>

> [!IMPORTANT]
> **Model status — 20 August 2026:** Kuaishou has not officially announced a Kling 4.0 model or API. The latest verified major release is **Kling AI 3.0**, launched on 5 February 2026. This repository is an independent, forward-compatible prompt collection built on confirmed Kling 3.0 capabilities, ready to be re-tested and updated when an official 4.0 specification appears. It is not affiliated with or endorsed by Kuaishou.

## Why this library is useful

Most AI video prompts describe only a pretty frame. Production prompts must also direct **time, motion, camera, continuity, sound and failure constraints**. Every recipe here is newly written around a reusable seven-layer structure:

```text
FORMAT → CONTINUITY ANCHORS → WORLD → TIMED SHOTS → PERFORMANCE → AUDIO → CONSTRAINTS
```

The collection includes:

- **24 original, copy-ready prompts** across 12 practical creator and business scenarios.
- **Text-to-video, image-to-video, start/end-frame and reference-led workflows**.
- **Single-take and multi-shot structures** with explicit timing and transition logic.
- **Native-audio direction** for dialogue, ambience, foley, music and intentional silence.
- **Five-language dialogue patterns** for Chinese, English, Japanese, Korean and Spanish.
- **Continuity anchors** for recurring characters, products, wardrobe, props and locations.
- **Model-aware guardrails** that reduce subject drift, speaker confusion and impossible motion.
- **Original example artwork** generated specifically for this repository, without reused thumbnails.

## Model status: read this first

The table deliberately separates verified facts from future-facing assumptions.

| Item | Verified status | How this repository handles it |
|---|---|---|
| Kling 4.0 release | **Not officially announced** as of 2026-08-20 | Uses “4.0-ready” naming; makes no invented resolution, price or API claim |
| Latest official generation | **Kling AI 3.0 series** | All capability labels use the official 3.0 release and guide as baseline |
| Video duration | Up to **15 seconds** in Video 3.0 | Prompts default to 5–15 second shot plans |
| Video output | Official guide lists **720p and 1080p** modes | No unsupported “native 4K video” claim |
| Multi-shot | Supported, including custom shot timing | Prompts separate beats by time, framing, motion and cut logic |
| Element consistency | Start frame + bound subject / element reference supported | Prompts declare stable identity and prop anchors |
| Native audio | Dialogue, ambience and effects; multilingual support | Audio is assigned per speaker and per time beat |
| Supported dialogue languages | Chinese, English, Japanese, Korean and Spanish | Ready-made syntax and examples for those five languages |
| 3+ character dialogue | Multi-character coreference is documented | Group scenes name every speaker and speaking order |
| Text preservation | Improved preservation of text from source images | Product prompts recommend supplying approved packaging as a reference |

Verified sources: [Kuaishou’s Kling AI 3.0 announcement](https://ir.kuaishou.com/news-releases/news-release-details/kling-ai-launches-30-model-ushering-era-where-everyone-can-be) and the [official Kling Video 3.0 user guide](https://app.klingai.com/cn/quickstart/klingai-video-3-model-user-guide).

## Start in 60 seconds

1. Pick a scenario from the [prompt catalog](prompts/README.md).
2. Replace every value in `{curly brackets}`; keep continuity anchors concrete.
3. Choose the appropriate generation mode: text, start image, start/end frames or element reference.
4. Match the requested duration and multi-shot settings in Kling’s interface.
5. Run a low-risk motion test, then change **one variable at a time**.

### Universal Kling video prompt template

```text
[OUTPUT]
Duration: {5–15 seconds}; aspect ratio: {16:9 / 9:16 / 1:1};
mode: {single continuous take / custom multi-shot}; visual finish: {look}.

[CONTINUITY ANCHORS]
Subject A: {age range, face, hair, body silhouette, wardrobe, signature detail}.
Subject B / product / prop: {shape, materials, fixed colors, fixed markings}.
Keep these anchors unchanged across every shot.

[WORLD]
{location, time, weather, practical light sources, foreground/background layout}.

[TIMED DIRECTION]
0–{x}s — {shot size + angle + camera path}. {one primary action}. {physical reaction}.
{x}–{y}s — {next shot or transition}. {one primary action}. {payoff}.

[PERFORMANCE]
{gaze, breathing, hand interaction, emotion progression, motion weight and speed}.

[AUDIO]
Speaker name ({language, tone, pace}): “{short line}”
Ambience: {continuous room tone}. Foley: {synchronized events}. Music: {entry/exit}.

[CONSTRAINTS]
Preserve identity, wardrobe, prop geometry, screen direction and lighting continuity.
One speaking mouth at a time. No unrequested text, subtitles, logos or watermarks.
No duplicate limbs, face drift, rubber motion, object penetration or teleporting props.
```

Read the [complete prompting guide](docs/PROMPT-GUIDE.md) for mode selection, timing, camera grammar, audio direction, negative constraints and iteration strategy.

## Featured original prompts

### 1. Premium botanical drink reveal

![Botanical drink product video keyframe](assets/images/prompt-product-botanical-drink.png)

A commercial workflow designed around stable packaging geometry, readable motion and three synchronized sound events.

**Best mode:** start image + element reference · **Format:** 9 seconds, 16:9 · **Skills:** macro motion, liquid physics, product lock, foley

[Copy the complete prompt →](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)

### 2. Authentic morning skincare UGC

<img src="assets/images/prompt-ugc-skincare.png" width="430" alt="Authentic vertical skincare UGC keyframe">

A deliberately imperfect phone-shot ad with a conversational hook, natural hand interaction and a clean claim-safe ending.

**Best mode:** image-to-video · **Format:** 12 seconds, 9:16 · **Skills:** handheld realism, direct-to-camera speech, natural skin texture

[Copy the complete prompt →](prompts/commercial-and-ugc.md#3-morning-skincare-ugc-one-take)

### 3. Multilingual station reunion

![Multilingual cinematic dialogue scene](assets/images/prompt-multilingual-reunion.png)

A restrained Korean–Spanish dialogue sequence using speaker assignment, eyeline continuity and rain ambience without subtitle dependence.

**Best mode:** multi-shot + two character references · **Format:** 15 seconds, 16:9 · **Skills:** identity continuity, multilingual speech, shot/reverse-shot

[Copy the complete prompt →](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)

### 4. Salt-canyon pursuit

![Science-fantasy salt canyon action sequence](assets/images/prompt-fantasy-salt-canyon.png)

A physics-led action prompt that separates vehicle trajectory, camera path, dust response and creature motion to keep the frame readable.

**Best mode:** start image + custom multi-shot · **Format:** 12 seconds, 21:9 or 16:9 · **Skills:** action geography, VFX scale, coherent motion

[Copy the complete prompt →](prompts/action-and-vfx.md#1-the-glass-manta-pursuit)

## Prompt catalog

| Collection | Practical scenarios | Prompts |
|---|---|---:|
| [Cinematic & dialogue](prompts/cinematic-and-dialogue.md) | short film, multilingual reunion, comedy dialogue, emotional micro-performance | 4 |
| [Commercial & UGC](prompts/commercial-and-ugc.md) | product reveal, e-commerce demo, skincare UGC, local-business ad | 4 |
| [Action & VFX](prompts/action-and-vfx.md) | pursuit, sports, material transformation, disaster-safe spectacle | 4 |
| [Style & performance](prompts/style-and-performance.md) | anime, fashion, music performance, dance motion | 4 |
| [Food, travel & spaces](prompts/food-travel-spaces.md) | ASMR cooking, destination film, hotel/real estate, craft process | 4 |
| [Education, documentary & social](prompts/education-documentary-social.md) | explainer, nature documentary, meme loop, public-interest story | 4 |

## Kling-oriented prompt design

### Use timed beats, not a shopping list

Each beat should contain one dominant subject action and one camera intention. For a 15-second clip, three or four readable beats generally outperform ten competing events.

### Lock references in language

Do not write “same woman” alone. Repeat a short, stable anchor such as “Mara — cropped silver hair, oval green glasses, rust utility coat” and bind the corresponding reference element when available.

### Separate camera motion from subject motion

```text
Camera: slow clockwise orbit, constant distance, horizon level.
Subject: bottle stays fixed; only condensation rolls downward.
Environment: mist travels left to right; peel completes one smooth spiral.
```

### Treat sound as a timeline

```text
0–3s: quiet room tone and fabric movement.
3.2s: cap click, centered and dry.
3–7s: fine carbonation rises; no music yet.
7–9s: two-note sonic signature enters, then clean silence.
```

### Prefer physical constraints over vague quality words

“Her right hand stays wrapped around the ceramic handle while the cup remains on the table” is more actionable than “perfect hands, masterpiece, best quality.”

## Languages

Repository navigation and quick-start guidance are available in five languages:

| Language | Guide | Native dialogue support in verified Kling 3.0 docs |
|---|---|---|
| English | [README](README.md) | Yes |
| 简体中文 | [使用指南](README.zh-CN.md) | 是 |
| 日本語 | [ガイド](README.ja-JP.md) | 対応 |
| 한국어 | [가이드](README.ko-KR.md) | 지원 |
| Español | [Guía](README.es-ES.md) | Sí |

For mixed-language scenes, pronunciation notes and speaker-safe examples, see [Multilingual Audio & Dialogue](docs/MULTILINGUAL-AUDIO.md).

## Originality and responsible use

- All prompts and descriptions in this repository were authored for this project; they are **not copied prompt entries** from another gallery.
- All local artwork was generated specifically for this repository and does not reuse third-party thumbnails or videos. See the [image asset manifest](assets/images/README.md) for provenance and generation prompts.
- Do not use a real person’s likeness, voice, brand assets or copyrighted characters without permission.
- Review product claims, disclosures, music rights, location rules and advertising requirements before commercial use.
- Generated output may contain errors. Check anatomy, speech, signage, packaging, safety and cultural context before publication.

## Contributing

New prompt recipes, tested failure notes, verified capability updates and translations are welcome. Each contribution must be original, reproducible and clearly separate **verified facts** from personal testing. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Code, documentation and original prompt text are released under the [MIT License](LICENSE). Generated media may be subject to the terms of the tool used to create it. “Kling” is a trademark of its respective owner; use here is descriptive.

---

<div align="center">

**Kling 4.0 prompts · Kling AI video prompts · AI video prompt engineering · cinematic prompts · product video prompts · UGC prompts · multilingual AI video**

If this library saves you a production test, consider starring the repository and sharing a tested variation.

</div>

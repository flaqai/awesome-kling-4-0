# Language & Localization Directory

[Home](../README.md) · [Prompt catalog](../prompts/README.md) · [Multilingual audio](MULTILINGUAL-AUDIO.md)

This repository provides navigation and quick-start guidance in **15 languages**. Language coverage in the repository is not the same as native speech support in a video model.

> **Verified Kling Video 3.0 native-dialogue languages:** Chinese, English, Japanese, Korean and Spanish. Other languages below are documentation/localization languages. For unsupported spoken dialogue, test the live model first or generate clean visuals and add verified voice-over in post-production.

## 15-language directory

| Language | Localized guide | Repository UI | Verified native dialogue baseline |
|---|---|---:|---:|
| English | [README](../README.md) | Full | Yes |
| 简体中文 | [使用指南](../README.zh-CN.md) | Full | 是 |
| 繁體中文 | [使用指南](../README.zh-TW.md) | Quick start | 是 |
| 日本語 | [ガイド](../README.ja-JP.md) | Quick start | 対応 |
| 한국어 | [가이드](../README.ko-KR.md) | Quick start | 지원 |
| Español | [Guía](../README.es-ES.md) | Quick start | Sí |
| Français | [Guide](../README.fr-FR.md) | Quick start | Not in verified list |
| Deutsch | [Leitfaden](../README.de-DE.md) | Quick start | Not in verified list |
| Português (Brasil) | [Guia](../README.pt-BR.md) | Quick start | Not in verified list |
| Italiano | [Guida](../README.it-IT.md) | Quick start | Not in verified list |
| العربية | [الدليل](../README.ar.md) | Quick start | Not in verified list |
| Русский | [Руководство](../README.ru-RU.md) | Quick start | Not in verified list |
| Bahasa Indonesia | [Panduan](../README.id-ID.md) | Quick start | Not in verified list |
| ไทย | [คู่มือ](../README.th-TH.md) | Quick start | Not in verified list |
| Tiếng Việt | [Hướng dẫn](../README.vi-VN.md) | Quick start | Not in verified list |

## What is localized

| Content | English | Simplified Chinese | Other 13 languages |
|---|---:|---:|---:|
| Project positioning and model-status warning | Full | Full | Summary |
| Prompt catalog navigation | Full | Full | Linked |
| Universal prompt structure | Full | Full | Localized quick template |
| 52 production prompts | Canonical English source | Canonical source linked | Canonical source linked |
| Native-audio examples | Five-language shared guide | Five-language shared guide | Shared guide with support warning |
| FLAQ.AI introduction | Full | Full | Localized summary |

The English prompt files are the canonical technical source. This prevents twenty-four complex shot plans from silently drifting across multiple translations. Localized guides explain the method and route readers to stable prompt IDs.

## Shared prompt labels

Use the same block order in any language. Models often handle clear labels better than prose with mixed purposes.

| Meaning | EN | 简中 | 日本語 | 한국어 | ES |
|---|---|---|---|---|---|
| Output | `[OUTPUT]` | `[输出]` | `[出力]` | `[출력]` | `[SALIDA]` |
| Continuity anchors | `[CONTINUITY ANCHORS]` | `[连续性锚点]` | `[連続性アンカー]` | `[연속성 앵커]` | `[ANCLAS DE CONTINUIDAD]` |
| World / location | `[WORLD]` | `[空间与环境]` | `[空間・環境]` | `[공간과 환경]` | `[MUNDO Y ESPACIO]` |
| Timed shots | `[TIMED SHOTS]` | `[逐秒镜头]` | `[時間別ショット]` | `[시간별 샷]` | `[PLANOS POR TIEMPO]` |
| Performance | `[PERFORMANCE]` | `[表演]` | `[演技]` | `[연기]` | `[INTERPRETACIÓN]` |
| Audio | `[AUDIO]` | `[声音]` | `[音声]` | `[오디오]` | `[AUDIO]` |
| Constraints | `[CONSTRAINTS]` | `[约束]` | `[制約]` | `[제약]` | `[RESTRICCIONES]` |

## Localization rules

1. Preserve prompt IDs, character names, timecodes and reference numbering.
2. Translate directing intent, not just individual words.
3. Keep exact spoken dialogue in the intended performance language.
4. Do not turn a documentation language into an unsupported native-audio claim.
5. Keep camera direction and screen direction unambiguous after translation.
6. Localize examples culturally; do not stereotype accents, clothing or behavior.
7. Verify names, numbers, technical terms, packaging and subtitles independently.
8. Add accessible captions in post-production when frame-to-frame text stability matters.

## Template for any language

```text
[OUTPUT / LOCALIZED LABEL]
{duration}; {aspect ratio}; {single take or multi-shot}; {visual finish}.

[CONTINUITY]
{named adult subject, stable face/hair/silhouette/wardrobe};
{product or prop shape, material, color, markings}. Keep unchanged.

[WORLD]
{location, time, weather, practical light, starting positions}.

[TIMED SHOTS]
0–{x}s — {shot size, angle, camera path}. {one primary action}. {physical response}.
{x}–{y}s — {next shot}. {one primary action}. {payoff and final frame}.

[AUDIO]
{speaker} ({language, tone, pace}): “{short exact line}”
{ambience}; {synchronized foley}; {music entry/exit}.

[CONSTRAINTS]
Preserve identity, geometry, direction and lighting. One speaking mouth at a time.
No unrequested text, translation, subtitles, logos, watermarks or extra objects.
```

## Contributing a localization

Before adding a language, translate one complete prompt and compare it with the canonical English version for timing, camera path, identity anchors, audio ownership and constraints. Ask a fluent reviewer to check both naturalness and technical meaning. See [CONTRIBUTING.md](../CONTRIBUTING.md).

# Kling AI Video Prompt Catalog

[Home](../README.md) · [中文指南](../README.zh-CN.md) · [15 languages](../docs/LANGUAGES.md) · [Prompting guide](../docs/PROMPT-GUIDE.md) · [Multilingual audio](../docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI workflow](../docs/FLAQ-AI.md)

This catalog contains **52 original production prompts** grouped into thirteen collections. It spans narrative, commerce, reference control, editing, mobility, industrial, education, viral social, motion graphics, transition and production-tool workflows. Every prompt can be copied as-is or treated as a scaffold. Replace `{variables}`, select the matching input mode, and remove any instruction that is not visible or audible in your intended clip.

> **Compatibility note:** The repository targets a future official Kling 4.0 release, but the capability labels are grounded in verified Kling Video 3.0 behavior as of 2026-09-01. Settings and availability can vary by region, account and model mode.

## Choose by goal

| Goal | Recommended prompt | Best input strategy |
|---|---|---|
| Emotional short film | [Last Bus Home](cinematic-and-dialogue.md#1-last-bus-home) | Text + character references |
| Multilingual conversation | [Paper Crane at Platform Seven](cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven) | Two character references + custom multi-shot |
| One-take character performance | [The Unsent Voice Note](cinematic-and-dialogue.md#3-the-unsent-voice-note) | Start image + single take |
| Three-person comedy | [The Missing Dumpling](cinematic-and-dialogue.md#4-the-missing-dumpling) | Three elements + multi-shot |
| Premium product ad | [Botanical Spark](commercial-and-ugc.md#1-botanical-spark-product-reveal) | Product reference + start image |
| E-commerce feature demo | [Modular Desk Lamp](commercial-and-ugc.md#2-modular-desk-lamp-feature-demo) | Product reference + start/end frames |
| Creator-style vertical ad | [Morning Skincare UGC](commercial-and-ugc.md#3-morning-skincare-ugc-one-take) | Creator start image + single take |
| Local business promotion | [Neighborhood Bakery](commercial-and-ugc.md#4-neighborhood-bakery-opening-day) | Location + owner references |
| Science-fantasy chase | [Glass Manta Pursuit](action-and-vfx.md#1-the-glass-manta-pursuit) | Start image + custom multi-shot |
| Sports commercial | [Indoor Climbing Finish](action-and-vfx.md#2-the-last-hold) | Athlete reference + single take |
| Material transformation | [Paper City Awakens](action-and-vfx.md#3-paper-city-awakens) | Start/end frames |
| Weather spectacle | [Storm in a Teacup](action-and-vfx.md#4-storm-in-a-teacup) | Start image + macro single take |
| Original animated action | [Ink Courier](style-and-performance.md#1-ink-courier-animated-chase) | Style + character references |
| Fashion transformation | [Four Seasons Coat](style-and-performance.md#2-four-seasons-one-coat) | Model/product reference + multi-shot |
| Live music performance | [Rooftop Percussion](style-and-performance.md#3-rooftop-percussion-at-dawn) | Performer elements + native audio |
| Dance motion study | [Shadow Echo Choreography](style-and-performance.md#4-shadow-echo-choreography) | Performer image + motion reference |
| Food ASMR | [Scallion Pancake](food-travel-spaces.md#1-scallion-pancake-asmr) | Start image + macro multi-shot |
| Destination story | [One Morning in Quanzhou](food-travel-spaces.md#2-one-morning-in-quanzhou) | Location references + multi-shot |
| Real-estate / hotel film | [Courtyard Light Study](food-travel-spaces.md#3-courtyard-light-study) | Room references + single take |
| Craft process | [Blue Pottery Kiln](food-travel-spaces.md#4-blue-pottery-kiln) | Artisan + object references |
| Educational explainer | [How a Heat Pump Moves Warmth](education-documentary-social.md#1-how-a-heat-pump-moves-warmth) | Designed start/end frames |
| Nature documentary | [The Night Pollinator](education-documentary-social.md#2-the-night-pollinator) | Text-to-video or start image |
| Seamless meme loop | [Infinite Umbrella Problem](education-documentary-social.md#3-the-infinite-umbrella-problem) | Start/end same frame |
| Public-interest mini story | [Thirty Seconds of Shade](education-documentary-social.md#4-thirty-seconds-of-shade) | Location + character references |
| Object-centered match cut | [Copper Compass Across Four Worlds](reference-editing-and-control.md#1-copper-compass-across-four-worlds) | Object + environment references |
| Multi-image character scene | [Sunday Table, Three Generations](reference-editing-and-control.md#2-sunday-table-three-generations) | Three character + room references |
| Motion-reference transfer | [Museum Guide Motion Transfer](reference-editing-and-control.md#3-museum-guide-motion-transfer) | Character + motion video reference |
| Weather edit and extension | [Rainy Platform Revision](reference-editing-and-control.md#4-rainy-platform-revision-and-extension) | Existing video + continuation brief |
| E-commerce livestream | [Foldable Kettle Live Demo](commerce-tech-mobility-industrial.md#1-foldable-kettle-live-demo) | Host + product references, single take |
| Gadget assembly | [Open-Ear Headset Assembly Proof](commerce-tech-mobility-industrial.md#2-open-ear-headset-assembly-proof) | Product reference + start/end frames |
| Automotive film | [Electric Hatchback, Quiet Departure](commerce-tech-mobility-industrial.md#3-electric-hatchback-quiet-departure) | Vehicle + cabin references |
| Industrial process | [Cobot Packs the Blue Valve](commerce-tech-mobility-industrial.md#4-cobot-packs-the-blue-valve) | Station + object references |
| Talking-head education | [Architecture Lesson](people-pets-learning-culture.md#1-the-forty-second-architecture-lesson) | Presenter reference + single take |
| Multilingual digital human | [Library Helper](people-pets-learning-culture.md#2-multilingual-library-helper) | Approved avatar + custom background |
| Pet adoption profile | [Pippa's Adoption Portrait](people-pets-learning-culture.md#3-pippas-adoption-portrait) | Pet + handler + room references |
| Child-safe science | [Pepper and Soap Science Table](people-pets-learning-culture.md#4-pepper-and-soap-science-table) | Educator + tabletop reference |
| Original game cinematic | [Lantern Runner](gaming-nature-and-production-tools.md#1-lantern-runner-game-cinematic) | Character + world references |
| Astronomy visualization | [Moon's Terminator](gaming-nature-and-production-tools.md#2-a-night-on-the-moons-terminator) | Text + designed reference frames |
| Compositing plate | [Clean-Screen Bicycle Turn](gaming-nature-and-production-tools.md#3-clean-screen-bicycle-turn-plate) | Performer reference + single take |
| White-model previs | [Stairwell Chase Previs](gaming-nature-and-production-tools.md#4-stairwell-chase-white-model-previs) | Text-to-video, grayscale blocking |
| Episodic vertical cliffhanger | [Metro Card That Came Back](short-drama-and-viral-social.md#1-the-metro-card-that-came-back) | Two characters + location reference |
| Workplace dialogue comedy | [Last Clean Mug](short-drama-and-viral-social.md#2-the-last-clean-mug) | Three character elements + multi-shot |
| Giant-object mockumentary | [Laundry Day Above the Harbor](short-drama-and-viral-social.md#3-laundry-day-above-the-harbor) | City start image + phone-style single take |
| Surreal social loop | [Shadow Takes the Early Train](short-drama-and-viral-social.md#4-the-shadow-takes-the-early-train) | Matched start/end frame |
| Script-led motion graphics | [Refill Tin](motion-graphics-and-transitions.md#1-refill-tin-script-to-motion-graphics-ad) | Script board + product + start/end frames |
| Multi-photo process transition | [From Seedling to Supper](motion-graphics-and-transitions.md#2-from-seedling-to-supper) | Four owned image references |
| Material-match transition | [Blue Glaze, Tidal Map](motion-graphics-and-transitions.md#3-blue-glaze-tidal-map) | Craft object + landscape references |
| Extreme scale reveal | [Crystal Canyon Is Breakfast](motion-graphics-and-transitions.md#4-the-crystal-canyon-is-breakfast) | Start/end reference frames |
| Closed-course racing | [Wet-Track Precision Lap](genre-action-and-sound.md#1-wet-track-precision-lap) | Vehicle + driver references |
| Mechanical animation | [Clockwork Heron Launch](genre-action-and-sound.md#2-clockwork-heron-launch) | Character design + mechanism references |
| Sound-led craft montage | [Glassblower Rhythm Cut](genre-action-and-sound.md#3-glassblower-rhythm-cut) | Artisan + workshop references |
| Orbital physics visualization | [Quiet Docking Above the Aurora](genre-action-and-sound.md#4-quiet-docking-above-the-aurora) | Vehicle references + multi-shot |

## Collections

1. [Cinematic & dialogue](cinematic-and-dialogue.md) — narrative pacing, micro-expression, speaker control and multilingual scenes.
2. [Commercial & UGC](commercial-and-ugc.md) — stable products, honest demonstrations, creator realism and local campaigns.
3. [Action & VFX](action-and-vfx.md) — spatial continuity, physics, sports movement and readable spectacle.
4. [Style & performance](style-and-performance.md) — original animation, fashion, music and choreography.
5. [Food, travel & spaces](food-travel-spaces.md) — sensory detail, destination identity, architecture and craft.
6. [Education, documentary & social](education-documentary-social.md) — explanations, factual tone, loops and social-impact stories.
7. [Reference, editing & control](reference-editing-and-control.md) — match cuts, multi-image scenes, motion transfer and targeted revision.
8. [Commerce, tech, mobility & industrial](commerce-tech-mobility-industrial.md) — livestreams, gadgets, automotive direction and manufacturing.
9. [People, pets, learning & culture](people-pets-learning-culture.md) — presenters, digital humans, animal profiles and supervised science.
10. [Gaming, nature & production tools](gaming-nature-and-production-tools.md) — game cinematics, astronomy, compositing plates and previsualization.
11. [Short drama & viral social](short-drama-and-viral-social.md) — vertical cliffhangers, dialogue comedy, mockumentary hooks and surreal loops.
12. [Motion graphics & transitions](motion-graphics-and-transitions.md) — script-led graphics, multi-photo processes, material matches and scale reveals.
13. [Genre action & sound sync](genre-action-and-sound.md) — closed-course racing, mechanical animation, craft audio and orbital physics.

## Prompt metadata

Every entry declares:

- **Use case** and target format.
- **Best mode** and reference strategy.
- **Why it works** for the intended model behavior.
- A complete prompt with continuity, timed direction, audio and constraints.
- **Swap ideas** for fast variations.
- A **failure check** to review before publishing.

## Responsible adaptation

Use generic or licensed products, actors, music and locations. Do not imitate a living artist, clone a person’s face or voice, or reproduce a protected character or brand identity without permission. Product claims and educational facts require independent review.

## Try the prompts on FLAQ.AI

FLAQ.AI currently provides browser and API entry points for Kling 3.0 Standard [text-to-video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) and [image-to-video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). This catalog does not claim Kling 4.0 availability. Check the live model page for current settings, prices and API parameters, then follow the [FLAQ.AI workflow guide](../docs/FLAQ-AI.md).

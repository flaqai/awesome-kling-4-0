# Commercial, Product & UGC Prompts

[← Catalog](README.md) · [Prompting guide](../docs/PROMPT-GUIDE.md)

Four original Kling prompts for product geometry, e-commerce demonstrations, creator-led UGC and local-business advertising. Use products and claims you own or are authorized to promote.

## 1. Botanical Spark Product Reveal

![Botanical drink reference frame](../assets/images/prompt-product-botanical-drink.png)

**Use case:** premium beverage commercial · **Format:** 9s, 16:9 · **Best mode:** product element reference + start image

**Why it works:** The bottle is locked while camera, condensation and peel receive separate motion instructions.

```text
[OUTPUT]
9 seconds, 16:9, premium non-alcoholic sparkling botanical drink commercial, photorealistic macro finish, three shots.

[PRODUCT LOCK]
One smoked-green glass bottle with a narrow shoulder, silver knurled cap and blank embossed oval on the front. No printed label or text. Preserve bottle silhouette, cap, oval, glass color and fill level exactly across all shots.

[WORLD]
Wet black basalt surface in a dark studio. Deep emerald rim light from frame left, cool silver key light overhead, narrow warm beam from frame right. Fine mist moves left to right.

[TIMED SHOTS]
0–3s — 100mm macro, low three-quarter angle. Camera slides slowly right while staying focused on condensation. One droplet forms at the shoulder and runs straight down; bottle remains motionless and vertical.
3–6s — Match cut to overhead close-up. A single pale-green citrus peel enters from frame left and completes one smooth clockwise spiral around the bottle without touching it. Fine bubbles rise inside the liquid at constant speed.
6–9s — Medium hero shot. Camera performs a slow 25-degree clockwise orbit at constant distance. The cap lifts two millimeters with a clean pressure release; a controlled halo of cold vapor blooms and clears. End with bottle centered and oval facing camera.

[AUDIO]
0–3s: low studio silence plus individual water drops. 3.1s: crisp peel swish. 6.4s: short cap click and delicate carbonation release. 8s: two warm glass-marimba notes, then silence.

[CONSTRAINTS]
The bottle never floats, bends, rotates independently or changes scale. Keep contact shadow attached to basalt. Physically plausible refraction, droplets, vapor and peel trajectory. No splash covering the product, alcohol cues, glassware, people, text, logo, watermark, label mutation or duplicate bottle.
```

**Swap ideas:** botanical drink → mineral water / cold brew / vinegar tonic; citrus peel → herb ribbon / tea leaf / berry mist.

**Failure check:** Compare the last frame against the product reference, especially shoulder width, cap and front oval.

## 2. Modular Desk Lamp Feature Demo

**Use case:** e-commerce product demonstration · **Format:** 12s, 1:1 · **Best mode:** product reference + start/end frames

**Why it works:** Each shot proves one feature with visible cause and effect instead of abstract beauty motion.

```text
[OUTPUT]
12 seconds, 1:1 square e-commerce feature demo, clean daylight studio, four sequential shots with simple match cuts.

[PRODUCT LOCK]
Compact matte-sand desk lamp: round weighted base, one slim vertical stem, flat circular light head, small copper touch disk on the base. No logo or printed text. Same dimensions, finish and copper disk in every shot.

[WORLD]
Pale oak desk against warm off-white wall. Notebook frame left, small ceramic planter rear right. Soft window light from frame left; product shadow falls consistently to the right.

[TIMED SHOTS]
0–3s — Locked 45-degree product shot. Adult hand enters from frame right and taps the copper disk once. Lamp turns on smoothly from zero to warm white over half a second. Hand exits by the same path.
3–6s — Side profile close-up. The same hand grips only the outer edge of the light head and tilts it downward on its hinge by exactly 35 degrees; stem and base remain fixed.
6–9s — Overhead shot. The circular head rotates clockwise to illuminate the notebook; the light pool travels across the desk without changing color.
9–12s — Match cut from notebook to a plain video-call setup. Lamp now points toward an empty chair, producing soft even face-height light. Camera pulls back slightly to show the compact footprint.

[AUDIO]
Quiet room tone; one dry touch click at 1s, soft hinge resistance at 4s, subtle rotational stop at 7.8s. Calm English voice-over: “Touch. Tilt. Turn. Light where work happens.” No background music.

[CONSTRAINTS]
Hand anatomy and contact must be natural. Base never slides; stem never bends; head moves only at defined joints. Preserve lamp color, scale and light temperature. No floating parts, extra buttons, visible cables, text, UI, logo, watermark or unsupported product claim.
```

**Swap ideas:** lamp → portable speaker / coffee grinder / travel kettle; features → click / fold / charge / pour.

**Failure check:** Every feature must be caused by the hand and the product must return no invented components.

## 3. Morning Skincare UGC One-Take

<img src="../assets/images/prompt-ugc-skincare.png" width="430" alt="Morning skincare UGC reference frame">

**Use case:** authentic creator ad · **Format:** 12s, 9:16 · **Best mode:** creator start image + single take

**Why it works:** The prompt keeps a credible phone-shot imperfection while defining safe hand/product interactions and non-medical language.

```text
[OUTPUT]
12 seconds, 9:16, one continuous mirror-selfie take, authentic morning UGC, ordinary smartphone exposure and natural skin texture.

[CONTINUITY ANCHORS]
Rin: adult East Asian woman, natural pores and faint under-eye texture, messy high bun, ivory cotton robe. Plain dark phone in left hand. Small unbranded frosted pump bottle on the sink. No visible label.

[WORLD AND CAMERA]
Small lived-in bathroom, soft overcast window light, light condensation at mirror edge, folded towel and one green plant. Mirror-selfie chest-up composition. Gentle handheld drift and one small imperfect reframe; no cinematic camera move.

[ACTION AND SPEECH]
0–3s — Rin looks into the phone lens, gives a tired half-smile and says in conversational English: “Okay, this is the step I don’t skip anymore.”
3–6s — Keeping the phone stable in her left hand, she presses the pump once with her right index finger. One pea-sized amount lands on two right fingertips. She glances down briefly; focus breathes naturally.
6–10s — She pats the product onto one cheek with the same two fingertips, three gentle contacts, then laughs when a water droplet slides near the lens edge. She says: “It just feels calm and light.”
10–12s — She holds the bottle near, not covering, her face for one second, then returns it to the sink and looks back at the lens.

[AUDIO]
Real bathroom room tone, distant water pipe, pump click and robe fabric. Rin’s voice is close and unprocessed. No music, voice-over, beauty-ad sparkle or subtitles.

[CONSTRAINTS]
One phone, one bottle, one pump action, same hand roles throughout. Natural finger count and mirror logic. Keep wording experiential, not medical; no before/after claim. Preserve pores and everyday lighting. No logo, label, text, watermark, face smoothing, jump cut, extra product, duplicated reflection or luxury set dressing.
```

**Swap ideas:** skincare → hair serum / hand cream / reusable bottle; bathroom → bedside / gym locker / desk break.

**Failure check:** Check mirror handedness, phone duplication, pump contact and whether speech silently changes into a stronger claim.

## 4. Neighborhood Bakery Opening Day

**Use case:** local-business vertical ad · **Format:** 15s, 9:16 · **Best mode:** owner + location + signature pastry references

**Why it works:** A real customer journey replaces generic montage, with one human voice and an editable end card added later in post.

```text
[OUTPUT]
15 seconds, 9:16, warm local bakery launch story, four shots, documentary-commercial blend, no generated captions.

[CONTINUITY ANCHORS]
Owner Mara: adult woman in her 40s, cropped silver hair, oval green glasses, indigo apron over cream shirt.
Signature pastry: palm-sized spiral bun with dark sesame center and glossy honey edge.
Bakery: narrow space, pale green tiles, wooden counter, round brass oven window. Keep all three consistent.

[TIMED SHOTS]
0–4s — Exterior-to-interior continuous push through the open door just after sunrise. Mara flips a blank wooden hanging sign and looks toward the first customer entering behind camera. Natural lens exposure settles as the camera crosses the doorway.
4–8s — Macro side shot. Mara slides one tray from the oven; heat shimmer rises. She lifts exactly one spiral bun with metal tongs and places it on kraft paper. Honey edge catches the light.
8–12s — Customer POV at counter. Mara extends the wrapped bun toward camera, maintains eye contact and says warmly in Mandarin Chinese: “第一炉，刚刚好。” Her hands remain beneath the paper; customer hands receive it from below.
12–15s — Wide from the back of the bakery. Two adult neighbors enter, morning light grows, Mara turns back toward the oven. End on clean negative space above the counter for a real title card to be added in post.

[AUDIO]
Door bell at 2.2s, tray rail scrape at 5s, paper fold at 9s, Mara’s single Mandarin line, low street bicycles and quiet oven fan. Light acoustic guitar begins at 11s without vocals.

[CONSTRAINTS]
Preserve Mara, apron, glasses, bakery geometry and pastry shape. Exactly one bun is transferred in the close-up. Natural tong and hand contact. No generated shop name, menu, price, subtitle, logo or watermark. No crowded grand opening, confetti, exaggerated steam or impossible oven fire.
```

**Swap ideas:** bakery → florist / ceramics studio / repair shop / tea counter; Mandarin line → supported local language.

**Failure check:** Leave the end-card area clean; add verified address, hours and offer text in post rather than generating it inside the video.

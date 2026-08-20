# Education, Documentary & Social Prompts

[← Catalog](README.md) · [Prompting guide](../docs/PROMPT-GUIDE.md)

Four original Kling prompts for explanation, nature observation, seamless loops and public-interest storytelling. Educational and documentary outputs require factual review; generative video is not evidence of a real event.

## 1. How a Heat Pump Moves Warmth

**Use case:** educational explainer · **Format:** 15s, 16:9 · **Best mode:** designed start/end frames + multi-shot

**Why it works:** The video uses one color-coded energy metaphor and a fixed left-to-right system, then reserves exact labels for post-production.

```text
[OUTPUT]
15 seconds, 16:9, clean 3D educational animation for a general adult audience, three stages, neutral light background, no generated text.

[SYSTEM LAYOUT]
Cutaway side view of a simple house on frame right and outdoor air on frame left. Outdoor coil outside left wall, compressor at lower center, indoor coil inside right wall. One continuous closed copper loop connects all parts. Blue particles represent lower-temperature refrigerant; orange particles represent higher-temperature refrigerant. House and loop stay fixed.

[ANIMATION]
0–5s — Cold outdoor scene. Blue particles travel clockwise through the outdoor coil and absorb small golden heat dots from surrounding air. Golden dots diminish outside and join the moving particles. Camera remains wide.
5–10s — Camera pushes to compressor at lower center. The same particles enter blue, compress closer together and shift smoothly to orange; a small vibration shows mechanical work. Nothing flows backward.
10–15s — Camera follows orange particles into indoor coil. Golden heat dots move from coil into the room; room color warms slightly. Particles continue around the closed loop and shift toward blue after releasing heat. End on the full system with one complete clockwise circuit visible.

[AUDIO]
Calm English voice-over: “A heat pump gathers available warmth outside, compresses the refrigerant to raise its temperature, then releases that warmth indoors.” Soft mechanical hum and subtle particle ticks. No music.

[CONSTRAINTS]
Conceptual explainer, not installation guidance. Preserve fixed component positions and clockwise closed loop. Heat direction follows the narration; colors remain consistent. No labels, equations, brand equipment, person, open electrical panel, invented efficiency claim, logo or watermark. Add verified labels and citations later in post.
```

**Swap ideas:** heat pump → refrigeration cycle / water treatment / battery charging; keep one visual metaphor and verify the science.

**Failure check:** A subject-matter reviewer should verify flow direction, component order and narration before release.

## 2. The Night Pollinator

**Use case:** nature-documentary micro story · **Format:** 12s, 16:9 · **Best mode:** text-to-video or macro start image

**Why it works:** Observable animal behavior replaces fantasy storytelling, and narration avoids claiming a species without verification.

```text
[OUTPUT]
12 seconds, 16:9, nocturnal macro nature-documentary style, realistic insect scale and behavior, two shots.

[SUBJECT]
One medium-sized hawk moth with mottled brown wings, long coiled proboscis and intact six legs. One cluster of pale tubular night-blooming flowers. Do not identify an exact species in narration.

[WORLD]
Quiet garden at night after light rain. Cool moonlit foliage, soft warm porch light far background, small droplets on leaves. Flower cluster remains stationary frame center.

[TIMED SHOTS]
0–6s — Locked macro side view. Moth approaches from frame left, hovers without landing, wings beating rapidly into a natural blur. It uncoils the proboscis forward and inserts only the tip into one flower tube. Body maintains stable hover distance.
6–12s — Tighter front three-quarter macro. Pollen grains brush the moth’s face as it withdraws and moves to the adjacent flower. One droplet falls from a leaf behind it. Moth exits frame right at normal speed; flower stems sway slightly from airflow, then settle.

[AUDIO]
Natural night insects, faint wing buzz close to camera and one water droplet. Calm English narrator: “After dark, some flowers trade color for scent, guiding hovering visitors from bloom to bloom.” No dramatic score.

[CONSTRAINTS]
Six legs, two antennae, one proboscis, coherent wing attachment and plausible flower interaction. No giant scale, glowing insect, magical pollen trail, predation, extra wings, flower morphing, fake scientific label, subtitle, logo or watermark. Treat visuals as illustrative, not recorded evidence.
```

**Swap ideas:** moth → bat / beetle / bee; adjust anatomy, time of day and behavior after research.

**Failure check:** Slow playback to confirm anatomy and that the proboscis, not the whole face, interacts with the flower.

## 3. The Infinite Umbrella Problem

**Use case:** seamless comedy loop / meme · **Format:** 8s, 9:16 · **Best mode:** identical start and end frame

**Why it works:** One repeated prop rule and a matched first/last pose create a loop without relying on text.

```text
[OUTPUT]
8-second seamless 9:16 comedy loop, realistic city sidewalk in gentle rain, locked medium-wide camera.

[CHARACTER AND PROP LOCK]
Niko: adult man, mustard raincoat, navy trousers, red sneakers, holding one closed black umbrella in right hand at start. Plain bus shelter frame left, puddle center, gray wall background. No signs or logos.

[LOOP ACTION]
0–2s — Niko steps into the puddle with left foot, looks up at rain and opens the black umbrella overhead. Water splash follows foot contact naturally.
2–4s — A smaller closed black umbrella drops from inside the open canopy into his left hand. He looks at it once, confused; large umbrella stays overhead in right hand.
4–6s — He opens the smaller umbrella. The original large umbrella instantly and cleanly folds upward into the smaller canopy only while the two canopies fully overlap, leaving Niko holding one normal closed black umbrella in his right hand.
6–8s — Niko lowers his arm, shifts weight back and returns exactly to the first pose just before the puddle step. Rain, traffic reflection and coat hem return to matching positions for the loop.

[AUDIO]
Steady rain loop, one shoe splash, umbrella open snap at 1.5s, tiny comedic wooden click at the nested reveal, second snap, then ambience aligns exactly to first frame. No dialogue, music or laugh track.

[CONSTRAINTS]
Start and end frame match in pose, umbrella state, rain direction, puddle ripples and camera. Umbrella transformation occurs only under full canopy occlusion. One person, no duplicate limbs, no extra umbrella remaining, no teleport outside occlusion, text, logo or watermark.
```

**Swap ideas:** umbrella → tote bag / lunchbox / hat; the prop must return to its original state.

**Failure check:** Play three loops; the audio bed and first/last frame should not reveal the seam.

## 4. Thirty Seconds of Shade

**Use case:** public-interest mini story · **Format:** 15s, 9:16 · **Best mode:** location + two character references

**Why it works:** The message emerges from one practical action and avoids statistics or institutional claims that might be fabricated.

```text
[OUTPUT]
15 seconds, 9:16, human-scale public-interest story about heat and mutual care, observational realism, three shots.

[CHARACTER LOCK]
Rosa: adult street vendor in her 50s, straw hat, pale-blue shirt, green pushcart with a small fixed canopy.
Imani: adult bicycle courier in her 20s, orange helmet, gray reflective vest with no logo, black bicycle.
Preserve identities, clothing, cart and bicycle.

[WORLD]
Hot late-afternoon neighborhood street. Hard sun from upper frame right; pale wall produces a narrow shadow. Heat shimmer is subtle. No identifiable city signage.

[TIMED SHOTS]
0–5s — Medium tracking shot. Imani walks the bicycle left-to-right, slows and wipes forehead. Sunlight is hard; footsteps and breathing natural. Rosa notices from beside her cart.
5–10s — Close two-shot at cart. Without speaking, Rosa releases one latch and rotates the canopy outward until its shadow covers Imani. The cart stays planted; shadow moves consistently with canopy geometry. Imani stops and looks up, surprised.
10–15s — Wider static shot. Imani rests in shade, takes one sip from her own bottle and gives Rosa a grateful nod. Rosa returns the nod and serves an off-screen customer. End on their two silhouettes sharing the same patch of shade, with clean lower-frame space for verified campaign copy added later.

[AUDIO]
Dry summer street, distant fan, bicycle freewheel and canopy latch. Rosa says in Spanish, gently: “Quédate un momento.” Imani answers in English: “Thank you.” No music until a single soft guitar harmonic after the nod.

[CONSTRAINTS]
Adult characters; realistic heat behavior and shade geometry. One speaking mouth at a time; keep lines in written languages. No medical emergency, collapse, invented charity branding, statistic, subtitle, generated campaign text, logo or watermark. Add verified local heat guidance and contact information in post.
```

**Swap ideas:** shade → water refill / seat offered / rain cover; use a small observable act rather than a broad claim.

**Failure check:** Verify canopy mechanics and shadow direction, then add only locally approved public-health information in post.

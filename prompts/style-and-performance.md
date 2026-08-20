# Style, Animation, Fashion & Performance Prompts

[← Catalog](README.md) · [Prompting guide](../docs/PROMPT-GUIDE.md)

Four original prompts for animation, fashion, music and dance. They describe visual properties directly and avoid artist names, protected characters and franchise imitation.

## 1. Ink Courier Animated Chase

**Use case:** original 2D animated action · **Format:** 12s, 16:9 · **Best mode:** character + style references, custom multi-shot

**Why it works:** The style is defined by line, texture, timing and palette rather than by imitating a named studio or artist.

```text
[OUTPUT]
12 seconds, 16:9, original hand-drawn 2D animation, expressive black brush line, visible paper grain, limited cel shading, palette of indigo, cream and vermilion, three shots.

[CHARACTER LOCK]
Courier Iko: adult nonbinary rider, short triangular indigo hair, cream wrap jacket with one vermilion sash, black cropped trousers, rectangular canvas mail case. Original design; preserve silhouette, face, colors and case.
Mount: long-legged blue paper bird with folded geometric wings and one cream beak.

[WORLD]
Vertical city built from stacked handwritten envelopes, suspended bridges made of red thread, cream sky with broad dry-brush clouds. No readable writing; marks remain abstract.

[TIMED SHOTS]
0–4s — Side-scrolling wide shot. Iko and the bird run left-to-right across a red-thread bridge. Animation uses strong contact poses: each foot compresses the thread, which rebounds after release. Camera pans at matched speed.
4–8s — Low front angle. A wall of loose envelopes slides down the street behind them. Iko pulls one ribbon; bird folds both wings tightly and slips through a narrow triangular gap. Speed lines remain brush strokes attached to direction of travel.
8–12s — Overhead shot rotates only 30 degrees as bird unfolds wings and glides over an ink canal. Iko opens the mail case; one glowing blank envelope rises, stamps the dark canal with a cream reflection, then returns to the case. End on a clean heroic silhouette.

[AUDIO]
Dry paper percussion, brush swishes, stretched thread plucks and rapid soft foot taps. One low wooden drum on the wing unfold. No dialogue or recognizable melody.

[CONSTRAINTS]
Consistent 2D drawing, line weight, paper texture and limited palette. Preserve original character and mount. No photorealism, 3D rendering, readable handwriting, existing uniforms, franchise symbols, extra limbs, sash color change, logo or watermark.
```

**Swap ideas:** envelope city → woven textile valley / ceramic market / chalkboard harbor; courier → botanist / baker / cartographer.

**Failure check:** Review whether the style remains 2D across every shot and whether the red sash and mail case persist.

## 2. Four Seasons, One Coat

**Use case:** fashion transformation film · **Format:** 15s, 9:16 · **Best mode:** model + garment reference, custom multi-shot

**Why it works:** The coat is a fixed product anchor; seasons change only while it is fully occluded by planned wipes.

```text
[OUTPUT]
15 seconds, 9:16, high-fashion vertical film, four seasons connected by motivated foreground wipes, elegant natural motion.

[MODEL AND GARMENT LOCK]
Amara: adult Black woman, close-cropped hair, athletic silhouette, neutral makeup.
Coat: ankle-length charcoal technical coat, asymmetric copper zipper from left hip to right collar, two rectangular pockets, matte fabric. Preserve coat cut, zipper, pockets and charcoal color in every season.

[SHOT PLAN]
0–4s SPRING — Medium full-body track in a pale greenhouse. Amara walks toward camera; flowering branch crosses the entire lens at 3.5s to create a soft wipe.
4–8s SUMMER — Continue the exact same step and body position on a bright coastal boardwalk. Coat is open but unchanged; a white sail passes fully across frame at 7.5s.
8–12s AUTUMN — Continue in a copper-leaf courtyard. Amara turns once; coat hem follows with believable fabric lag. A cluster of leaves fills the lens at 11.5s.
12–15s WINTER — Continue the turn on a snowy minimalist street. Coat is zipped with same copper zipper. She stops, looks into lens and exhales one visible breath. Camera settles into a symmetrical full-body hero frame.

[AUDIO]
One continuous minimal percussion pulse across all seasons. Greenhouse birds → coastal wind → dry leaves → soft snow hush, crossfaded under each wipe. Fabric movement remains consistent. No speech.

[CONSTRAINTS]
Model identity, body proportions and coat geometry never change. Each transition occurs only under full foreground occlusion and continues the same motion phase. Natural fabric weight. No new accessories, wardrobe recolor, season blend before wipe, exposed mid-transition morph, text, logo or watermark.
```

**Swap ideas:** one coat → shoe / handbag / watch; seasons → four cities / work-to-evening / weather states.

**Failure check:** Match Amara’s foot position and turn phase on both sides of every wipe.

## 3. Rooftop Percussion at Dawn

**Use case:** native-audio music performance · **Format:** 15s, 16:9 · **Best mode:** three performer references + multi-shot

**Why it works:** The score is built from three simple original rhythms and specific contact events instead of requesting an existing song.

```text
[OUTPUT]
15 seconds, 16:9, live rooftop percussion performance at dawn, documentary concert energy, original rhythm, four shots.

[PERFORMER MAP]
Aya: adult Japanese woman, red windbreaker, short hair, frame left, plays one shallow metal handpan.
Malik: adult British man, blue overshirt, shaved head, center, plays one wooden cajón.
Camila: adult Colombian woman, yellow knit top, long braid, frame right, plays two small seed shakers.
Preserve faces, instruments, clothing colors and left-center-right positions.

[RHYTHM AND SHOTS]
0–4s — Wide locked shot, pale sunrise behind city roofs. Malik starts a steady low cajón pulse: four evenly spaced hits. The others listen and sway naturally.
4–8s — Medium side track from Aya to Malik. Aya adds a three-note handpan phrase after every second cajón hit. Her fingers contact visible tone fields; each note aligns exactly to contact.
8–12s — Close-up on Camila’s hands and face. She adds a soft double-shake pattern, wrists moving compactly. Camera rack-focuses from seeds inside the translucent shaker to her smile.
12–15s — Return to wide. All three play one synchronized final accent, then freeze their hands while the metal note decays. A flock of ordinary birds crosses far background after the final hit.

[AUDIO]
Native performance only: dry low cajón, warm resonant handpan, fine seed texture, rooftop wind and distant city. No sampled song, vocals, cheering or added orchestra. Maintain room-free outdoor acoustics and realistic decay.

[CONSTRAINTS]
One instrument per performer; accurate hand-to-sound synchronization; fixed stage positions. No extra sticks, changing instruments, impossible hand speed, duplicated fingers, lip movement, visible brand, skyline text or watermark.
```

**Swap ideas:** rooftop → courtyard / ferry deck / warehouse; instruments → frame drum / clay pot / bamboo clappers.

**Failure check:** Mute and replay visually—every audible note should correspond to a plausible visible action.

## 4. Shadow Echo Choreography

**Use case:** dance motion study · **Format:** 10s, 1:1 · **Best mode:** performer image + motion reference where available

**Why it works:** The dancer and shadow obey the same motion with a precise delay, creating one controlled surreal rule.

```text
[OUTPUT]
10 seconds, 1:1, one continuous full-body dance shot, minimalist contemporary movement, controlled surreal shadow effect.

[PERFORMER LOCK]
León: adult Latino dancer, lean build, shaved head, loose cream shirt, black wide trousers, barefoot. Full body visible at all times.

[WORLD]
Empty pale-gray studio, matte floor, one hard warm spotlight positioned high frame left. Camera locked at waist height, 50mm natural perspective, no crop changes. Real shadow falls to frame right.

[CHOREOGRAPHY]
0–2s — León stands still, then lifts right forearm to shoulder height over one second. Real body moves first; shadow remains still.
2–5s — Exactly 0.8 seconds later, shadow repeats the same forearm motion while León steps left and rolls shoulders once. Every shadow movement repeats León’s prior pose sequence, never inventing a gesture.
5–8s — León performs one slow clockwise turn with arms extended. Delayed shadow begins the same turn 0.8 seconds later, attached correctly to both feet and consistent with spotlight direction.
8–10s — León stops facing camera with palms down. Shadow completes its delayed turn, arrives at the same final pose, and synchronizes precisely on the final beat.

[AUDIO]
Bare feet on matte floor, shirt fabric, breathing and one original low pulse every second. At synchronization, one dry handclap-like accent with no visible clap. No melody or speech.

[CONSTRAINTS]
Shadow remains attached to floor contact, uses León’s silhouette and follows a constant 0.8-second delay until final sync. Correct spotlight geometry. No second dancer, detached shadow, extra limbs, camera move, cropped feet, wardrobe change, text, logo or watermark.
```

**Swap ideas:** delayed shadow → delayed reflection / chalk trace / dust echo; dance → tai chi / mime / simple gesture study.

**Failure check:** The shadow may lag in time but must never detach spatially from floor perspective.

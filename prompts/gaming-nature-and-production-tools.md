# Gaming, Nature & Production-Tool Prompts

[← Catalog](README.md) · [Prompting guide](../docs/PROMPT-GUIDE.md)

Four original Kling recipes for game cinematics, astronomy visualization, clean-screen production plates and white-model previsualization. These prompts prioritize reusable assets and explicit review boundaries.

## 1. Lantern Runner Game Cinematic

**Use case:** original game trailer beat · **Format:** 12s, 16:9 · **Best mode:** character + world references, custom multi-shot

**Why it works:** The character, route, game-space landmarks and camera side are fixed before the effect beat.

```text
[OUTPUT]
12 seconds, 16:9, stylized original third-person adventure cinematic, painterly 3D finish, three shots.

[LOCKS]
Mara, original adult courier: cropped black hair, rust-red cape, charcoal boots, round amber lantern in left hand. World: flooded stone archive with waist-high shelves, three glowing blue doorways and ankle-deep water. No existing franchise design.

[GEOGRAPHY]
Mara travels left-to-right through the same central aisle. Blue doorway A behind, B at midpoint, C ahead. Camera remains on her near side; screen direction never reverses.

[TIMED SHOTS]
0–4s — Low rear three-quarter tracking. Mara runs through shallow water; each footfall creates one delayed splash. Lantern swings opposite her stride and illuminates nearby shelves.
4–8s — Side medium shot at doorway B. She plants right foot, slides 50cm and raises lantern. A circular amber light wave expands across water, revealing a safe stone path; shelves do not move.
8–12s — High wide shot. Mara follows the revealed path toward doorway C while blue light dims behind her. Camera cranes upward and stops on the readable route, with Mara still moving left-to-right.

[AUDIO]
Boot splashes, cape cloth, lantern glass rattle and one low magical pulse. Original percussion enters after the light wave; no dialogue.

[CONSTRAINTS]
Preserve identity, costume, lantern hand, landmarks and screen direction. One character, no enemy or weapon, no copied character, UI, quest text, logo or watermark. Light reveals the path but does not move objects.
```

**Swap ideas:** archive → orchard ruins / ice cavern / cloud workshop; retain three landmarks and one readable ability.

**Failure check:** Map the route across cuts and ensure lantern hand, doorway order and travel direction never flip.

## 2. A Night on the Moon's Terminator

**Use case:** astronomy mini-documentary visualization · **Format:** 15s, 21:9 · **Best mode:** text-to-video + designed reference frames

**Why it works:** Lighting geometry and scale cues are explicit, while narration labels the sequence as a visualization rather than real footage.

```text
[OUTPUT]
15 seconds, 21:9, scientifically restrained lunar-surface visualization, slow documentary camera, three shots.

[WORLD]
Airless gray lunar terrain near the day-night boundary. Low sun just above left horizon casts long hard shadows to frame right. Black sky with sparse fixed stars; no atmospheric haze, clouds or wind. One 40cm boulder provides scale.

[TIMED SHOTS]
0–5s — Ground-level wide. Camera glides forward 1m toward the boulder; fine regolith remains undisturbed because no subject touches it. Sun angle and shadows remain fixed.
5–10s — Macro on boulder edge. Sharp sunlight reaches one side while the opposite remains dark; camera racks focus from lit grains to a distant crater rim. Stars do not blur or twinkle.
10–15s — Slow crane to a high wide view revealing the boundary across cratered terrain. Hold for two seconds without accelerating.

[AUDIO]
No diegetic wind or surface sound. Calm English narrator: “This visualization follows the lunar terminator, where low sunlight stretches shadows across airless ground.” Very quiet non-diegetic tonal bed only.

[CONSTRAINTS]
Visualization, not claimed mission footage. No Earth unless position is verified, astronaut, flag, vehicle, dust gust, blue sky, aurora, twinkling stars, generated labels, logo or watermark. Astronomy review required.
```

**Swap ideas:** lunar terminator → asteroid surface / polar crater / eclipse geometry; verify scale, light and viewpoint.

**Failure check:** Remove any atmosphere-like motion, then have a reviewer verify the narration and illumination logic.

## 3. Clean-Screen Bicycle Turn Plate

**Use case:** compositing-ready green-screen action plate · **Format:** 8s, 16:9 · **Best mode:** performer reference + single take

**Why it works:** Lighting, full-body clearance, contact shadow and loop-safe movement are designed for extraction instead of finished storytelling.

```text
[OUTPUT]
8 seconds, 16:9, full-body compositing plate, locked camera, evenly lit chroma-green cyclorama and floor.

[PERFORMER AND PROP]
Consented adult performer Kai in matte gray fitted sportswear, gray shoes, tied-back dark hair. One plain matte-black city bicycle with no reflectors, labels or chrome. Preserve body, wardrobe and bicycle geometry.

[FRAMING AND LIGHT]
Camera at hip height, 50mm-equivalent, entire bicycle and performer stay at least 12% inside all frame edges. Two soft keys create even exposure and a short neutral contact shadow; no green spill on skin, clothing or bicycle.

[ACTION]
0–2s — Kai stands left of bicycle, both wheels planted, right hand on saddle and left on handlebar.
2–5s — Walks the bicycle in a smooth semicircle clockwise, turning it from profile to front three-quarter. Wheels roll with ground distance; feet never cross unnaturally.
5–8s — Stops, lowers kickstand with right foot, releases hands and holds still for the final 1.5s.

[AUDIO]
Muted production reference audio: footsteps, tire roll and kickstand click. No music or speech.

[CONSTRAINTS]
Uniform chroma green, no set seam, tracking marker, green wardrobe, motion blur on body edges, crop, reflection, extra shadow, rider mounting, prop duplication, text, logo or watermark.
```

**Swap ideas:** bicycle → suitcase / chair / sports equipment; choose wardrobe and prop surfaces that separate cleanly from the key color.

**Failure check:** Inspect hair, spokes, shoe contact and frame clearance at 200% before attempting a key.

## 4. Stairwell Chase White-Model Previs

**Use case:** camera blocking and safety previsualization · **Format:** 12s, 16:9 · **Best mode:** text-to-video, white-model style

**Why it works:** Neutral geometry strips away finish so the team can judge camera path, distance, screen direction and unsafe collisions.

```text
[OUTPUT]
12 seconds, 16:9, grayscale white-model previsualization, no textures, three clearly separated shots.

[BLOCKING]
Simple concrete-gray stairwell: two flights, central landing, one door at top. Figure A is matte white with a black shoulder stripe; Figure B is medium gray with a white wrist band. Both are adult-scale featureless mannequins. A begins lower flight, B begins 3m behind. No weapons or falls.

[TIMED SHOTS]
0–4s — Wide side master. A runs up six steps left-to-right; B follows at constant 3m distance. Camera locked; foot plants align to steps.
4–8s — Overhead landing shot. A turns clockwise around the rail, B follows the identical safe line. Maintain 1m clearance from railing and each other.
8–12s — Shoulder-height camera retreats up second flight ahead of A at walking-gimbal speed. A slows before the top door; B stops on landing. Camera never passes through walls or railings.

[AUDIO]
Reference-only metronome at 120 BPM and dry footstep cues. No score, dialogue or environment design.

[CONSTRAINTS]
Previs only, not final footage. Fixed stair geometry, character markers, distance and screen direction. No texture, face, costume, stunt contact, jump, fall, camera collision, dynamic light, text, logo or watermark.
```

**Swap ideas:** stairwell → shop aisle / stage / warehouse path; keep geometry simple and label performers by visual markers.

**Failure check:** Review with stunt and camera teams; measure clearances and revise before any real-world action setup.


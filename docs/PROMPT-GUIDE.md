# Kling Video Prompt Engineering Guide

[Home](../README.md) · [Prompt catalog](../prompts/README.md) · [15 languages](LANGUAGES.md) · [Multilingual audio](MULTILINGUAL-AUDIO.md) · [FLAQ.AI workflow](FLAQ-AI.md)

This guide turns an idea into a prompt that directs not just appearance, but also **time, motion, camera, continuity and audio**. It is written for the verified Kling 3.0 toolset and is structured to remain useful when an official Kling 4.0 model becomes available.

## 1. Choose the right input mode

| Situation | Start with | Why |
|---|---|---|
| Visual discovery matters more than exact identity | Text-to-video | Maximum creative freedom |
| Composition, packaging or a face must start precisely | Image-to-video | The opening frame acts as a strong visual anchor |
| A transformation needs a controlled destination | Start + end frames | Defines both sides of the transition |
| A person, product or prop must survive angle changes | Element / subject reference | Reuses a bound visual identity across shots |
| Gesture or choreography must follow a known path | Motion reference, where available | Separates performance design from appearance |
| Several scenes require exact pacing | Custom multi-shot | Assigns duration, framing, action and camera per shot |

Do not combine every control by default. More references can create conflicts. Use the smallest set that clearly fixes the problem you care about.

## 2. The seven-layer prompt

### Layer 1 — Output contract

State duration, aspect ratio, single/multi-shot mode and overall finish. Keep quality adjectives short.

```text
12 seconds, 9:16, one continuous handheld take, natural smartphone realism.
```

### Layer 2 — Continuity anchors

Name reusable subjects and describe only stable identifiers.

```text
Mara: adult woman, cropped silver hair, oval green glasses, rust utility coat.
Parcel: small cube, recycled gray paper, one blue cotton cord, no printed text.
```

Good anchors are visible, distinctive and repeatable. Avoid subjective phrases such as “very beautiful” or overloaded clothing lists.

### Layer 3 — World geometry

Describe where things are before motion begins. This helps preserve screen direction.

```text
Narrow bakery. Oven at frame left, counter center, glass door frame right.
Morning sun enters from the right and remains the only hard light source.
```

### Layer 4 — Timed shot direction

Use one primary action per beat. Separate the camera path from the subject path.

```text
0–4s — Medium profile tracking shot. Mara walks left to right at a steady pace.
Camera tracks parallel, constant distance, horizon level. Background moves right to left.
```

### Layer 5 — Performance and physics

Replace emotion labels with observable behavior.

```text
She recognizes him: inhale pauses, eyes widen slightly, grip loosens, then shoulders settle.
```

For objects, state weight, contact and reaction.

```text
The heavy lid rotates on its hinge; the base stays planted; its shadow remains attached to the table.
```

### Layer 6 — Audio timeline

Assign each voice, line, ambience and foley event. State where silence matters.

```text
Room tone continues across the cut. At 4.2s the latch clicks once.
Mara (English, quiet, breath catching): “You kept it.”
No music until the final two seconds.
```

### Layer 7 — Constraints

Prioritize the failures most damaging to this shot. A giant negative list can dilute the prompt.

```text
Keep Mara’s face, glasses, coat and screen direction stable. One speaking mouth at a time.
No subtitles, logos, duplicate hands, floating props or lighting changes.
```

## 3. Timing that fits

Use a realistic action budget:

| Duration | Suggested structure | Appropriate complexity |
|---:|---|---|
| 5s | One setup + one payoff | Product motion, portrait action, simple transition |
| 8–10s | Two or three beats | Short ad, UGC hook, compact action gag |
| 12–15s | Three or four beats | Dialogue, mini story, multi-shot commercial |

Dialogue needs breathing room. A 15-second video is not a page of screenplay. Keep lines short, reduce speaker changes and let expressions carry meaning.

## 4. Camera grammar

Use camera instructions only when they create story value.

| Intent | Useful direction | Common failure |
|---|---|---|
| Reveal information | slow push-in, rack focus, tilt from detail to face | Combining zoom, orbit and crane in one beat |
| Follow movement | parallel track, trailing follow, low side track | Camera and subject paths contradict each other |
| Build unease | locked frame with slow environmental motion | Constant random shake |
| Show scale | foreground anchor + wide pull-back | Scale object has no reference point |
| Feel authentic | small handheld drift, imperfect reframing | “Handheld” plus perfectly stabilized crane motion |

Name the frame size, angle, path, speed and endpoint only if each matters.

## 5. Character and product continuity

1. Create or select a clean reference with visible silhouette and uncluttered lighting.
2. Bind the reference as the matching subject or element when the mode allows.
3. Repeat a short continuity anchor in the prompt.
4. Keep wardrobe and signature props unchanged unless transformation is the story.
5. In multi-shot scenes, repeat the character name rather than switching among “woman,” “girl,” “she” and “hero.”
6. For products, lock silhouette, cap, label placement, material, color and orientation.
7. Place exact packaging text in the source image; ask the video to preserve it instead of inventing new lettering.

## 6. Native audio and dialogue

- Name the speaker before every line.
- Keep one speaking mouth active at a time unless overlap is essential.
- State language, tone, volume and pace in a compact parenthesis.
- Keep ambience continuous across cuts to hide visual edits.
- Tie foley to visible contact events: cap click, shoe landing, knife hitting board.
- Avoid demanding a full song, rapid dialogue, voice-over and dense effects in the same short clip.
- If exact wording is critical, verify the output and be ready to replace audio in post.

See [Multilingual Audio & Dialogue](MULTILINGUAL-AUDIO.md) for five-language examples.

## 7. Negative constraints by failure type

Choose a small relevant set.

### People

```text
No face drift, age shift, duplicate limbs, fused fingers, sliding feet or wardrobe changes.
```

### Products

```text
No label mutation, cap deformation, scale change, floating contact shadow or invented text.
```

### Multi-shot

```text
Preserve screen direction, weather, time of day, prop position and character identity across cuts.
```

### Dialogue

```text
One speaking mouth at a time; lines stay with their named speakers; no subtitles unless requested.
```

### Action

```text
No teleporting, object penetration, speed discontinuity, weightless impacts or camera crossing the action axis.
```

## 8. Iteration ladder

Do not rewrite everything after a weak result. Diagnose and change one layer:

1. **Composition test:** static or minimal movement; check subject and references.
2. **Motion test:** add only the primary action; check contact, speed and weight.
3. **Camera test:** add one camera path; check geography and horizon.
4. **Audio test:** add dialogue and foley; check speaker assignment and sync.
5. **Polish pass:** add atmosphere, secondary motion and color finish.

Keep a simple run log:

```text
Prompt ID: commercial-01
Model/mode/date: {fill in}
Changed variable: orbit speed from medium to slow
Result: label stability improved; peel timing late
Next test: move peel launch from 1.0s to 0.4s
```

## 9. Practical prompt compression

If a prompt becomes too long, preserve information in this order:

1. Continuity anchors.
2. Primary actions and timing.
3. Camera geography.
4. Speaker assignment and exact lines.
5. Critical constraints.
6. Lighting and atmosphere.
7. Decorative adjectives.

## 10. Pre-publish review

- Does every shot contain a readable action?
- Are face, hands, feet and object contact plausible?
- Does packaging or signage match the approved source?
- Do lines belong to the correct speakers and language?
- Are dialogue, ambience and effects balanced?
- Is the loop, transition or cut physically continuous?
- Are claims, likenesses, music, locations and brand assets cleared?
- Does the result need captions, accessibility description or an AI disclosure in its destination market?

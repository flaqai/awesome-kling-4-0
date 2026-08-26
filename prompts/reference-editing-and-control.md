# Reference, Editing & Control Prompts

[← Catalog](README.md) · [Prompting guide](../docs/PROMPT-GUIDE.md)

Four original Kling recipes for match cuts, multi-image continuity, motion references and controlled video revision. Give every reference one explicit job and use only assets you own or are licensed to modify.

## 1. Copper Compass Across Four Worlds

**Use case:** object-centered match-cut montage · **Format:** 12s, 16:9 · **Best mode:** object reference + four environment references

**Why it works:** The compass stays fixed in screen position and scale while each cut hides inside a repeatable lid-closing action.

```text
[OUTPUT]
12 seconds, 16:9, four-scene cinematic match-cut montage, crisp realistic materials, exactly four shots.

[REFERENCE ROLES]
Object reference locks one palm-sized scratched copper compass with a dark blue needle and plain lid. Environment references control only: coastal cliff at dawn, night train table, desert survey camp, snowy observatory. Do not transfer people or objects between environment references.

[MATCH-CUT RULE]
The compass center remains at 52% frame width and 58% frame height, same apparent size and same 35-degree lid angle at every cut. Each transition occurs during the final six frames of a hand closing the lid; motion direction stays right-to-left.

[TIMED SHOTS]
0–3s — Coastal cliff macro. Weathered adult hand opens the compass; needle settles north, salt mist crosses left-to-right, slow 5cm push-in.
3–6s — Cut under closing fingers to the same compass on a night-train table. Different sleeve, same hand path. Passing lights sweep across copper; needle trembles once with rail vibration.
6–9s — Cut under the lid to a desert survey cloth. Fine sand moves around, never onto, the hinge. Hand rotates the whole compass 20 degrees clockwise; needle independently returns north.
9–12s — Cut under closing fingers to snowy observatory stone. Gloved hand opens the lid fully; camera tilts from compass toward a clear polar star, ending with the compass still visible at lower center.

[AUDIO]
One continuous low musical note bridges all cuts. Distinct layers: surf and lid click; rail rhythm; dry wind; high mountain air. The same metal click lands exactly at 2.8s, 5.8s and 8.8s.

[CONSTRAINTS]
One compass only. Preserve scratches, hinge, needle color, scale and screen position. Cuts happen only behind fingers and lid; no dissolve, portal, morphing map, readable text, logo or watermark.
```

**Swap ideas:** compass → ceramic cup / pocket watch / seed tin; change worlds while keeping one measurable transition gesture.

**Failure check:** Overlay the four transition frames; the object center, size, lid angle and hand direction should align.

## 2. Sunday Table, Three Generations

**Use case:** multi-image family continuity · **Format:** 15s, 16:9 · **Best mode:** three character references + one room reference

**Why it works:** Each portrait controls only one adult identity, while seating, gaze and serving order are declared separately.

```text
[OUTPUT]
15 seconds, 16:9, intimate family lunch scene, naturalistic cinema, three connected shots with native dialogue.

[REFERENCE ROLES]
Image 1 locks Mei, adult grandmother with short white curls and burgundy cardigan. Image 2 locks adult daughter An, chin-length black hair and olive shirt. Image 3 locks adult grandson Leo, curly dark hair and mustard sweater. Image 4 supplies only the small sunlit dining room and oval wooden table; ignore any people in it.

[GEOGRAPHY]
Mei sits frame left, An frame right, Leo centered on far side. One blue serving bowl in the table center. Their seats, wardrobe and eyelines never swap.

[TIMED SHOTS]
0–5s — Wide locked master. Mei lifts the blue bowl with both hands and passes it clockwise to An. Leo watches the bowl, then glances at Mei.
5–10s — Medium two-shot across table. An receives the bowl from below, sets it down once and says in Mandarin: “还是这个味道。” Mei is soft foreground left, listening without speaking.
10–15s — Close on Mei. She smiles with restrained pride, looks toward An and answers in English: “You remembered.” Focus shifts to Leo quietly taking one dumpling from the bowl; end on all three sharing a small laugh.

[AUDIO]
Quiet midday room, ceramic contact, chair fabric and distant neighborhood birds. Only An speaks the Mandarin line; only Mei speaks the English line. No narrator or subtitles.

[CONSTRAINTS]
Exactly three adults, one bowl and one dumpling lifted. Natural hand contact and table occlusion. Preserve identity, age, hair, clothing, seat and screen direction. No face blending, duplicate people, extra dishes appearing, generated wall text, logo or watermark.
```

**Swap ideas:** lunch → workshop / rehearsal / train compartment; replace the bowl with one shared task object.

**Failure check:** Freeze each cut and verify faces, seating order, eyelines and bowl handoff direction.

## 3. Museum Guide Motion Transfer

**Use case:** character and motion reference separation · **Format:** 10s, 9:16 · **Best mode:** character image + motion video reference

**Why it works:** The source clip supplies timing and body mechanics only; identity, clothing and location remain bound to separate references.

```text
[OUTPUT]
10 seconds, 9:16, one continuous vertical museum-guide presentation, realistic documentary finish.

[REFERENCE ROLES]
Character image locks adult guide Noor: warm brown skin, short coiled hair, charcoal suit and teal scarf. Gallery image locks white curved wall, one abstract bronze sculpture and polished gray floor. Motion video supplies only the walk-pause-turn gesture and its timing; do not copy the source person's face, body, wardrobe, background or camera.

[CAMERA AND ACTION]
Chest-height gimbal moves backward at Noor's walking pace, holding a medium full shot. 0–3s — Noor walks three measured steps toward camera, hands relaxed. 3–6s — she stops beside, never in front of, the sculpture and turns her torso 45 degrees left. 6–8s — open-palm gesture toward the sculpture, fingers together, gaze follows hand. 8–10s — she returns gaze to lens and gives one inviting nod. Camera decelerates with her and never orbits.

[SPEECH]
Noor says in French, calmly: “Regardez d'abord la forme, puis l'espace qu'elle retient.” Speech begins after the stop at 3.4s; lips, breath and gesture cadence align.

[AUDIO]
Clear close voice, low gallery HVAC, soft shoes and natural two-second reverberation. No music or crowd.

[CONSTRAINTS]
Transfer motion timing only. Preserve Noor's identity, proportions, suit, scarf and gallery. One sculpture, correct floor contact, no sliding feet, exaggerated imitation, source-scene leakage, subtitle, signage, logo or watermark.
```

**Swap ideas:** museum guide → coach / retail trainer / science host; keep motion ownership separate from appearance ownership.

**Failure check:** Compare pose timing to the motion reference, then confirm no identity or background details leaked from it.

## 4. Rainy Platform Revision and Extension

**Use case:** in-video editing plus continuation · **Format:** existing 7s clip + 5s extension, 16:9 · **Best mode:** video editing / extension

**Why it works:** The edit list isolates one environmental change, protects the original performance and defines the new action from the final source frame.

```text
[EDIT INTENT]
Modify the supplied 7-second platform clip, then extend it by 5 seconds. Preserve original camera path, timing, adult actor identity, navy coat, suitcase, train, platform geometry and all hand/body motion.

[CHANGE ONLY]
Replace dry overcast weather with light rain. Add physically consistent small droplets, wet platform reflections and a few damp marks growing on the coat shoulders. Keep visibility high. Reflections follow original lights and camera motion. Do not change time of day or add wind.

[AUDIO REPAIR]
Retain original footsteps, train brake and announcement timing. Add low rain on the roof and two suitcase-wheel splashes. Do not regenerate or alter existing speech.

[EXTENSION FROM FINAL FRAME]
7–9s — Continue the same camera velocity as the train stops. The nearest door opens once; its reflection moves across the wet platform.
9–12s — Actor lifts suitcase handle, takes two steps toward the open door and pauses to let one adult passenger exit. Camera slows to a stop at the same shoulder-level distance. End before boarding.

[CONTINUITY]
Match lens, exposure, grain, rain density, rail direction, actor stride and suitcase-wheel rotation across the original/extension seam.

[CONSTRAINTS]
No face, wardrobe, suitcase, train, architecture, dialogue or camera redesign. Do not remove original objects. No lightning, heavy storm, crowd multiplication, umbrella, slow motion, text, logo or watermark.
```

**Swap ideas:** weather-only edit → season / practical light / approved prop color; always list protected pixels and sounds before additions.

**Failure check:** Watch the source/edit boundary at half speed for rain popping, exposure jumps, foot sliding or audio replacement.


# Commerce, Tech, Mobility & Industrial Prompts

[← Catalog](README.md) · [Prompting guide](../docs/PROMPT-GUIDE.md)

Four original Kling recipes for live selling, gadget demonstrations, automotive films and industrial process visualization. Use approved products, claims, facilities and safety procedures.

## 1. Foldable Kettle Live Demo

**Use case:** e-commerce livestream segment · **Format:** 15s, 9:16 · **Best mode:** host + product references, single take

**Why it works:** One feature is demonstrated through visible hand contact while pricing, availability and overlays stay outside generation.

```text
[OUTPUT]
15 seconds, 9:16, credible live-commerce demonstration, one continuous phone-camera take, no generated interface.

[LOCKS]
Host Ava: adult woman, braided ponytail, coral overshirt, neutral manicure. Product: unbranded collapsible travel kettle, white rigid base, three gray silicone rings, white lid and short black cord. Preserve part count and proportions.

[SET]
Bright apartment kitchen counter. Kettle center, clear measuring cup left, folded pouch right. Locked phone at eye height, slight autofocus breathing, soft window light.

[ACTION AND SPEECH]
0–4s — Ava holds the collapsed kettle beside her face without blocking it and says in English: “This is the packed size.”
4–9s — She sets it flat, keeps left palm on the base and pulls the lid upward with right hand until exactly three silicone rings extend. She rotates it 30 degrees to show the profile.
9–13s — She pours one measured cup of water inside, closes the lid and points to the cord; she does not plug it in or claim a boil time. She says: “Open, fill, and check your local voltage before use.”
13–15s — Product rests centered; Ava places both hands behind it for clean scale reference and smiles at lens.

[AUDIO]
Close phone-mic voice, silicone folds, water pour and room tone. No music, sales chime or synthetic audience.

[CONSTRAINTS]
No boiling, steam, outlet contact, price, discount, countdown, certification, false capacity, generated comments, text, logo or watermark. Natural fingers and product contact; base never deforms.
```

**Swap ideas:** kettle → folding lantern / compact steamer / travel bowl; demonstrate only an approved, visible feature.

**Failure check:** Confirm three rings, dry electrical parts, exact host wording and no invented shopping UI.

## 2. Open-Ear Headset Assembly Proof

**Use case:** consumer-tech feature film · **Format:** 10s, 1:1 · **Best mode:** product reference + start/end frames

**Why it works:** A finite component list and mechanically plausible paths prevent generic “exploded view” hallucinations.

```text
[OUTPUT]
10 seconds, 1:1, clean photorealistic product-engineering animation, dark neutral studio, two shots.

[PRODUCT LOCK]
One generic open-ear headset: flexible graphite neckband, two identical oval speaker pods, two small copper hinge pins and one central charging contact. No buttons, screen or logo. Start frame shows five separated components; end frame shows one assembled headset.

[ANIMATION]
0–5s — Orthographic three-quarter view. Five parts float no more than 4cm apart in a straight exploded arrangement. Camera makes a slow 15-degree orbit while soft edge lights reveal material differences. Parts do not spin.
5–10s — Neckband stays fixed. Left and right pods translate inward simultaneously along straight guides; copper pins insert once into matching hinges; charging contact seats last with a subtle click. Camera stops before contact and holds the completed silhouette for two seconds.

[AUDIO]
Low electronic air, two soft mechanical seats at 6.5s, one precise contact click at 7.8s, then silence. No voice-over.

[CONSTRAINTS]
Exactly five starting components and one final headset. No new screws, batteries, wires or circuitry. No melting, magnetic snap from a distance, intersection, asymmetry, text, technical claim, logo or watermark.
```

**Swap ideas:** headset → hand tool / camera grip / desk accessory; enumerate components and insertion axes.

**Failure check:** Count parts on the first frame and confirm every part has one visible destination in the final product.

## 3. Electric Hatchback, Quiet Departure

**Use case:** automotive brand film · **Format:** 15s, 21:9 · **Best mode:** vehicle + cabin references, custom multi-shot

**Why it works:** Vehicle geometry, wheel motion, road direction and legal driver behavior are locked separately from cinematic camera movement.

```text
[OUTPUT]
15 seconds, 21:9, premium generic electric hatchback film at blue hour, three shots, photorealistic.

[VEHICLE LOCK]
One compact pearl-gray five-door hatchback, continuous dark glass roof, narrow front light bar, six-spoke wheels, blank plates and no logo. Same clean body, ride height, cabin and wheel design throughout.

[TIMED SHOTS]
0–5s — Interior rear three-quarter. Adult driver seated, belt fastened, both hands at 9 and 3. Dashboard remains abstract and unreadable. Driver checks left mirror, then forward; cabin ambient strip brightens softly.
5–10s — Exterior curb-height side tracking. Car moves left-to-right at low urban speed on a damp empty access road. Wheels rotate with travel, contact shadows stay attached, reflections slide backward. Camera matches speed without passing.
10–15s — Wide elevated front three-quarter. Car follows one gentle right-hand curve, slows at a marked stop line and comes to a complete stop. City lights remain distant; end with clean sky space.

[AUDIO]
Seat-belt fabric, soft indicator tick, tire hiss on damp pavement and restrained tonal music. No engine roar, tire squeal or voice-over.

[CONSTRAINTS]
One vehicle, licensed adult driver, safe speed, correct lane and full stop. Preserve panels, doors, lights and wheels. No autonomous-driving claim, racing, road traffic, drifting, transformed bodywork, readable dashboard, badge, plate text or watermark.
```

**Swap ideas:** hatchback → cargo bike / shuttle / mobility scooter; specify safe behavior and wheel-ground physics.

**Failure check:** Track one wheel and one body seam through every shot; neither should change shape or slide.

## 4. Cobot Packs the Blue Valve

**Use case:** industrial manufacturing explainer · **Format:** 12s, 16:9 · **Best mode:** station reference + object reference

**Why it works:** A short pick-inspect-place cycle defines tool orientation, safety zone and object count without inventing factory claims.

```text
[OUTPUT]
12 seconds, 16:9, realistic industrial process visualization, one locked wide shot plus one inspection insert.

[SYSTEM LOCK]
One small six-axis collaborative robot with a two-finger gripper. One matte-blue metal valve body on the left fixture, one camera inspection gate center, one open molded tray right. Yellow floor boundary remains clear. No people inside the boundary.

[CYCLE]
0–4s — Wide. Gripper approaches vertically, closes around the valve's flat side and lifts 8cm. Wrist remains level; fixture does not move.
4–8s — Cut to fixed inspection insert. Robot carries valve through center gate and pauses for one white light pulse. Valve rotates exactly 90 degrees clockwise for the second face, then returns.
8–12s — Return to the original wide angle. Robot translates right, lowers valve into the matching tray cavity, opens gripper and retreats vertically. Valve remains seated; robot returns to neutral pose.

[AUDIO]
Low ventilation, quiet servo movement, gripper click, inspection beep and tray contact. No music or narration.

[CONSTRAINTS]
One robot, one valve and one tray. Mechanically plausible joint motion, no self-intersection, high-speed swing or human entry. Preserve cell geometry, safety boundary and cycle order. No sparks, welding, productivity claim, readable control panel, logo or watermark.
```

**Swap ideas:** valve → packaged food / lab vial / machined part; adapt gripper and safety logic to the approved process.

**Failure check:** Review joint paths, grasp contact, object count and clearance from the safety boundary.


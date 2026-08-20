# Contributing to Awesome Kling 4.0 Prompts

Thanks for helping build a practical, original and evidence-aware Kling video prompt library.

## What we accept

- Original prompts for a clearly named real-world use case.
- Reproducible prompt variations and failure notes.
- Corrections backed by official Kling / Kuaishou documentation.
- High-quality translations that preserve prompt intent rather than translating word-for-word.
- Accessibility, safety, cultural-context and rights-review improvements.

## Originality requirement

Submit only material you wrote or are authorized to license under this repository’s MIT License. Do not copy prompt entries, descriptions, thumbnails, videos, author lists or promotional links from galleries, social posts or other repositories. Inspiration from a broad scenario category is fine; wording, story, characters, shot design, props and examples must be independently created.

Do not submit:

- Prompts that imitate a living artist or request a recognizable copyrighted character.
- Real-person face or voice cloning without documented permission.
- Unlicensed brand assets, music, footage or locations.
- Fabricated model features, prices, benchmarks, API identifiers or release dates.
- Medical, legal, financial or public-safety claims presented without suitable review.

## Prompt entry format

````markdown
## Title

**Use case:** ... · **Format:** ... · **Best mode:** ...

**Why it works:** One short explanation.

```text
[OUTPUT]
...

[CONTINUITY ANCHORS]
...

[WORLD]
...

[TIMED SHOTS]
...

[AUDIO]
...

[CONSTRAINTS]
...
```

**Swap ideas:** ...

**Failure check:** ...
````

## Capability claims

Separate three categories clearly:

1. **Officially verified:** link directly to an official Kuaishou or Kling page and record the access date.
2. **Observed in testing:** identify model, mode, date and settings; do not generalize one run into a guaranteed feature.
3. **Expected / unverified:** do not place in capability tables; label plainly if discussion is still useful.

Until Kuaishou officially announces Kling 4.0, do not describe any “4.0” specification as confirmed.

## Testing checklist

- Replace all `{variables}` or explain why they remain.
- Confirm duration and shot timing add up.
- Check subject, product, prop and location continuity.
- Check hand/object contact, weight and screen direction.
- Check that dialogue belongs to the named speaker and language.
- Verify exact text, pronunciation and packaging separately.
- Confirm there are no unauthorized faces, voices, brands, characters or music.
- Record the most likely failure and how to inspect it.

## Translation checklist

- Keep prompt labels and timing unambiguous.
- Preserve proper names and exact spoken lines unless localization is intentional.
- Adapt punctuation and natural phrasing for the target language.
- Do not add model claims absent from the source guide.
- Ask a fluent reviewer to check dialogue tone and cultural context.

## Pull request scope

Keep each pull request focused: one prompt collection, one translation or one documented capability update. Explain what changed, what was tested and what remains unverified.

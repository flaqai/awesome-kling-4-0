# Contributing to Awesome Kling 4.0 Prompts

Thanks for helping build a practical, original and evidence-aware Kling video prompt library.

## Choose the easiest contribution path

| You have… | Best route |
|---|---|
| A complete original recipe | [Submit a prompt issue](https://github.com/flaqai/awesome-kling-4-0/issues/new?template=prompt.yml) |
| A useful scenario but no finished prompt | [Request a missing scenario](https://github.com/flaqai/awesome-kling-4-0/issues/new?template=request.yml) |
| A tested recipe, translation or documentation fix | Open a focused pull request |

Untested ideas are welcome when marked **recipe-only**. Tested submissions should record the model, mode, date, duration, ratio, input roles and failure notes. Capability corrections need an official primary source.

## What we accept

- Original prompts for a clearly named real-world use case.
- Reproducible prompt variations and failure notes.
- Corrections backed by official Kling / Kuaishou documentation.
- High-quality translations that preserve prompt intent rather than translating word-for-word.
- Accessibility, safety, cultural-context and rights-review improvements.

## Originality requirement

Submit only material you wrote or are authorized to license under this repository’s MIT License. Do not copy prompt entries, descriptions, thumbnails, videos, author lists or promotional links from galleries, social posts or other repositories. Inspiration from a broad scenario category is fine; wording, story, characters, shot design, props and examples must be independently created. See [Curation, Inspiration and Originality](docs/CURATION.md) for the distinction between a coverage reference and a close rewrite.

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

## Review labels

- **Recipe-only:** structurally reviewed but not presented as a benchmark.
- **Community-tested:** includes enough setup and failure notes for another person to repeat the test.
- **Source-verified:** a capability or compatibility statement linked to current official documentation.

A preview image or video is optional. If supplied, include alt text, input/reference roles, generation notes and a license compatible with the repository. Reviewers may accept the prompt without the media.

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
- Keep documentation-language claims separate from native speech support; use the [language matrix](docs/LANGUAGES.md).

## Pull request scope

Keep each pull request focused: one prompt collection, one translation or one documented capability update. Explain what changed, what was tested and what remains unverified.

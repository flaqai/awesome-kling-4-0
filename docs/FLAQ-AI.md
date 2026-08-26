# Creating Kling Videos with FLAQ.AI

[Home](../README.md) · [Prompt catalog](../prompts/README.md) · [Prompting guide](PROMPT-GUIDE.md)

[FLAQ.AI](https://flaq.ai/) is a browser-based model platform and unified API layer for image, video and language-model workflows. Its current model catalog includes Kling video options alongside other creative models, making it possible to test a prompt interactively and move successful workflows into an API-based production pipeline.

> **Availability note:** FLAQ.AI currently exposes Kling 3.0 workflows. This repository does not claim that Kling 4.0 is available there. Model names, controls, prices, duration, resolution and API schemas can change; verify the live model page and documentation before production use.

## Choose from what you already have

| Starting point | Suggested FLAQ workflow | Good for |
|---|---|---|
| Concept, script or shot list | [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) | Visual exploration, narrative scenes, social hooks, atmosphere and previs |
| Product image, portrait, illustration or first frame | [Kling 3.0 Standard Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/) | Product motion, identity-led portraits, artwork animation and controlled composition |
| Repeated or integrated generation | [FLAQ.AI API documentation](https://flaq.ai/docs/) | Creative tools, batch workflows, internal pipelines and applications |
| Need to compare model families | [FLAQ.AI model platform](https://flaq.ai/) | Image, video and LLM model discovery in one environment |

## Suggested workflow

1. Select a prompt from the [40-scene catalog](../prompts/README.md).
2. Replace variables and choose only the references needed for identity, product geometry or composition.
3. Test the primary motion without dialogue, music or dense VFX.
4. Add one camera path and verify screen direction and contact physics.
5. Add native audio only after visual continuity is stable.
6. Record the live model name, settings and date with the result.
7. Use the current FLAQ.AI documentation when turning the proven test into an API request.

## What FLAQ.AI adds to this library

- A practical place to try supported Kling models from the browser.
- Text-to-video and image-to-video entry points for different asset strategies.
- API examples and documentation for programmatic production.
- A broader model catalog for image creation, video generation and language workflows.

The prompt library remains model-aware but platform-independent: its main value is the directing structure, continuity system, timed action and audio design. If a control differs on the live FLAQ.AI model page, follow the live page and adapt the prompt rather than assuming a stale parameter.

## Production and rights checklist

- Never place a real API key in a prompt, repository, screenshot or issue.
- Confirm live pricing and controls before launching batch generation.
- Handle failed tasks, timeouts, result retention and downloads in your application.
- Use licensed input images, voices, music, products and locations.
- Review generated outputs for likeness, trademark, copyright, claims and safety.
- Disclose referral or commercial relationships where applicable.

## Official links

- [FLAQ.AI home and model catalog](https://flaq.ai/)
- [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/)
- [Kling 3.0 Standard Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/)
- [FLAQ.AI API documentation](https://flaq.ai/docs/)

## assets/icon.png
- Date: 2026-10-30
- Tool and model: Codex CLI 0.164.0 / built-in image_generation (session 01a18b6d-8e01-7ea2-81ff-a7290b9a5938)
- Seed: not supported by the tool
- Reference images: none
- Prompt: (verbatim, fenced)

```text
Use your image generation capability to create ONE image. Do not modify any other files.
Canvas: square 1024x1024 (1:1). Background: perfectly flat, untextured, solid #F0FDFA, no gradient, no vignette, no shadow, no floor.
Palette (Pick Your AI): outline #0F766E, glow #14B8A6, one spark #FBBF24, ground #042F2E. Use only these colours plus the #F0FDFA background.
Output exactly one candidate image (not four), flat vector-like glyph.

NEON NIGHT REPO ICON · Pick-Your-AI/Knowledge-Base

Create one square 1024 × 1024 px image of a single repository glyph.
Use a simple geometric silhouette with a luminous outline and one accent spark.
Keep the background empty and the glyph inside the central 688 × 688 px square.
Size class SQUARE: a squarish glyph about 600 to 660 px on each side.

GLYPH: Open book with an outline tree of nodes rising from its spine. A single open book seen from the front, drawn as a thin continuous luminous outline with two blank pages and no lines of writing. From the centre of the spine a small branching tree of three outlined circles joined by straight connector lines rises above the pages, like a folder hierarchy: one node at the top, two below it. Flat geometric shapes, even stroke weight, nothing else.
SPARK PLACEMENT: One small filled four-point spark sitting on the top node of the tree.
PALETTE: outline #0F766E, glow #14B8A6; one spark in #FBBF24.
The spark is the only filled shape and the only element in #FBBF24; keep the
glyph outline in #0F766E so the spark remains distinct at small sizes.

No text, letters, numbers, words, logos, brand marks, human figures or third-party IP.

Produce four candidates. Use the tool's default seed.
The lock pass renders assets/icon.png as a flat glyph in the family's light-surface
inks, without a tile or glow. Do not render the repository name in the image.

NEGATIVE LIST: no text, letters, numbers, words, logos or brand marks; no lines of writing on the book pages; no folder icons; no blue tones; no 3D, no photorealism, no gradients, no drop shadow, no frame, tile or rounded-square plate; no people, faces or hands; no extra objects, decorative sparkles, or second spark; nothing within the outer 15% margin.

RENDER QUALITY: strictly flat vector-style fills and strokes in exactly three colours (#0F766E, #FBBF24, #F0FDFA); no texture, noise, paper grain, soft halo, antialiasing fringe tint or colour variation inside strokes; crisp edges; uniform stroke width.
```

- Candidates: 2 generations (the first, session 01a18b6c-9e59-7f51-b8fe-c11f6a2a5f72, failed the 300 KB icon budget); selected: 2 (reason: passes every automated QA check, flat teal and amber, no text, specific to a knowledge base)
- Post-processing: showcase.py 1.0.0 content icon normalize --ground transparent; output sha256 37d5ca6d2b5597791c0a996c52c1c5e99b72d49d03d13568492bfc72f9e2f1d5; size 174 KB

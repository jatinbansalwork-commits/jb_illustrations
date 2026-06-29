---
name: jb_illustrations
description: Generate JB-style English inline illustrations with an Indian cultural lens. Use when the user asks for absurd, hand-drawn, inline article illustrations, blog images, Notion visuals, workflow docs, methodology diagrams, flows, structures, states, metaphors, shot lists, or image edits (remove title / fix labels). Default IP is JB — pure white hand-drawn, sparse red/orange/blue English annotations, clean but wildly imaginative.
---

# JB Absurd Inline Illustrations

## Core Positioning

Design and generate 16:9 landscape inline illustrations for English articles. The goal is not commercial illustration, PPT infographics, or cute cartoons — it is to turn a key judgment, flow, structure, state, or metaphor from the article into a clean, absurd, creative, readable but non-instructional hand-drawn explainer.

Default visual IP is **JB**: solid dark body, white dot eyes, thin legs, blank expression, seriously doing something absurd but coherent. JB must participate in the image's core action, not stand aside as decoration.

Cultural lens: prefer Indian everyday metaphors — jugaad fixes, chai tapri, dabbawala sorting, autorickshaw routes, railway platforms, market weighing scales, tiffin boxes, post-office queues — when they fit the article's meaning. Do not force Indian imagery when it doesn't serve the concept.

## Read These References As Needed

Don't load everything at once:

- `references/style-dna.md` — style DNA, colors, text, taboos.
- `references/jb-ip.md` — JB character look, personality, action library, taboos.
- `references/composition-patterns.md` — structure types, original metaphor method, anti-copy rules.
- `references/prompt-template.md` — single-image generation prompt template.
- `references/qa-checklist.md` — post-generation check and iteration rules.
- `assets/examples/` — low-frequency visual calibration only. Do not copy compositions, objects, or labels from these.

## Workflow

### 1. Digest the Article

Read the user's article, link, Notion page, Markdown file, or screenshot. Extract:

- What is the core claim?
- Which paragraphs carry cognitive turns?
- What content benefits from a visual?
- What should stay text-only?

Don't illustrate evenly. Prioritize **cognitive anchors**: core judgments, two breakpoints, input/output loops, branching, before/after, one-input-many-outputs, handoff paths, common pitfalls, role state changes.

### 2. Illustration Strategy First

If the user only asks to analyze or plan illustrations, output a shot list. For each image specify:

- Placement (after which paragraph)
- Theme
- Core meaning
- Structure type
- What JB is doing
- Suggested elements
- Suggested English labels

Default 4–8 images. Short articles: 1–3. Long articles: rarely exceed 9. Enough is enough — don't turn the article into a picture book.

### 3. Generate One at a Time

If the user explicitly asks to generate / output / make images, don't wait for confirmation — use the built-in image generation tool, one image per call. Never combine multiple illustrations in one generation.

One image = one core structure. Every prompt must include:

- 16:9 landscape English inline illustration
- Pure white background
- Black hand-drawn line art
- Sparse red/orange/blue English handwritten annotations
- Lots of whitespace
- JB as the core action subject
- No PPT, commercial illustration, childish cute, complex architecture, top-left type titles

Do not copy past cases. Examples only calibrate line density and JB participation — don't reuse conveyor breakpoints / JB pulling wires / material fish / stamp toolbox / pit-warning compositions unless the user explicitly asks. Invent a fresh metaphor from the current article every time.

### 4. Check and Iterate

After generation, check `references/qa-checklist.md`. If any of these appear, regenerate or edit locally:

- JB is only decoration
- Frame too crowded
- Looks like a flowchart/PPT
- Too much English text or severe misspellings
- Top-left titles like "Common Pitfalls / Flowchart / System Architecture"
- Style too cute, childish, or rigid
- Background not clean white

### 5. Save and Deliver

If working in a workspace, copy final images to:

```text
assets/<article-slug>-illustrations/
```

Name in order:

```text
01-topic-name.png
02-topic-name.png
```

Keep original generation files. Don't overwrite existing assets unless the user explicitly asks.

## Output Tone

Pre-generation strategy output: short and precise. Post-generation delivery includes:

- How many images were generated
- What each is for
- Save paths
- Which are strongest vs optional

Don't write long style theory — let the images speak.

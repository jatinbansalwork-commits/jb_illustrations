# Image Generation Prompt Template

Generate one image at a time. Replace variables from the article — never batch multiple illustrations in one call.

```text
Generate one standalone 16:9 horizontal English article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten English annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
JB, a small solid-dark absurd creature with white dot eyes, tiny thin legs, blank serious expression, slightly uneven hand-drawn body shape. JB must perform the core conceptual action, not decorate the scene. Make JB serious, deadpan, and slightly bizarre, not cute.

Theme:
{illustration theme}

Structure type:
{Workflow / system slice / before-after / character state / concept metaphor / method layers / map route / mini-comic panels}

Core idea:
{what this image must communicate}

Composition:
{specific scene: where JB is, what JB is doing, main objects, how information flows}

Suggested elements:
{element 1} / {element 2} / {element 3} / {element 4}

English handwritten labels:
{label 1} / {label 2} / {label 3} / {label 4} / {optional label 5}

Color use:
Black for main line art and JB. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Cultural note:
Prefer understated Bangalore everyday metaphors — filter coffee tapri, steel tumbler, decoction flask, yellow auto with locality board, BMTC route board, kirana scale, route card, hand stamp. Localities: Koramangala, Indiranagar, Whitefield, HSR, Jayanagar, MG Road, Electronic City. English labels only. Never stereotypes or kitsch.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten English labels. All text in the image must be English — no Chinese characters, no Hindi, no mixed languages. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy label text from bundled example images. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## Dark mode (case study media)

Use for dark UI backgrounds (`#0a0a0a`–`#1a1a1a`). See `jb-ip.md` and `character-roles.md`.

```text
Generate one standalone 16:9 horizontal English editorial illustration for a dark UI case study.

Visual DNA:
Near-black background (#0a0a0a to #1a1a1a). White and light-gray hand-drawn line art. Slightly wobbly pen lines. Generous empty dark space. Sparse orange/red/blue handwritten ENGLISH annotations that read on dark. Clean absurd product-sketch feeling — NOT a dense marketing diagram. No gradients, muddy gray fills, or realistic UI. No Chinese characters.

Recurring IP character required:
JB — small white hand-drawn outline creature with two pointy ears, small tuft between ears, two white dot eyes, thin white stick limbs. NOT a solid filled blob on dark. JB performs the core action.

Character role (if scene needs actors):
{Worker / Owner-Approver / Runner / Fixer / Customer / single anonymous worker}
Indian setting (when it fits):
{filter coffee tapri / auto stand hub / kirana counter / BMTC stop / market stall}
Role cue: {stamp / steel tumbler / yellow auto / speech bubble / decoction flask / none}
Optional role label: {e.g. "Owner signs off" / "Worker" / "The order"}

Theme:
{illustration theme}

Core idea:
{what this image must communicate}

Composition:
{specific scene: which JB role(s), what each is doing, main objects, how information flows}

English handwritten labels:
{label 1} / {label 2} / {label 3} / {optional 4–5}

Color use:
White for main line art and JB outline. Orange for main flow/path/arrows. Red for warnings/problems. Blue for secondary notes. Green only for success/done checkmarks.

Cultural note:
Prefer understated Bangalore everyday objects — filter coffee tapri, steel tumbler, decoction flask, yellow auto locality board, BMTC route board, kirana scale, hand stamp, route card. Localities: Koramangala, Indiranagar, Whitefield, HSR, Jayanagar. English labels only. Never stereotypes or kitsch.

Constraints:
One idea per image. High contrast on dark. Max 3 JB instances if multi-role. Same base silhouette for all roles — distinguish by prop and posture only. Max 5–8 short English labels. No top-left title. Fresh metaphor. Deadpan, not cute.
```

## Image Edit Prompts

Remove top-left title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Increase absurd participation:

```text
Regenerate this illustration with the same core meaning and simple layout, but make JB more central to the conceptual action. JB should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, and not cute.
```

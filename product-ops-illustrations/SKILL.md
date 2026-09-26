---
name: product-ops-illustrations
description: Create and edit English visual explainers for processes and workflows across the mining value chain—pit operations, processing plants, rail, and ports—and for AI and business intelligence products. Use for workflow illustrations, system overviews, operational handoffs, product concepts, and illustration planning.
---

# Product & Operations Illustrations

Turn a supplied process or concept into an accurate, sparse, original visual explainer. Offer two coordinated versions: **Realist** (the default, with natural faces and modest shading) and **Cartoon** (spare, expressive ink drawing). Both use the named human cast, photo-guided workwear, teal and amber flow cues, and short English labels. This skill produces conceptual illustrations, not engineering drawings, implemented dashboards, complete slide decks, or motion graphics. When those are the main request, use the appropriate workflow; apply this skill only to an explicitly requested illustration within it.

## Understand the brief

Accept pasted text, documents, accessible links, screenshots, an existing image, or a single concept. Read the supplied content before planning. If a source cannot be accessed, say so and request its relevant content; do not invent its process.

Identify the audience, process boundary, intended takeaway, actors, sequence, essential terminology, and required labels. Infer reasonable audience and placement defaults when they do not change meaning; briefly state consequential assumptions. Ask one focused question when missing information would materially change the process. Otherwise remain conceptual and show only supported stages.

The supplied process is the source of truth. Do not invent equipment, connections, site names, metrics, outcomes, or product capabilities. Shorten labels without changing their meaning. Explicit user choices override defaults.

Read only the applicable domain guidance:

- Mining flows and handoffs: [mining](references/mining.md).
- AI or BI products: [AI and BI](references/ai-bi.md).
- Combined mining and digital workflows: read both, including the combined-workflow section in AI and BI.

When a brief includes mining subjects, consult the [mining cutout library](references/mining-asset-library.md). For every diagram, use [hand-drawn diagram notation](references/diagram-notation.md).

## Select the mode and template

- **Plan-only:** When asked for ideas, a shot list, or planning without generation, return the plan and stop. Do not call an image tool.
- **Generate:** When asked to create or generate illustrations, prepare a compact specification and proceed directly to the available built-in image-generation tool. No approval pause is required for ordinary generation.
- **Edit:** Inspect the supplied image and change only the requested content. Preserve its composition, wording, palette, ratio, and character outside the requested change. Do not retrofit this skill's human cast, workwear, or English language into an unrelated edit unless requested.

Use [the template catalog](references/templates.md) to select Process and Systems, Before and After, or Framework and Journey. An explicit template choice takes priority. Read that pack's recipe. Use calibration images for visual calibration; invent a fresh composition for the current brief. Never transplant facts or labels from an example.

Select Realist unless the user asks for Cartoon or supplies a different style. The template pack and visual version are independent choices. When the user asks for both, generate two separately named PNGs with the same process facts and labels. See [the style and cast guide](references/character-and-uniforms.md) for reference priority, four names, heights, and selectable uniforms. Any named character may wear the Rio Tinto navy jacket, navy polo, or yellow/navy operations shirt; the user's assignment takes priority over the default sheet. A single person can appear at any size needed for readability; when people appear together, keep Brett shortest, Phill tallest, and Paulo and Kayne at similar middle heights.

Default to one image for a single concept and three for a document. Reduce a set when there are fewer distinct ideas. Use at most six unless the user asks for more. Each image communicates one takeaway. For plan-only output, give a compact table: placement, takeaway, template, scene, character action and outfit, and exact proposed labels.

## Generate and inspect

Read [the visual system](references/visual-system.md) and [character and uniform guidance](references/character-and-uniforms.md). Inspect the selected version's named team sheet and the relevant uniform photo before the first generation in a task. Pass both through the image tool's supported reference mechanism: the sheet guides character identity and style; the photo guides garment cut and color; the user's specified character-to-uniform assignment and red Rio Tinto chest wordmark take priority. Use the alternate-uniform sheet when the user requests a reassignment. Inspect at most one relevant template example initially; consult more only to resolve a visual uncertainty.

Generate each requested illustration as a separate image. Default to 16:9 PNG, requesting a landscape size such as 2048 × 1152 if the available tool supports it. Allow up to one pixel of raster rounding for the default aspect ratio; report actual dimensions when a fixed pixel size was requested, and never claim an unsupported exact size. Use the built-in image tool for requested illustrated bitmap scenes and cutouts; use the editable SVG notation primitives for deterministic arrows, flowchart shapes, and simple icons when composing a diagram in an appropriate vector workflow. Do not replace requested illustrated mining cutouts with programmatically drawn placeholders. If generation is unavailable, explain the limitation and deliver an accurately labelled plan/prompt rather than claiming an image was created. Do not switch to a paid external/API workflow without authorization.

For mining subjects, use only source-supported assets from the cutout library, preserving their recognizable pit benches, plant conveyors, loaded wagons, and bulk-port shapes as applicable. Keep cutouts truly transparent when delivering reusable isolated assets; place them on white only in a finished diagram. For every diagram, apply the hand-drawn notation guide to arrows, boxes, icons, and keys. Include the approved process facts, a single takeaway, the selected recipe, the chosen Realist or Cartoon version, the named character's meaningful action and photo-guided outfit, exact quoted labels, palette, whitespace, and any critical excluded connections in the prompt. Default to 3–5 short English labels, with fewer where appropriate. Preserve source facts in the depicted relationships without turning every fact into a label. Combine related wording and move supporting definitions to the accompanying explanation before increasing image text. If a critical gate or required term still needs an extra label, use the smallest necessary exception and say why; never omit it to meet a count. Do not render internal template names, a slide heading, or invented numerical results.

When material and information coexist, use solid amber arrows for physical movement and dashed teal arrows for information, and explain this distinction with two short English key labels. Route information to the actual decision-maker; show a control action only when supplied. Count key labels within the label budget when practical; accuracy can justify a few more short labels.

Inspect the actual image against [the QA checklist](references/qa.md), including aspect ratio and exact lettering. Correct an isolated error through a targeted image edit; for structural errors or multiple bad labels, regenerate with a simpler composition. Reinspect the changed result. If two targeted corrections do not resolve the same problem, report the remaining limitation and offer a simpler or text-light version rather than repeating indefinitely.

## Save and deliver

Follow a user-provided destination and the current workspace's output conventions first. Otherwise save to `assets/<source-slug>-illustrations/` within the active workspace. Use ordered descriptive filenames such as `01-pit-to-port.png`. If a name exists, choose `-v2`, `-v3`, and so on; never overwrite without an explicit replacement request. Preserve the original when editing.

Copy generated assets from the tool's storage into the delivery directory. Verify that delivered paths exist and contain the actual images. Return the images or clickable paths, their purposes, and any unresolved issues. Keep the final explanation short. Never claim a concept illustration validates engineering design or demonstrates real performance improvements.

## Add personal templates

For a new pack, follow the contribution steps in [the template catalog](references/templates.md): add the user's approved reference images, a short recipe, and a catalog entry. Inspect and describe the user's references before writing rules. Keep their image identity and use permissions; do not silently redraw or replace a supplied template. Do not change the shared visual identity unless the user requests it.

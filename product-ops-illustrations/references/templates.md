# Adaptable template catalog

Select by the reader's intended takeaway, then respect any explicit user override. Domain alone does not select a pack: each pack can express mining, AI/BI, or a combined workflow. A single illustration uses one primary pack.

| Pack | Use when | Avoid when | Recipe |
| --- | --- | --- | --- |
| Process and Systems | The sequence, connection, handoff, dependency, or bottleneck matters | The actual takeaway is a comparison rather than a flow | [Recipe](packs/process-systems.md) |
| Before and After | A supplied change or tradeoff needs a matched comparison | Only one state is known; do not invent an after state | [Recipe](packs/before-after.md) |
| Framework and Journey | Stages, layers, responsibilities, or a decision journey need grouping | Precise causal or material flow is the essential point | [Recipe](packs/framework-journey.md) |

When a template override has insufficient facts, use it if the missing content is merely stylistic. If it requires an unknown operational state, ask for that state rather than fabricating it or silently switching packs. Never insert an approval delay for a complete generation request.

## How to use references

Each recipe links three subjects in both Realist and Cartoon versions. Inspect the version and subject closest to the brief, along with its named team sheet and relevant outfit photo selected through [the uniform guide](character-and-uniforms.md). Use references to calibrate character consistency, wardrobe, spacing, linework, icon treatment, and lettering, while changing the arrangement and objects to express the current brief. For mining subjects, also inspect the relevant [transparent cutouts](mining-asset-library.md); for arrows, flowcharts, and small icons follow [diagram notation](diagram-notation.md). The user's outfit choice takes priority; the photo guides its cut and color, and the named sheet guides identity. Keep reference imagery's labels out of a new scene unless those labels are supported by the current source.

## Add your own pack

1. Place 1–3 approved reference images in a new folder under `assets/templates/` with descriptive filenames. Keep attribution or use restrictions supplied with them.
2. Add a short Markdown recipe under `references/packs/`. Include its name, intended takeaway, when to use/avoid it, what stays fixed, what can vary, links to its images, prompt slots, and a concrete failure check.
3. Add its row to this catalog. Identify its selection cue in plain language; no programmatic registration or schema is required.
4. Try one representative brief with an explicit pack choice, then a similar request without that choice. Inspect the results and adjust only rules supported by the observed mismatch.

For your own image plus prompt, label the image as a style reference or edit target, identify which prompt phrases express enduring rules, and preserve exact text only where it belongs in future outputs. If a new pack intentionally changes the shared identity, record that explicit exception in its recipe; do not silently change other packs.

---
name: xxd-panel-101
description: "XXD Panel 101｜Nine-Cell Memory Notebook: breaks one photo into nine small memories drawn on a loose, hidden 3×3 grid — the subject, a detail, something carried, a plant, food, a way of travelling, a pose or a mood symbol, each a naive hand-drawn doodle with wobbly, uneven, open outlines, coloured pencil and crayon fill that leaves paper grain, slightly offset icons with plenty of space, a low-saturation retro candy palette (sage, mint, crayon blue, cobalt, cream yellow, dusty pink, strawberry, a little coral red) on warm off-white textured paper, a few red hand-drawn annotations such as circles, arrows, hearts and stars, a short handwritten title on top and a tiny caption below. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-101 or asks for a 3×3 doodle icon grid, journal page, memory list or hand-drawn collection sheet from a photo."
---

# XXD Panel 101

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-101/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-101-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks

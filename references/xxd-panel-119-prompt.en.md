# Panel 119 delivery adapter

Read `original-prompt/zh-CN.md` completely before each generation. It alone controls aesthetics. Reading translations are not runtime substitutes.

- Inputs: one original photograph or an isolated directory batch. Never reprocess another Panel, sample, or intermediate stylisation.
- `top-bottom`: exactly two full-width regions; photograph above, textile collage below, 50:50.
- `left-right`: overrides the source brief's top-bottom delivery only; exactly two full-height regions; photograph left, textile collage right, 50:50. No internal top-bottom split.
- `design-only`: textile collage fills the canvas; the original remains a non-visible reference.
- `wallpaper-pack`: full-canvas textile artworks for phone, iPad, desktop and watch; resolve `linked` or `independent` and device dimensions.
- Sizes: `auto`, `source`, common/custom ratios or exact pixels; resolve before generation.
- Text: `prompt`, `exact`, `none`; explicitly resolve locale. Prompt text is sparse, source-grounded editorial wording; exact text is verbatim; none excludes all visible text and pseudo-text.
- Append only the selected mode, size, text and explicit non-style requirements after the complete canonical Chinese source. Generate each comparison as one complete canvas in one pass.
- Preserve selective extraction, few large layered fabric shapes, cotton-linen fibres, raw-edge appliqué, sparse stitches, 2–4 warm lively source colours, and abundant negative space. Never add unrelated style rules.
- Save collision-safe PNGs flat in one fresh task folder; inspect exact midpoint, identity, textile material, whitespace and text; clean AI metadata before delivery.

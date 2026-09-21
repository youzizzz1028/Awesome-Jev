# Figure contract and QA notes

## Figure 1 — Machine-native decision-model landscape

- **Core conclusion:** machine-native decision models can be compared along five separable design dimensions, each with a distinct evidence boundary.
- **Archetype:** taxonomy-led review figure.
- **Evidence logic:** the top strip formalizes the operational object; five aligned rows map design dimensions to representative choices; the right column prevents structural, semantic, probabilistic, and decision claims from being conflated.
- **Data:** no empirical or simulated observations; the figure is a conceptual synthesis of the cited review literature.
- **Reviewer risk:** arrows indicate conceptual contribution, not historical causality or architectural inheritance.

## Figure 2 — Evaluation and control loop

- **Core conclusion:** reliability is a closed-loop property that needs complementary structural, semantic, probabilistic, selective, and operational views.
- **Archetype:** asymmetric mixed-modality review figure.
- **Evidence logic:** panels a–b establish the control loop and four evaluation layers; panels c–e show the diagnostic views for calibration, selective prediction, and system trade-offs.
- **Data:** no empirical or simulated observations.
- **Reviewer risk:** the diagram gives a general protocol; particular deployments may omit or add actions.

## Export and visual QA

- HTML/CSS with editable SVG is the rendering source. Interface and evaluation glyphs come from the open-source Lucide icon set; the vendored license is in `icons/LICENSE`.
- Fixed export canvas: 1800 × 1060 px (Figure 1) and 1800 × 1120 px (Figure 2).
- The HTML remains fully editable; browser-rendered PNG files are the manuscript previews.
- Color is redundant with labels and spatial position; interpretation does not rely on red/green contrast.
- Text is manually line-broken within fixed safe zones; no label is allowed to touch or cross a container boundary at the final export size.
- Arrows encode only three relations: solid horizontal arrows for inference, a solid downward path for action/outcome flow, and one dashed outer-edge path for monitoring feedback.
- Generated files are reproducible from the two HTML files in this directory.
- Visual organization was informed by the lifecycle taxonomy and acquisition/retrieval figures in Zhou et al., *A Comprehensive Survey on Agent Skills* (arXiv:2605.07358). No source panel, icon, text, or artwork was copied.

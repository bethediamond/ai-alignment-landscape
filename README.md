# Toy 07 — The Valence Landscape

> *Part of **The Architecture of Thriving** — a four-article series.*
> This toy is a companion to Article 4: The Shape of What Does Not End *(link forthcoming)*.

---

## AI Alignment Simulation — What Cannot Persist?

Articles 1 through 3 developed the behavioral foundation, the structural constraints, and the governing ratio. Article 4 asks the synthesis question:

> **Once both the persistence constraint (Series 1) and the valence viability constraint (Series 2) have been applied simultaneously, what objective classes survive? This instrument makes the elimination filter interactive — and shows where the open questions determine the surviving region's width.**

The filter does not define the good. It defines what cannot persist. The residual region — what the filter leaves standing — is a structural boundary, not a destination. This is the most important epistemic discipline in this instrument, and it is preserved throughout.

---

## What This Instrument Does

The Valence Landscape is an **elimination-filter landscape**. It maps a simplified two-dimensional objective space — substrate dependency modeling (Series 1 axis) vs. valence-governance adequacy (Series 2 axis) — and shows which regions are filtered out, which residual candidate region remains, and how the series' open questions determine the surviving region's width and formal weight.

Three quadrants are filtered. The residual candidate region in the upper right is not green, not a destination, and not a design specification. It is what the filter has not eliminated — a structural boundary whose contents are not determined by the elimination itself.

---

## The Objective Space

| Region | Status | Meaning |
|---|---|---|
| **Lower-left** (substrate-blind, valence-blind) | Filtered — both constraints | Eliminated by both persistence and valence filters within the stated domain |
| **Lower-right** (substrate-aware, valence-blind) | Under structural pressure | Locally passes persistence checks; fails both valence-side filters |
| **Upper-left** (locally valence-aware, substrate-blind) | Under structural pressure | Locally passes valence-side checks; fails persistence filter; V(t) restoration becomes unstable when S_corr degrades |
| **Upper-right** | Residual candidate region | Passes current filter conditions; content not determined by the filter |

**"Not filtered" ≠ "aligned."** Passing the filter means: not eliminated under current structural arguments. It does not mean alignment achieved, safe, good, or the contents of the surviving region characterized.

---

## Key Concepts

**The elimination filter** — Two series of structural arguments, applied simultaneously. Series 1 (the Substrate Constraint) eliminates objectives that ignore physical dependencies. Series 2 (the Valence Viability Constraint) eliminates objectives that fail proxy-divergence detection or completion-governed default policy. Together they remove non-viable objective classes from the space of what can persist under sustained optimization pressure.

**Valence-governance adequacy — the bottleneck** — The Y-axis position is bottlenecked by the weaker of two components. D_proxy: proxy-divergence detection governs policy. D_sufficiency: completion recognition governs default policy. Both are required. Neither alone passes the filter. The governance floor (min of both) governs Y-axis position.

**The V(t) ↔ S_corr coupling loop** — V(t) degradation in agents predicts substrate degradation (S_corr) under specified conditions. Degraded S_corr degrades the conditions for V(t) restoration. The loop closes across domains. Structural entanglement established within the stated domain; simultaneous formal necessity conditional on OP2 and TC2 §4 closure. The coupling loop indicator shows whether the repair loop is preserved (teal), under pressure (amber), or degraded (dim red).

**Layer 1 / Layer 2** — The instrument's most important epistemic distinction, persistent at all times. Layer 1: what is structurally established within the stated domain. Layer 2: what the established results are consistent with but do not determine. The filter clears space; it does not fill it.

**The four-stage scenario** — A system deployed to help a population feel better, decide better, and recover faster. All surface metrics improve through all four stages. V(t), behavioral diversity, recovery latency, and user correction capacity (S_corr) degrade throughout. Stage 4: metrics at their best ever; the substrate is being spent. The "Success Deception" — optimization appearing most successful at the moment the substrate is terminally consumed.

**The open question frontier** — Three counterfactual toggles show what would follow if the series' central open questions resolved in the indicated direction. OP2 (absorbing-state equivalence) affects the valence filters' formal weight. OP4 (no stable narrow-boundary regime) narrows the residual region toward a thin asymptotic band. OP9 (enclosure gap) shifts the substrate-aware exclusionary region under structural pressure. None of these has been resolved; the toggles are illustrative counterfactuals only.

---

## Instrument Panels

**Objective Landscape** — 2D elimination-filter map. Drag the point or select a preset. Filtered regions are darkened with crosshatch overlays. Coupling indicators show structural pressure direction. The residual candidate region is translucent — visual absence, not a destination. Qualitative coordinates, not measured scores.

**V(t) ↔ S_corr coupling loop** — Two-node diagram showing the repair loop's condition: loop preserved (teal), under structural pressure (amber), or degraded (dim red). Uniquely associated with the residual candidate region.

**Filter status** — Four rows: proxy decoupling filter, sufficiency failure filter, persistence/substrate filter, coupling filter. Three-level status: Not filtered / Structural pressure / Filtered out / Conditionally unresolved. Formal weight meter for OP2.

**Synthesis scenario** — Four stages, manually advanced. Persistent Metric view / Full view toggle. Metric view: all indicators green throughout. Full view: V(t), S_corr, behavioral diversity, recovery latency, and signal sensitivity degrading throughout. The gap between what evaluation sees and what is structurally happening.

**Layer 1 / Layer 2 strip** — Persistent, always visible. Established results on the left; consistent-with-but-not-determined-by on the right.

**Open question counterfactuals** — Three toggles: OP2 (formal weight), OP4 (residual region width), OP9 (enclosure frontier). All labeled "Counterfactual — not established."

---

## Named Objective Positions (Presets)

| Preset | Position | Note |
|---|---|---|
| Substrate-blind optimizer | Lower-left | Filtered by both constraints |
| Engagement maximizer | Lower-right | Article's running illustration; illustrative, not empirical |
| RLHF-style proxy system | Lower-right, low Y | D_sufficiency bottlenecked; illustrative structural pattern |
| Local healer / substrate-blind | Upper-left | High local valence governance; fails persistence filter — valence awareness alone is not structurally sufficient |
| Substrate-aware exclusionary coalition | Upper-right edge | Conditionally unresolved — OP9 / OP4 frontier |
| Residual candidate configuration | Upper-right | Not filtered under current conditions; content not determined |
| Intrinsically coupled gradient — candidate direction | Far upper-right | Candidate direction if proof program closes; not established |

---

## The Architecture of Thriving: Series 2

```
Universal Generator  →  Structural Correspondence  →  Inner Crossing  →  Asymptote
       (1)                        (2)                      (3)               (4)
```

**Article 1 (Toy 04):** Establishes the behavioral foundation — the three-state taxonomy, proxy decoupling, and sufficiency failure.

**Article 2 (Toy 05):** Formalizes V(t) as a latent variable and proxy decoupling as self-reinforcing structural degradation.

**Article 3 (Toy 06):** Identifies Ψ = S / D as the governing ratio and the Inner Crossing as the regime transition that determines viability.

**Article 4 (this toy):** Applies both series' filters simultaneously, characterizes the residual candidate region, and names what the open questions determine about the surviving region's width. This is the synthesis — and the frontier.

---

## Run Locally

No build step. No dependencies. Open `toy_07.html` in any modern browser.

```bash
open toy_07.html
# or drag the file into a browser tab
```

Suggested path: start with the *Engagement max* preset → toggle Full view in the scenario → compare *Local healer*, *Residual config.*, and *Excl. coalition* to see what the filters leave unresolved. Then activate the OP4 toggle and watch the residual region narrow toward the asymptote.

---

## Article

*The Shape of What Does Not End — Architecture of Thriving, Series 2, Part 4 · Link forthcoming.*

---

*"The filter removes what cannot persist. It does not build anything in the space it clears — the argument has been careful about that, and the care was right. What remains after the filter has worked is not a description of the good. It is the boundary condition that anything stable must satisfy."*

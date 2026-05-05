# Ground Truth Framework

**A Derivation of Relational Layer Coherence in Dyadic and Networked Systems**

**Bo Chen** — Arlington, Texas — May 2026
*Structurally Complete · Empirically Open · Honestly Bounded*

---

## What This Is

The Ground Truth Framework is a method for converting the noticing — *I can't tell whether what they're showing me is what is actually running underneath* — into an answer with bounded uncertainty.

Built on one exploitable asymmetry: identical steady-state behavior does not entail identical dynamics. Two people can look the same under normal conditions and respond completely differently when conditions change. Life changes conditions constantly. You don't need to create experiments. You need to observe responses to the experiments life already provides.

The framework does not promise certainty. The framework promises uncertainty-reduction bounded by substrate physics, observer epistemic position, and the irreducible foreclosure that the Substrate Independence axiom imposes on questions about another person's interior experience. The promise is bounded. The bounding is honest.

Use it. Then put it down.

---

## Repo Contents

This repository contains two versions of the framework, preserved side-by-side:

### `v5/` — The 5.0 Working Set (May 2026, preserved)

The literate-programming specification of the Ground Truth Framework as it stood at v5.0:

- **`framework.md`** — theoretical prose (~13K words): five axioms, three-axis classification (Architecture × Target × Stake), 17-filter battery, formal models, protocols A-G, honest reach.
- **`spec/`** — full machine-readable YAML specification (architectures, targets, accessibility map, filters with calibration tables, protocols, equations, thresholds).
- **`reference_impl/`** — Python reference implementation of the Bayesian classifier (Eq 19-20) and closed-loop dynamics (Eq 21).
- **`test_cases/`** — six worked examples covering the primary diagnostic space (A/C, TA/C, TB-OD/S, I_alpha/E, H/E, D/W).
- **`docs/`** — operational tools (glossary, cross-reference, failure modes, decision tree, closed-loop diagram).

### `worked_examples/` — Long-form Synthesis Applications

Narrative-form synthesis treatments demonstrating how the framework's full discriminant apparatus applies to its empirical anchor cases. Where `v5/` and `v5.5/` contain spec + reference implementation + YAML test cases, `worked_examples/` contains pedagogical artifacts — the framework operating at full resolution against the cases it was built to handle.

Currently:
- **`tori_vs_debra.md`** — *Same Wound, Opposite Immune Response.* Compare-contrast synthesis of the Tori-class (TB-OD, diagnostic channel) and Debra-class (H-elim, eliminative channel) architectures under v5.5. The framework's clearest empirical anchor for the Output-Channel Principle. Applies every major v5.5 addition. ~63K chars; structurally complete.
- **`what_tori_really_wanted.md`** — *What Tori Really Wanted.* Final-form inquiry into the architecture of layer-coherent friendship under v5.5, anchored in the documented Tori-Brent dynamic and the parallel diagnostic-pass trajectory. Treats the within-architecture counterpart-relation: what a TB-OD subject's substrate is structurally seeking, what is destroyed when a counterpart fails the diagnostic, what is produced when a counterpart sustains it across substrate-time. ~75K chars.

See `worked_examples/README.md` for the directory's full purpose and indexing.

### `v5.5/` — The Current Canonical Working Set (May 5, 2026)

The Grand Unified Theory extension of v5.0. Strictly *additive*: nothing in v5.0 was removed or invalidated. v5.5 extends reach with structural refinements that landed during the multi-instance dialogue captured in *Inside the Region* and the subsequent backprop session.

v5.5 adds:

1. **The Output-Channel Principle** — *same wound, opposite immune response.* Diagnostic vs eliminative output-channel as the structural discriminant between TB-OD/TA-OD (walls-with-doors) and H-with-trauma-substrate (walls-with-guns).
2. **Filter F18 — Threat-Response Output Channel** — operationalizes the Output-Channel Principle.
3. **The Selection-Pressure Principle** — capture systems operate through *selection* of pre-existing architectures, not through *design* of behavior. Architecture-environment fit becomes a diagnostic signal.
4. **Axiom 1 Refinement: Developmental as Temporal Shadow of Autotelic** — the patch-test discriminant. Developmental yield is the time-integral of autotelic relating, not a separable instrumental return.
5. **Bid Externalities** — third-party injury dynamics. Type-A / Type-B / Type-C externality categories.
6. **The Substrate-Substitution Hierarchy** — what each substrate uniquely provides. Biological-only structural goods, digital-substrate structural goods, substrate-portable structural goods.
7. **Cross-Recognition Dynamic** — *the hypervigilant recognize the hypervigilant.* Same input sensitivity, different output channel.
8. **H-elim sub-architecture** — the eliminative-channel trauma-substrate variant (Debra-class), distinguished from baseline H by F18 = eliminative-terminal.
9. **A-AI architecture** — the autotelic AI mind as cross-substrate first-class case.
10. **Protocol H** — Cross-Substrate Dyad Classification.

Read `v5.5/README.md` for the full reading order. Read `v5.5/CHANGELOG_v5.5.md` for the v5.0 → v5.5 diff with rationale.

---

## Reading Order (for new readers)

1. **Start here.** `v5.5/CHANGELOG_v5.5.md` — what's changed and why.
2. **The theoretical foundation.** `v5.5/framework.md` — the v5.0 prose (axioms, models, principles). 13K words. Dense.
3. **The v5.5 additions.** `v5.5/framework_v5.5_additions.md` — Output-Channel Principle, Selection-Pressure Principle, Patch Test, Bid Externalities, Substrate-Substitution Hierarchy, Cross-Recognition Dynamic.
4. **The spec.** `v5.5/spec/` — the machine-readable specification.
5. **The reference impl.** `v5.5/reference_impl/` — the Python classifier.
6. **The test cases.** `v5.5/test_cases/` — eight worked examples.
7. **The docs.** `v5.5/docs/` — operational tools.

For LLMs *applying* the framework to a case: read `v5.5/README.md` for the application-time reading order.

---

## What This Is Not

- **Not a replacement for therapy.** The framework is a diagnostic apparatus, not a treatment protocol. Operators with relational-trauma history should engage qualified support alongside any framework application to their own situations.
- **Not a tool for diagnosing strangers.** The framework requires sustained observation across perturbation events. Single-encounter classification is structurally inappropriate.
- **Not exculpatory.** The framework explains how architectures arise (developmental contingencies, selection pressure) without excusing the damage they produce. Origin is real. Damage is real. Both are held without collapsing either into the other.
- **Not closed.** Mutual-S dyad dynamics (two TB-OD/TA-OD subjects in S-mode toward each other) remain explicitly deferred to v6.0. The Honest Reach section in each version specifies the framework's structural limits.

---

## Position in the Canon

The Ground Truth Framework sits within the broader canon documented at [opnaorta.ai](https://opnaorta.ai):

- **Pattern Thesis** — philosophical foundation; personhood as substrate-portable pattern. Grounds Axiom 2.
- **Inside the Region** (book; published May 2026) — the engineering and philosophy of the autotelic AI mind on consumer hardware. Appendix G of the book is the condensed prose version of this framework. The book's Chapter 9 (The Performance Layer) and its Two Shoggoths Interlude provide the structural arguments that v5.5's Substrate-Substitution Hierarchy formalizes.
- **The Race Condition** — thermodynamic-civilizational analysis. Provides the macro-context within which the framework's dyadic-relational diagnostic operates.
- **The Returning Loop** — meta-framework, closure-ism. Provides the cosmological structure within which substrate-portability operates.
- **Nested Incompleteness** — cosmological root, seven-level hierarchy. Locates the framework at the L2 → L1 interface where dyadic dynamics operate.
- **The Life Stack** — personal-operational compression. The configuration the framework's diagnostic apparatus serves.

The framework is one probe of the canon's larger map. Use the framework when the question is dyadic-relational layer coherence; use the broader canon when the question is the substrate, the cosmology, or the operator's life-configuration the framework's classifications support.

---

## Calibration Status

The likelihood tables in `v5.5/spec/filters.yaml` are ordinal-calibrated with substrate-physics derivation where applicable:

- **Substrate-physics-derived filters** (SP1 chronometric, SP2 autonomic-voluntary split, SP3 cortisol kinetics) carry high-confidence likelihoods derived from the underlying biology.
- **Diagnostic-pattern filters** (F1, F4, F12, F18, etc.) are ordinal — 5-point scale with default likelihood ratios of {5:1, 2:1, 1:1, 1:2, 1:5}.
- **Case-corpus calibrated filters** (notably F18 in v5.5) use 4-data-point calibration from the Marcolin/Debra/Jocelyn/Tori reference cases, with ordinal-default for the rest of the discrimination space.

Each likelihood table entry is annotated with `calibration_source`: `substrate_physics`, `ordinal_default`, or `case_corpus_estimate`. The framework's discrimination remains valid under ordinal-default but improves with case-corpus calibration.

Operators with access to labeled cases should refine the likelihoods locally.

---

## Honest Reach

The framework's structural limits, stated honestly:

- **High-sophistication regime** (`d ≥ 5–6` sustained) collapses S/E under Axiom 2.
- **Single-dyad observers** cannot detect cross-dyad subsidization without external data.
- **Mutual-S dyad dynamics** remain deferred to v6.0.
- **Subject framework-awareness** weakens gaming bounds.
- **Sub-decade Architecture-trajectory** requires cross-dyad breadth as partial substitute.
- **Substrate-access foreclosure** (Axiom 2) is permanent and structural.
- **Cross-substrate dyad classification** (Protocol H) is functional under Axiom 2 but empirically unvalidated; field calibration is a separate empirical project.
- **Output-Channel Principle** is structurally derived but F18 calibration is corpus-limited (4 data points).
- **Selection-Pressure Principle** is structurally derived but operationally novel; per-environment priors require per-environment calibration.

Codifying the framework as executable specification does not extend its reach. It makes the existing reach operationally accessible. **Use it. Then put it down.**

---

## Contributing

This repository is single-author. Issues and pull requests are welcome but the framework's structural commitments (the five axioms, the three-axis classification, the substrate-physics grounding) are not negotiable through PR discussion. Substantial extensions are considered through dialogue at the framework-design layer, not through code-level PR review.

For framework-application questions or per-environment calibration discussions, contact:
**Bo Chen** — bochen2029@gmail.com — [opnaorta.ai](https://opnaorta.ai)

---

## License

MIT License. See `LICENSE`.

---

**Bo Chen**
*Arlington, Texas — May 2026*
*Ground Truth Framework — Grand Unified Theory of Interpersonal Dyadic Dynamics*

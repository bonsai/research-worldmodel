# Research Lab Protocol

## 1. Unit of research

Every research item is a chain:

`Question → Hypothesis → Method → Observation → Evidence → Evaluation → Claim update`

A result is not considered complete when code runs. It is complete when the observation has been evaluated against the hypothesis.

## 2. Thesis / antithesis

Every active thesis must have at least one explicit antithesis or falsification condition.

The lab must search for evidence that would weaken the thesis, not only evidence that supports it.

## 3. World Model mapping

For each system, record:

- **World scope** — what part of reality/system is modeled.
- **Interface** — how observations/actions enter or leave the system.
- **Cognition** — what distinctions, representations, inference, or decision processes are performed.
- **Data** — what is measured, recorded, encoded, or learned from.
- **Symbolic** — what signs, language, predicates, formulas, code, or explicit semantics are used.
- **Dynamics** — what changes are predicted or simulated.
- **Action** — whether and how an agent acts on the modeled system.
- **View boundary** — what the model excludes.

## 4. Failure categories

Use these labels when the ontology does not fit cleanly:

- `missing-layer`
- `cross-layer`
- `ambiguous-boundary`
- `wrong-order`
- `world-vs-model-confusion`
- `action-without-explicit-interface`
- `symbolic-without-cognition`
- `data-without-observation`
- `other`

A failure is evidence about the ontology itself.

## 5. Reproducibility

An experiment should specify:

- input corpus/version
- model/system version
- mapping rules
- procedure
- expected observation
- falsification condition
- output artifacts
- evaluation criteria

## 6. Research state

The lab publishes structured state so `bonsai/research-agent` can discover gaps and generate the next Work.

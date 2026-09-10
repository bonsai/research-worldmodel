# research-worldmodel

A research laboratory for testing a **View-Based World Model** against existing World Model research.

## Research question

Can existing World Models be understood as **models/views of a world**, while the distinction

`Physical → Interface → Cognition → Data → Symbolic`

provides a useful cross-paradigm ontology?

## Lab loop

`Question → Thesis → Antithesis → Corpus → Experiment → Evidence → Evaluation → Thesis revision → Next Question`

The lab is deliberately falsification-oriented. A counterexample is a successful research result.

## Repository structure

```text
questions/       research questions and hypotheses
corpus/          papers, models, datasets, systems
experiments/     experiment protocols and results
evidence/        normalized evidence records
theses/          current claims and revisions
ontology/        lab-specific schemas and mappings
lab/             reproducibility and experiment conventions
```

## Relationship to bonsai research system

- `bonsai/world` — canonical World / View ontology.
- `bonsai/research-agent` — autonomous research-state reasoning and Work generation.
- `bonsai/think` — reusable reasoning methods.
- `research-worldmodel` — empirical research, comparison, experiments, and evidence.

## First experiment

Map representative World Model families to the five-layer ontology and explicitly record:

1. direct mappings,
2. ambiguous mappings,
3. missing concepts,
4. counterexamples,
5. explanatory value gained or lost.

Current literature already shows that the World Model field is fragmented across internal representation, future prediction, generative simulation, embodied systems, and action-coupled models. citeturn0academia25turn0search4

The lab therefore tests whether a view-oriented ontology can unify comparisons without pretending that all World Models are the same kind of system.

## Status

Research lab scaffold initialized. See [Issue #1](https://github.com/bonsai/research-worldmodel/issues/1) for the ADR.

# EXP-001 Next Verification

## Objective

Determine whether the View-Based World Model ontology adds explanatory information beyond established World Model taxonomies.

## Competing descriptions

### Baseline A — native taxonomy

Describe each system using its own/native terminology and established axes such as functionality, temporal modeling, spatial representation, observation, latent state, dynamics and action.

### Candidate B — View ontology

Describe each system using:

`Physical → Interface → Cognition → Data → Symbolic`

plus `Dynamics`, `Action`, and `View Boundary`.

## Test unit

For each corpus system, record:

- distinction present in both A and B
- distinction newly exposed by B
- distinction lost by B
- ambiguity introduced by B
- contradiction between B and native terminology
- whether the distinction changes an architectural or epistemic interpretation

## Scoring

Each candidate distinction receives:

- `0` = no additional information
- `1` = clearer terminology only
- `2` = exposes a meaningful boundary
- `3` = changes comparison/classification
- `4` = enables a new research question or interoperability relation

Penalty:

- `-1` = ontology introduces avoidable ambiguity
- `-2` = ontology contradicts source architecture without justification

## Counterexample criteria

The hypothesis is weakened if at least one of the following is demonstrated:

1. all five layers map one-to-one to existing categories without additional explanatory content;
2. layer order produces no stable distinction across systems;
3. the World/Model boundary cannot be represented consistently;
4. Cognition cannot be separated from representation without arbitrary interpretation;
5. Symbolic is merely a data encoding detail in every relevant case;
6. the ontology produces more ambiguity than explanatory gain.

## Deliverable

`experiments/EXP-001/comparison-matrix.yaml`

The matrix must distinguish source fact, ontology interpretation, evaluation score, and counterexample status.

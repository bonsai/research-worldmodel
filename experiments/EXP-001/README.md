# EXP-001 — Cross-Family View Mapping

## Goal

Test whether the View-Based World Model ontology can represent heterogeneous World Model families without erasing important differences.

## Input families

1. Dreamer / model-based reinforcement learning
2. JEPA / V-JEPA
3. Generative video / interactive environment models
4. Embodied world models
5. Structured environment/simulation representations

## Procedure

For each selected system:

1. identify the modeled world/system;
2. identify observations and interfaces;
3. identify learned or explicit cognitive representations;
4. identify data and training/measurement processes;
5. identify symbolic structures, if any;
6. identify predicted dynamics and action coupling;
7. define the view boundary;
8. record ambiguities and ontology failures;
9. compare with the system's native terminology;
10. evaluate whether the five-layer ontology adds information.

## Output

- `matrix.yaml` — normalized mapping
- `observations.md` — observations and interpretation separated
- `counterexamples.md` — cases that resist the ontology
- `result.md` — evaluation and thesis impact

## Success criterion

Success does **not** mean every system fits. The experiment succeeds if it can clearly show where the ontology explains, where it fails, and whether those failures produce useful next research questions.

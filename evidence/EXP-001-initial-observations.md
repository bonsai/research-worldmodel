# EXP-001 Initial Observations

Date: 2026-09-10
Status: observed

## Research question

RQ-001: Does a View-Based Ontology Explain Existing World Models?

## Procedure

Five World Model families were normalized using the EXP-001 protocol:

1. DreamerV3 — model-based reinforcement learning
2. V-JEPA — latent predictive video representation
3. V-JEPA 2 — latent predictive embodied world model
4. Genie — generative interactive environment
5. Embodied World Models survey — embodied-AI taxonomy

The mapping was performed only after recording source terminology. Ontology mappings are interpretations and are not attributed to the original authors.

## Observations

### O-001 — Physical is usually implicit

All five families refer to an environment, visual world, or physical/embodied environment, but the boundary between the external world and the learned model is not uniformly formalized.

### O-002 — Interface is explicit in embodied and action-conditioned systems

DreamerV3, V-JEPA 2 and embodied-world-model formulations expose observation/action channels. V-JEPA is primarily observational. Genie exposes conditioning and latent-action interaction. This suggests Interface can distinguish passive observation from active interaction without requiring a single model architecture.

### O-003 — Cognition is not a native category

Latent representations, prediction, planning and decision making can be mapped to Cognition, but the source literature generally uses representation/function terminology rather than an explicit cognition layer. This is therefore a cross-literature interpretation, not source terminology.

### O-004 — Data is operationally explicit

All systems rely on videos, trajectories, sensory inputs or experience data. Data is therefore readily identifiable as recorded/processed material, while its relationship to observation differs across systems.

### O-005 — Symbolic is not universal

DreamerV3, V-JEPA and the embodied-world-model survey do not require a symbolic layer in their core world-model formulation. Genie includes text as a conditioning modality, but this does not establish that symbolic representation is constitutive of its internal world model. V-JEPA 2 includes language alignment in downstream capabilities, again without establishing symbolic representation as a core world-model layer.

### O-006 — World/model boundary becomes most visible in Genie

Genie explicitly generates interactive environments from learned video dynamics. This makes the distinction between source world, observed data, learned model, and generated environment especially useful for the View-Based hypothesis.

### O-007 — Current evidence does not yet establish explanatory superiority

The mappings are possible, but this first pass does not yet demonstrate that the five-layer ontology explains the systems better than existing taxonomies. Comparative scoring and counterexample analysis are still required.

## Evidence status

These are **observations derived from source descriptions**. They become research Evidence only after provenance, interpretation, and evaluation criteria are recorded and the observation is judged relevant to a specific claim.

## Next verification

1. Compare each mapping against the native taxonomy/architecture of the source.
2. Identify cases where the five-layer order changes a classification or exposes a hidden boundary.
3. Search for counterexamples where the proposed order fails or creates ambiguity.
4. Score explanatory value against the falsification conditions in `theses/current.md`.

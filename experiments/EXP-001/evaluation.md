# EXP-001 Evaluation — First Pass

Date: 2026-09-10
Status: provisional

## RQ

RQ-001: Does a View-Based Ontology Explain Existing World Models?

## Evaluation target

The test is not whether every World Model can be forced into five layers. The test is whether the layers expose distinctions that are otherwise implicit, while preserving the source model's native terminology.

## Findings

### 1. Comparative coverage

The five layers can be assigned to all five corpus families at least partially. However, `cognition` is usually an interpretive mapping rather than a native category, and `symbolic` is often absent.

**Result:** coverage is possible, but not uniformly native.

### 2. Boundary detection

The ontology makes two boundaries particularly visible:

- observation/interface versus internal representation/cognition
- source world versus learned/generated model

Genie is the strongest case because its generated interactive environment is itself a learned model/view rather than the physical world. citeturn0academia1

### 3. Embodiment

Embodied World Model literature explicitly connects perception, action, prediction and decision making. This supports treating Interface as more than an input/output implementation detail when comparing passive predictive models with action-coupled models. citeturn0academia0

### 4. Existing taxonomy remains strong

The embodied-AI survey already provides useful functional, temporal and spatial axes. Therefore the proposed five-layer ontology cannot claim to replace existing World Model taxonomies. Its potential value is orthogonal: it describes *where a representation sits in the relation between world, interface, cognition, data and symbolic representation*. citeturn0academia0

### 5. Main counterargument

A critic can argue that `interface`, `cognition`, `data`, and `symbolic` are simply alternative names for observation space, latent representation, training data and language/metadata. If that is consistently true, the ontology adds little.

This counterargument is not resolved by the first pass.

## Provisional conclusion

**H1 is partially supported, but not established.**

The ontology appears to reveal boundary questions that are not central axes in common World Model taxonomies, especially the distinction between world, observation interface, internal representation and generated model. However, the current evidence does not demonstrate measurable superiority in explanatory power.

## Required next verification

1. Construct explicit competing descriptions using a conventional taxonomy and the five-layer ontology.
2. Identify classification disagreements.
3. Test whether disagreements correspond to meaningful architectural or epistemic differences.
4. Search for counterexamples where the five layers collapse without useful distinction.
5. Score explanatory gain, ambiguity, and interoperability separately.

## Evidence status

This evaluation is a provisional interpretation of source-derived observations. It should not be treated as final evidence until the comparative and counterexample tests are completed.

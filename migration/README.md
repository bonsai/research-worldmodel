# World-model repository organization

## Decision

`bonsai/world` is the canonical decision layer. It contains only concepts and definitions that have been accepted as current decisions.

`bonsai/research-worldmodel` is the research layer. It contains historical models, competing ontologies, experiments, evidence, datasets, quizzes, and rejected or unresolved alternatives.

## Absorbed now

### `bonsai/world-ontology`

Absorbed into `ontology/legacy/` as research material.

- `ontology/world.schema.json` → `ontology/legacy/world.schema.json`
- The original repository remains available as historical provenance.

### `bonsai/world-model2`

Absorbed the first WorldModel DSL quiz corpus.

- `wiki/make-quiz/quiz.schema.v1.json` → `ontology/legacy/quiz.schema.v1.json`
- `wiki/make-quiz/questions.json` → `datasets/quizzes/worldmodel-dsl/questions.json`
- `wiki/make-quiz/answers.json` → `datasets/quizzes/worldmodel-dsl/answers.json`

The quiz corpus is evidence/training material, not a canonical ontology.

## Candidate sources to review

| Repository | Role | Treatment |
|---|---|---|
| `bonsai/world` | accepted ontology / decisions | canonical, do not absorb into research |
| `bonsai/research-worldmodel` | research lab | canonical research home |
| `bonsai/world-ontology` | older ontology + schema + runtime mappings | absorb selected artifacts; preserve provenance |
| `bonsai/world-model2` | DSL, philosophy, SDK, quizzes | absorb datasets/specs selectively |
| `bonsai/world-model` | older world-model implementation | inspect before migration |
| `bonsai/world-model-form` | definitions / conceptual model | inspect and migrate useful definitions |
| `bonsai/world-model-v3` | experimental world-model | inspect before migration |
| `bonsai/worldmodel-pm` | private PM/work material | inspect only if needed |
| `bonsai/nazo-world` | world/riddle data + ontology-like structures | treat as dataset/experiment candidate |
| `bonsai/quizplatform2` | quiz runtime / cross-world quiz research | keep as implementation candidate; migrate datasets only when useful |

## Rule for future migration

1. Copy or reference the historical artifact into `research-worldmodel`.
2. Record its source repository and source revision.
3. Compare it against the current thesis/ontology.
4. Keep contradictions as research evidence.
5. Only accepted conclusions are promoted to `bonsai/world`.

This prevents historical experiments from silently becoming current ontology.

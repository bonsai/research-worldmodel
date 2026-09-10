# Research Plan — View-Based World Model

## 0. Principle

**研究計画が研究資産の中心である。**

論文、コード、データ、実験、Issueは研究計画を実行するための手段であり、研究計画から外れた資産は原則として研究資産として採用しない。

The lab is therefore organized as:

`Research Plan → Research Question → Thesis/Antithesis → Gap → AW Work → Evidence → Evaluation → Thesis Revision → Next Question`

## 1. Purpose

既存の World Model 研究を横断的に比較し、View-Based World Model の有効性・限界・反証条件を明らかにする。

対象となる仮説は、世界そのものと世界についてのモデルを区別し、

`Physical → Interface → Cognition → Data → Symbolic`

という依存・生成順序を、異なる World Model を比較する共通座標として利用できるか、である。

## 2. Research Questions

### RQ1 — Comparative representation

異なる World Model を同じ View ontology で記述できるか。

### RQ2 — Dependency order

`Physical → Interface → Cognition → Data → Symbolic` は既存研究に対して新しい説明力を持つか。

### RQ3 — View boundary

World Model が「世界」ではなく「世界のあるView/model」であることを明示すると、何が説明可能になるか。

### RQ4 — Failure

どの World Model がこの ontology に適合せず、なぜ適合しないのか。

### RQ5 — Utility

View-Based ontology は比較、説明、再利用、相互運用、研究課題発見のいずれに実用的な価値を持つか。

## 3. Core Thesis

> Existing World Models can be treated as views/models over a world, and an explicit Physical → Interface → Cognition → Data → Symbolic dependency structure may provide a useful cross-paradigm coordinate system.

**Status:** unverified

## 4. Antithesis

> Existing World Model taxonomies already provide sufficient explanatory structure, so the five-layer ontology adds little or no research value.

## 5. Falsification

以下のいずれかが確認された場合、テーゼを弱める・分割する・棄却する。

- 既存 taxonomy と完全に同値で追加説明力がない。
- 重要な World Model の差異を識別できない。
- View boundary が一貫して定義できない。
- 五層の順序が事例によって頻繁に逆転し、依存関係として成立しない。
- ontology が説明よりもambiguityを増加させる。
- 比較・説明・再利用・相互運用・gap discovery の改善が観測できない。

## 6. Research Phases

### Phase 1 — Literature Corpus

既存 World Model を一次資料中心に収集し、原文の定義を保存する。

**Asset:** corpus records

### Phase 2 — Native Model Description

Ontologyへのマッピングを行う前に、各研究の native terminology、architecture、input、output、training、evaluation、limitations を記録する。

**Asset:** normalized model records

### Phase 3 — View Mapping

各モデルを Physical / Interface / Cognition / Data / Symbolic の観点から記述する。

**Asset:** mapping matrix

### Phase 4 — Counterexample Search

適合する事例だけでなく、ontologyを壊す事例を積極的に探索する。

**Asset:** counterexamples

### Phase 5 — Comparative Evaluation

native taxonomy と View-Based ontology を比較する。

**Asset:** evaluation

### Phase 6 — Thesis Revision

Evidenceに基づいて thesis を strengthen / qualify / split / reject する。

**Asset:** dated thesis revision

### Phase 7 — Autonomous Continuation

revisionから新しい gap を生成し、research-agent → AWへ渡す。

**Asset:** next research question / executable Work

## 7. AW Execution Contract

研究計画の各PhaseはAW上では Work として扱う。

```text
Research Plan
  ↓
Research Gap
  ↓
Work
  ↓
Job
  ↓
Task
  ↓
Action
  ↓
Outcome
  ↓
Evidence
  ↓
Research Asset
```

**完了条件はAction成功ではなく、研究計画上のOutcomeがEvidenceによって評価可能になったこと。**

## 8. Research Asset Rule

すべての資産は以下を持つ。

- stable ID
- research plan reference
- research question / gap reference
- provenance
- producing Work / Job
- evidence status
- interpretation status
- reuse relationship

## 9. Evidence Discipline

必ず分離する。

```text
Observation ≠ Interpretation ≠ Hypothesis ≠ Conclusion
```

また、

```text
Evidence → supports / refutes / qualifies / neutral
```

を明示する。

## 10. Expected Outcome

最終成果は「World Modelについての説明文」ではない。

以下の研究資産群を残す。

1. World Model corpus
2. normalized model descriptions
3. View mapping matrix
4. ontology failure/counterexample database
5. comparative evaluation
6. reproducible experiments
7. thesis history
8. unresolved research gaps
9. AW-executable research Work definitions
10. machine-readable research state

## 11. Success Condition

研究計画が人間の一回限りの計画書で終わらず、

`Plan → Work → Evidence → Knowledge → Next Work`

として循環すること。

その時点で研究ラボは、**研究を記録する場所ではなく、研究資産を継続的に生産するWork system**になる。

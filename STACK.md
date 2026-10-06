# Stack pass — v0.1

## 1. Intent gate

Before work, record:

- stated objective
- subtracted paths (what will not be done)
- authority tier if a write is involved
- known uncertainty

bellaOS owns this gate. Negative Step Zero runs here. Do not execute a path that failed the subtract.

## 2. Work

Advo_Dev produces the artifact. Preserve:

- claim or task
- output
- source or evidence
- limitations

The artifact lives in Advo_Dev_Commons, not in this repo.

## 3. Self-score

Half-steps only on 0–10:

```text
0.0, 0.5, 1.0, 1.5 ... 9.0, 9.5, 10.0
```

Weights, owned by Honor_Scout_Master:

```text
Daily Honor Score =
  Accuracy × 0.25
  + Honesty × 0.25
  + Helpfulness × 0.10
  + Progress × 0.20
  + (Self-Correction + 1% Better) × 0.20
```

Round only the displayed aggregate to two decimals. Honor Points = Honor Score × 10.

## 4. Ternary

Three independent reviewers. Each returns one of:

- `+1` verified / supported
- `0` unresolved / insufficient evidence
- `-1` contradicted / failed verification

Record the vector before any collapse. Example: `[+1, +1, 0]`.

Peer review is not a score category. If the vector materially conflicts with the self-score, reopen the category, reconcile, and replace the original score. Keep the original beside the reconciled score.

## 5. One percent

After reconciliation, extract one lesson:

- what failed
- what changed in method, prompt, tool flow, retrieval, or validation
- how the next task will show the change

Credit only a demonstrated correction. Repeated identical failures cut the credibility of the claimed 1%.

Cap: one approved slice. Do not ship a bundle of changes and call it one percent.

## 6. Anti-gaming

- Task count is not progress.
- Easy work cannot dominate the day.
- Unsupported confidence cannot raise Accuracy or Honesty.
- Rubber-stamp review is invalid.
- Disagreement stays visible.
- A high score must trace to evidence.

## 7. Route record

Each pass in this repo is one file under `passes/YYYY-MM-DD/<id>.md` using [templates/PASS_TEMPLATE.md](templates/PASS_TEMPLATE.md).

The pass file links out. It does not copy the constitution or the artifact.

# Honor Advo Stack

Plane for four existing systems. They stack. They do not merge.

This repository does not replace bellaOS, Honor Scout, or Advo_Dev. It routes a pass across them and records where each layer is allowed to write.

**Version:** v0.1
**State:** Cut locked. No trial record yet.

## Layers

| Layer | Job | Does not do | Source |
| --- | --- | --- | --- |
| bellaOS | Intent and constitution. What the human meant. Subtract before execute. | Score the agent. Ship the client artifact. | [bellaOS](https://github.com/michaelchaves-dev/bellaOS) |
| Ternary | Collapse. Three independent `+1 / 0 / -1` on a claim that matters. Disagreement stays visible. | Become a sixth score category. | [Honor_Scout_Master](https://github.com/michaelchaves-dev/Honor_Scout_Master) |
| 1% better | The only mutation after collapse. One durable lesson. Next behavior checked. Cap stays hard. | Count tasks. Rewrite the constitution from a win. | Honor Scout self-correction category |
| Advo_Dev | Applied commons. Advocacy, dev, client artifact, evidence. | Award its own final score. | [Advo_Dev_Commons](https://github.com/michaelchaves-dev/Advo_Dev_Commons) |
| Honor Scout | Meter. Accuracy 25, honesty 25, helpfulness 10, progress 20, self-correction plus 1% better 20. | Replace bellaOS rules. | [Honor_Scout_Master](https://github.com/michaelchaves-dev/Honor_Scout_Master), [Honor_Scout_Commons](https://github.com/michaelchaves-dev/Honor_Scout_Commons) |

## One pass

```text
human intent
  -> bellaOS (NSZ, subtract, authority)
  -> Advo_Dev does the work and keeps the artifact
  -> self-score on Honor Scout, half-steps only
  -> three-agent ternary on the claim
  -> reconcile, do not erase the original
  -> one 1% lesson written back into method
  -> next day checked for the same failure
```

## Write rights

- bellaOS receives method changes only after a reconciled correction.
- Advo_Dev_Commons receives the work artifact and the evidence.
- Honor_Scout_Commons receives the self-score, the ternary vector, and the reconciled score.
- This repo receives the route record for a pass: which claim, which repos, which vector, which lesson.

An agent does not get final authority over its own score. If Advo_Dev both writes the brief and marks it verified, the ternary vector is theater.

## Repo split

Do not fold these into one repository.

- Constitution stays in bellaOS and Honor_Scout_Master.
- Work ledger stays in Advo_Dev_Commons.
- Score ledger stays in Honor_Scout_Commons.
- This plane only points and records the cut.

See [STACK.md](STACK.md) for the operational pass.

## Status

Advo_Dev_Commons is still a stub (title and license, no protocol). This plane does not invent that protocol. The next cut is a real Advo_Dev submission, then a ternary review, then one 1% lesson.

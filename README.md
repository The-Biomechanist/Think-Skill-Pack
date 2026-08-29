# Think Skill Pack

Four focused reasoning-control skills for changing the right part of a problem state: expanding possibilities, explaining failures, choosing a path, and updating a prior model from evidence.

The pack is deliberately decomposed. The skills are not interchangeable modes of “thinking”; each owns a different transition and hands off when another operator becomes the correct one.

## Skills

| Skill | Use it when | It should produce |
| --- | --- | --- |
| [`think-ideate.skill`](./think-ideate.skill) | Materially different approaches, mechanisms, architectures, or hypotheses are still missing from the live option space. | A small set of genuinely different candidates plus the consequence that would distinguish them. |
| [`think-diagnose.skill`](./think-diagnose.skill) | An observed mismatch, failure, regression, incident, or unexpected outcome needs causal explanation. | The earliest supported causal divergence, live alternatives, and bounded closure or an explicit unresolved state. |
| [`think-navigate.skill`](./think-navigate.skill) | Viable paths already exist and the task is to choose what to do next under constraints, tradeoffs, timing, authority, risk, or uncertainty. | One best-fit next action, or the exact blocker that prevents a defensible commitment. |
| [`think-recalibrate.skill`](./think-recalibrate.skill) | A prior model, expectation, diagnosis, assumption, interpretation, or reusable policy exists and new witnessed or authoritative evidence bears on whether it should change. | A scoped update—or an explicit decision to preserve the prior object—grounded in the new evidence. |

## Routing

A compact way to distinguish the four:

```text
Are important possibilities missing?
  -> Think-Ideate

Is there an observed mismatch whose cause is still live?
  -> Think-Diagnose

Are the options/model sufficiently settled and a next action must be chosen?
  -> Think-Navigate

Does new evidence bear on a prior model, expectation, interpretation, or policy?
  -> Think-Recalibrate
```

Some problems legitimately move through several skills in sequence. A failure may first require **Diagnose**, then **Navigate** once the causal question is settled. A design problem may use **Ideate** to create materially different candidates and then **Navigate** to choose among them. New observed evidence may later trigger **Recalibrate**.

## Boundary discipline

The distinctions matter:

- **Ideate does not choose among ordinary tradeoffs.** Its job is to change the possibility space.
- **Diagnose does not treat an expectation as proof of failure.** It starts from an observable mismatch and separates evidence from inference.
- **Navigate does not invent a new design space when the missing work is genuine ideation.** It selects among live paths using only distinctions that can change the action.
- **Recalibrate requires both a prior object and new evidence.** Generic self-critique or “thinking again” is not recalibration.

## Shared operating principles

The four skills share a few constraints without collapsing into one meta-skill:

- establish the actual objective, state, constraints, and authority before acting;
- preserve materially different alternatives until evidence distinguishes them;
- ask for or acquire only facts whose answers could change the continuation;
- keep hard constraints hard unless their owner changes them;
- bind claims to witnessed evidence rather than narrative confidence;
- stop when the operator’s own transition is complete and hand off rather than absorbing downstream work.

## Using the pack

Each root-level `.skill` file is a self-contained packaged skill. Download the operator you need and import it into a compatible skills runtime; the packages can be used independently.

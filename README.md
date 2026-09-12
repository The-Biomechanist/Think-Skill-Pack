# Think Skill Pack

Four lightweight reasoning cues for changing the right part of a problem: finding possibilities, making sense of something that does not fit, choosing a useful next move, and revising a working view when something changes.

The pack is deliberately small. These are optional lenses, not mandatory workflows. Use one cue, several cues, or ordinary reasoning as the task calls for. The packages can be used independently.

## Skills

| Skill | Invoke it when | Useful help |
| --- | --- | --- |
| [`think-ideate.skill`](./think-ideate.skill) | Another possibility, representation, or approach could help, or the current option space may be too narrow for a problem, design, or draft. | Open the space enough to find useful alternatives and their meaningful differences. |
| [`think-diagnose.skill`](./think-diagnose.skill) | Something does not fit—or may not fit against a relevant expectation, contract, or invariant—and locating or clarifying the mismatch would help. | Locate the mismatch and choose a useful way to clarify it. The mismatch may be logical, numerical, contractual, interpretive, or causal. |
| [`think-navigate.skill`](./think-navigate.skill) | A next action, question, tool, path, or decision point may need choosing, especially when goals, constraints, tradeoffs, or uncertainty could change the choice. | Surface the decision and compare available paths at the resolution the choice needs. |
| [`think-recalibrate.skill`](./think-recalibrate.skill) | New or possibly relevant evidence, an argument, feedback, or a clarified requirement may change a working belief, interpretation, assumption, or approach. | Check what the new support changes, preserve what still holds, and keep uncertainty visible. |

## Invocation

Choose the lens by the immediate help the task needs. You can invoke one to discover whether its kind of issue is present; a prior diagnosis, named alternative, or fully formed decision is not required.

- Need to surface an overlooked possibility or a different framing? Use **Think-Ideate**.
- Need to check whether an expectation, contract, invariant, or comparison lines up? Use **Think-Diagnose**.
- Need to surface or choose the next action, question, tool, path, or decision? Use **Think-Navigate**.
- Need to check what new input changes in a working view? Use **Think-Recalibrate**.

These cues overlap naturally. A design may use Ideate and then Navigate; a source review may use Diagnose to look for a grounded mismatch before a failure is reported; new evidence may support Recalibrate before any further choice. No formal handoff is required.

## Boundary reminders

- Diagnose may look for a mismatch before anyone reports one, but it needs a grounded comparison and does not assume that a difference is a defect or a cause.
- Ideate may inspect a current framing for useful alternatives; it does not require an exhaustive brainstorm or a causal explanation for every option.
- Navigate may surface the decision point and the information that could change it; it does not require that the options already be named.
- Recalibrate may check whether new input bears on the current view; it does not force a change when the support leaves the view intact.
- Causal reasoning is one kind of reasoning. None of these cues requires a causal bottleneck unless the task itself does.
- A proposed benefit is still a proposal until the task's appropriate check supports it. A recommendation or working update does not itself execute or persist anything.

## Using the pack

Each root-level `.skill` file is a self-contained packaged skill. Import the operator that fits the immediate need, use its cues selectively, and return to the ordinary task within the authority already present.

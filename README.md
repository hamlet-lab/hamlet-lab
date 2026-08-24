# Hamlet Lab / AIOE

Researching AI systems that do more than generate plausible text — especially **semantic trust before execution, falsifiable evidence-seeking behavior, and stateful/governed AI system architecture**.

## Public work

### [AiNIR](https://github.com/hamlet-lab/AiNIR)

**Semantic trust boundaries for AI-generated program behavior.**

AiNIR treats model output as a claim, not a fact. It checks bounded workflow semantics before lowering, host handoff, or execution while leaving real execution authority with the host.

Current public line: **v1.0 RC candidate public demo**.

### [Falsifiable Lifting](https://github.com/hamlet-lab/falsifiable-lifting)

**Testing whether agents know when their observation space is incomplete.**

The research asks whether an agent can keep compatible hidden explanations alive, choose a reality-contact observation that distinguishes them, update from evidence, and know when to stop or ask for more.

### [SEA Ops Arena](https://github.com/hamlet-lab/sea-ops-arena)

**A public benchmark for execution authority around AI output.**

The arena compares what changes when model text acts directly versus when the same output remains a candidate behind state, evidence, and policy gates. It is a benchmark/evidence surface, not a production plant-safety or certification claim.

## Research posture

A recurring theme across the public work is separation of concerns:

```text
proposal != fact
reasoning != authority
evidence != truth
verification != execution
operational commitment != permanent epistemic closure
```

Additional architecture, learning, memory, perception, control, and product research remains private until an explicit publication or release review determines an appropriate public scope.

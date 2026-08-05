# Grill Me Plus

**An adaptive, risk-first AI interview skill for turning vague ideas into defensible decisions.**

Created by [Sepehr Bayat](https://github.com/sepehrbayat).

## What it improves

The original `grill-me` concept is powerful: interrogate an idea through a dependency-aware decision tree instead of jumping into implementation.

Grill Me Plus extends that model with:

- three interrogation depths: quick, standard, and deep;
- risk-first question ordering;
- explicit fact, assumption, decision, constraint, risk, and experiment tracking;
- contradiction detection across rounds;
- cognitive limits for each question round;
- forced real-world experiments when conversation cannot resolve uncertainty;
- success metrics and explicit kill criteria;
- a final decision record with owners and next actions;
- special attention to product, business, architecture, and vibe-coded projects.

## Installation

Copy the `SKILL.md` file into your agent's skills directory under a folder named `grill-me-plus`.

Example:

```text
skills/
└── grill-me-plus/
    └── SKILL.md
```

Then invoke it explicitly with a prompt such as:

```text
Use grill-me-plus in deep mode to stress-test my SaaS idea.
```

## Example triggers

- “Grill this product idea.”
- “Try to destroy this plan before I build it.”
- “Interrogate my architecture decisions.”
- “Find the assumptions I am ignoring.”
- “Run a deep grill on this business model.”

## Design philosophy

Good questioning is not a long checklist. It is a dependency graph.

A useful interview asks only the decisions that can be answered now, resolves contradictions before expanding, and converts unknowable claims into cheap experiments. The goal is not endless skepticism; it is a decision that survives contact with reality.

## Attribution

This project is an expanded derivative inspired by Matt Pocock's MIT-licensed [`grill-me`](https://github.com/mattpocock/skills/blob/main/skills/productivity/grill-me/SKILL.md) and [`grilling`](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md) skills.

The original copyright and MIT license notice are preserved in [`LICENSE`](./LICENSE).

## License

MIT. See [`LICENSE`](./LICENSE).

# Decision record template for Important Technical Decisions (ITDs)

This is the Important Technical Decisions (ITD) template described in
[ITDs: a lean ADR for executive technical decision-making at scale - Ignacio Larrañaga](https://ignaciolarranaga.medium.com/itds-a-lean-adr-for-executive-technical-decision-making-at-scale-e18bb3f6a563).

ITDs are a focused evolution of ADRs, optimized for speed, clarity, and
executive validation. Where an ADR documents what was decided, an ITD is a
lean, decision-first artifact that makes the decision itself reviewable, so
stakeholders can scan it quickly and challenge it easily. ITDs are well suited
to technical decisions that are not strictly architectural, such as choosing a
model, a library, or a CI/CD strategy.

In each ITD file, write these sections:

# Title

State the decision itself, not a description of the topic.
For example, "Use Qwen2.5 1.5B Instruct for on-device translation".

## The Problem

One sentence stating what we are trying to solve.

## Options Considered

The alternatives that were on the table, with the selected option in **bold**.

## Rationale

Only the decisive factors that led to the choice, not an exhaustive list of
every pro and con.

## Notes

Optional. Any additional context worth recording, such as constraints,
assumptions, or links.

---

## Tic Track — Important Technical Decisions

Pre-determined decisions (set for the project, not team-decided):
- Target device: Android
- CSS framework: Bootstrap

Team-decided ITDs:
1. [Use React Native for the development framework](0001-use-react-native-for-development-framework.md)
2. [Use Stack Navigation](0002-use-stack-navigation.md)
3. [Use no hardware features](0003-use-no-hardware-features.md)
4. [Use Local Storage](0004-use-local-storage.md)

See [ATTRIBUTION.md](ATTRIBUTION.md) for the team's division of labour on
these decisions.

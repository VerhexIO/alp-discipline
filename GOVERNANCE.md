# Governance

This file defines how the Alp Discipline text changes. It is deliberately small; the
discipline's own growth rule applies to its governance too.

## Surfaces and their change regimes

- **Core (DISCIPLINE.md and ESSENCE.md):** frozen. It reopens only on usage evidence,
  decided by the owner. A wording defect, meaning a reading that contradicts the doctrine's
  evident intent, may be fixed without usage evidence, but the fix is still recorded in
  [AMENDMENTS.md](AMENDMENTS.md).
- **APPLYING.md:** governed by its own growth rule. It holds at most 3 or 4 entries, and a
  new entry is admitted only for a question actually asked in real usage.
- **README.md, EXAMPLES.md, and repository files:** packaging. They change freely and are
  recorded in AMENDMENTS.md when the change is meaningful.

## What counts as usage evidence

Usage evidence is a concrete situation from real usage, by a human or an agent, in which the
current text gave no answer, gave a wrong answer, or was systematically misread. It names
the situation, the surface and clause involved, what the practitioner actually did, and what
the text should have said. Reasoned argument alone, however good, is not usage evidence.
Submit it with the usage evidence issue template.

## Amendment procedure

1. Evidence arrives, through an issue or through the owner's own record.
2. The owner classifies it: a wording defect, a one-off, or structural.
3. Structural evidence changes the text. The change is drafted in the source language
   (Turkish), translated to English, and both files change in the same commit.
4. The entry is recorded in AMENDMENTS.md and the version is bumped.

## Language rule

Turkish is the source language and carries authorial intent; English is the publication
canon. Semantic divergence between the two is a defect, not a fork. When one is found,
intent is read from the Turkish text, the fix is applied to both languages in one atomic
commit, and the case is recorded in AMENDMENTS.md.

## Versioning

- **Patch (1.0.x):** wording, packaging, and translation fixes.
- **Minor (1.x.0):** amendments based on usage evidence that add or change clauses.
- **Major:** doctrinal change.

Each release is tagged, and the current version is visible in the version line of
ESSENCE.md, so an agent can report which surface it runs.

## Decision authority

Alperen Sartacoglu owns the core. The discipline's own Principle 2 binds the owner too: the
owner does not grant themself an extension without a record, and AMENDMENTS.md is that
record.

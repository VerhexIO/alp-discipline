# Amendments

This file is the complete change record of the Alp Discipline text. The core (DISCIPLINE.md
and ESSENCE.md) reopens only on usage evidence, and every change, including editorial ones,
is recorded here. Each entry states what changed, why it changed (which usage, which
evidence), whether it is one-off or structural, and which surfaces it touched. The change
rule itself is stated in the README. Version numbers: the third digit marks wording and
packaging fixes, the second digit marks changes that add or alter clauses on usage evidence,
and the first digit marks doctrinal change.

A note on provenance: the repository was imported as a single squashed commit ("Alp
Discipline v1.0, initial standalone import"), so the freeze of 2026-07-18 and the first
amendment of 2026-07-22 are not separable in git history. This file is the authoritative
record of that sequence.

## v1.0 (2026-07-18): core freeze

The core was authored in Turkish, translated to English, and frozen with the owner's
approval. The root English text is the publication canon; the Turkish text carries authorial
intent.

## v1.0.1 (2026-07-22)

### 1. First amendment based on usage evidence (core, owner approved)

Added to the "Loss" definition in DISCIPLINE.md: if no goal has been declared and no measure
has been accepted, a loss cannot be verified and Principle 3 cannot fire; the first move is
to get the goal declared. Class: structural clarification driven by usage. The change
predates the git import, so it is recorded here rather than being visible as a diff.

### 2. Editorial flow revision (all surfaces, owner ordered)

Dash punctuation and fragmented sentence constructions were removed across all English and
Turkish surfaces, and sentences were rewritten as complete, flowing prose for both human and
AI readers. Hyphenated Turkish coinages (for example "tek-seferlik", "kullanım-kanıtı") were
dissolved into natural phrases. Grammatically required English hyphens (for example
"one-off", "non-goal", "load-bearing") were kept. No doctrinal content changed.

### 3. Wording defect: "only law"

"The surface an agent sees is its only law" could be misread, inside a prompt hierarchy, as
placing ESSENCE above system and safety policies. Reworded in README.md and DISCIPLINE.md:
ESSENCE is the agent's single canonical Alp Discipline surface and operates within every
higher priority constraint the agent already has. No doctrinal change; the four floors
already bound the agent.

### 4. Relicense from CC BY 4.0 to MIT (owner decision)

The discipline's primary recommended use embeds ESSENCE.md in machine-consumed prompts,
where displaying attribution is impractical. MIT removes that friction. The README
additionally states that embedding ESSENCE.md in a machine-consumed prompt requires no
attribution display.

### 5. APPLYING entry 1: the record precedes execution

One clause was added to the necessity record mechanics: the record must be written before
execution begins, because a record written afterwards documents a justification, not a
decision. This closes the falsifiability gap in the temporal split of solo ownership (audit
finding, owner approved).

### 6. Fourth worked example: an implicit boundary (journalism)

EXAMPLES.md previously proved field independence only for domains with a formally named
boundary owner. A journalism example was added in which the boundary is implicit and social
and identifying the owner is itself part of the work.

### 7. Packaging and governance scaffolding

Added AMENDMENTS.md (this file), GOVERNANCE.md, CONTRIBUTING.md, issue templates for usage
evidence and translation divergence, CITATION.cff, repository metadata, and a visible
version line in ESSENCE.md so that an agent can report which surface version it runs.

## v1.0.2 (2026-07-22): universality cleanup (packaging, owner ordered)

All references to specific tools, products, and organizations were removed from the text.
The discipline must be adaptable to any environment, so the repository names no
implementation; implementations live in separate repositories. The pending measurement note
below was likewise made generic. No doctrinal content changed.

## v1.0.3 (2026-07-23): read and apply simplification (packaging, owner ordered)

The repository's target posture is "this is a text: read it and apply it". GOVERNANCE.md,
CONTRIBUTING.md, the issue templates, and CITATION.cff were removed, and the change rule was
folded into the README in a few sentences. This file remains as the change record, because
in a doctrine repository a diff shows what changed but cannot show with which evidence and
why. No doctrinal content changed.

## v1.0.4 (2026-07-23): consistency audit fixes

A full audit of the text found and closed the following. The core changes were approved by
the owner one by one.

- The DISCIPLINE.md footers (English and Turkish) still declared v1.0.1; they now carry the
  current version (wording defect).
- The Turkish DISCIPLINE.md title carried the English article ("The Alp Discipline"); it is
  now "Alp Discipline" (translation defect, introduced in the v1.0.1 revision).
- ESSENCE question 2 in Turkish repeated the word "engel"; it now reads "Engellenen hedef
  mi, seçtiğim yaklaşım mı?" (core, owner approved; the meaning is unchanged and the English
  side was already clean).
- In English Principle 3, "then whoever set the route, stop before executing" was
  grammatically ambiguous; it now reads "then no matter who set the route" (wording defect;
  the Turkish side was already clear).
- The Turkish overriding norms sentence carried a stray semicolon after its subject
  (punctuation defect, removed).
- The README Status section now states which files are the frozen core and that the rest is
  packaging; this rule had disappeared with the removal of GOVERNANCE.md.
- The introduction of this file now defines what the version digits mean.
- ACKNOWLEDGEMENTS.md was removed and folded into the README (owner approved).
- The last tool reference in the repository (the .gitignore comment and pattern) was
  removed; the local ignore rule moved out of the repository.

## Pending, awaiting usage evidence

- An ESSENCE floor for the case where the goal is undeclared and the owner is unreachable:
  does the agent continue or come to a safe stop? To be measured in real agent usage.
- A Principle 3 antipattern for suppressing a legitimate stand by inflating Principle 2's
  burden of proof ("you have not exhausted the alternatives yet, so do not escalate").
- An APPLYING entry with a discriminator between the slice and design altitudes (proposed
  test: if an interface or contract that others depend on changes, the work is design).

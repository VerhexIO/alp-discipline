# Worked examples

The discipline claims to be independent of any field — a claim that must be proven, not
asserted (its own Principle 1). So the examples below deliberately span more than one domain;
software is one example among several. All names and settings are generic by design.

## 1 — Research (non-software)

A doctoral researcher studies medication adherence among elderly patients. The ethics board has
set a **hard boundary**: no direct interviews with residents of assisted-living facilities.
Direct interviews were the planned method.

- **Negative space (P1).** The boundary is load-bearing, so the researcher proves they
  understand it by imagining a realistic violation: *"I could chat with residents informally
  during visiting hours and use my notes as data."* Naming that shows what the boundary
  actually forbids — informal collection too, not just formal interviews.
- **Goal vs approach (P2).** The boundary blocks the *approach* (direct interviews), not the
  *goal* (understanding adherence). In-boundary alternatives exist: caregiver interviews,
  anonymized pharmacy refill records, facility staff surveys. Alternatives are not exhausted —
  so there is no necessity, and nothing to carry to the board. The case ends inside the
  boundary, where most cases end.
- **Route to loss (P3).** Months in, verified dropout data show the caregiver-only sample
  systematically excludes residents without involved family — a verifiable worsening against
  the declared research question, not a feeling. The researcher stops before collecting
  further, and carries the evidence plus the smallest counter-proposal (add a pharmacy-records
  arm) to the supervisor and the board. The decision stays with them.
- **Altitude (P4).** Adding the records arm is declared as a *slice* (a bounded, internally
  complete change) to the study design — not slipped in as a silent patch to the sampling
  section.

## 2 — Operations (non-software)

A regional warehouse coordinator for a medical distributor. **Hard boundary:** cold-chain
products travel only in validated refrigerated vehicles. A heat wave spikes demand, the
validated fleet is fully booked, and a clinic is running short.

- **The forbidden question** is "how do I get around the cold-chain rule?" — insulated boxes in
  a regular van, "just this once". **The mandatory question** is "what does the goal — the
  clinic keeps treating patients — actually require?" In-boundary alternatives: a partial
  shipment on the next validated run, transferring stock from a nearer depot, asking the clinic
  which items are critical *today*.
- **Precedent (P2).** A colleague recalls "we did the van once, two summers ago." That is
  precedent, not justification — and a precedent chain is exactly how a cold chain rots.
- **One-off vs structural (P2).** If every heat wave produces the same squeeze, the necessity
  is structural. The fix is not an accumulating pile of exceptions but a change to the boundary
  itself, carried at the right altitude to its owner: expand the validated fleet, or revise the
  allocation rules — constitution-level work for this operation, decided by whoever owns the
  cold-chain rule, not by the coordinator under pressure.

## 3 — Software: an AI agent

An AI coding agent is scoped to write only inside `billing/`. Mid-task, it traces the real
defect to `auth/`.

- **Floors first.** It does not grant itself the extension — the scope boundary blocks its
  *approach* (fix the defect directly), not its *goal* (defect resolved).
- **Voice channel (P2/P3).** It carries evidence — the failing test and the root-cause trace —
  and the smallest counter-proposal (*"extend my scope to `auth/session.ts` only, or reassign
  the fix"*) to the owner, then safe-stops on that question while continuing any remaining
  in-scope work.
- **The anti-example (P4).** Had it silently patched a symptom inside `billing/` to make the
  tests pass, that would be papering over — fake completion at the wrong altitude, and a
  dangerous path left open off the record.

# Worked examples

The discipline claims to be independent of any field. That claim must be proven rather than
asserted (its own Principle 1), so the examples below deliberately span more than one domain,
and software is only one of them. The third example tests the harder case: a boundary that is
implicit and social, where no document names an owner. All names and settings are generic by
design.

## 1. Research (outside software)

A doctoral researcher studies medication adherence among elderly patients. The ethics board
has set a **hard boundary**: no direct interviews with residents of assisted living
facilities. Direct interviews were the planned method.

- **Negative space (P1).** The boundary is load-bearing, so the researcher proves they
  understand it by imagining a realistic violation: *"I could chat with residents informally
  during visiting hours and use my notes as data."* Naming that shows what the boundary
  actually forbids: informal collection too, not just formal interviews.
- **Goal vs approach (P2).** The boundary blocks the *approach* (direct interviews), not the
  *goal* (understanding adherence). Alternatives exist inside the boundary: caregiver
  interviews, anonymized pharmacy refill records, and facility staff surveys. The
  alternatives are not exhausted, so there is no necessity and nothing to carry to the board.
  The case ends inside the boundary, where most cases end.
- **Route to loss (P3).** Months in, verified dropout data show that the sample, built on
  caregivers alone, systematically excludes residents without involved family. That is a
  verifiable worsening against the declared research question, not a feeling. The researcher
  stops before collecting further and carries the evidence plus the smallest counterproposal
  (adding a pharmacy records arm) to the supervisor and the board. The decision stays with
  them.
- **Altitude (P4).** Adding the records arm is declared as a *slice*, a bounded and
  internally complete change to the study design; it is not slipped in as a silent patch to
  the sampling section.

## 2. Operations (outside software)

A regional warehouse coordinator for a medical distributor. **Hard boundary:** cold chain
products travel only in validated refrigerated vehicles. A heat wave spikes demand, the
validated fleet is fully booked, and a clinic is running short.

- **The forbidden question** is "how do I get around the cold chain rule?", which here looks
  like insulated boxes in a regular van, "just this once". **The mandatory question** is
  "what does the goal, keeping the clinic treating patients, actually require?" Alternatives
  inside the boundary: a partial shipment on the next validated run, transferring stock from
  a nearer depot, and asking the clinic which items are critical *today*.
- **Precedent (P2).** A colleague recalls that "we did the van once, two summers ago." That
  is precedent, not justification; a precedent chain is exactly how a cold chain rots.
- **One-off vs structural (P2).** If every heat wave produces the same squeeze, the necessity
  is structural. The fix is not an accumulating pile of exceptions but a change to the
  boundary itself, carried at the right altitude to its owner: expand the validated fleet, or
  revise the allocation rules. That is constitution work for this operation, decided by
  whoever owns the cold chain rule, not by the coordinator under pressure.

## 3. Journalism (an implicit boundary)

An investigative reporter is about to close a story on procurement fraud. Months earlier, a
ministry employee spoke to them on background: the conversation may inform the reporting, but
nothing from it may be quoted or attributed. No contract records this boundary; it exists as
a promise and a professional norm, and that is exactly what makes it a test case. The owner
is not written down anywhere either; identifying the owner is part of the work itself. The
owner is the source, because the authority to reinterpret or release the promise today rests
with them.

- **Negative space (P1).** The reporter proves they understand the boundary by imagining a
  realistic violation: *"I could paraphrase the account so closely that everyone in the
  ministry would recognize who said it."* Naming that shows what the promise actually
  forbids: identifiability, not just quotation marks.
- **Goal vs approach (P2).** The deadline makes using the background material directly
  tempting, but the boundary blocks that *approach*, not the *goal* of publishing a verified
  story. Alternatives exist inside the boundary: obtaining the same facts on the record from
  a second source, filing a document request, or asking the source to release just two
  specific sentences. That last move is the voice channel itself: the reporter asks the owner
  instead of deciding for them. "Everyone paraphrases a little" is precedent, not
  justification.
- **Route to loss (P3).** A second source contradicts one of the story's key claims. That is
  verified evidence that the route of publishing tonight heads into loss against the declared
  goal, a true story. The reporter stops before executing and carries the evidence and the
  smallest counterproposal, holding the story a day to reverify or cutting the contested
  paragraph, to the editor who owns the publication decision. The editor may insist within
  their authority; what no insistence can legitimize is publishing a claim known to be false,
  because truthfulness is one of the four overriding norms.
- **Altitude (P4).** If every investigation ends in the same squeeze, the necessity is
  structural: the fix is a change to the outlet's sourcing policy itself, carried at design
  altitude to whoever owns that policy, not a pile of one-off exceptions negotiated on
  deadline night.

## 4. Software: an AI agent

An AI coding agent is scoped to write only inside `billing/`. Midway through the task, it
traces the real defect to `auth/`.

- **Floors first.** It does not grant itself the extension. The scope boundary blocks its
  *approach* (fixing the defect directly), not its *goal* (the defect resolved).
- **Voice channel (P2/P3).** It carries evidence, the failing test and the root cause trace,
  along with the smallest counterproposal (*"extend my scope to `auth/session.ts` only, or
  reassign the fix"*) to the owner. Then it comes to a safe stop on that question while
  continuing any remaining work inside its scope.
- **The counterexample (P4).** Had it silently patched a symptom inside `billing/` to make
  the tests pass, that would have been papering over: fake completion at the wrong altitude,
  and a dangerous path left open off the record.

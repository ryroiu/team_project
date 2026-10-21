# Music Club Equipment Tracker — Specification

> **When:** Week 1 (Section 0), Week 2 (the rest), refined in Week 3
>
> **Owner:** Ryan Roberts — Product Owner
>
> **Version:** 0.1 · **Updated:** 2026-10-22
>
> **Approved on:** Pending · **by:** Ryan Roberts — Product Owner; Connor Nease — Architecture Lead; Kristiana Lulgjuraj — Delivery Lead (team approval pending)
>
> **Status:** Week 1 Constitution draft for team adoption. Later sections are explicitly scheduled below; this is not an approved build specification.
>
> **Guide:** [Specification guide](reference/specification-guide.md) · **Example:** [Course example](examples/specification-example.md)

The [Business Case](business-case.md) describes a fictional Music Club at Indiana University. Product assumptions are not user evidence. The team owns the final principles, priorities, requirements, and approvals.

## 0. Constitution

These three proposed principles implement the selected small-club equipment-tracker direction. Team adoption is pending (Q4).

| # | Principle | Why it exists / feature it would stop |
|---|-----------|--------------------------------------|
| 1 | Serve one club with only two product roles: member and equipment coordinator. Only the coordinator records checkouts and returns. | Keeps responsibility clear; stops multi-club administration, additional approval roles, and member self-checkout. |
| 2 | Track each physical item individually and allow it at most one active loan. Keep its completed loan records. | Makes availability explainable; stops overlapping loans, quantity-only inventory, and deleting loan history to make an item appear available. |
| 3 | Limit this version to equipment availability and borrowing records; exclude reservations, payments, fines, messaging, and external integrations. | Protects the nine-week scope; stops calendar booking, payment processing, automated notifications, and IU system integration. |

## 1. Problem & Evidence

**Problem and success:** ASSUMPTION: members cannot quickly establish equipment availability, and the coordinator cannot reliably identify current borrowers. Proposed targets are at least 80% of test participants finding availability within 30 seconds without help, and the coordinator correctly recording a checkout or return within 60 seconds per action. See Business Case Section 1.

**Evidence — due Week 2, updated in Week 3:** No interviews, observations, or prototype tests have been conducted or recorded. Collect 3–5 conversations or observations with real people outside the team who have relevant equipment-sharing experience; record the Week 3 prototype test separately. Never use fictional club members, example documents, or AI-generated statements as evidence.

| ID | What we heard or saw | From whom |
|----|----------------------|-----------|

Assign E1 onward only when real evidence is recorded. A participant code and relevant role can identify the source without publishing contact details.

**Riskiest assumption:** A coordinator will consistently record handoffs, and members will check the tracker before asking in chat. Test this through the Week 2 conversations and a Week 3 borrowing-workflow prototype; revise the scope if a spreadsheet better serves the users.

## 2. Scope

**Week 1 planning direction — to refine in Week 2:** Members browse equipment and its availability. A coordinator records a checkout to a member, sees current loans, and records a return. Each microphone, keyboard, amplifier, or other asset is a separate physical item.

**Out of scope:** Reservations, waitlists, payments, fines, messaging, barcode scanning, multiple clubs, and external integrations. The classroom build uses fictional sample identities and equipment records, with no real IU accounts or data.

## 3. User Scenarios

**Due Week 2 — not yet drafted or prioritized.** Write 3–5 scenarios with actor, trigger, steps, success outcome, and failure outcome. Keep P1 to 1–2 scenarios forming a complete journey. The proposed P1 candidates are finding available equipment and the coordinator's checkout-to-return journey; the team assigns priorities after reviewing evidence.

## 4. Requirements & Acceptance Tests

**Due Week 2 — not yet drafted.** Assign stable R1 onward IDs once the team writes the requirements. Each requirement must use an EARS sentence pattern and have a priority, a concrete acceptance test, and evidence or an explicit ASSUMPTION label. Include each scenario's failure outcome and measurable accessibility/privacy requirements. No implementation is authorized by this draft alone.

| ID | Requirement | Priority | Acceptance test (do → expect) | Evidence |
|----|-------------|----------|-------------------------------|----------|

## 5. Open Questions

This is the shared list for questions from any document. Update the affected document before marking a question resolved. Owners below reflect the role assignments Ryan supplied on 2026-10-22. An AI-drafted note is not evidence that an owner personally completed or approved it.

| ID | Question | Raised by | Owner | Status |
|----|----------|-----------|-------|--------|
| Q1 | Who owns each course role and document? | Week 1 setup | Ryan Roberts | Resolved 2026-10-22 — Ryan Roberts: Product Owner (Business Case, Specification); Connor Nease: Architecture Lead (Plan, Data & API Design); Kristiana Lulgjuraj: Delivery Lead (Style Guide, Tasks, Weekly Status), as supplied by Ryan |
| Q2 | What are the team members' and instructor's GitHub usernames, and have all required collaborators received and accepted invitations? | Week 1 setup | Kristiana Lulgjuraj | Open — Ryan reports team usernames unknown; instructor username also needed; public repo confirmed, collaborator access unverified |
| Q3 | Who is the sponsor, and what is their decision? | Week 1 setup | Ryan Roberts | Resolved 2026-10-22 — Ryan Roberts identified himself as sponsor; his instruction to proceed is recorded as Go in the Business Case |
| Q4 | Does the team adopt the three proposed Constitution principles, scope limits, and success targets? | Week 1 draft | Ryan Roberts | Open — team decision and dated acknowledgment pending |
| Q5 | Which 3–5 real people outside the team can discuss borrowing or managing shared equipment for Week 2? | Week 1 draft | Ryan Roberts | Open — no evidence collected |
| Q6 | What borrower information and loan dates are necessary, and who may view them? | Week 1 draft | Ryan Roberts | Open — decide in Week 2 before writing related P1 requirements |
| Q7 | Can the team support the proposed effort allowance and course-default build approach within the remaining weeks? | Week 1 draft | Connor Nease | Open — validate capacity; record build option and designed-for database in ADR-00 during Week 3 |

## SVC Self-Check

**Week 1 check:** Three principles with specific feature consequences are drafted in Section 0. Adoption is pending Q4. Sections 1–4 are planning notes or future work, not claims that Week 2 or Week 3 work is complete.

- [ ] **Simple** — each requirement is one sentence in one EARS pattern; no jargon a new teammate would not know. Requirements are due Week 2.
- [ ] **Valuable** — the Constitution has 2–3 feature-stopping principles; the Evidence table has 3+ real outside-team sources plus the prototype test; each P1 requirement cites evidence, a standard, or ASSUMPTION; the riskiest assumption is named. Evidence and prototype work are due Weeks 2–3.
- [ ] **Complete** — 3–5 complete scenarios with 1–2 P1 journeys; unique requirement IDs, priorities, and acceptance tests; no question blocks a P1 requirement; team approval. Due Weeks 2–3.

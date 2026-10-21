# Music Club Equipment Tracker — Business Case

> **Owner:** Ryan Roberts — Product Owner · **Version:** 0.1 · **Updated:** 2026-10-22
>
> **Sponsor decision:** Go · **By:** Ryan Roberts · **Date:** 2026-10-22. Ryan selected this project, instructed it to proceed, and identified himself as sponsor.
>
> **Context:** Fictional Music Club at Indiana University. Club operations below are assumptions, not interview findings or IU endorsement.

## 1. Problem

**Who is affected?** Members borrowing the fictional club's microphones, amplifiers, keyboards, and other shared equipment, and its equipment coordinator.

**What's wrong today?** ASSUMPTION: messages and a handwritten list leave members unsure what is available and the coordinator unsure who has each item.

**How will we know it worked?** Proposed targets: at least 80% of test participants identify availability within 30 seconds without help; a coordinator correctly records a checkout or return within 60 seconds per action. Compare with the current approach using fictional records; report measured results.

## 2. Proposed Solution

A small tracker gives members one place to check availability and gives the coordinator one place to record borrowers and returns. It supports one club and tracks each physical item separately.

## 3. Options Considered

| Option | Description | Pros | Cons |
|--------|-------------|------|------|
| Do nothing | Keep messages and handwritten list | No setup | Information remains scattered |
| Option A | Shared spreadsheet | Familiar; quick setup | Manual consistency and editing errors |
| **Option B — recommended** | Equipment tracker | Consistent records and availability rules | Design, testing, and upkeep effort |

## 4. Can We, and Is It Worth It?

| Question | Answer |
|----------|--------|
| **Will people actually use it?** | Unvalidated. Interview 3–5 real people outside the team with equipment-sharing experience in Week 2. |
| **Can we build it with what we have?** | Provisionally: one club, two roles, small inventory. Confirm team skills and capacity. |
| **Can it be done in time to matter?** | Target Week 6 validation and Week 8 final build; exclude reservations, payments, fines, and messaging. |
| **What does it cost?** | ASSUMPTION: $0 additional setup spending and $0/year for the classroom demonstration using existing equipment and no paid services. Allow roughly 3–5 coursework hours per teammate weekly, subject to team confirmation. Real deployment and post-course maintenance need separate estimates. |
| **What do we gain?** | Measure availability and recordkeeping time against the targets above. Clearer responsibility is expected; financial savings and reduced equipment loss are unproven. |

## 5. Recommendation

Approve Option B as a limited classroom project. Starting now allows user validation before later documents depend on the assumptions; delay reduces that testing time.

## SVC Self-Check

- [x] **Simple** — about one page; no technical stack or screens.
- [x] **Valuable** — specific users and pain; measurable targets distinguished from findings.
- [x] **Complete** — baseline, alternatives, feasibility, ongoing costs, clear recommendation, and sponsor decision included.

See the [guide](reference/business-case-guide.md), [example](examples/business-case-example.md), and [Open Questions](specification.md#5-open-questions). Team review remains pending.

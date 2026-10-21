# Music Club Equipment Tracker — project guidance

## Start each session

- Read the project overview at the top of `README.md`, the newest entry in `docs/WEEKLY-STATUS.md`, and the Open Questions in `docs/specification.md`.
- Check the working tree before editing. Preserve teammates' existing changes.
- This is a fictional Music Club at Indiana University for a System Design course. Do not imply IU affiliation, endorsement, real club operations, or real research findings.

## Team and ownership

- Ryan Roberts — Product Owner; owns `docs/business-case.md` and `docs/specification.md`; also the coursework sponsor.
- Connor Nease — Architecture Lead; owns `docs/plan.md` and `docs/data-api-design.md`.
- Kristiana Lulgjuraj — Delivery Lead; owns `docs/style-guide.md`, `docs/tasks.md`, and `docs/WEEKLY-STATUS.md`.
- GitHub collaborator access is a separate setup requirement. Read the current status rather than assuming an invitation was sent or accepted.

## Course workflow

- Follow the course schedule and rubrics in `README.md`, with templates and guides from `https://github.com/jlyst/C450-team-project-framework`.
- The six canonical project documents are directly in `docs/`. `docs/design/specification.md` is a legacy link, not a second source of requirements.
- Fix documents before dependent documents or code. Build only the authorized scope and current task; later-week templates are not completed design decisions.
- Follow `CLAUDE.md` for build behavior. The imported course skills supply implementation patterns, not product requirements.
- Preserve requirement IDs once assigned. Trace them through data/API design, plan, tasks, and acceptance tests.
- Bump an approved document's version and obtain dated re-approval when its content changes. Unapproved drafts remain drafts; Tasks has no version.
- Team members make priorities, Constitution decisions, architecture choices, and approvals. Mark proposals and pending decisions honestly; never invent a teammate's review or individual contribution.
- Evidence must come from real people outside the team. Never turn fictional personas, sample data, course examples, or AI-generated quotes into evidence.
- Use fictional names, emails, and equipment records in the public demonstration. Do not add real participant contact details to public documents.
- Update the weekly status with actual work, next steps, blockers, open questions, and AI use. Leave instructor responses for the instructor.
- Keep Week 6 validation output under `validation/` uncommitted. Do not modify the imported course skills or build app code under `docs/`.

## Scope direction

The selected product tracks one club's individual equipment items and their checkout/return records. The proposed Constitution and all current decisions live in `docs/specification.md`; consult it before adding features. Do not add reservations, payments, fines, messaging, barcode scanning, multi-club support, or integrations as incidental extras.

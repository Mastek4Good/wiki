# Simon on the Streets project wiki

This repository is the shared project wiki for the Mastek4Good work with Simon on the Streets. It captures research notes, workshop outputs, problem statements, and early product thinking for a potential replacement or improvement to parts of the current frontline case management experience.

The repo exists so new contributors can quickly understand:

- what problem the project is trying to solve
- what has already been learned from frontline/user research
- what the emerging MVP direction is
- what questions still need to be answered before implementation decisions are made

There is no application code in this repository yet. Treat it as the source of context for discovery, product definition, delivery planning, and future implementation work.

## Project context

Simon on the Streets supports people experiencing homelessness and rough sleeping. The research in this repo focuses on the practical realities of frontline outreach work: mobile working, interrupted sessions, trauma-informed support, safeguarding, risk management, referrals, reporting, and follow-up actions.

The current case management process is described as difficult to use in the field. Workers rely on workarounds such as paper notes, calendars, photos, notebooks, memory, email, and separate forms. This creates duplicated admin, data loss risk, and less time spent directly supporting people.

The main problem statement captured in the repo is:

> Frontline staff need a case management process that fits the reality of mobile, time-pressured, trauma-informed support work, because the current Inform experience makes it too difficult to capture, access and manage the right information quickly, creating unnecessary admin burden and reducing time spent with the people they support.

## Repository structure

```text
.
├── README.md
├── .github/
│   └── CODEOWNERS
└── Simon on the streets/
    └── User Research/
        ├── Mastek4Good_Research_Presentation.pdf
        ├── SotS-Problem Statements.md
        ├── Group Session 30-04-26/
        │   ├── Problem 1.md
        │   ├── Problem 2.md
        │   ├── Problem 3.md
        │   ├── Problem 4.md
        │   ├── Problem 5.md
        │   ├── Problem 6.md
        │   └── imgs/
        │       └── IMG_1274.jpg
        ├── Group Session 27-05-26/
        │   ├── Group 1 - MVP Definition.md
        │   ├── Group 2 - Data and Integration.md
        │   ├── Group 3 - Risk Management and Safeguarding.md
        │   └── Group 4 - Ways of Working.md
        └── Group Session 24-06-26/
            ├── Actions, Outcomes and Reporting.md
            ├── Mobile Wireframes.md
            └── Recording Interactions in the Field.md
```

## Recommended reading order

If you are new to the repo, start here:

1. `Simon on the streets/User Research/SotS-Problem Statements.md`

   This is the best high-level summary. It gives the main problem statement, six sub-problems, and early functional, workflow, and technical requirement signals.

2. `Simon on the streets/User Research/Group Session 27-05-26/Group 1 - MVP Definition.md`

   This describes the emerging MVP direction: a single-page, web-based client information view that works on phones, laptops, and desktops.

3. `Simon on the streets/User Research/Group Session 24-06-26/Recording Interactions in the Field.md`

   This captures the latest thinking on low-friction, mobile-first recording in the field, including incremental profile building, must-have fields, location capture, and AI-assisted or conversational input options.

4. `Simon on the streets/User Research/Group Session 24-06-26/Mobile Wireframes.md`

   This captures the latest mobile wireframe notes for homepage case access, case-record priorities, interaction history, and profile search.

5. `Simon on the streets/User Research/Group Session 24-06-26/Actions, Outcomes and Reporting.md`

   This captures the latest thinking on post-interaction capture, action and outcome recording, consent-sensitive audio or text notes, and review-before-submit workflows.

6. `Simon on the streets/User Research/Group Session 27-05-26/Group 3 - Risk Management and Safeguarding.md`

   This captures safeguarding, worker safety, client risk, records management, and the need to handle complex human situations without over-formalising frontline work.

7. `Simon on the streets/User Research/Group Session 27-05-26/Group 4 - Ways of Working.md`

   This is an early working charter for the volunteer/community project. It covers onboarding, status updates, task sizing, tooling, ownership, and collaboration behaviours.

8. `Simon on the streets/User Research/Group Session 30-04-26/Problem *.md`

   These are raw workshop notes for the six sub-problems. Read them when you need detail behind a specific problem area.

9. `Simon on the streets/User Research/Mastek4Good_Research_Presentation.pdf`

   This is the research presentation artifact. Use it alongside the Markdown notes for wider context.

## Key themes from the research

### Mobile-first frontline capture

Workers need to capture important information quickly and reliably while supporting people in the field. The current experience pushes them into informal workarounds, especially when connectivity is poor or interactions are sensitive.

### Fewer steps for common notes

Simple case notes and actions should not require many clicks, repeated fields, or unclear decisions. The notes point toward templates, free-text entry, speech-to-text, offline capture, and careful use of AI-assisted summarisation as possible options to explore.

### Easier navigation of client records

Workers need to find the right person, understand recent context, and continue a record without moving through many pages or confusing categories. Location, name, date of birth, and possibly photos were discussed as ways to help identify people, with appropriate consent and safety considerations.

### Balanced reporting

Structured data is needed for funding, accountability, and reporting, but it should not make frontline recording harder than necessary. Future reporting needs should shape the data model without overburdening the MVP workflow.

### Follow-up actions in one trusted place

Reminders, next steps, calendar integration, task dashboards, and completion tracking are recurring needs. Workers currently rely on diaries, calendars, and memory to avoid missing actions.

### Trauma-informed support planning and risk recording

Support planning, safeguarding, and risk management need to reflect real outreach practice. The notes emphasise trust, safety, context switching, incomplete information, and the risk of making clients repeat traumatic details.

## Emerging MVP direction

The strongest MVP signal in the repo is a single-page, web-based client information tool. The goal is not to replace every existing system immediately, but to prove that client information can be captured, viewed, and updated in a simpler way.

The proposed MVP should allow a worker to search for a client and open a page where they can:

- view key client information
- see previous notes
- add a new note
- record a welfare check
- see consent status
- offer and capture consent where needed
- complete standard checks from one place

The MVP is expected to be accessible from phone, laptop, and desktop. It does not need full synchronisation with existing systems at first, but it should define a data schema that can support future migration, reporting, and integration.

## Open questions

The repo intentionally preserves open questions. Current areas needing clarification include:

- What exact fields must appear on the single-page client view?
- What is the minimum safe information to capture for a welfare check?
- What information must be captured for safeguarding?
- What does digital consent need to contain?
- Is a digital signature required for the MVP?
- What data is needed for fundraising and reporting?
- Which reports matter most in the short term?
- What information must still be copied into the existing system during MVP use?
- What security, permissions, and access controls are required?
- How should offline capture and later sync work?
- Which channels, such as email, calendar, WhatsApp, voice notes, or forms, are in scope?
- Which tools will the volunteer project use for tasks, decisions, and status updates?

## How to use this repo

Use this repo as a living wiki:

- Add new research notes under `Simon on the streets/User Research/`.
- Keep workshop notes dated and grouped by session.
- Prefer Markdown for notes so they are searchable and easy to review.
- Link back to the relevant problem statement when adding new findings.
- Keep summaries concise, but preserve raw observations where they may affect product decisions.
- Avoid storing sensitive personal data, client-identifiable information, or operationally sensitive safeguarding details in this repo.

When turning research into delivery work, start by mapping new tasks back to the problem statements and MVP direction. This helps avoid solving isolated UI or technology ideas before the underlying frontline need is clear.

## Contribution workflow

1. Create a branch for your change.
2. Add or update the relevant Markdown files.
3. Keep changes focused and easy for other volunteers to pick up.
4. Open a pull request for review.
5. Request review from the code owner listed in `.github/CODEOWNERS`.

For documentation changes, include enough context in the pull request description for someone who was not in the workshop or meeting to understand why the change matters.

## File naming conventions

The current repo uses dated group-session folders and descriptive Markdown filenames. Continue that pattern where possible:

```text
Simon on the streets/User Research/Group Session DD-MM-YY/Topic Name.md
```

For new assets, place images or supporting files close to the note that references them, ideally in an `imgs/` folder for that session.

## Current state

As of the latest notes in this repo, the project is in discovery and MVP definition. The repository contains research outputs and early product direction, not an implemented product.

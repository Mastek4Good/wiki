# Workshop Session: Recording Interactions in the Field

**Date:** Wednesday 24 June 2026

Breakout 1 focused on how frontline outreach workers record interactions while they are with people in the field.

The discussion centred on the need for a low-friction, mobile-first capture tool that supports real outreach practice: time pressure, interruptions, incomplete information, trust-building over time, and the need to stay present with the person being supported.

## User Needs

Frontline outreach workers need to capture key information quickly and reliably while they are with a person, in mobile, time-pressured, and interrupted environments.

There was strong agreement that any solution must:

* Be low-friction and fast to use.
* Work on mobile first, but also on desktop.
* Allow workers to stay present with clients.

## Problem Framing

The current approach does not adequately support real-time capture. Workers therefore rely on memory, notebooks, and informal tools, which introduces risk of data loss, duplication, and delay.

The current system also enforces a one-size-fits-all data capture approach rather than allowing workers to build a record incrementally over time.

## Design Principles

### Incremental, Longitudinal Record-Building

The group discussed a shift away from single intake forms and toward ongoing profile building.

Workers need to be able to add small pieces of information over time, reflecting the reality that trust is built gradually and not all information will be available during the first interaction.

### Capture in the Moment

The solution should prioritise minimal required input during an interaction.

Workers need to be able to log information rapidly and trust that the data has been saved, reducing the need for later transcription or duplication.

### Support for Non-Caseload Individuals

Workers need to be able to capture interactions before a person has formally become a client.

This is important for safeguarding, coordination with partner organisations, and gradual record-building. A person should only transition to client status after the appropriate consent and background checks have taken place.

## Proposed Solution Direction

The group identified a responsive web application as the preferred direction.

The application should work across mobile and desktop and feed directly into the central database.

## Data Model

### Must-Have Fields

The following fields were identified as must-have fields, validated according to Anya:

* First name
* Surname
* Date of birth
* Gender
* Phone number
* Location, such as what3words
* Case notes
* Physical description

These fields support identity verification, safeguarding, and record matching.

### Could-Have Fields

The group also identified the following possible fields:

* Photograph
* Voice note

## Interaction Model

The group explored a number of possible interaction models.

### Conversational or AI-Assisted Capture

A worker could speak or type naturally, with the system extracting structured fields from the input.

### Voice Note to Structured Data

A worker could capture a voice memo and use it to generate notes or pre-populate structured fields.

### Lightweight Structured Input

The system could provide simple mobile-optimised forms with progressive disclosure, so workers are only asked for the information needed at that point.

### Messaging-Style Interface

The group also discussed a WhatsApp-like interaction model for logging interactions.

## Location Capture

The group discussed using precise location tools such as what3words, with the potential to track location patterns over time.

## Technical Considerations

The group identified several technical questions that need further exploration:

* What constitutes a unique identifier? Is date of birth enough?
* How should duplicate entries be detected and merged?
* To what extent can Salesforce support AI-assisted capture and matching?
* How should the solution balance data capture with later access and use?
* What belongs in the MVP, and what belongs in a more complete minimum marketable product?

## Risks and Considerations

The group identified the following risks and considerations:

* Client trust when recording audio, photos, or detailed notes.
* Volunteer cognitive load during interactions.
* Data quality from AI-assisted capture or rushed input.
* Fit with existing CRM limitations.

## Summary

There is a clear need for a low-friction, mobile-first capture tool that supports incremental profile building and balances structured and conversational input while integrating with backend systems.

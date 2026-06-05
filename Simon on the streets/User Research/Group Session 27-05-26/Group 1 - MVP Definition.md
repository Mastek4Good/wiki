# Workshop Session: Group 1 - MVP Definition

Group 1 focused on defining the MVP for the work we will do for Simon on the Streets.

The discussion centred on the smallest useful product we could create that would deliver a meaningful benefit to outreach workers. We explored the current as-is state, the desired to-be state, and the longer-term direction, then used that to shape an initial view of the MVP.

## Workshop Focus

The group repeatedly came back to one question: what is the least amount of work we can do that would make outreach workers feel a practical benefit?

The answer was not to replace every existing system immediately. Instead, the group felt the first product should prove that client information can be captured, viewed, and updated in a simpler way.

If the MVP can reduce the time outreach workers spend on admin, even by a small amount, that would be a meaningful first success.

## As-Is State

### Client Information and Case Notes

There is a current challenge in managing information, data, forms, and voice notes between clients.

Workers have to move between lots of different pages in the current system, going back and forth to update information. This creates friction and makes it harder to capture the right information.

The current system is difficult to use when looking for case notes. This can make it harder for workers to see the right clients and maintain accurate records.

There is too much admin work in the current process.

### Safeguarding and Welfare Checks

The group discussed whether there is a requirement for general chat or conversation logging with the people Simon on the Streets serves.

There were also questions about welfare checks:

* Do welfare checks need to be explicitly recorded?
* Could a welfare check be tracked as a simple checkbox to say it has been completed?
* What information is essential for safeguarding purposes?

### Referrals and Forms

Referrals to housing associations are a pain point.

This is currently managed online across separate forms. The group discussed the need for a more frictionless process where information can be captured in one place and then translated into the required forms.

### Worker Safety and Location

There are no current tracking systems in place to know where Simon on the Streets workers are.

There is no way for workers to raise an SOS if they are in danger. This makes it difficult to know whether everyone is safe.

### Client Location and Identification

The people Simon on the Streets serve can be transient, which can make it difficult to find the right person at the right time.

Clients also do not always give correct information. The group discussed the idea of location-based accounts, where workers could record that clients are known to operate in or around certain areas.

### Calendars and System Friction

Calendars are managed through Outlook. There are issues with information not being saved at the right times.

Anything tracked from one app to another can be lost in translation. This contributes to data loss and creates additional admin effort.

The current system also has issues with unrealistic timelines, which can cause delays.

## To-Be State

The group identified two broad capabilities that the future product should support:

* Add and manage clients.
* See reports and sync data.

The future product should work from mobile phones, laptops, and desktops. A web-based application was considered the right direction because outreach workers need to access information while away from a laptop.

### Better Mobile Access

Workers currently have to carry a lot of equipment. Being able to operate from a phone would make day-to-day work easier.

The product should make it simple to add notes from a phone and give workers something useful to look at when they do not have a laptop with them.

### Single-Page Client View

The future product should make it easier to find, view, and add to case notes.

The group discussed the need for a single page where workers can:

* Find a client.
* See key client information.
* View previous notes.
* Add new notes.
* Record welfare checks.
* See whether a consent form has been completed.
* Offer and capture a consent form when needed.

The aim is to allow standard checks and updates to happen from one place.

### Consent Capture

Digital consent should be available from the client page.

Currently consent is manual, offline, or paper-based. This creates further admin overhead.

The group discussed the need for workers to gather customer data and have clients consent to that data being gathered and used later.

### Reporting and Data Quality

Reporting needs more accurate data.

Simon on the Streets currently suffer from data loss across systems. Workers often have to manually correct data or report data loss back into the current system.

The data they gather is important because it is required for fundraising and other activities.

The future system will need consistent data capture and processing across systems. This does not need to be fully solved in the MVP, but it must be kept in mind when designing the data model.

### Maps and Worker Location

The group discussed the value of a map or location-based system to track where workers are.

This could support worker safety and make it easier to understand where clients and workers are operating.

### Automation and Follow-Up

The future product should automate repeated manual processes where possible.

It should also make deadlines and client follow-ups easier to manage.

## MVP Direction

The group agreed that the most effective MVP would be a single-page, web-based application focused on client information.

The MVP should provide as much useful client information as possible on one page and be accessible from a phone, laptop, or desktop.

At MVP stage, the product does not need to synchronise data with existing systems. Instead, it should define a data schema that future migration from the old system can map into.

The purpose of the MVP is to prove that Simon on the Streets can capture and use client data in a simpler, more consistent way.

## Proposed MVP Capabilities

The group agreed that the MVP should allow workers to search for a client by name and open a page containing that client's information.

From that page, workers should be able to:

* Tick a box to record that a welfare check has been completed.
* See previous notes.
* Add new notes.
* See whether a consent form has been completed.
* Offer the consent form to the client if it has not been completed.
* Capture a digital signature for the consent form, if possible.
* Complete standard checks from the same page.

The product should gather this data safely and securely and store it long term.

Workers may still need to manually transfer information into the old system during the MVP phase. The new product should make that manual transfer as simple as possible by organising information clearly in one place.

## Data and Migration

The group recognised that all data from the current system will eventually be needed.

However, importing existing data is not required in order to move forward with the MVP.

The immediate priority is to create a new data schema that:

* Supports the MVP workflow.
* Captures data consistently.
* Can support future translation or migration from the existing system.
* Can support future reporting needs.

## Follow-Up Questions

The group agreed that more detail is needed after the session to define exactly what the MVP should look like.

Questions to explore include:

* What exact fields must appear on the single-page client view?
* What information must be captured for a welfare check?
* What information must be captured for safeguarding?
* What does the digital consent form need to contain?
* Is a digital signature required for the MVP, or can it follow later?
* What data is needed for fundraising and reporting?
* Which reports are most important in the short term?
* What information needs to be copied into the existing system during the MVP phase?
* What security and access controls are required for client data?

## Conclusion

The group concluded that the MVP should focus on reducing admin friction for outreach workers.

The strongest candidate is a responsive, single-page client application that allows workers to search for a client, view key information, add notes, record welfare checks, and manage consent.

The MVP does not need to replace the existing system immediately. Its value is in proving that data can be captured in a simpler and more consistent way, while still allowing workers to transfer information into the current system until migration becomes possible.

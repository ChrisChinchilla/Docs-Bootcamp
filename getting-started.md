## How to get started - An example

Start with the most important ‘need to know’ details first, then lead from there. Start with the conclusion of what people will need to know and why and then tell them how to get there; this might be the reverse of what you are used to with essays, stories, etc.

-   Getting started, top easy tips to getting started writing ‘good’ docs.
-   Documentation is a process that involves outlining, drafting, editing, and responding to reviews/feedback.
-   Perfection is an impossible standard, don’t let it get in the way of getting started.
-   When to start
-   Early in the software dev lifecycle is better
-   Planning
-   what do you think your users need (what is their goal?)
-   figuring out change set (what is new information? Is anything being retired/replaced?)
-   state your assumptions/prerequisites (are these docs dependant on others?)
-   co-ordination with releases (when do you need this?)
-   Collaboration (who do you need to work with?)
-   Approval/ownership (who will approve docs and own them after you?)
-   Templates (are there existing formats you can use?)
-   Format (what types of doc do you need?)

Example: Error message [work through example]

User: Non-technical

Context:

-   Trying to submit information via a form
-   Form will not accept because:
    ○	1) Form is incomplete
    ○	2) Submission error like validation
-   User may be frustrated

Goal:

-   Help users complete the form

Information:

-   What has happened, why it doesn’t work, what they need to do

Assumptions/prerequisites:

-   User is only interacting with the form (Just UA and embedded help text)
-   Not dealing with translation

When:

-   Frequency of message

Collaboration/approval:

-   Design, product management, QA

Templates:

-   Not appropriate for this type of content

Format:

-   Error string

Example: New API endpoint to existing Google Mapping REST API

User: Technical, frontend dev, inexperienced with existing API

Context:

-   User has been asked to integrate map into application
-   Has a fixed deadline  

Goal:

-   Help user integrate map into their application

Information:

-   New information
-   Call
-   Parameters
-   Example and example response
-   Qualities: pagination, rate limiting, HTTP responses

So much info, what kind of docs would meet the user need here?

Examples:

-   Release note
-   How-to guide
-   API reference

Can’t assume user will see or need all of these. They should work alone in isolation.

Assumptions/prerequisites:

-   User is aware of product capabilities of Google Maps
-   Has used other APIs
-   No authentication required

When:

-   Document as you build

Collaboration/approval:

-   Anyone who has worked on the rest of the API doc
-   Product manager/owner for approval

Templates:

-   For API reference, look at other API endpoints in documentation
-   Follow release note template
-   Follow how-to guides

# Blackbird Data Modeling
## Agenda
- Review primary requirements and features (see [below](#background--context))
  - Could it help to sketch out some user journeys for any of these?
- Data model
  - Main components:
    - Production plan
    - Production target
    - Inventory
  - What about sales projections, subscriptions, orders, etc?
- Prototyping
  - Any low-hanging fruit features that could be prototyped quickly, like dashboards or UI components?
  - Can Runrig be of any help here?

## Attendees
- 
- ...


## Notes
- 
- ...


## Background & context
Chris's initial call-to-action from the DTI Discord channel, with 6 high-level features and/or requirements:

> I'm about to start working on my own custom app for handling sales both front and back of house. I just completed a time-audit of the largely manual AirTable/Google Form/Square/JS orgy of technical debt I'm using to manage this stuff and now I'm... upset. I'm looking at:
> 
> 1. A mobile and web app for allowing people to sign up for CSA subscriptions (with our proprietary model that allows people to have different shares delivered on different schedules) and ad-hoc sales for both retail and wholesale. And determining based on delivery address whether or not people are in our service range.
> 
> 2. Automatically nudge subscribers toward cost savings by optimizing their delivery schedules and such, and also allows subscriptions to be put together based on budgets and preferences (e.g. "I can't spend more than $90/month and I really like ribeyes; gimme some options")
> 
> 3. Integrate in real time with our routing software (OptimoRoute), and allow people to shift delivery dates, combine or redirect orders, etc.
> 
> 4. Provide some business intelligence: specifically, using subscription data to provide a dashboard of necessary production and purchases from partner farms, and the ability to forecast profitability by comparing production costs with sales
> 
> 5. Possibly integrate with a CRM like Salesforce to improve customer capture
> 
> 6. Double bonus: coding up our own payment gateway, which could save us a small fortune in revenue (Square/Stripe fees are going to cost us $20K+ this year).
> 
> Ideally this system will allow me to retire Square, AirTable, Google Forms, Integromat/Make, Stripe, the handful of scripts making it all work together, and my part-time IT job coordinating it all.
> 
> My specific ask is this: I am absolute sh*t with UI stuff, and have no mobile chops whatsoever. I can hold my own with algorithms, data schemas, cloud, web services, and other backend stuff... so I could definitely use some help from someone with experience in React, Angular, Swift, XCode, etc.
> 
> I'd like to set this up as a separate service that Sylvanaqua / Blackbird both pays for an co-owns along with whatever other developers help put it together.
> 
> Anybody wanna get to hacking?

Following up on this...
- Chris shared this design doc with more details: [Blackbird app (Google Doc)](https://docs.google.com/document/d/1V7Cg7xsKQCnVm2NOjuXMy5Xu_wBxfXTP5pGGN116lpo/edit)
- Kickoff meeting includes extensive discussion of the features and requirements as well: [Notes for Skywoman DTI Call Mar 2 (Google Doc)](https://docs.google.com/document/d/1C3SZ4gR8RD8RZjcHvp8YXCF2GlRSH7nDZxLneYSXQSs/edit#)



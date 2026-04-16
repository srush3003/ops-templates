# Integration Planning Template

Most app launch delays are not caused by code. They are
caused by missing credentials, unclear ownership, and
integrations nobody started early enough.

This template surfaces those dependencies before
development starts so your team is not blocked waiting
on a DNS record or OAuth approval the week before launch.

**When to use this:** At project kickoff, before 
development begins. Fill it out with your developer 
and client in the same session.

---

## How to use this template

1. Copy this file into your project folder
2. Fill in every section during kickoff
3. Start longest-wait items immediately after kickoff
4. Review the readiness checklist before development starts
5. Update the integration tracker weekly until launch

---

## Project Overview

| Field | Detail |
|-------|--------|
| Project Name | |
| Project Duration | weeks |
| Launch Date | |
| Coordinator | |
| Lead Developer | |
| Client Contact | |

---

## Integration Tracker

Track every integration in one place. Update weekly.

| Integration | Status | Owner | Blocker | Start by | Target Date | Wait Time | Setup Time | Priority |
|-------------|--------|-------|---------|----------|-------------|-----------|------------|----------|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Status options:** Not started / In progress / Waiting on client / Waiting on approval / Done

**Priority options:** Critical / High / Medium / Low

---

## Longest-Wait Items

Start these on day one. These are the integrations with
the longest approval or propagation times. DNS changes,
OAuth app approvals, and payment gateway verifications
typically take 3-7 business days minimum.

1. 
2. 
3. 

> Rule: if it requires a third party to approve something,
> start it before anything else.

---

## Access and Ownership

Be explicit about who manages what. Ambiguity here
causes the most delays.

**Client manages:**
- 

**We manage:**
- 

---

## Required Credentials Checklist

Document every credential needed before development
starts. Do not begin development with gaps in this list.

### Example: Email service

- Domain name:
- DNS access or contact who has it:
- Preferred from address:

### Example: Payment gateway

- Account email:
- Business verification documents ready:
- Webhook endpoint confirmed:

> Add one section per integration. Remove examples
> that do not apply to your project.

---

## Cost Estimation

Calculate before launch, not after. Surprises here
damage client trust.

| Service | Free Tier Limit | Paid Tier Cost | Expected Usage | Estimated Cost |
|---------|----------------|----------------|----------------|----------------|
| | | | | |
| | | | | |
| | | | **TOTAL** | $ |

### Budget by phase

| Phase | Estimated monthly cost |
|-------|----------------------|
| Testing (free tier) | $ |
| Launch (1,000 users) | $ |
| Scale (10,000 users) | $ |

---

## Environment Configuration Matrix

Document credentials per environment from the start.
This prevents the most common launch-week bug: something
that works in development but breaks in staging or
production because credentials were never configured.

Fill this out for every integration before development
starts.

**Integration name:**

| Environment | Credential Type | Value | Status |
|-------------|----------------|-------|--------|
| Development | | | |
| Staging | | | |
| Production | | | |

**Status options:** Configured / Pending / Not started

> Repeat this table for each integration in your tracker.

---

## Pre-Development Readiness Checklist

Do not start development until every item is checked.
An unchecked item is a future delay.

- [ ] All required integrations identified and listed
- [ ] Access and ownership confirmed for each integration
- [ ] Longest-wait items started
- [ ] Integration tracker created and shared with team
- [ ] Environment configuration matrix prepared
- [ ] Developer has all credentials for development environment
- [ ] Client understands timeline including wait periods
- [ ] Communication cadence agreed and documented
- [ ] Cost estimate reviewed and approved by client
- [ ] Backup plans identified for likely blockers

**All checked:** Ready to start development.

**Any unchecked:** Resolve before starting. Every
unchecked item is a predictable delay you are choosing
not to prevent.

---

## Notes and Decisions Log

Document decisions made during kickoff and any changes
during the project. One line per entry with a date.

| Date | Note or decision |
|------|-----------------|
| | |
| | |

---

*Part of the ops-templates repo by Srush*  
*Full portfolio: srushtip.notion.site/portfolio*

---
layout: default
---

Something is going wrong in your project and it has nothing to do with code — an argument that
will not resolve, a contributor whose behaviour is hard to name, a pile-on that arrived from
somewhere else. Nobody handed you a job description for this part; most of us learned it during
the incident, in public.

We are a working group at the [Nivenly Foundation](https://nivenly.org/) writing that down. Our
own guidance is in draft, targeted for December 2026. Until then, here is what already exists.

## If something is happening right now

None of the following is ours, and none of it is a procedure to follow. It is the material we reach
for ourselves.

**For the shape of the problem.**
[How to keep open source open without leaving our communities open to threats](https://media.ccc.de/v/39c3-how-to-keep-open-source-open-without-leaving-our-communities-open-to-threats)
— a talk from the 39th Chaos Communication Congress on the rise in crisis events in open source
since 2014, and what the public record shows about it.

**If the question is who should be able to see this.**
[Open Source Governance Needs Private Spaces](https://sarahnovotny.com/2026/04/14/open-source-governance-needs-private-spaces/)
— the case that some community communication legitimately should not be public, and the five kinds
of it that need somewhere to happen other than an open issue tracker.

**If you need to say something without saying everything.**
The [Traffic Light Protocol](https://www.first.org/tlp/) is how security teams mark how widely a
piece of information may travel, and [CISA's guidance](https://www.cisa.gov/tlp) shows it in
practice. It was built for incident response between organisations rather than for volunteer
projects, so it will not fit you exactly — but it gives you words for a decision you are already
making under pressure.

**If you want to see this done well by someone else.**
Django publishes an [enforcement manual](https://www.djangoproject.com/conduct/enforcement-manual/)
describing how code of conduct reports are handled, alongside
[transparency reports](https://github.com/django/code-of-conduct/blob/main/transparency.md) on the
actions it has taken. The Apache Software Foundation
[scopes its private list](https://www.apache.org/dev/pmc.html) to an enumerated set of matters, so
that using it for anything else is visibly out of bounds. Both are worth reading before writing
your own.

## What we think the problem is

Open source security has well-funded attention on code: dependencies, signing, build provenance,
supply chains. The communities that produce the code have had much less. A project can have
reproducible builds and still come apart under a conflict nobody knew how to name.

Two directions matter here, and they need different answers. One is someone acting in bad faith
from inside a community. The other is someone outside it using the community's own structures —
its openness, its processes, its willingness to assume good faith — as the way in.

We are also moving away from calling this moderation. Moderation sounds like a role with a mute
button, and in French it carries a strong flavour of policing a space and handing out sanctions.
The more honest framing is that doing your work in public comes with expectations, most of which
nobody wrote down. Some of those expectations can be met with **responsible friction** — friction
placed deliberately where it helps: a slower path into authority, a documented way to raise a
concern, a decision that takes more than one person. Enough that acting in bad faith costs
something, and not so much that contributing becomes miserable.

## What we're building

Phase 1 is communication norms: guidance a project can use to decide what to say, to whom, and in
what measure, during a social crisis or a security event. It is about how to communicate rather
than what to do. Phase 2 turns the same attention on governance patterns themselves, threat
modelling and abuse testing the structures projects already run on.

We reviewed the frameworks you would expect us to review and decided to write our own rather than
endorse any one of them. Each carried failure modes under bad-faith use, or assumptions that do not
travel well outside the anglosphere. What we are building instead has four layers, each aimed at
different people:

| Layer | Who it is for |
|---|---|
| Communication norms | Everyone who contributes |
| Conflict assessment | Moderators and maintainers |
| Governance structure | Leadership and governance bodies |
| Repair | Whoever handles an incident |

It is built to scale. A two-person project and a foundation with fifty thousand contributors do not
need the same thing, and the small end is a floor rather than a ceiling.

Two commitments shape all of it:

**Work with what is already there.** Every part of this asks a project to look at its existing
practice before anything new gets introduced. Finding that you have none is useful information, not
a failing grade.

**Transparency of process, not content.** A project can be open about how it communicates and makes
decisions without publishing every deliberation. Private space belongs in good governance when its
scope is defined and its existence is public. Where neither is true, suspicion is a reasonable
response.

Phase 1 output is targeted for December 2026. It is in draft and has not yet been through full
working-group review, which is why this page describes its shape rather than publishing it.

## Who's building this

The Securing Open Source Communities Working Group is part of the
[Nivenly Foundation](https://nivenly.org/). Our
[charter](https://github.com/nivenly/securing-open-source-communities-wg/blob/main/README.md),
[operational agreement](https://github.com/nivenly/securing-open-source-communities-wg/blob/main/OPERATIONS.md),
[code of conduct](https://github.com/nivenly/securing-open-source-communities-wg/blob/main/CODE_OF_CONDUCT.md)
and [contributor list](https://github.com/nivenly/securing-open-source-communities-wg/blob/main/CONTRIBUTORS.md)
are all public, in [the repository](https://github.com/nivenly/securing-open-source-communities-wg).

Membership is by invitation and the group is deliberately small, so that people can speak frankly
about incidents they have handled. If you have taken an open source project through a governance
crisis, or you work in security and want to lend that perspective, reach out to
[Quintessence](https://github.com/quintessence).

If you would rather just watch the work land, the repository is public.

---

*Content is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).*

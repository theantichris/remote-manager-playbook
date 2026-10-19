# Asynchronous Messaging

Distributed teams should be able to make progress without waiting for everyone to be online at the same time. The goal is to share enough context that people can understand the work and take the next step.

## Four Parts of a Useful Async Message

1. **Context:** What's happening, why it matters, and links to the relevant work.
1. **Ask or decision:** What do you need from the reader?
1. **Owner:** Who is responsible for responding or taking the next step?
1. **Timing:** When do you need an answer or decision? Include the time zone if there's a deadline.

Answer the likely follow-up questions, but don't bury the ask in a wall of text. A good message should make it clear what someone can do next.

## Template

- Context: What's going on and why it matters.
- Ask/Decision: What you need from whom.
- Owner(s): Who is responsible for the next step.
- Deadline/Timezone: When you need it and in which time zone.
- Links/Docs: Supporting information and evidence.

## Example

**Useful message**

- Context: Checkout errors increased after today's deploy; logs point to the tax calculation.
- Ask: Product and Engineering need to decide whether to roll back or ship a fix.
- Owner(s): Engineering lead and PM.
- Deadline/Timezone: Decision needed by 15:00 Eastern today.
- Links/Docs: Dashboard, error logs, and the related PR.

**Not useful**

> Something's broken. Thoughts?

There's no context, clear owner, or next step.

## When a Conversation Is Better

Async is a default, not a mandate. Talk live when:

- Giving sensitive or difficult feedback.
- Working through a complicated problem where rapid back-and-forth will help.
- Resolving a conflict or misunderstanding.
- Responding to something urgent that can't wait for an async reply.

Kickoffs and working sessions can benefit from written context before a conversation. Routine project updates and decisions often work well asynchronously when the owner and expectations are clear. See [Project Ownership and Weekly Updates](../process/project-ownership.md).

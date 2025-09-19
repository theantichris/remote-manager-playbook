# Asynchronous Messaging

## Four components of a great asynchronous message

1. Include enough information to cover all follow-up questions.
1. Include a deadline for when you need an answer.
1. Add any links, images, and as much context as is possible.
1. Include a concrete need or outcome.

## Template

- Context: what's going on and why it matters.
- Ask/Decision: what you need from whom.
- Owner(s): who's responsible for the next step.
- Deadline/Timezone: when you need it and in which TZ.
- Links/Docs: supporting info.

## Examples

- Good

  - Context: Checkout errors spiked to 2.4% after today's deploy; logs point to tax calc.
  - Ask: Product + Eng to decide rollback vs. hotfix.
  - Owner(s): @alex (Eng), @jordan (PM)
  - Deadline/Timezone: Need a decision by 3pm ET today.
  - Links: dashboard, Sentry issue #123, PR #456

- Anti-pattern
  - "Something's broken. Thoughts?" (No context, no owner, no deadline.)

## When not to use async communication

1. Delivering critical feedback.
1. Solving challenging problems.
1. Project kick-offs.
1. Project sync-ups.
1. Long chats.

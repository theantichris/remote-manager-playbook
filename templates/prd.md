# PRD: {{title}}

A Product Requirements Document helps us understand the problem we're trying to solve, why it matters, and what success looks like.

I believe Product, Engineering, and Design should collaborate on understanding the problem and identifying the best solution.

The PRD should provide direction without prescribing every implementation detail.

Keep the document focused on what we need to know to make good decisions. Not every project requires every section.

## Overview

**DRI:** [Person responsible for the outcome]

**Status:** Draft / In Review / Approved / Completed

**Stakeholders:** [Relevant people or teams]

**Target Date:** [If applicable]

### Summary

Briefly explain the opportunity, the problem, and the intended outcome.

Someone unfamiliar with the project should be able to understand why we're considering this work without reading the entire document.

## Problem

What problem are we trying to solve?

- Who is experiencing the problem?
- What are they trying to accomplish?
- How are they solving it today?
- What frustrations or limitations exist?
- Why does this problem matter now?
- What happens if we do nothing?

Focus on understanding the problem rather than justifying a solution we've already chosen.

## Evidence and Assumptions

What evidence supports our understanding of the problem?

Consider customer feedback, research, usage data, support requests, or other relevant information.

**What we know:**

- [Evidence or established fact]

**What we believe:**

- [Assumption or hypothesis]

**What we still need to learn:**

- [Unknown or unanswered question]

Clearly distinguish facts from assumptions.

## Desired Outcomes

What will be meaningfully better if we solve this problem?

Consider outcomes for customers, users, and the business.

- **Customer outcome:** [How the user's experience improves]
- **Business outcome:** [What value the organization expects]
- **Supporting outcomes:** [Other meaningful improvements]

The outcome should explain why the work matters, not simply describe what we're going to build.

## Success Criteria

How will we know whether we succeeded?

| Measure | Baseline | Target | Timeframe |
| --- | --- | --- | --- |
| [Primary outcome] | [Current value] | [Desired value] | [When] |
| [Supporting measure] | [Current value] | [Desired value] | [When] |

Not every outcome can be measured numerically. Use observable behaviors, feedback, or other evidence when appropriate.

Consider whether we need guardrails to protect reliability, quality, cost, or another important existing capability.

## Proposed Solution

Describe the proposed approach at a high level.

- What are we proposing?
- How does it address the problem?
- Why do we believe it will work?
- What assumptions does it depend on?
- What alternatives have we considered?

This isn't a detailed technical design.

Engineering and Design should have room to explore implementation approaches and make appropriate trade-offs.

Link to a [Detailed Design Document](detailed-design-document.md) when deeper technical discussion is necessary.

## Scope

### In Scope

- [Capability or behavior we intend to deliver]
- [Additional scope]

### Out of Scope

- [What we are deliberately not addressing]
- [What may be considered later]

Be explicit about boundaries to keep the work focused.

## Discovery and Validation

What's the least expensive useful way to test our assumptions before making a larger investment?

| Question or Assumption | Validation Approach | Evidence of Success |
| --- | --- | --- |
| [What we need to learn] | [Research or experiment] | [What would support the hypothesis] |

Consider customer interviews, prototypes, experiments, technical investigations, and limited releases.

We should be willing to change our proposed solution when the evidence challenges our assumptions.

## User Experience and Adoption

How will people interact with or adopt the solution?

- Does it change an existing workflow?
- Will users need to learn something new?
- Are migration or onboarding steps required?
- What could prevent adoption?
- How will we gather feedback?

The value of the solution should justify the effort required to adopt it.

## Dependencies and Constraints

What could affect our ability to deliver the intended outcome?

- [Relevant teams or systems]
- [Technical or operational constraints]
- [External dependencies]
- [Timeline, capacity, or resource limitations]

Make dependencies and ownership clear without duplicating the project's task tracker.

## Risks and Trade-offs

| Risk | Potential Impact | Mitigation |
| --- | --- | --- |
| [Risk or unknown] | [Consequence] | [How we'll address it] |

Consider the consequences of both taking action and choosing not to act.

## Delivery and Rollout

Describe the major milestones or phases when a phased approach is useful.

### Milestones

- [Milestone and expected outcome]
- [Milestone and expected outcome]

### Rollout

- How will we introduce the solution?
- Can we release incrementally?
- How will we verify it works?
- What happens if the rollout doesn't go as expected?

Keep implementation tasks in the team's existing project management system.

## Measuring Results

After delivery, we'll evaluate whether the solution achieved the intended outcomes.

- Did we solve the problem?
- Did the intended users adopt the solution?
- Did their experience improve?
- Did we achieve our success criteria?
- What did we learn?
- What should we continue, change, or stop doing?

**Shipping the solution isn't the same as succeeding.**

## Open Questions and Decisions

### Open Questions

- [Question requiring further investigation or discussion]

### Decisions

| Decision | Rationale | Owner | Date |
| --- | --- | --- | --- |
| [Decision] | [Why] | [Who] | [When] |

Capture meaningful decisions so people can understand the reasoning behind them.

## References

- [Customer research or feedback]
- [Related project or strategy documents]
- [Designs and technical proposals]
- [Issues, discussions, and supporting evidence]

---

A PRD should help us understand the problem, align on the outcome, and make informed decisions together.

**The goal isn't to produce a perfect requirements document. It's to give us enough clarity to solve the right problem and deliver meaningful value.**

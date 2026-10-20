# Detailed Design Document: {{title}}

A detailed design document explains how we intend to solve a technical problem, why we've chosen a particular approach, and what trade-offs we're making.

The goal isn't to document every implementation detail or create another approval process. It's to give people enough context to evaluate the approach, identify risks, and make informed decisions.

Use the sections that are relevant to the work. Smaller, easily reversible changes shouldn't require the same level of documentation as significant architectural decisions.

## Overview

**DRI:** [Person responsible for the design and outcome]

**Status:** Draft / In Review / Accepted / Superseded

**Reviewers:** [People whose expertise or input is needed]

**Decision Needed By:** [Date, if applicable]

### Summary

Briefly explain what we're proposing and why.

Someone unfamiliar with the project should be able to understand the problem, the recommended approach, and its expected benefits without reading the entire document.

## Problem and Desired Outcome

### Problem

What problem are we trying to solve?

- Who or what is affected?
- Why does this matter now?
- What limitations exist in the current system?
- What happens if we do nothing?

Link to the relevant PRD, project brief, or other documentation rather than duplicating information unnecessarily.

### Desired Outcome

What will be better if we're successful?

Describe the customer, engineering, or business outcomes we're trying to achieve.

How will we determine whether the solution worked?

## Scope and Constraints

### In Scope

- [What this design addresses]

### Out of Scope

- [What we're deliberately not addressing]

### Constraints and Assumptions

- What technical, operational, or organizational constraints exist?
- What dependencies do we need to consider?
- What assumptions are we making?
- What requirements are non-negotiable?

## Proposed Design

Explain the recommended technical approach and why you believe it's appropriate.

Focus on the important architectural decisions and trade-offs rather than providing an exhaustive implementation guide.

### Architecture

Include a diagram when it helps explain the design.

Describe:

- The major components and their responsibilities.
- How those components interact.
- The flow of data and requests through the system.
- Dependencies on existing services or infrastructure.
- Changes to existing architectural boundaries.
- Systems or teams that may be affected.

Diagrams should clarify the design, not simply make the document look more complete.

### Interfaces and Contracts

What interfaces, APIs, events, or contracts are being introduced or changed?

Consider:

- Inputs and outputs.
- Compatibility with existing consumers.
- Error handling and failure behavior.
- Versioning and migration requirements.
- Ownership of the interfaces.

### Data

How will the solution handle data?

Consider:

- What data is required or produced?
- Where will it be stored?
- How will it be accessed and protected?
- Are schema changes or migrations necessary?
- What are the retention and deletion requirements?
- How will data consistency and integrity be maintained?
- Will downstream consumers or reporting systems be affected?

Include migration or compatibility considerations when changing existing data.

## Non-Functional Requirements

A solution needs to do more than produce the correct result. It should also be secure, reliable, maintainable, and capable of operating effectively over time.

Consider the areas relevant to the proposed design.

For each important requirement, describe the expected behavior, any meaningful thresholds, how the design addresses it, and how we'll verify it.

### Security and Compliance

- How is access controlled?
- How are sensitive data and credentials protected?
- What security or compliance requirements apply?
- How are important actions monitored or audited?

### Performance and Scalability

- What performance expectations must the system meet?
- What workloads or usage patterns should we expect?
- How will the system handle increasing demand?
- What limitations or bottlenecks might emerge?
- What metrics and thresholds will help us evaluate performance?

### Availability and Resilience

- What availability expectations apply?
- What happens when a dependency fails?
- How will the system recover from failures?
- Are redundancy, retries, timeouts, or graceful degradation necessary?
- What recovery expectations must we meet?

### Observability and Debuggability

- How will we know whether the system is healthy?
- What metrics, logs, and traces will help us understand its behavior?
- What conditions should trigger alerts?
- How will we investigate problems in production?
- Can engineers safely diagnose issues without exposing sensitive information?

### Maintainability and Modularity

- Is the proposed design unnecessarily complex?
- Can the components be understood and changed independently?
- Are responsibilities and boundaries clear?
- What technical debt are we introducing or removing?
- Could parts of the solution be reused without adding unnecessary abstractions?

### Configuration and Deployment

- How will the system be configured across environments?
- How are configuration changes managed?
- Can changes be deployed safely and consistently?
- What automation is needed?
- What operational dependencies are introduced?

### Testability

- How will we verify the solution behaves as expected?
- What automated testing is appropriate?
- How will we test failure scenarios?
- Are integration, load, security, or migration tests needed?

### Documentation

- What documentation will engineers or operators need?
- Are runbooks or troubleshooting guides required?
- Where will this documentation live?
- Who will maintain it?

### Capacity and Cost

- What resources will the solution require?
- What are the expected infrastructure and operational costs?
- How might those costs change as usage grows?
- What cost-related trade-offs are we making?

Not every design requires an extensive discussion of every category. Focus on the requirements that meaningfully affect the solution and its operation.

## Rollout and Operations

### Implementation Approach

Describe the major phases or milestones required to implement the design.

Focus on dependencies and significant implementation decisions rather than duplicating the project's task tracker.

### Rollout

- Can the solution be introduced incrementally?
- Will feature flags or a phased rollout be useful?
- Are existing consumers or systems affected?
- How will we validate the solution before broader adoption?
- What needs to happen before the rollout is considered complete?

### Rollback and Recovery

- What happens if the implementation doesn't behave as expected?
- Can we safely reverse the change?
- Are there irreversible data or infrastructure changes?
- How will we minimize disruption during recovery?

### Operational Ownership

Who will own the solution after it's delivered?

What responsibilities will the team have for monitoring, maintaining, and supporting it?

## Alternatives and Trade-offs

What alternatives did we consider?

| Approach | Benefits | Costs and Trade-offs |
| --- | --- | --- |
| Recommended approach | | |
| Alternative | | |
| Do nothing | | |

Explain why the recommended approach is preferable given the current goals and constraints.

Don't evaluate alternatives solely on technical elegance. Consider delivery time, operational complexity, cost, maintainability, and long-term flexibility.

## Risks and Mitigations

What could prevent this design from succeeding?

| Risk | Likelihood | Impact | Mitigation |
| --- | --- | --- | --- |
| [Risk] | Low / Medium / High | [Impact] | [Approach] |

Focus on meaningful risks rather than attempting to document every hypothetical failure.

Identify important unknowns and explain how we'll reduce uncertainty.

## Open Questions and Decisions

### Open Questions

- [Question requiring investigation, feedback, or a decision]

### Decisions

Capture important decisions made during the design process.

| Decision | Rationale | Owner | Date |
| --- | --- | --- | --- |
| [Decision] | [Why] | [Who] | [When] |

Document decisions so future engineers can understand why the system was designed this way.

## Review and Next Steps

Before moving forward, make sure we've answered the important questions:

- Does the design address the intended problem?
- Are the trade-offs and alternatives understood?
- Have we considered the important non-functional requirements?
- Are the significant risks and unknowns visible?
- Do the people affected understand the approach?
- Is ownership clear?
- Do we know how we'll verify success?

Not every design needs formal approval. The amount of review should reflect the risk, complexity, and reversibility of the decision.

Once we're aligned, identify the next steps and make sure the work has clear ownership.

## References

Link supporting information rather than duplicating it.

- [Product or project requirements]
- [Related technical documentation]
- [Relevant decisions or proposals]
- [Research, experiments, or benchmarks]
- [Issues, PRs, and other supporting artifacts]

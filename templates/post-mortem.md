# Post-Mortem: {{title}}

Incidents are opportunities to learn about our systems, understand where they failed, and identify improvements that make them more reliable.

The goal of a post-mortem isn't to assign blame. It's to understand what happened, why it happened, how we responded, and what we can do to reduce the likelihood or impact of similar incidents.

I believe we should focus on improving our systems and processes rather than finding someone to hold responsible for a mistake.

**The goal isn't to make sure nobody ever makes a mistake. It's to build systems that can withstand mistakes and failures.**

## Incident Overview

**Date:** [Date]

**Severity:** [If applicable]

**Status:** Resolved / Monitoring / Follow-up Required

**Incident Owner:** [Person coordinating the investigation and follow-up]

**Affected Systems:** [Systems or services affected]

**Duration:** [Start and end times, including time zone]

### Summary

Briefly describe what happened, how it affected users or systems, and how the incident was resolved.

Someone unfamiliar with the incident should be able to understand the situation without reading the entire document.

## Impact

What was the actual impact of the incident?

Consider:

- Which customers, users, or internal teams were affected?
- What functionality was unavailable or degraded?
- How long did the impact last?
- How significant was the disruption?
- Were there financial, operational, security, or other consequences?

Quantify the impact when possible.

Clearly distinguish confirmed impact from estimates or unknowns.

## Timeline

Document the important events leading up to, during, and following the incident.

Use 24-hour time and specify the time zone.

| Time | Event |
| --- | --- |
| [HH:MM] | [Relevant event] |
| [HH:MM] | [Issue detected] |
| [HH:MM] | [Investigation or response] |
| [HH:MM] | [Mitigation applied] |
| [HH:MM] | [Service restored] |

Include relevant deployments, configuration changes, alerts, decisions, and recovery actions.

Focus on events that help us understand what happened rather than documenting every message exchanged during the incident.

## Detection and Response

### Detection

How did we discover the problem?

- What alerts or monitoring systems identified it?
- Did a customer or team member report it?
- How much time passed between the beginning of the incident and detection?
- Were there signals we could have recognized earlier?

### Response

How did we respond?

- What actions did we take to investigate the issue?
- What did we do to mitigate the impact?
- What helped us understand or resolve the problem?
- What made the investigation or recovery more difficult?
- Were the necessary people, tools, and information available?

### Resolution

What ultimately restored normal operation?

Describe the changes or actions taken and how we verified that the problem was resolved.

Distinguish temporary mitigation from a permanent solution.

## Analysis

### What Happened?

Explain the technical sequence of events that led to the incident.

Describe how the system behaved, what we expected it to do, and where those expectations differed from reality.

### Contributing Factors

What conditions made the incident possible or increased its impact?

Consider:

- Architectural or technical limitations.
- Missing safeguards or failure handling.
- Testing or deployment gaps.
- Monitoring and observability limitations.
- Unclear ownership or operational processes.
- Dependencies and unexpected interactions between systems.
- Assumptions that didn't hold true.

Avoid stopping at explanations such as "human error."

People make decisions based on the information, tools, and circumstances available to them. Understanding those conditions helps us improve the system.

### Why Wasn't It Prevented or Detected Earlier?

What safeguards might have prevented the incident or helped us recognize it sooner?

Consider whether existing protections failed, were missing, or behaved differently than expected.

We don't need to invent preventative measures for every hypothetical scenario. Focus on practical improvements that meaningfully reduce risk.

## What Went Well?

What helped us respond effectively?

- [Useful monitoring, tooling, or documentation]
- [Effective collaboration or communication]
- [Resilience mechanisms that reduced impact]
- [Other strengths worth preserving]

Recognizing what worked helps us reinforce good practices rather than focusing exclusively on problems.

## What Could Be Better?

Where did we experience unnecessary friction or uncertainty?

- [What slowed detection or recovery?]
- [What information was difficult to obtain?]
- [Where could coordination or communication improve?]
- [What safeguards or capabilities were missing?]

Focus on improvements within our influence rather than assigning blame.

## Improvements and Follow-up

Identify a small number of meaningful actions that address the most important contributing factors.

| Improvement | Owner | Priority | Target Date | Expected Outcome |
| --- | --- | --- | --- | --- |
| [Action] | [Person] | [Priority] | [Date] | [Risk or impact reduced] |

Good follow-up actions should be specific, actionable, and connected to something we learned.

Avoid creating a long checklist of changes that won't be completed.

Track the work in the team's existing project management system and link the relevant issues here.

### Evaluating Improvements

How will we know whether our changes worked?

- What outcome do we expect?
- How will we verify the improvement?
- Are there tests, alerts, or operational metrics we should revisit?
- When will we review the results?

An action isn't necessarily successful simply because we completed it. We should understand whether it meaningfully improved the system.

## Communication

Who needs to understand what happened and what we're doing about it?

Consider:

- Customers or affected users.
- Internal stakeholders.
- Teams responsible for related systems.
- Support and operational teams.

Document relevant communications and follow-up commitments.

Share information appropriately and avoid including sensitive customer or security details in documents that don't have suitable access controls.

## What We Learned

Summarize the most important lessons from the incident.

What did we learn about our systems, assumptions, processes, or ability to respond?

Are there insights that could benefit other teams?

The purpose is to turn the experience into lasting improvements rather than simply record that an incident occurred.

## References

- [Incident tracking issue]
- [Relevant alerts, dashboards, or logs]
- [Related PRs or deployments]
- [Runbooks and technical documentation]
- [Follow-up issues]

---

A post-mortem should be detailed enough to help us understand the incident and learn from it, but it doesn't need to become an exhaustive document.

The amount of investigation and documentation should reflect the severity, impact, and complexity of the incident.

**A successful post-mortem doesn't mean we've eliminated every possible failure. It means we've learned something valuable and made our systems better because of it.**

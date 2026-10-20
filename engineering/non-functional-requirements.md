# Non-Functional Requirements

Functional requirements describe what software should do. Non-functional requirements (NFRs) describe how well it should work.

They help us establish expectations around security, performance, reliability, maintainability, and other qualities that affect the long-term success of a system.

I believe we should consider these requirements early in technical design, but we shouldn't treat them as a checklist that every project must satisfy equally.

The importance of each requirement depends on the problem we're solving.

## Areas to Consider

### Security and Privacy

How will we protect systems, users, and information?

- How is access controlled?
- What information requires protection?
- What security or compliance requirements apply?

### Performance

How quickly and efficiently should the system operate?

- What response times are acceptable?
- What workloads should it support?
- How will we measure performance?

### Availability and Reliability

How consistently should the system work?

- What level of availability is needed?
- What happens when something fails?
- How will the system recover?

### Scalability

How will the system accommodate increasing demand?

- What growth do we anticipate?
- Where might bottlenecks emerge?
- What changes would support additional capacity?

### Observability and Debuggability

How will we understand the system's behavior and investigate problems?

- What should we monitor?
- What logs, metrics, and traces are necessary?
- How will engineers diagnose failures?

### Maintainability

How easily can engineers understand, modify, and improve the system?

- Is the architecture unnecessarily complex?
- Are responsibilities and boundaries clear?
- Can we make changes without introducing excessive risk?

### Configuration and Deployment

How will we configure, release, and operate the system?

- How are environments configured?
- Can deployments be automated?
- How will we roll back unsuccessful changes?

### Testability

How will we verify that the system behaves correctly?

- What automated testing is appropriate?
- Can important failure scenarios be tested?
- How will we recognize regressions?

### Documentation

What information will future engineers need?

- Are important decisions documented?
- Are operational instructions available?
- Who maintains the documentation?

### Cost

What will the solution cost to build and operate?

- What infrastructure and services are required?
- How might costs change over time?
- Are the costs reasonable for the expected benefits?

## Applying Non-Functional Requirements

Not every project needs detailed answers to every question.

During technical design, identify the requirements that matter most, establish reasonable expectations, and document significant trade-offs.

Consider how those expectations will be measured or verified.

For larger architectural decisions, use the [Detailed Design Document](../templates/detailed-design-document.md) to capture the relevant requirements.

**The goal is to make thoughtful engineering decisions without adding unnecessary complexity.**

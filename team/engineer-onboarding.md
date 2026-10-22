# Engineer Onboarding

Use this guide to prepare a plan for each new team member. Adjust it for their role, experience, team, and the work available. The first 30, 60, and 90 days are useful points to review progress together; they aren't deadlines for proving independence or shipping a particular project.

## Before their first day

### Confirm the basics

- [ ] Confirm their preferred name, start date, role, manager, and email.
- [ ] Ask for their time zone and usual working hours before scheduling. Don't infer these from a mailing address.
- [ ] Choose an onboarding buddy, confirm they have time to pair, and arrange backup coverage for absences.
- [ ] Confirm who handles equipment, accounts, company orientation, and required training.
- [ ] Create the onboarding plan and share it somewhere both of us can update.

### Get equipment and access ready

- [ ] Confirm the laptop has been prepared and delivery is arranged.
- [ ] Confirm the corporate account works and the engineer has sign-in instructions.
- [ ] Create an access request with an owner and status for each tool.
- [ ] Collect the account handles needed for source control and package registries. Record the handles directly in the access request; a link to an email isn't a substitute.
- [ ] Compare the request with engineers doing similar work, then check what this role actually needs. Don't copy another person's permissions wholesale.
- [ ] Separate required access from tools that are only needed for specific work.
- [ ] Link to the actual training portal and setup instructions. Confirm invitation requirements and deadlines with the owner.

Check source control, package registries, development environments, issue tracking, documentation, chat, calendars, CI, test environments, observability, and any role-specific tools. Request production access through the normal approval process when the work requires it. Never put passwords or tokens in the plan.

Track requested, granted, and verified access separately. An invitation being sent doesn't mean the engineer can use the tool. During setup, verify they can sign in and complete a basic task.

### Prepare the first week

- [ ] Check existing company orientation sessions before adding meetings.
- [ ] Schedule an initial manager 1:1 and a separate buddy introduction. Put the manager conversation first when practical so we can establish context before diving into setup.
- [ ] Confirm availability, time zones, and the corporate email before sending invitations. Check for conflicts and existing invitations.
- [ ] Arrange a weekly 30-minute [1:1](../meetings/one-on-ones.md).
- [ ] Add the engineer to relevant recurring meetings and share the team calendar. These are separate steps; one doesn't guarantee the other.
- [ ] List the initial chat channels with links, including team, project, support, and announcement channels. Arrange invitations for private channels.
- [ ] Leave time for setup, reading, and self-directed exploration. Label that time clearly so an empty calendar doesn't feel like missing instructions.

Verify the first upcoming meeting occurrences, especially when recurring series have exceptions. Check whether invitations were accepted and resolve conflicts rather than adding more meetings around them.

## Write a useful individual plan

Start with the team's current documentation hub. Link to the roadmap, development setup, product walkthrough, customer examples, and support contacts. Check that the links work and that the named owners still work on the team.

Use concrete actions and outcomes. For example, replace "understand the architecture" with "run the service locally, trace one customer request, and explain where to inspect failures with the buddy." Replace "build relationships" with a list of people to meet and what each person owns.

For each milestone, identify the work or learning outcome, who can help, and how we'll know it is useful. Keep detailed scope and acceptance criteria in the team's issue tracker and link to them. Mark proposed dates as proposed, and name who will confirm any open scope decisions.

Avoid making separate deliverables out of every learning activity. A discussion, paired change, or existing team demo may provide all the evidence needed. Remove repeated checklists, generic encouragement, and requirements that don't serve this engineer's role.

## First week

Use the first manager conversation to explain the team's purpose, current priorities, and where this role fits. Discuss communication preferences, working hours, how to ask for help, and what to do when blocked. Walk through the plan together and change anything that doesn't fit.

The buddy should help the engineer get the system running and pair on real work. Choose something small enough to follow through implementation, testing, review, and release. Talk through the decisions as well as the mechanics.

Arrange a product walkthrough with someone who understands customer needs. Have the engineer try the product and join an existing customer-feedback or product-testing session when useful. Connect the code they'll work on to what customers are trying to accomplish.

Make a named introduction list covering immediate teammates and relevant product, design, customer-facing, platform, data, and operational partners. Explain why each connection matters. Spread introductions across the first month rather than filling the first week with calls.

## First 30 days

The focus is learning the product and codebase while contributing with support. Example milestones to adapt:

- Run the relevant system locally and trace a representative workflow through its main components, logs, and tests.
- Pair with the buddy on current priority work and follow a change through review and release.
- Start a shared assignment with a clear customer or operational purpose. Confirm its remaining scope against what has already shipped.
- Discuss one concrete improvement noticed while using the product or working in the codebase.
- Meet the people on the introduction list and learn what they own and when to involve them.

At the 30-day check-in, review what is working, what remains unclear, and what support is missing. Adjust the next phase for the actual progress and opportunities available. Access delays and missing documentation are problems for me to help resolve.

## Move from pairing to independent work

The manager and buddy should agree with the engineer on a small next piece of work. Readiness means they can run and test the relevant system, explain the change, identify its risks, and know when and where to ask for help. Adjust support based on the task rather than waiting for a calendar date.

For the first independent change, review the before-and-after behavior and relevant tests or evaluations. Before release, cover permissions, logging, rollout, and rollback where they apply. Consider performance or cost when the change affects them. Keep a clear route back to the buddy for support.

## First 60 days

The focus is contributing with increasing independence. Example milestones to adapt:

- Deliver a small change independently, with the buddy available for support.
- Explain how the change was verified and review the result with the relevant partners.
- Take responsibility for an agreed part of an existing project or system.
- Fill in a [career development plan](../templates/career-development-plan.md) and discuss growth interests in our 1:1.

Use the 60-day check-in to review the work and agree on the next scope of responsibility. Keep development goals in the organization's existing growth system rather than maintaining a duplicate onboarding version.

## Transfer ownership deliberately

When the engineer is taking over someone else's work, separate unfinished tasks from ongoing ownership. Review the current inventory together and agree on:

- What has shipped, what remains open, and what should be stopped or reassigned.
- The features or services included in the handoff and the boundaries that still need a decision.
- Maintenance, monitoring, production triage, and support expectations.
- Known risks, operational instructions, important partners, and outstanding decisions.
- The primary owner, backup, and where to escalate problems.

Keep the live inventory in the issue tracker. A list of inherited tickets is a starting point for discussion, not an automatic commitment to finish everything during onboarding. Confirm ownership with the people affected before treating the handoff as complete.

## First 90 days

The focus is delivering and owning the agreed work with appropriate support. This can build on the work started earlier; there is no need to invent a separate capstone project.

- Review a delivered change: what improved for customers or the team, how we verified it, and what still needs follow-up.
- Confirm ongoing ownership and backup coverage for the agreed areas.
- Update the relevant documentation with how the system works, common troubleshooting steps, and who can help.
- Share the work in an existing team meeting when useful, then agree on the next priorities.

Review the first 90 days together and revisit growth goals. Use the organization's existing review process if one applies. Otherwise, this is a conversation in our regular 1:1, not an additional reflection form or ceremony.

## Improve the next onboarding

Ask which setup steps were confusing, which links were missing, and what they wish someone had explained sooner. Fix the reusable instructions while the gaps are fresh. Remove onboarding-only meetings and access that are no longer needed, and carry ongoing work into the team's normal planning process.

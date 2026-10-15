# Project 4 — Process Improvement (Sample Project)

**Scenario:** Customer support ticket handling  
**Type:** Fictional portfolio exercise — no real organization or measured outcome is represented.

## 1. Business problem

Assume a support team receives requests through email and chat but does not use a consistent intake process. Tickets may be missing key details, priorities may be unclear, and requesters may not know the current status.

These are hypothetical pain points to investigate, not measured findings from a real company.

## 2. Objective

Design a more consistent workflow for capturing, prioritizing, assigning, and tracking support tickets.

## 3. Stakeholders

- Customer / requester
- Support agent
- Support team lead
- Service owner
- IT/system administrator

## 4. AS-IS process (hypothesis to validate)

1. Request arrives through an informal channel.
2. Agent manually collects missing information.
3. Priority and ownership may be assigned inconsistently.
4. Requester follows up for status.
5. Team lead manually reviews unresolved items.

Before proposing a real change, a BA should validate this flow through stakeholder interviews, process observation, and available ticket data.

## 5. Potential root causes to investigate

- No standard intake form or required fields
- No agreed priority definitions
- No explicit ownership or escalation rules
- Limited status visibility for requesters
- No consistent reporting on backlog and aging

These are hypotheses, not confirmed root causes.

## 6. Proposed TO-BE process

1. Capture the request through a standardized intake form.
2. Validate required information and categorize the request.
3. Apply agreed priority rules based on impact and urgency.
4. Assign the ticket to a responsible queue or owner.
5. Notify the requester of receipt and status changes.
6. Escalate tickets that breach agreed service targets.
7. Review backlog, aging, reopen rate, and service-level performance.

## 7. Requirements to consider

| ID | Proposed requirement | Acceptance idea |
|---|---|---|
| PR-01 | A ticket must capture category, description, requester, and impact information. | Incomplete tickets prompt the user to supply required fields. |
| PR-02 | Each submitted ticket must have an owner or queue. | The ticket record displays the assigned owner/queue. |
| PR-03 | The requester must be able to view ticket status. | The requester sees the latest permitted status. |
| PR-04 | Tickets approaching an agreed target should be flagged. | A test ticket meeting the configured condition appears in the escalation view. |
| PR-05 | Team leads should be able to review backlog and ticket aging. | A report groups open tickets by age, priority, and status. |

## 8. Success metrics to baseline

Do not set improvement claims until the current baseline and measurement rules are known.

- Median time to first response
- Median time to resolution
- Percentage of tickets resolved within the agreed service target
- Reopen rate
- Number and age of overdue tickets
- Percentage of tickets missing required information
- Requester satisfaction, if measured consistently

For each metric, define the period, population, exclusions, data source, and calculation method.

## 9. Risks and dependencies

- Inconsistent historical data can distort the baseline.
- Priority rules require business-owner agreement.
- Automation depends on tool capabilities and access permissions.
- New workflows may require training and change management.
- Reporting should respect data-access and privacy requirements.

## 10. Recommended next steps

1. Interview stakeholders and map the actual AS-IS process.
2. Review a representative sample of ticket data.
3. Validate root causes and quantify the baseline.
4. Agree the TO-BE workflow, roles, and service targets.
5. Create requirements and test scenarios.
6. Pilot the process, compare results against the baseline, and iterate.

**Status:** Fictional portfolio exercise. No real process change or performance improvement is claimed.

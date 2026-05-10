# Nora Denial Prevention Review

| Case ID | Root Cause | Operational Impact | Suggested Prevention Step |
|---|---|---|---|
| PA-002 | Clinical documentation was incomplete before authorization submission | Authorization cannot move forward, which creates delay and possible claim readiness risk | Add a documentation completeness check before authorization submission |
| PA-004 | Payer response tracking did not trigger escalation before the due date passed | Appointment readiness and patient communication may be affected | Use a response due date flag with same-day escalation rules |
| PA-005 | Insurance data was captured incorrectly during intake | Eligibility and authorization may be based on the wrong payer or member record | Add an insurance verification checkpoint before authorization review |
| PA-007 | Authorization approval was received but not documented in the tracker | Claim may be submitted without proof of authorization match | Require authorization number documentation before claim release |
| PA-008 | Patient demographic data was incomplete | Claim creation and downstream billing accuracy may be affected | Add required demographic field validation before claim creation |
| PA-010 | No escalation owner was assigned | Workflow ownership is unclear, increasing risk of missed authorization submission | Assign one escalation owner for every high-risk authorization case |

## Key Denial Prevention Pattern

The strongest denial prevention opportunity is upstream control. Most risk appears before the claim is created, especially during intake, eligibility verification, documentation review, authorization submission, payer response tracking, and handoff ownership.

## Recommended Prevention Controls

1. Required eligibility verification before authorization review.
2. Required documentation check before authorization submission.
3. Payer response due date tracking.
4. Escalation owner assignment for every delayed or incomplete case.
5. Authorization number documentation before claim readiness confirmation.
6. Claim readiness check before release.

## Nora Insight

Denial prevention should not begin after denial. It should begin when the workflow first shows signs of missing information, delayed response, or unclear ownership.

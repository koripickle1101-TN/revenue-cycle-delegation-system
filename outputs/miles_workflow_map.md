# Miles Workflow Map

## Prior Authorization Delay Prevention Workflow

| Step | Responsible Role | Input Needed | Output Produced | Failure Point | Prevention Control |
|---|---|---|---|---|---|
| Patient scheduled | Scheduling team | Appointment request and service type | Scheduled appointment | Service entered without authorization review | Add authorization requirement check to scheduling workflow |
| Insurance captured | Front office or intake staff | Payer name, member ID, demographics | Insurance record | Incorrect insurance or missing demographic data | Use required intake field validation |
| Eligibility verified | Eligibility staff | Insurance record and patient demographics | Eligibility confirmation | Eligibility not verified before authorization review | Require eligibility status before moving forward |
| Service reviewed for authorization requirement | Prior authorization staff | Service type, payer rules, eligibility status | Authorization requirement decision | Authorization requirement missed | Add payer requirement review checkpoint |
| Clinical documentation checked | Clinical documentation support or assigned reviewer | Notes, order, diagnosis, service details | Documentation readiness status | Missing or incomplete notes | Require documentation checklist before submission |
| Authorization submitted | Prior authorization staff | Complete payer requirement packet | Submitted authorization request | Submission delayed or incomplete | Require submission status and date field |
| Payer response tracked | Prior authorization staff | Submission date and payer response due date | Response status | Payer response overdue | Use due date tracking and escalation flag |
| Missing information escalated | Escalation owner | Missing item, due date, responsible party | Escalation action | No owner assigned | Require escalation owner for every high-risk case |
| Approval documented | Prior authorization staff | Approval response and authorization number | Documented authorization approval | Approval received but not recorded | Require authorization number before claim readiness |
| Claim readiness confirmed | Revenue cycle or billing support | Eligibility, authorization, documentation, approval record | Claim readiness status | Claim released without authorization match | Use final claim readiness checklist |

## Miles Insight

This workflow has the highest failure risk at handoff points. The strongest controls are not complicated. They are clear ownership, required fields, response due date tracking, and final claim readiness confirmation.

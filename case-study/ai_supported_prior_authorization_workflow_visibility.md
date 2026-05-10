# AI-Supported Prior Authorization Workflow Visibility

## Project Name

The Revenue Cycle Delegation System

## Created By

Kori Pickle  
BSHA Student | Healthcare Workflow Analysis | Revenue Cycle Operations

---

## Problem

Prior authorization delays create administrative pressure, patient frustration, and downstream claim risk. In many healthcare administration workflows, the problem is not only the volume of work. The deeper issue is that missing information, delayed payer responses, documentation gaps, and unclear handoffs are often discovered too late.

---

## Goal

Design a simple AI-supported workflow system that helps identify missing information, response delays, escalation gaps, and claim readiness risks before they become denials, delays, rework, or patient frustration.

---

## Tools Used

- Google Sheets
- ChatGPT
- GitHub
- LinkedIn
- Fictional sample data only

---

## Workflow Studied

Prior Authorization Delay Prevention

The workflow follows a basic administrative path:

1. Patient scheduled
2. Insurance captured
3. Eligibility verified
4. Service reviewed for authorization requirement
5. Clinical documentation checked
6. Authorization submitted
7. Payer response tracked
8. Missing information escalated
9. Approval documented
10. Claim readiness confirmed

---

## Method

This project used a fictional prior authorization tracker with 10 sample cases. Each case included payer type, service type, appointment date, authorization status, payer response due date, missing information, escalation owner, risk level, next action, and claim readiness status.

Three role-based AI assistants were then used to review the fictional workflow data:

| Assistant | Function |
|---|---|
| Vera | Prior authorization risk review |
| Nora | Denial prevention analysis |
| Miles | Workflow mapping and handoff analysis |

---

## Key Findings

Most risk appeared before claim submission.

The highest-risk points were:

- Missing payer requirements
- Incomplete clinical documentation
- Delayed payer responses
- Incorrect insurance information
- Approval not documented
- No escalation owner assigned
- Claim readiness confirmed too late

---

## Recommended Fix

Use a role-based AI delegation model to review workflow tracker data, flag cases by risk level, and produce next-action summaries for staff review.

This does not replace human judgment. It supports operational visibility by helping staff identify which cases need attention first.

---

## Professional Insight

AI should not replace healthcare staff. It should help make hidden workflow risk easier to see, prioritize, and prevent.

The biggest value is not random prompting. The value is structured delegation: giving each assistant a clear role, repeatable workflow, and defined output.

---

## Privacy and Compliance Note

This project uses fictional training data only. It does not contain real patient information, protected health information, or confidential organizational data.

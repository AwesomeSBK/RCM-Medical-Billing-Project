# Eligibility – Medical Billing

## Overview

Insurance eligibility verification is an important step in the Revenue Cycle Management (RCM) process. It helps confirm a patient's active insurance coverage and understand the patient's financial responsibility before services are provided.

This module demonstrates the eligibility verification workflow, insurance benefit verification, documentation, follow-up, and eligibility-related issue management.

---

## Eligibility Verification Workflow

1. Receive patient appointment or registration information
2. Identify the patient's insurance payer
3. Verify member information
4. Check insurance eligibility
5. Confirm coverage effective date
6. Verify plan status
7. Review benefits
8. Verify copay
9. Verify deductible
10. Verify coinsurance
11. Verify out-of-pocket responsibility
12. Check authorization requirements when applicable
13. Document verification results
14. Communicate issues to the appropriate team
15. Update the billing or practice management system

---

## Information Verified

During eligibility verification, the following information may be reviewed:

* Patient name
* Date of birth
* Member ID
* Group number
* Insurance payer
* Plan type
* Coverage status
* Effective date
* Termination date
* Copay
* Deductible
* Coinsurance
* Out-of-pocket maximum
* Remaining deductible
* Remaining out-of-pocket amount
* Primary care requirements
* Specialist benefits
* Referral requirements
* Prior authorization requirements
* In-network / out-of-network benefits

> All patient and insurance information used in this project is fictional and created for demonstration purposes.

---

## Eligibility Status

| Status                | Meaning                                |
| --------------------- | -------------------------------------- |
| Active                | Insurance coverage is currently active |
| Inactive              | Coverage is not currently active       |
| Terminated            | Coverage has ended                     |
| Pending               | Eligibility could not be confirmed     |
| Unable to Verify      | Payer system or information issue      |
| Incorrect Information | Member information does not match      |
| Coverage Not Found    | No matching coverage was located       |

---

## Sample Eligibility Verification Tracker

| Verification ID | Patient ID | Payer           | DOS        | Eligibility      | Plan Type | Copay | Deductible | Status             |
| --------------- | ---------- | --------------- | ---------- | ---------------- | --------- | ----: | ---------: | ------------------ |
| ELG001          | PT1001     | Alpha Health    | 02/10/2026 | Active           | PPO       |   $30 |     $1,500 | Verified           |
| ELG002          | PT1002     | Beta Insurance  | 02/11/2026 | Active           | HMO       |   $40 |     $1,000 | Verified           |
| ELG003          | PT1003     | Gamma Health    | 02/12/2026 | Inactive         | PPO       |     — |          — | Follow-up Required |
| ELG004          | PT1004     | Delta Insurance | 02/13/2026 | Active           | EPO       |   $25 |       $750 | Verified           |
| ELG005          | PT1005     | Omega Health    | 02/14/2026 | Unable to Verify | PPO       |     — |          — | Pending            |

*All data in this table is fictional.*

---

## Benefits Verification

### Copay

The fixed amount the patient may be required to pay for a covered service.

### Deductible

The amount the patient may need to pay before the insurance plan begins paying according to the plan's benefits.

### Coinsurance

The percentage of the allowed amount that may be the patient's responsibility after applicable deductible requirements.

### Out-of-Pocket Maximum

The maximum amount a patient may be responsible for paying toward covered services during the applicable plan period, subject to plan rules.

---

## Example Eligibility Analysis

### Scenario

A fictional patient has the following benefits:

* Insurance Status: Active
* Plan Type: PPO
* Specialist Copay: $40
* Annual Deductible: $1,500
* Deductible Met: $1,200
* Coinsurance: 20%
* Out-of-Pocket Maximum: $5,000
* Out-of-Pocket Amount Met: $2,100

### Analysis

The patient's insurance is active.

The deductible has not been completely satisfied, so the remaining deductible should be considered when reviewing the patient's expected financial responsibility.

The applicable copay, deductible, coinsurance, network status, and plan-specific benefit rules should be reviewed before determining the patient's final responsibility.

---

## Common Eligibility Issues

### 1. Inactive Coverage

The patient's insurance may have terminated or may not be active for the date of service.

### 2. Incorrect Member Information

A mismatch in member ID, date of birth, or patient name may prevent successful verification.

### 3. Coverage Effective Date Issue

Coverage may begin after the planned date of service.

### 4. Terminated Coverage

The insurance plan may have ended before the date of service.

### 5. Unable to Verify

The payer portal or eligibility system may be unavailable.

### 6. Multiple Insurance Plans

The patient may have more than one insurance plan, requiring coordination-of-benefits review.

### 7. Authorization Requirement

Certain services may require prior authorization according to the payer and plan.

### 8. Referral Requirement

Some plans may require a referral for certain specialist services.

---

## Eligibility Follow-Up Process

When eligibility cannot be verified:

1. Review the information entered.
2. Confirm the insurance payer.
3. Recheck member information.
4. Verify the date of service.
5. Check the payer portal or eligibility system again.
6. Contact the payer when necessary.
7. Document the verification attempt.
8. Update the account with the verification result.
9. Escalate unresolved issues when required.

---

## Eligibility KPIs

Important eligibility metrics include:

* Eligibility verification rate
* Successful verification rate
* Unable-to-verify rate
* Inactive coverage rate
* Eligibility error rate
* Average verification turnaround time
* Number of accounts requiring follow-up
* Number of eligibility-related claim rejections

---

## Impact on Revenue Cycle Management

Effective eligibility verification can help:

* Reduce eligibility-related claim rejections
* Identify inactive coverage before billing
* Improve clean claim submission
* Reduce avoidable patient billing issues
* Improve front-end revenue cycle performance
* Reduce AR caused by incorrect insurance information
* Improve patient financial communication

---

## Objective

The objective of eligibility verification is to confirm active insurance coverage, accurately identify applicable benefits, document the patient's potential financial responsibility, and reduce preventable claim issues before services are billed.

---

## Data Privacy

This GitHub project uses fictional data for educational and portfolio purposes.

Never upload real patient information, member IDs, dates of birth, insurance credentials, passwords, or confidential employer information to a public repository.


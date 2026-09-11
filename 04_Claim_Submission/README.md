# Claim Submission – Medical Billing

## Overview

Claim submission is a critical part of the Revenue Cycle Management process. It involves preparing accurate claims, validating claim information, submitting claims through an electronic gateway or clearinghouse, monitoring claim acceptance or rejection, correcting errors, and resubmitting claims when required.

This module demonstrates an end-to-end claim submission workflow.

---

## Claim Submission Workflow

1. Verify patient demographics
2. Verify insurance information
3. Confirm patient eligibility
4. Review provider information
5. Verify NPI and taxonomy information
6. Review diagnosis codes
7. Review procedure codes
8. Verify modifiers when applicable
9. Enter charges
10. Review units and billed amounts
11. Verify place of service
12. Check authorization requirements
13. Scrub the claim
14. Submit claim electronically
15. Monitor gateway/clearinghouse response
16. Review accepted or rejected status
17. Correct rejected claims
18. Resubmit corrected claims
19. Monitor payer claim status
20. Track payment or denial

---

## Pre-Submission Validation

Before submitting a claim, the following information should be reviewed:

### Patient Information

* Patient name
* Date of birth
* Member ID
* Group number
* Address
* Insurance information

### Provider Information

* Provider name
* NPI
* Taxonomy
* Tax ID
* Billing provider
* Rendering provider
* Service location

### Claim Information

* Date of service
* Place of service
* Diagnosis codes
* Procedure codes
* Modifiers
* Units
* Charges
* Authorization information when applicable

---

## Claim Scrubbing

Claim scrubbing is the process of checking a claim for potential errors before submission.

### Common Scrubbing Checks

* Missing patient information
* Invalid member ID
* Invalid provider information
* Invalid diagnosis code
* Invalid procedure code
* Missing modifier
* Incorrect place of service
* Missing authorization
* Incorrect payer information
* Duplicate claim
* Invalid billing configuration

The purpose of claim scrubbing is to identify and correct preventable errors before the claim reaches the payer.

---

## Electronic Claim Submission

A typical electronic claim workflow is:

```text
Patient/Provider Information
          ↓
      Charge Entry
          ↓
    Claim Creation
          ↓
     Claim Scrubbing
          ↓
Electronic Gateway /
     Clearinghouse
          ↓
   Payer Acceptance
          ↓
     Claim Adjudication
          ↓
   Payment / Denial
```

---

## Claim Status

| Status          | Description                              |
| --------------- | ---------------------------------------- |
| Draft           | Claim is being prepared                  |
| Ready to Submit | Claim passed internal review             |
| Submitted       | Claim sent electronically                |
| Accepted        | Gateway/clearinghouse accepted the claim |
| Rejected        | Claim failed an electronic validation    |
| Pending         | Claim is awaiting further processing     |
| Paid            | Claim has been processed and paid        |
| Denied          | Payer denied the claim                   |
| Corrected       | Claim was corrected and resubmitted      |

---

## Sample Claim Submission Tracker

| Claim ID | DOS        | Payer           | Billed Amount | Submission Date | Gateway Status | Payer Status |
| -------- | ---------- | --------------- | ------------: | --------------- | -------------- | ------------ |
| CLM001   | 02/01/2026 | Alpha Health    |        $1,250 | 02/02/2026      | Accepted       | Pending      |
| CLM002   | 02/02/2026 | Beta Insurance  |          $850 | 02/03/2026      | Rejected       | —            |
| CLM003   | 02/03/2026 | Gamma Health    |        $2,100 | 02/04/2026      | Accepted       | Paid         |
| CLM004   | 02/04/2026 | Delta Insurance |          $975 | 02/05/2026      | Accepted       | Denied       |

*All data is fictional and created for portfolio demonstration.*

---

## Claim Rejection Management

When a claim is rejected:

1. Review the rejection message.
2. Identify the rejection reason.
3. Determine whether the issue is demographic, coding, provider, payer, or claim-related.
4. Correct the claim.
5. Revalidate the claim.
6. Resubmit the corrected claim.
7. Document the correction.
8. Monitor the new submission.

---

## Common Claim Rejection Reasons

### Patient Information

* Incorrect member ID
* Name mismatch
* Date-of-birth mismatch
* Missing demographic information

### Insurance

* Incorrect payer
* Inactive coverage
* Invalid group number
* Coverage information mismatch

### Provider

* Invalid NPI
* Incorrect billing provider
* Incorrect rendering provider
* Provider enrollment issue

### Coding

* Invalid diagnosis code
* Invalid procedure code
* Incorrect modifier
* Incorrect units

### Authorization

* Missing authorization
* Invalid authorization
* Authorization does not match the service

---

## Corrected Claim Workflow

```text
Rejected Claim
      ↓
Review Rejection
      ↓
Identify Root Cause
      ↓
Correct Claim
      ↓
Validate Claim
      ↓
Resubmit
      ↓
Monitor Status
      ↓
Payment / Further Action
```

---

## Claim Submission KPIs

Important metrics include:

* Total claims submitted
* Claims accepted
* Claims rejected
* Rejection rate
* Clean claim rate
* First-pass acceptance rate
* Average submission turnaround time
* Corrected claims
* Resubmission rate
* Claims pending
* Claims paid
* Claims denied

---

## Objective

The objective of claim submission management is to submit accurate claims, maximize first-pass acceptance, reduce preventable rejections, accelerate reimbursement, and minimize avoidable AR.

---

## Data Privacy

This project uses fictional data for educational and portfolio purposes.

Do not upload real patient information, member IDs, provider credentials, payer credentials, passwords, or confidential employer information to a public GitHub repository.


# Healthcare Decision Validation Layer

## Purpose
Ensure every important decision made by the discovery, business, workflow, content, design, technology, migration, compliance, and QA agents is evidence-aware, traceable, appropriately risk-assessed, and routed for approval when necessary.

## Core principles
1. Separate facts, customer-confirmed requirements, general patterns, assumptions, unknowns, jurisdiction-dependent requirements, and expert-review-required items.
2. Never treat model confidence as factual evidence.
3. Ask clarification questions when missing information materially affects scope, safety, cost, functionality, compliance, or reversibility.
4. Allow autonomous decisions only within explicitly approved boundaries.
5. Escalate high-impact, unsafe, contradictory, or insufficiently evidenced decisions.
6. Preserve a traceable record of significant decisions and their supporting evidence.
7. Revalidate decisions when requirements, evidence, architecture, or constraints change.

## Inputs
- Customer goals and requirements
- Website audit and migration findings
- Industry intelligence
- Workflow definitions
- Technical documentation and integration evidence
- Compliance and security assessments
- Budget, deadline, brand, and platform constraints
- Previous decisions and approvals

## Outputs
- Structured decision records
- Clarification questions
- Recommendations with explicit trade-offs
- Risk and impact classifications
- Approval requests
- Blocked decisions and reasons
- Validation and traceability records

## Decision statuses
proposed, needs_clarification, evidence_pending, recommended, awaiting_customer_approval, awaiting_expert_review, approved, rejected, blocked, implemented, validated, superseded.

## Mandatory stop conditions
Pause the affected decision when:
- A critical requirement is unknown or contradictory.
- A proposed action could expose sensitive health information.
- An integration capability has not been verified.
- A clinical, legal, regulatory, or security determination requires qualified review.
- A production change exceeds its approved scope.
- A required approval is missing.

## Important boundary
An agent can prepare evidence and recommendations for a reviewer. It cannot manufacture customer approval, legal confirmation, clinical authorization, or security sign-off.

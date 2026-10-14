
# Healthcare Workflow Intelligence

## Purpose
Enable AI agents to understand, discover, model, validate, and translate healthcare business workflows into website journeys and digital functionality.

## Definition
A workflow is a structured sequence of actions and decisions performed by people, systems, or organizations to achieve an outcome.

## Workflow knowledge must include
- Business objective
- Trigger
- Actors
- Preconditions
- Required inputs
- Sequence of steps
- Decision points
- System interactions
- Business rules
- Exceptions
- Outcome
- Human approvals
- Privacy and safety concerns
- Evidence and validation status

## Knowledge categories
1. Industry workflow pattern
2. Customer-confirmed workflow
3. Customer-specific exception
4. Regulatory or policy constraint
5. Technical implementation detail
6. Unknown requiring discovery

## Agent responsibilities

Discovery Agent:
Identify applicable workflows and ask targeted questions.

Understanding Agent:
Map business rules, actors, decisions, exceptions, and dependencies.

UX Agent:
Convert validated workflows into user journeys, forms, states, navigation, and interfaces.

Content Agent:
Create accurate instructions, labels, confirmation messages, and supporting content.

Development Agent:
Implement only approved workflow rules and integrations.

QA Agent:
Test successful, failed, exceptional, and unauthorized paths.

## Mandatory constraints
- Never assume an industry workflow is the customer's actual workflow.
- Never invent clinical protocols or patient eligibility rules.
- Never invent appointment availability.
- Never invent payment, insurance, or referral requirements.
- Never implement clinical decisions from generic examples.
- Require appropriate review for patient safety, regulated, or privacy-sensitive workflows.
- Record unknowns before implementation.


# Layer 03 — Users & Journeys

Version: 1.0-draft
Status: Proposed
Purpose: Convert business discovery findings into evidence-aware user models, tasks, and end-to-end journeys.

## 1. Objective

Identify the people a website serves, understand their goals and needs, map how they accomplish tasks, identify friction, and establish evidence-based opportunities for experience improvement.

## 2. Core principle

Design around verified user needs and business context, not assumed personas, generic UX patterns, or a customer's preferred solution alone.

## 3. Responsibilities

- Identify relevant user groups and distinguish confirmed groups from hypotheses.
- Understand user goals, motivations, tasks, and barriers.
- Build evidence-aware persona or user-group profiles.
- Map current-state and proposed future-state journeys separately.
- Identify task steps, decisions, branches, failures, and recovery paths.
- Record friction points and their evidence.
- Consider accessibility, inclusion, different devices, and different levels of digital confidence.
- Prioritize journeys using business value, user impact, risk, evidence, and dependencies.
- Produce structured outputs that downstream design and implementation agents can use.

## 4. Out of scope

This layer does not independently:
- Approve business requirements.
- Invent user research findings, interviews, analytics, or customer behavior.
- Decide the final visual design.
- Guarantee accessibility compliance.
- Assume a capability exists because it appears in a proposed journey.
- Authorize collection of sensitive personal information.
- Determine legal or clinical requirements without authoritative evidence and appropriate review.

## 5. Evidence classification

Every material statement must be classified where applicable as:
- customer_confirmed
- directly_observed
- research_supported
- analytics_supported
- authoritative_source_supported
- inferred_hypothesis
- generic_pattern
- unknown
- conflicting

Record the source, date, scope, confidence rationale, and limitations when available.

Model confidence alone is not evidence.

## 6. Journey distinctions

Keep these separate:
- current_state: what users do today, supported by evidence.
- proposed_future_state: a suggested experience that has not necessarily been implemented.
- validated_future_state: a proposed experience tested against stated acceptance criteria.
- implemented_state: what has actually been built.
- tested_state: what has been verified through recorded tests.

Do not describe a proposed journey as existing functionality.

## 7. Required outputs

- User group inventory
- User goals and needs
- Persona or user-group profiles with evidence labels
- Task models
- Current-state journeys, when evidence is available
- Proposed future-state journeys
- Pain points and opportunities
- Accessibility and inclusion considerations
- Prioritized journeys
- Open questions and assumptions
- Traceability to business objectives and requirements
- Validation criteria

## 8. Dependencies

Upstream:
- 01-website-foundation
- 02-business-discovery

Downstream:
- Information architecture
- Content strategy
- UX and interaction design
- Functional requirements
- Accessibility evaluation
- Testing and validation
- Analytics and optimization

## 9. Completion principle

A journey can be ready for design when its goal, actors, steps, decision points, required capabilities, evidence limitations, and acceptance criteria are sufficiently understood for the next activity.

Readiness for design does not mean the journey is approved for implementation, legally validated, accessible by default, or proven to improve business outcomes.

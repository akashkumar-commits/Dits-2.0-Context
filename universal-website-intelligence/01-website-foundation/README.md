
# Layer 01 — Website Foundation

## Purpose

This layer provides foundational, industry-independent website knowledge for the DITS 2.0 autonomous website platform.

It supports website creation, redesign, revamping, migration, maintenance, and optimization.

The knowledge is intended to support AI agents in understanding website categories, business purposes, capabilities, lifecycle stages, and classification decisions.

## Core responsibilities

1. Identify the customer's website objective.
2. Classify the website using evidence.
3. Identify likely website capabilities without treating them as confirmed requirements.
4. Understand whether the project involves a new website, redesign, rebuild, migration, or optimization.
5. Establish the minimum website context needed for downstream decisions.
6. Identify unknown information and clarification questions.
7. Prevent unsupported assumptions from being promoted into facts.

## Knowledge boundaries

This layer does not:
- Determine customer-specific workflows.
- Guarantee regulatory compliance.
- Select a final technology stack.
- Define a complete sitemap.
- Invent customer services, products, or integrations.
- Assume website features are required merely because they are common in an industry.
- Authorize production changes.

These decisions require additional universal layers, relevant industry knowledge, customer evidence, and approval rules.

## Primary consumers

- Discovery Agent
- Business Understanding Agent
- Website Analysis Agent
- Planning Agent
- UX/UI Agent
- Content Agent
- Technology Agent
- Migration Agent
- QA Agent

## Classification principles

A website may have multiple purposes and capabilities.

Website type, business model, industry, project type, and implementation technology are separate dimensions.

A business may operate multiple websites with different purposes.

Classification must distinguish confirmed facts, supported inferences, hypotheses, and unknowns.

## Evidence precedence

For customer-specific facts, prioritize:
1. Verified customer-approved requirements and system evidence.
2. Direct observations from the existing website and connected systems.
3. Customer statements awaiting verification.
4. Relevant industry intelligence and general website patterns.
5. Unverified hypotheses.

Higher-priority evidence does not override applicable legal, security, or safety requirements.

Conflicts must be escalated or resolved through the decision-governance layer.

## Dependencies

- Universal Layer 02: Business Discovery
- Universal Layer 03: Users and Journeys
- Universal Layer 04: Information Architecture
- Universal Layer 07: Website Functionality
- Universal Layer 08: Technology Architecture
- Universal Layer 14: Decision Governance
- Applicable Industry Intelligence
- Customer Project Context

## Output

The expected output is a structured Website Foundation Context containing:
- Website classification
- Business purpose
- Project intent
- Known website capabilities
- Potential capabilities requiring confirmation
- Constraints
- Evidence references
- Unknowns
- Clarification questions
- Preliminary risks

## Validation

Evaluate the layer against the tests in evaluation-tests/website-foundation-tests.json.

Passing static knowledge tests does not prove that an LLM will apply the knowledge correctly. Runtime tests are required.

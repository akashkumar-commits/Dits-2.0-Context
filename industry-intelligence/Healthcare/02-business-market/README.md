
# Healthcare Business and Market Intelligence

Version: 0.1.0
Status: Initial knowledge package
Scope: Global healthcare business patterns; market and regulatory differences must be validated by region.

## 1. Purpose

This package helps DITS 2.0 understand the commercial and organizational context of healthcare businesses.

It supports decisions about:
- Customer business models and value propositions
- Target audiences and purchasing stakeholders
- Service delivery and revenue models
- Market dynamics and competitive positioning
- Business goals and success metrics
- Website and digital-platform capabilities that may support those goals

## 2. Package contents

- `healthcare-business-models.json`: Business types and value creation.
- `stakeholder-ecosystem.json`: Stakeholders, responsibilities, and relationships.
- `revenue-and-service-models.json`: Funding, payment, and service delivery patterns.
- `market-dynamics.json`: Market drivers and competitive factors.
- `business-goals-and-kpis.json`: Business objectives and measurable outcomes.
- `sources/source-registry.json`: Evidence sources.
- `evaluation-tests/02-business-market-tests.json`: Evaluation cases.

## 3. Usage by DITS agents

### Discovery agent
Identify the organization's business model, customer groups, service offering, operating regions, and primary business priorities.

### Understanding agent
Connect business goals to the organization's actual services, workflows, and operating constraints.

### UX agent
Identify the audiences, their tasks, and the journeys that support the business goals.

### Content and SEO agent
Determine which services, audiences, locations, and business claims need clear and accurate representation.

### Architecture and migration agents
Identify the business-critical capabilities, integrations, and constraints that must be preserved or implemented.

### Validation agent
Check that proposed capabilities support confirmed business goals and that assumptions remain explicit.

## 4. Decision rules

1. Do not infer a customer's revenue model from its segment alone.
2. Distinguish the person receiving a service from the person paying for it.
3. Distinguish the service provider from the platform facilitating the service.
4. Treat business models as potentially mixed or changing.
5. Do not assume every business goal is primarily revenue growth.
6. Confirm how success is measured before recommending optimization.
7. Record evidence, assumptions, unknowns, and customer decisions separately.
8. Do not publish market statistics without a traceable source and reference period.

## 5. Relationship to other layers

This package explains the business and market context.

Use:
- `01-industry-foundation/` for industry definitions and segment classification.
- `03-users-personas/` for user roles, needs, and behaviors.
- `04-workflows/` for operational processes and decision points.
- `05-digital-experience/` for website and product experience patterns.
- `06-content-seo/` for content, search visibility, and information architecture.
- `07-technology-integrations/` for systems and technical dependencies.
- `08-compliance-security/` for jurisdiction-specific legal and security requirements.
- `09-decision-validation/` for evidence and decision controls.
- `10-performance-optimization/` for measurement and continuous improvement.

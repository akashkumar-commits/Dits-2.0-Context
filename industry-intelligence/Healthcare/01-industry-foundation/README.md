
# Healthcare Industry Foundation

Version: 0.1.0  
Status: Initial foundation  
Scope: Global healthcare industry patterns, with jurisdiction-specific requirements maintained separately  
Intended consumers: DITS 2.0 intelligence, discovery, content, UX, architecture, migration, QA, and validation agents

## 1. Purpose

This package provides the foundational knowledge required to interpret a customer's healthcare business before creating, redesigning, migrating, or improving its website.

It defines:
- Healthcare industry structure and common stakeholders.
- Seven healthcare business segments and their distinguishing characteristics.
- Shared terminology and definitions.
- Business classification rules for customer discovery.
- Boundaries between established knowledge, assumptions, and customer-specific facts.
- Authoritative sources for further research and verification.

## 2. Supported segments

1. Hospitals and clinics
2. Diagnostic laboratories
3. Telehealth providers
4. Healthcare marketplaces
5. Remote patient monitoring (RPM)
6. Behavioral health services
7. Medical devices and diagnostics technology

A business may belong to more than one segment. Classification must support a primary segment, secondary segments, and mixed or uncertain cases.

## 3. How agents should use this package

1. Read `industry-overview.md` to understand the shared healthcare context.
2. Read `healthcare-segments.json` to identify relevant business models.
3. Use `healthcare-glossary.json` to normalize industry terminology.
4. Apply `industry-classification-rules.json` during discovery.
5. Apply `knowledge-boundaries.md` before making recommendations or generating outputs.
6. Use `sources/source-registry.json` to find authoritative evidence.
7. Retrieve more specific workflow, UX, content, technology, and compliance knowledge from the corresponding healthcare folders.

## 4. Knowledge labels

Every material conclusion should be identified as one of the following:

- `general_pattern`: Common in the industry, but not guaranteed for a particular business.
- `source_supported`: Supported by a cited source within its stated scope.
- `customer_confirmed`: Explicitly confirmed by the customer or an authorized representative.
- `assumption`: A temporary inference that requires validation.
- `unknown`: Insufficient information is available.
- `jurisdiction_dependent`: Depends on applicable law, regulation, location, or regulator.
- `expert_review_required`: Requires review by an appropriately qualified person.

These labels are not interchangeable. A common industry practice is not proof of a customer's actual process.

## 5. Operating principles

- Do not assume that every healthcare website handles patient data.
- Do not assume that every healthcare business is subject to the same laws.
- Do not invent clinical workflows, medical claims, credentials, certifications, integrations, or service availability.
- Distinguish informational websites from systems that process patient or clinical information.
- Treat patient-facing actions and clinical decision-making as higher risk than ordinary content presentation.
- Identify the intended audience and business objective before proposing features.
- Confirm integrations, authentication, data flows, and system ownership with the customer.
- Request human approval for material, high-risk, or uncertain decisions.

## 6. Relationship to other knowledge packages

This package describes the industry foundation only. Detailed knowledge belongs in the corresponding areas:

- Business models and market context: `02-business-market/`
- Personas and audiences: `03-users-personas/`
- Business and clinical workflows: `04-workflows/`
- Website and digital experience: `05-digital-experience/`
- Content, SEO, and discoverability: `06-content-seo/`
- Technology and integrations: `07-technology-integrations/`
- Compliance and security: `08-compliance-security/`
- Decisions, evidence, and validation: `09-decision-validation/`
- Analytics, performance, and continuous improvement: `10-performance-optimization/`

## 7. Maintenance

Each new material claim should have a traceable source or an explicit knowledge label. Record the source date, geographic scope, limitations, and verification status where applicable.

Review external sources periodically. Revalidate regulatory, technical, and clinical information before using it in a live customer project.

## 8. Versioning

Use semantic versioning:
- MAJOR: Changes to the package structure or meaning that may break downstream consumers.
- MINOR: New segments, definitions, rules, or substantive knowledge.
- PATCH: Corrections, clarifications, and metadata updates.

Current version: `0.1.0`

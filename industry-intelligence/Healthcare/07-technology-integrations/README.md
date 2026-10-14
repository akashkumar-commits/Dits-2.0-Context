
# Healthcare Technology and Integrations

## Purpose
Enable DITS 2.0 agents to discover, evaluate, plan,
implement, and validate healthcare website technology
and integration requirements.

## Scope
- Healthcare system landscape
- Existing technology discovery
- Website architecture
- API and integration patterns
- Data ownership and system boundaries
- Authentication and authorization
- Content management systems
- Technology migration and modernization
- Technical decision validation

## Required inputs
- Customer business objectives
- Website scope
- Existing website technology
- Existing connected systems
- Confirmed workflows
- Data classification
- Integration documentation
- Authentication requirements
- Hosting and deployment constraints
- Applicable security and regulatory requirements

## Required outputs
- Current system inventory
- Proposed website architecture
- Integration inventory
- Data flow map
- System-of-record mapping
- Authentication and authorization requirements
- CMS recommendation
- Migration strategy
- Technical risks
- Dependencies and unknowns
- Approval requirements

## Mandatory rules
1. Do not invent APIs or integration capabilities.
2. Do not assume an EHR or EMR is directly accessible.
3. Do not assume a website stores patient records.
4. Do not expose sensitive information through public APIs.
5. Do not generate or store production credentials
   inside the knowledge repository.
6. Do not assume one technology stack fits every customer.
7. Preserve required integrations during migration.
8. Require security review for sensitive data flows.
9. Require customer approval before replacing systems.
10. Validate technical behavior through actual testing.

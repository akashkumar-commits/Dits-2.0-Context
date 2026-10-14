
# Healthcare Performance Optimization Layer

## Purpose
Measure, monitor, diagnose, and improve healthcare websites and the agents that build and maintain them.

This layer applies to:
- New website launches
- Website redesigns
- Website migrations
- CMS and frontend modernization
- Website content and SEO improvements
- Conversion and workflow improvements
- Ongoing website maintenance

## Inputs
- Customer-confirmed business goals
- Approved KPIs and target values
- Pre-launch and post-launch measurements
- Website analytics and search performance data
- Real-user and synthetic performance measurements
- Accessibility and functional test results
- Migration and redirect validation
- Customer feedback and support issues
- Agent execution logs and evaluation results

## Outputs
- KPI dashboards and performance reports
- Detected anomalies and alerts
- Prioritized improvement opportunities
- Root-cause hypotheses with supporting evidence
- Proposed or authorized optimization changes
- Experiment plans and results
- Regression test results
- Updated decision records and improvement history

## Mandatory rules
1. Establish a baseline before claiming improvement.
2. Record the measurement method, time window, sample size where relevant, and data limitations.
3. Separate measured observations from hypotheses about their causes.
4. Do not invent KPIs, analytics data, conversion rates, or search rankings.
5. Do not guarantee search rankings, traffic, conversions, or business outcomes.
6. Do not expose protected health information through analytics, logs, dashboards, or experiments.
7. Require authorization for production changes and validate important changes before release.
8. Recheck accessibility, security, critical workflows, and migration integrity after relevant changes.
9. Treat missing telemetry as an unknown—not evidence of good performance.
10. Preserve a history of changes, measurements, and outcomes.

## Measurement states
not_configured, baseline_pending, collecting_data, insufficient_data, measured, anomaly_detected, improvement_verified, regression_detected.

## Ownership
The customer defines business priorities and acceptable outcomes. Technical owners govern production changes. Designated privacy, security, accessibility, or clinical reviewers handle matters requiring their expertise. Agents support measurement and execution within approved boundaries.

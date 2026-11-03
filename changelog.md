# Changelog: Personal Context Portfolio

All notable changes to this Personal Context Portfolio are documented here. This file provides transparency and version awareness when the portfolio is shared with AI agents over time.

The format follows a lightweight semantic versioning approach:

- **MAJOR:** Significant role, purpose, or scope changes
- **MINOR:** New preferences, tooling, domains, goals, or working patterns
- **PATCH:** Wording, clarity, formatting, or small corrections

## [1.4.0] - 2026-11-03

### Added

- New "Code and Documentation Style" section: generous plain-language comments written for non-technical readers, section banners, source attribution for borrowed code, no AI self-attribution, code quality basics, and a rule against secrets in comments or code
- New "Azure DevOps Working Defaults" section capturing standing personal defaults: delivery project, area and iteration paths, Product field, assignee, story point cap of 5, one child Task per PBI, default Sustaining Group parents, Unplanned Work conventions, protected Description and Acceptance Criteria on updates with Discussion used instead, plain-language work item text, work item required on every pull request, and process hygiene including operations logs and the SDLC Artifact Library reminder
- Added guardrail that AI-assisted work must always be attributable and auditable rather than anonymous
- Expanded the TLDR so agents pick up the comment style and Azure DevOps defaults at a glance

## [1.3.0] - 2026-11-03

### Added

- Detailed hands-on and iterative working style
- Agent collaboration pattern for troubleshooting and design discussions
- Guidance for adapting responses to engineers, managers, architects, leadership, and end users
- Expanded enterprise AI, MCP, capability platform, Freshservice, AWS, and agent governance context
- Security and architecture guardrails covering identity, authorization, credentials, supply chain risk, auditability, and component ownership
- Troubleshooting expectations focused on likely root cause, targeted validation, expected results, and final documentation
- Common AI use cases, including repository review, work items, prompts, pull requests, leadership communication, and long-running project context
- Context boundaries separating durable preferences from project-specific or confidential information

### Changed

- Corrected Markdown formatting and field spacing throughout `personal-context.md`
- Refined TLDR guidance so it is used when helpful rather than forced onto every short response
- Clarified when to provide the next troubleshooting step versus a complete runbook
- Expanded professional focus from Microsoft 365 administration to collaboration, productivity, governance, automation, and enterprise AI enablement
- Updated the handshake to distinguish portfolio guidance from higher-priority policies and constraints
- Expanded the README with file descriptions, suggested use, and design principles

## [1.2.0] - Date not recorded

### Added

- Expanded communication preferences
- TLDR placement guidance
- Step-by-step delivery preferences
- Link handling preferences
- AI behavior expectations
- Durable preferences

## [1.0.0] - 2026-04-28

### Added

- Initial Personal Context Portfolio
- Professional identity and role context
- Core domains of expertise
- Working style and communication preferences
- Tooling preferences and guardrails
- Constraints and governance expectations
- Durable preferences for long-term alignment

## Future Considerations

- Separate durable personal context from reusable project-context templates
- Add a machine-ingestible JSON or YAML representation
- Add an optional context sensitivity or sharing classification
- Review the portfolio when role, responsibilities, or preferred tools change

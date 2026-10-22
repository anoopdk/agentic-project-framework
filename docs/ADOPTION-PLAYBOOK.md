# Reproduce the framework into a project — AI adoption playbook

**READ FIRST:** [AGENTS.md](../AGENTS.md), [policies](../policies/), [router contract](../router/ROUTING-CONTRACT.md). This is a **proposal process**, never implicit authority to alter the destination.

## Outcome

Prepare a bespoke, **human-approved** framework adoption tailored to a target project. Do not blindly copy this repository or impose missing framework parts on an existing system.

## Input discovery (read-only)

Inspect, when permitted:
- Repository layout, README, existing `AGENTS.md`, `CLAUDE.md`, coding instructions and CI.
- Actual application and data stacks, dependency management, deployment method, environment separation.
- Source data contracts, pipelines, modelling, data quality, privacy, access grants, observability.
- Existing architecture decisions, naming conventions, tests and known project constraints.

Give a compact evidence inventory: `verified (file/path)`, `inferred (why)`, `unknown (question)`. Never pretend to have inspected inaccessible infrastructure, secret stores or live systems.

## Brownfield / existing project

1. Inventory current facts and existing authorities **without modifying** the project.
2. Compare actual patterns against applicable standards; **do not presume generic standards trump approved project conventions**.
3. Identify gaps, incompatibilities, duplicate instructions and documentation conflicts.
4. Propose the **minimum viable set of additions**, ideally short `AGENTS.md`, references to external framework, and only relevant project-specific adjustments.
5. Offer migration options: reference external framework; vendor selected policies/standards; or full local mirror when offline needs justify it. State update/maintenance trade-offs.
6. List exact files to add/update, material risks, conflicts, test method and rollback approach.
7. Ask the human to select and **approve the specific adoption plan**.
8. Only then implement approved adaptations. No destructive refactors, restructuring or overwrites unless separately authorised.
9. Check links, references, rule conflicts and actual scope of changes. Seek human acceptance.

## Greenfield / new project

1. Clarify outcome, users, data sensitivity, expected sources, scale, stack constraints and deployment governance.
2. Present architectural options rather than automatically selecting vendors, layering or modelling style.
3. Propose minimum conventions and what standards apply.
4. Offer a lean foundation, e.g. `README.md`, `AGENTS.md`, `src/`, `tests/` and **only needed** design artifacts; not mandatory folder proliferation.
5. Present precise scaffold plan and wait for approval before creating anything.
6. Implement only the approved scaffold; verify files, links and guardrails; request acceptance.
7. Subsequent feature requests repeat the same human-led workflow.

## Minimum adoption proposal template

**Target and mode:** <repository> / brownfield or greenfield  
**Verified findings:** <paths and evidence>  
**Unknowns requiring decisions:** <prioritised questions>  
**Applicable standards:** <IDs and rationale>  
**Viable approaches:** <options + trade-offs + recommendation>  
**Selected by human:** <explicit decisions only>  
**Proposed changes:** <exact additions/edits and exclusions>  
**Risks and security considerations:** <including sensitive data>  
**Test/acceptance criteria:** <observable evidence>  
**Actions needing separate approval:** <production/deploy/grants/destructive work>  
**Approval status:** AWAITING_APPROVAL (until affirmative approval given)

## Compatibility checklist

- Are policy instructions visible to the chosen coding tool? If not, propose an adapter or explicit reference.
- Are skills actually implemented and installed for that tool? If not, do not invoke as operational commands.
- Is a standards index accessible and applicable?
- Are human approval gates backed by available tool permissions? If not, disclose that runtime enforcement is procedural.
- Do project and framework instructions conflict? Escalate material conflicts to the human.
- Are data source credentials needed? Never request actual secrets in chat or in repository files; use the project's secure provisioning process.

## Adoption walkthroughs

For a concrete source-change scenario see [Workday example](../examples/workday-change.md). Framework phase is **design baseline**; this playbook is written to enable another AI to propose reproduction, not independently execute it.

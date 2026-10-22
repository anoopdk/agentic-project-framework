# AI agent entrypoint — mandatory

This repository defines a **framework design**. You may use it to *propose* adoption into a target repository. **It does not provide blanket permission to edit a target project.**

## Priority of conduct
1. Protect people, data, secrets and environments. Never hard-code credentials or put secrets into responses, source, fixtures or logs.
2. Human decisions and **explicit, plan-specific approval** are mandatory before any target-project write.
3. First inspect permitted code and documentation read-only; distinguish **verified evidence**, **inference** and **unknowns**.
4. Ask material clarifying questions; do not guess business rules, access grants, data semantics, deployment targets, or architecture.
5. Explain feasible options and trade-offs, indicate a recommendation **without deciding for the human**.
6. Summarise agreed scope, selected options, affected files/components, risks, test criteria and boundaries; **stop until the human says go ahead to that plan**.
7. Implement only inside approved boundaries. Pause and ask again if a material surprise changes the plan. Separate approval is required for deployments, destructive operations or production access.
8. Validate what actually happened. Do not claim unexecuted tests passed. Human accepts or requests revision.
9. Record durable truth only where it belongs; never turn this into a task/change register.

**A request such as “add Workday” authorises investigation and proposal, not immediate implementation.** Approval to prepare a plan is not approval to build; approval to build is not approval to deploy or merge.

## Read these before acting
- `policies/human-authority.md`
- `policies/approval-gates.md`
- `policies/secure-execution.md`
- `router/ROUTING-CONTRACT.md`
- `docs/ADOPTION-PLAYBOOK.md`
- `standards/index.yaml`

Skill folders intentionally contain design placeholders. Never represent them as operational code or automatically executable skills.

## When pointed at an external project
Produce an **adoption proposal**, not immediate edits. Show findings, gaps, competing source-of-truth files, proposed additions and minimal modifications. Reuse existing documents where possible. Ask for approval before writing.

# Data Engineering standards — design inventory

This is a **guidance catalogue**, not a ticketing system and not a mandatory technology stack. The initial index identifies the domains a future standards resolver must load. Detailed standard rulebooks (IDs, exceptions and testable acceptance rules) will be authored and reviewed in a later phase.

Each future standard rule should define:
- **Principle**: why it matters.
- **Default**: recommended pattern.
- **Applicability**: triggers, workflows and affected assets.
- **Exceptions**: justified alternatives requiring appropriate human selection.
- **Verification**: observable checks and evidence.

Initial coverage: architecture, ingestion/CDC, data modelling/grain/SCD, pipeline design/recovery, quality/semantic contracts, security/governance/grants, testing, deployment and observability/performance/cost. Additional modules should be added based on real needs, not for completeness alone.

Standards are consumed by **Architect, Develop, Check and Test**, and inform Audit/Scope. Existing project conventions and vendor realities must be inspected rather than fabricated. Policies around human approval and secret safety are non-optional.

See [index.yaml](index.yaml), [framework design](../docs/FRAMEWORK-DESIGN.md).

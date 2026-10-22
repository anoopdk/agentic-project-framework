# Workflow skill design catalogue

**No operational skill packages are implemented yet.** The directory taxonomy expresses the agreed architectural grouping. Skill-specific inputs, steps, prompts, tests and tooling are intentionally deferred to a later design cycle.

| Stage | Capability | Planned directory |
| --- | --- | --- |
| Discover | Audit | `01-discover/audit/` |
| Discover | Scope | `01-discover/scope/` |
| Decide | Architect | `02-decide/architect/` |
| Build | Develop | `03-build/develop/` |
| Validate | Check | `04-validate/check/` |
| Validate | Test | `04-validate/test/` |
| Record | Document | `05-record/document/` |
| Align | Sync | `06-align/sync/` |
| Cross-cutting | Debug | `debug/` |

All skills inherit the foundational policies and routing gates, including debugging. Detailed tool-specific skill installation format is NOT yet defined and must not be presumed automatic.

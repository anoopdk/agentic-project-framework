# Architecture

## Context diagram

```mermaid
flowchart TB
  H[Human authority] --> R[Router]
  P[Policies] --> R
  S[Standards] --> R
  C[Verified project context] --> R
  R --> D1[Discover]
  D1 --> D2[Decide]
  D2 --> G{Scoped approval?}
  G -->|No| D2
  G -->|Yes| B[Build]
  B --> V[Validate]
  V --> REC[Record]
  REC --> A[Align]
```

## Implementation flow

```mermaid
flowchart LR
  AG[AGENTS.md] --> POL[policies/]
  POL --> ROU[router/]
  ROU --> SK[skills catalogue]
  SK --> STD[standards/]
  STD --> ADOPT[adoption playbook]
```

## Design notes

- Prefer layered medallion / governed platform patterns where applicable.
- Keep configuration and secrets outside Git.
- Preserve auditability: documentation must match repository evidence.

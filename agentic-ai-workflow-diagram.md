# Agentic AI Workflow Diagram

This diagram shows a general agentic AI workflow with planning, tool use, validation, and human approval.

```mermaid
flowchart TD
    A[User Goal] --> B[Agent Planner]
    B --> C[Task Breakdown]
    C --> D[Tool Selection]
    D --> E[Knowledge Retrieval / API / System Action]
    E --> F[Draft Output]
    F --> G[Validation Layer]
    G --> H{Human Approval Needed?}
    H -->|Yes| I[Human Review]
    H -->|No| J[Final Output]
    I --> K{Approved?}
    K -->|Yes| J
    K -->|Edit Needed| F
    K -->|Rejected| L[Stop / Escalate]
    J --> M[Logging and Monitoring]
```

## Key Principle

Agentic AI should be designed with clear roles, limited tool access, validation, monitoring, and human approval for sensitive workflows.

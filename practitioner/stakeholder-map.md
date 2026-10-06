# Stakeholder and Authority Map

[← Multi-Operator Challenge](../docs/03-multi-operator-challenge.md)

Complete one row per stakeholder role.

| Role | Primary goal | Information needed | Commands/authority | Failure responsibility | Handoff to |
|---|---|---|---|---|---|
| Operator |  |  |  |  |  |
| Maintenance |  |  |  |  |  |
| Domain expert / inspector |  |  |  |  |  |
| Integration engineer |  |  |  |  |  |
| Manager / supervisor |  |  |  |  |  |
| Safety / compliance |  |  |  |  |  |

## Conflict check

For every pair of roles, ask:

- Do they need different representations of the same robot state?
- Could they issue conflicting commands?
- Does one role depend on data produced by another?
- Is there ambiguity over who owns a decision after a fault?
- Is any role receiving uncertainty without having authority to respond?

## Handoff record

Document the minimum information that must be transferred during:

- operator shift change;
- maintenance handover;
- transition from autonomous to manual operation;
- escalation from operator to integration engineer;
- return to service after a safety stop.

# 2. The Reliability Imperative

[← Overview](01-overview.md) · [Next: Multi-Operator Challenge →](03-multi-operator-challenge.md)

## Principle

In high-stakes industrial environments, the relevant question is not merely **“Can the interaction work?”** but **“Can it continue to work safely, predictably, and recoverably under operational constraints?”**

## Why reliability dominates

Industrial HRI can fail because of conditions that are secondary in controlled laboratory demonstrations:

- sensing degradation or environmental variation;
- communication or network interruption;
- non-expert recovery after a fault;
- task-cycle and throughput constraints;
- configuration drift after maintenance;
- operator handover and shift changes;
- integration with legacy automation;
- safety limits that alter robot speed, force, or reachable behavior.

## Reliability-first design questions

Before adopting a novel interaction modality, ask:

1. What happens when the preferred sensing channel becomes unreliable?
2. Can the operator recover without a robotics specialist?
3. Is a safe manual or degraded mode available?
4. Can the interaction tolerate normal environmental variability?
5. Does the system preserve acceptable task-cycle performance after safety constraints are applied?
6. Is failure behavior understandable to the people who must respond to it?

## Reliability is broader than uptime

A system can be technically available but operationally unusable. RAISE-HRI therefore treats reliability as a combination of:

| Dimension | Practical meaning |
|---|---|
| Predictability | Similar conditions produce understandable behavior |
| Recoverability | Humans can restore operation after faults |
| Degraded-mode operation | Partial failure does not create uncontrolled behavior |
| Maintainability | Faults can be diagnosed and corrected efficiently |
| Repeatability | Performance remains stable across shifts and runs |
| Integration robustness | Dependencies do not become hidden single points of failure |

## Deployment evidence

The paper connects this theme to evidence on teleoperation learning, collaborative manufacturing, physiological response, and industrial validation. See the [evidence map](../references/evidence-map.md) for the claim-to-reference mapping.

## Practical resource

Use the [deployment checklist](../practitioner/deployment-checklist.md) before field trials and the [failure review template](../practitioner/failure-review.md) after incidents or difficult deployments.

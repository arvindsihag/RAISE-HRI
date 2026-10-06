# 4. Trust Across Stakeholders

[← Multi-Operator Challenge](03-multi-operator-challenge.md) · [Next: Four Transferable Lessons →](05-four-transferable-lessons.md)

## Principle

Trust is not a single score attached to a robot. In deployment, trust depends on at least:

**Role × Task × Context × Consequence of error**

A robot can reasonably be trusted for repetitive assembly while the same stakeholder remains unwilling to rely on it for maintenance diagnosis or a safety-critical decision.

## Appropriate trust, not maximum trust

The goal is **calibrated reliance**:

- too little trust → unnecessary disuse, excessive intervention, lost productivity;
- too much trust → over-reliance, missed faults, poor supervision;
- calibrated trust → reliance that matches actual capability and context.

## Stakeholder examples

| Stakeholder | What tends to matter |
|---|---|
| Operator | predictability, transparent state, controllability |
| Maintenance | diagnosability, logs, failure modes, repairability |
| Manager | uptime, throughput, staffing effect, cost |
| Inspector/domain expert | data quality, traceability, confidence in evidence |
| Customer/end recipient | safety, outcome quality, accountability |
| Regulator/safety team | verifiability, limits, auditability |

## Trust-calibration questions

1. What decision is this stakeholder being asked to delegate?
2. What evidence can they observe?
3. Can they act on uncertainty when the robot exposes it?
4. What is the consequence of misplaced trust?
5. Does the interface support both intervention and informed non-intervention?

## Relation to the paper

The white paper connects foundational trust research with industrial survey evidence showing that acceptance varies substantially by task. The practical implication is that “increase trust” is too vague to be a deployment objective.

## Practical resource

Use the [trust calibration worksheet](../practitioner/trust-calibration.md) for each major stakeholder role.

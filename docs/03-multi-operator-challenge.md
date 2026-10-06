# 3. The Multi-Operator Challenge

[← Reliability Imperative](02-reliability-imperative.md) · [Next: Trust Across Stakeholders →](04-trust-across-stakeholders.md)

## Principle

The deployed unit of interaction is often **not one human and one robot**. It is a socio-technical team.

A single robot may be touched by several roles:

- operator;
- maintenance technician;
- domain expert or inspector;
- integration engineer;
- production manager;
- safety or compliance personnel;
- downstream customer or service recipient.

## Why single-user assumptions break

Different roles need different information and different control authority.

| Role | Typical need | Risk if ignored |
|---|---|---|
| Operator | live state, commands, alarms, recovery | unsafe or inefficient intervention |
| Inspector/domain expert | evidence, annotations, data quality | poor task judgment |
| Maintenance | diagnostics, logs, component health | long downtime |
| Integrator | configuration, interfaces, calibration | brittle deployment |
| Manager | throughput, availability, intervention burden | misleading business assessment |
| Safety/compliance | traceability, limits, incident evidence | unverified or non-compliant operation |

Trying to compress all needs into one interface can create information overload and unclear authority.

## Design objective

The design task is not “make one interface simpler.” It is:

> **Give each role the information and authority it needs while making handoffs, escalation, and shared responsibility explicit.**

## Questions for design reviews

- Who can stop the robot?
- Who can restart it?
- Who can modify parameters?
- Who decides whether degraded performance is acceptable?
- Who needs raw data versus interpreted results?
- Who owns the decision after an alarm?
- How does responsibility transfer between shifts or roles?

## Field implication

Group-robot and multi-party HRI research reinforces the broader point that real interaction can extend beyond a simple human–robot dyad. RAISE-HRI translates that insight into an industrial role-and-authority perspective.

## Practical resource

Create a deployment-specific map using the [stakeholder map template](../practitioner/stakeholder-map.md).

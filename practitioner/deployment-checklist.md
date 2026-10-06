# Reliability-First Deployment Checklist

[← Repository home](../README.md) · [Readiness scorecard →](readiness-scorecard.md)

Use this checklist at design review, pilot readiness, and production handover.

## A. Reliability and recovery

- [ ] Critical interaction functions have defined failure modes.
- [ ] A degraded or fallback operating mode exists where appropriate.
- [ ] Operators can identify when perception/autonomy is uncertain.
- [ ] Recovery does not depend on undocumented specialist knowledge.
- [ ] Restart/recovery behavior has been tested after realistic faults.
- [ ] Environmental variation has been included in validation.
- [ ] Logging is sufficient to reconstruct a failure.

## B. Team and authority

- [ ] All operational stakeholder roles are identified.
- [ ] Control authority is explicit for each role.
- [ ] Stop/restart/configuration permissions are defined.
- [ ] Handoffs between roles and shifts are documented.
- [ ] Interfaces expose role-appropriate information.
- [ ] Escalation paths are defined for unresolved faults.

## C. Trust calibration

- [ ] Trust is evaluated by stakeholder role and task.
- [ ] The system communicates uncertainty where users can act on it.
- [ ] Operators can intervene without excessive friction.
- [ ] The interface avoids implying capability the robot does not have.
- [ ] Training includes known limits and realistic failure scenarios.

## D. Actual-user fit

- [ ] The real operator profile matches the assumed user profile.
- [ ] Training time is known and budgeted.
- [ ] Routine troubleshooting can be performed by the intended support role.
- [ ] Documentation reflects actual field procedures.
- [ ] Specialist intervention frequency is measured during pilots.

## E. Safety and usability

- [ ] Relevant safety requirements are identified and implemented.
- [ ] Safe settings have been evaluated for workload and cycle-time impact.
- [ ] Safety behavior is understandable to users.
- [ ] Users can distinguish a safety stop from a software/communication fault.
- [ ] Usability is evaluated after safety configuration, not before it.

## F. Deployment evidence

- [ ] Pilot conditions reflect actual lighting, noise, layout, and workload.
- [ ] Intervention count is tracked.
- [ ] Recovery time is tracked.
- [ ] Availability/downtime is tracked.
- [ ] Quality/rework impact is tracked where relevant.
- [ ] Known unresolved limitations are documented before handover.

## Exit question

> **If the robot becomes uncertain at the worst realistic moment, does the team know who should notice, who should act, what they should do, and how operation will be recovered?**

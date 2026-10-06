# Trust Calibration Worksheet

[← Trust Across Stakeholders](../docs/04-trust-across-stakeholders.md)

Use one worksheet per **stakeholder × task** pair.

## 1. Context

- **Stakeholder:**
- **Task/capability:**
- **Operating environment:**
- **Consequence of robot error:**
- **Consequence of unnecessary human intervention:**

## 2. Evidence available to the stakeholder

- What does the user see about robot state?
- What confidence/uncertainty information is available?
- Are alerts actionable?
- Can the user inspect the evidence behind a robot decision?

## 3. Reliance decision

- When should the stakeholder rely on the robot?
- When should the stakeholder intervene?
- What observable signal should trigger intervention?
- Can the user override or pause the system safely?

## 4. Miscalibration risks

### Over-trust

- What could the robot do incorrectly while still appearing normal?
- What critical information might the interface hide?

### Under-trust

- What unnecessary intervention could reduce throughput or increase workload?
- Are repeated false alarms teaching users to ignore the system?

## 5. Validation

Record evidence using behaviors, not only questionnaire scores:

- intervention frequency;
- missed interventions;
- unnecessary interventions;
- response time after uncertainty/fault;
- reliance under normal vs degraded conditions.

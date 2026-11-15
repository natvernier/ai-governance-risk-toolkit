# AI use decision log: template

One entry per decision. Copy the block below.

```md
# Decision [ID]: [short title]

## 1. Decision
Date:
Decision: [approved / approved with conditions / rejected / paused]
Decided by: [role]
Workflow owner: [role]

## 2. Use case
What the AI system does in this workflow:
Who uses it:
Who is affected by the output:
What is out of scope:

## 3. Tool and data
Tool or model:
Where it runs and where data is stored:
Data that goes in: [public / internal / confidential / personal]
Data that must never go in:

## 4. Risk check
Possible harm if the output is wrong:
Risk level: [low / medium / high]
Regulatory check: [e.g. EU AI Act category, transparency duty, GDPR basis, works council]
Checked by: [roles, e.g. data protection, information security]

## 5. Human oversight
Review step before output is used:
Who signs off:
What the reviewer checks:

## 6. Conditions
[Conditions attached to the approval, numbered]

## 7. Evidence
[Links to test results, assessments, vendor documents. No copies of personal data.]

## 8. Review
Review date:
Trigger for an earlier review:
Signals to watch:

## 9. Change history
[Date: what changed and why]
```

## Notes on filling it in

* **Decision** names a role, not only a person, so the entry stays readable when people change jobs.
* **Possible harm** describes what happens to people if the output is wrong. "Low risk" without this sentence is not a risk check.
* **Regulatory check** names what was checked and by whom. This is a record, not legal advice.
* **Conditions** should be checkable. "Use responsibly" is not a condition; "no personal data in prompts, checked monthly by spot check" is.

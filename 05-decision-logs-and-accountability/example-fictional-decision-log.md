# Decision 2026-07: AI-supported summaries of customer feedback

**Status:** Filled example, fictional. Organisation, roles and details are invented.
**Template:** [`decision-log-template.md`](decision-log-template.md)

**Fictional setting:** Calder Mutual, an insurer with about 3,000 employees. The customer service team wants AI-supported weekly summaries of free-text customer feedback for the product teams.

## 1. Decision

Date: 14 July 2026
Decision: approved with conditions
Decided by: Head of Customer Service, after review by Data Protection and Information Security
Workflow owner: Customer Insights Lead

## 2. Use case

What the AI system does in this workflow: groups about 1,200 free-text comments per week into themes and drafts a one-page summary with example quotes.
Who uses it: two analysts in Customer Insights.
Who is affected by the output: product teams who set priorities based on the summary; indirectly, customers whose feedback is summarised.
What is out of scope: decisions about individual customers, complaints handling, any scoring of employees.

## 3. Tool and data

Tool or model: the company's approved enterprise AI workspace (EU data residency, no training on company data according to the contract).
Where it runs and where data is stored: vendor cloud, EU region; summaries stored in the insights team's folder.
Data that goes in: internal. Comments are pseudonymised before upload: names, contract numbers, e-mail addresses and phone numbers are removed automatically.
Data that must never go in: unredacted comments, health information, contract numbers, any data from complaints cases.

## 4. Risk check

Possible harm if the output is wrong: a theme is over- or underweighted, and a product team sets the wrong priority for a quarter. No direct effect on individual customers.
Risk level: medium (because product decisions rely on it).
Regulatory check: not a high-risk use case under the EU AI Act; no decisions about natural persons. GDPR: pseudonymisation before upload, legal basis confirmed by Data Protection. Works council informed, as employee comments in feedback are possible.
Checked by: Data Protection Officer, Information Security, works council (informed).

## 5. Human oversight

Review step before output is used: an analyst checks every theme against a random sample of 30 original comments.
Who signs off: Customer Insights Lead.
What the reviewer checks: themes match the sample; example quotes are real and contain no personal data; numbers in the summary add up.

## 6. Conditions

1. Pseudonymisation runs before every upload; the analyst confirms it in the weekly checklist.
2. Every summary states that it is AI-supported and reviewed, and names the reviewer.
3. Product teams receive the theme counts with the sample size, not only the narrative.
4. Information Security spot-checks one upload per month for leftover personal data.

## 7. Evidence

* Test run on four weeks of historical comments: themes compared with the analysts' manual coding (link to internal test report).
* Vendor data processing agreement and EU residency confirmation (link).
* Data Protection note on pseudonymisation (link).

## 8. Review

Review date: 14 January 2027
Trigger for an earlier review: any personal data found in an upload; a product team disputes a summary twice in a row; a change of model or vendor.
Signals to watch: share of themes the analyst corrects; time per weekly summary; product team feedback.

## 9. Change history

* 14 July 2026: approved with conditions 1, 2 and 4.
* 2 September 2026: condition 3 added after a product team read a small theme as a trend.

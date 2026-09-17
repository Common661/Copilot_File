# 40 Use-Case-Driven Copilot Prompts for Excel

Replace bracketed placeholders with your organization-specific details and review generated output before use.

**Prompt count: 40**

## 1. Executive KPI dashboard

Using the table in [workbook/table], create an executive KPI summary for [period]. Show actual, target, variance, trend, and RAG status for revenue, margin, cash, customer retention, and delivery. Flag data-quality issues and explain the three decisions leaders should consider.

## 2. Budget versus actual analysis

Analyze [Budget] and [Actuals] tables by department and month. Calculate absolute and percentage variance, identify the five largest unfavorable variances, suggest likely business questions to investigate, and create a management-ready variance chart.

## 3. Sales pipeline health

Analyze the sales pipeline by stage, region, owner, deal size, and expected close date. Calculate weighted pipeline, stage conversion, aging, and coverage against target. Highlight stalled or high-risk opportunities and summarize recommended follow-ups.

## 4. 12-month rolling forecast

Create a 12-month rolling forecast from the historical data in [table]. State the method and assumptions, show best/base/worst scenarios, visualize monthly results, and flag where limited history or outliers reduce confidence.

## 5. Customer profitability

Calculate revenue, direct cost, contribution margin, and margin percentage by customer and segment. Identify high-revenue low-margin accounts, loss-making accounts, and customers with improving or declining profitability.

## 6. Product and region performance

Create a pivot-style analysis of product performance by region. Show sales, units, average selling price, gross margin, and year-over-year growth. Identify the strongest and weakest product-region combinations.

## 7. Data quality audit

Audit this dataset for missing values, duplicates, inconsistent categories, invalid dates, outliers, and broken formulas. Create an issue log with row reference, issue type, severity, and recommended correction. Do not change source data without listing proposed changes.

## 8. Formula troubleshooting

Review formulas in [range]. Identify errors, inconsistent references, hard-coded values, and opportunities to simplify. Explain each issue in plain language and provide a corrected formula with a test case.

## 9. Resource capacity planning

Compare team capacity with project demand by week, role, and skill. Calculate utilization, over-allocation, bench capacity, and skill gaps. Create a heatmap and list hiring, reallocation, or sequencing options.

## 10. Project portfolio status

Summarize projects by status, budget, completion percentage, milestone health, risk, and owner. Identify projects needing steering-committee attention and produce a concise portfolio dashboard.

## 11. Inventory optimization

Analyze inventory by SKU, location, demand, lead time, stock on hand, and reorder point. Identify excess, shortage, slow-moving, and obsolete stock. Recommend reorder priorities using the available data.

## 12. Procurement savings

Compare supplier prices, volumes, payment terms, lead times, and quality scores. Quantify potential savings from consolidation or renegotiation and flag supplier concentration or service risks.

## 13. Cash-flow forecast

Build a weekly cash-flow forecast from receivables, payables, payroll, capex, and opening cash. Show minimum cash point, funding gap, and sensitivity to delayed collections or accelerated payments.

## 14. Receivables aging

Create an accounts-receivable aging analysis by customer and owner. Show current, 1-30, 31-60, 61-90, and 90+ day balances. Prioritize collection actions based on value, age, and customer risk.

## 15. Expense anomaly detection

Analyze employee expenses for duplicate claims, round-number patterns, weekend submissions, policy-limit exceptions, unusual merchants, and category spikes. Produce a review list without asserting fraud.

## 16. Headcount and attrition

Analyze headcount, hires, exits, tenure, role, location, and business unit. Calculate voluntary attrition and identify patterns that leadership should investigate. Protect privacy by reporting aggregated groups only.

## 17. Training effectiveness

Compare training attendance, completion, assessment scores, and post-training performance indicators. Identify courses with strong or weak outcomes and suggest questions for follow-up evaluation.

## 18. Survey analysis

Analyze survey responses by question and permitted demographic segment. Summarize themes, score distributions, and material differences. Suppress small groups and avoid inferring individual sentiment.

## 19. Service desk trends

Analyze ticket volume, category, priority, resolution time, reopen rate, SLA status, and channel. Identify recurring issues, peak periods, and automation or knowledge-base opportunities.

## 20. SLA compliance

Calculate SLA compliance by service, customer, priority, and month. Highlight breach drivers, repeat offenders, and trends. Create a chart suitable for an operations review.

## 21. Marketing campaign ROI

Calculate campaign reach, leads, conversion, revenue, cost, CAC, and ROI by channel. Compare campaigns fairly, state attribution limitations, and recommend where to test or reallocate spend.

## 22. Website funnel

Analyze visits, product views, cart additions, checkout starts, and purchases by device and source. Calculate conversion and drop-off at each stage and identify the largest improvement opportunities.

## 23. Pricing scenario model

Model the effect of [price change] on volume, revenue, gross margin, and break-even demand using the assumptions table. Create scenario controls and clearly separate inputs, formulas, and outputs.

## 24. Break-even analysis

Calculate fixed cost, variable cost per unit, contribution margin, break-even units, and break-even revenue for each product. Add a chart showing profit across a realistic volume range.

## 25. Operational cycle time

Analyze process timestamps to calculate waiting time, processing time, total cycle time, and percentile performance by step. Identify bottlenecks and quantify their impact.

## 26. Quality defect Pareto

Classify defects by type, line, supplier, and shift. Create a Pareto analysis, quantify the vital few causes, and propose where root-cause investigation should begin.

## 27. Scenario sensitivity table

Create one-way and two-way sensitivity analyses for [output metric] using [input variables]. Highlight thresholds where the decision changes and document all assumptions.

## 28. Board metric pack

Create a board-ready table of financial, customer, people, risk, and operational metrics. Include current period, prior period, target, variance, trend, and a one-line evidence-based commentary.

## 29. M&A synergy tracker

Track planned versus realized synergies by initiative, owner, timing, cost to achieve, and confidence. Flag delayed or unsupported benefits and summarize value at risk.

## 30. ESG metrics review

Analyze available environmental, social, and governance metrics against targets and prior periods. Highlight missing evidence, inconsistent definitions, and areas requiring assurance review.

## 31. Compliance exceptions

Summarize control-test exceptions by process, risk, severity, owner, due date, and remediation status. Identify overdue high-risk items and recurring control themes.

## 32. Vendor scorecard

Build a vendor scorecard using cost, quality, delivery, innovation, security, and support measures. Normalize scores, show weighting, rank vendors, and provide a sensitivity check on the weights.

## 33. Workforce skills matrix

Create a skills matrix by employee, role, proficiency, certification, and project demand. Identify critical single points of dependency and priority learning or hiring needs.

## 34. Meeting action tracker

Turn this action log into a tracker showing action, owner, due date, status, age, dependency, and escalation need. Flag overdue items and create a weekly summary.

## 35. Benefits realization

Compare business-case benefits with actual realized benefits by initiative and period. Calculate variance, confidence, and evidence status. Identify benefits at risk and required corrective actions.

## 36. Cloud cost optimization

Analyze cloud cost by subscription, service, environment, owner, and month. Identify idle or anomalous spend, commitment opportunities, and tagging gaps without making changes.

## 37. License utilization

Analyze assigned versus active software licenses by product, department, and user type. Identify unused or low-use licenses and estimate optimization potential using stated assumptions.

## 38. Risk heatmap

Score risks using likelihood and impact fields, build a heatmap, summarize top residual risks, and flag missing mitigation owners or review dates. Do not invent risk ratings.

## 39. What-if hiring plan

Model monthly hiring demand, recruiter capacity, time-to-fill, attrition, and onboarding throughput for [period]. Compare three hiring scenarios and show the effect on vacancy backlog.

## 40. Workbook executive narrative

Using all relevant tables in this workbook, write a concise executive narrative covering performance, drivers, risks, opportunities, and next actions. Cite worksheet and cell/table references for every quantitative statement.

# IT Helpdesk Performance Analysis | Power BI

Self-initiated Power BI project analyzing **11,923 IT support tickets** across 10 countries — built to mirror the SLA and agent-performance reporting I owned as an **Associate, IT Helpdesk**, now applied as a Business Analyst portfolio piece.

📄 **[Full Project Report (PDF)](IT_Helpdesk_Performance_Analysis_Report.pdf)** — detailed write-up of methodology, every visual, and insights.

---

## Dashboards

**SLA Compliance**
![SLA Compliance Dashboard](Reports/sla_compliance_page.png)

**Agent Performance**
![Agent Performance Dashboard](Reports/agent_performance_page.png)

---

## Headline Results

| Metric | Result |
|---|---|
| Overall SLA Compliance | **75.7%** (9,023 / 11,923 tickets) |
| High-Priority SLA | **98.3%** — target met comfortably |
| Medium-Priority SLA | **56.0%** — biggest gap, largest ticket volume |
| Avg. Rating | **3.97 / 5** |
| Countries / Queues / Agents | 10 / 10 / 12 |

**Key finding:** Medium-priority tickets (42% of all volume) are the main driver of missed SLAs — closing that gap would move overall SLA performance more than any other lever.

## What I Did

- Cleaned and modeled raw ticket data into a star schema (fact + Calendar + Country dimensions) in Power BI
- Wrote **42 DAX measures** covering SLA logic, time intelligence, and agent/queue performance
- Built derived business logic: Severity classification, SLA targets by priority, resolution-time calculations
- Designed a 2-page interactive report with bookmark navigation, drill-through, and dynamic titles

## Tools

Power BI Desktop · Power Query (M) · DAX · Star Schema Design

## Run It

1. Clone the repo
2. Open `PowerBI/IT_Helpdesk_Performance.pbix` in Power BI Desktop
3. Refresh the data source if prompted

---

*Sreekar Tirunagari — Associate, IT Helpdesk → Business Analyst. [LinkedIn](#) · [GitHub](#)*

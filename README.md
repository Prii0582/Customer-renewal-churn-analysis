# Customer-renewal-churn-analysis
Churn risk identification and renewal audit for 11 enterprise SaaS foundry customers — Python, HTML, data analysis
# Customer Renewal & Churn Signal Report — July 2026 Cohort

> **Structured churn risk identification and renewal audit for enterprise SaaS customers**  
> Built at **NowPurchase / MetalCloud MIS** · Python · HTML/CSS · Data analysis · Customer Success

---

## What This Project Does

Every quarter, the Customer Success team at NowPurchase reviews a cohort of customers due for AMC (Annual Maintenance Contract) renewal. The goal is to identify which customers are at risk of churning *before* the renewal conversation happens, so the team can intervene early.

This project produced a **professional audit report** for the July 2026 renewal cohort — 11 foundry customers, total AMC value ₹7,42,600 — with visual risk classification, per-customer module health metrics, and team action assignments.

---

## Cohort Overview

| Metric | Value |
|---|---|
| Total customers | 11 |
| Total AMC value | ₹7,42,600 |
| Renewal period | July 2026 |
| Risk categories | 4 (Critical / High / Medium / Healthy) |

---

## Risk Classification Framework

### 🔴 Critical
**Brakes India (Flometallic)** — ₹1,21,000 AMC  
Zero activity since December 2025. No spectro files uploaded, no chargemix usage, no heat plan engagement. Immediate escalation required before renewal conversation.

### 🟠 High Risk
**Kumar Auto Unit 2, Doraha** — ₹1,20,000 AMC  
Files stopped uploading after 7th May. 0% across all module metrics. Likely to churn without active intervention.

### 🟡 Medium Risk (4 customers)
Active users with specific module configuration issues currently being fixed by the product team. Retention likely if issues resolved before renewal.

### 🟢 Healthy / Upsell Opportunity (5 customers)
Strong engagement across all modules. Identified as candidates for module upsell (AI Vision, MTC Reports, additional plants).

---

## Module Health Metrics Tracked Per Customer

For each customer, the report tracks:

| Module | Metric |
|---|---|
| **Spectro Analysis** | File upload count, parsing %, sample tagging %, grade tagging % |
| **Chargemix** | Suggestion generation rate (%), suggestion acceptance rate |
| **Heat Plan** | Heat plan usage frequency |
| **MTC Reports** | HMT file counts (Tensile / Microstructure / Hardness), parsing status |
| **AI Vision** | Safety Shield active / inactive |

---

## Report Structure

```
┌────────────────────────────────────────────┐
│  Header: Customer Audit & Churn Report     │
│  July 2026 Renewal Cohort                  │
├────────────────────────────────────────────┤
│  Summary Cards:                            │
│  [11 Customers] [₹7,42,600 AMC] [4 Risks] │
├────────────────────────────────────────────┤
│  Executive Summary Table                   │
│  Risk category | AMC | Key observation     │
├────────────────────────────────────────────┤
│  Customer Snapshot Table                   │
│  • Color-coded risk stripe per row         │
│  • Progress bars under each metric value   │
│  • Risk pills on customer names            │
│  • Module group color headers              │
│    (Blue = Spectro, Teal = Heat Plan,      │
│     Purple = MTC)                          │
│  • Remark tags per customer                │
├────────────────────────────────────────────┤
│  Intervention Matrix                       │
│  POC assignments: Ankit / Harshit / Deepak │
└────────────────────────────────────────────┘
```

---

## Output Formats

- **HTML report** — full visual report with progress bars, risk colour coding, and structured tables
- **High-resolution PNG** — 3× DPI (5400 × 5682 px) for sharing in presentations or emails
- **WhatsApp team summary** — WhatsApp-native bold/italic formatted message summarising audit findings with POC assignments

---

## WhatsApp Summary Format (Example)

```
*MetalCloud MIS — July Renewal Cohort Audit*

🔴 *Critical:* Brakes India (Flometallic) — POC: Ankit
→ Zero activity since Dec 2025. Immediate call needed.

🟠 *High Risk:* Kumar Auto Unit 2 — POC: Harshit
→ Files stopped May 7. All metrics at 0%.

🟡 *Medium (4):* Config issues being fixed — POC: Deepak
🟢 *Healthy (5):* Upsell candidates — flag for expansion
```

---

## Business Impact

- Gave the CS team a **single source of truth** for all 11 renewal accounts before any renewal call
- Enabled proactive escalation for 2 critical accounts **30+ days before** renewal date
- Identified 5 healthy accounts for upsell conversations — estimated expansion opportunity
- POC assignments ensured no customer was missed

---

## Skills Demonstrated

`Python` `HTML/CSS` `Data analysis` `Customer success analytics` `Churn prediction` `SaaS renewal management` `MIS reporting` `Stakeholder communication` `Foundry domain` `Visual report design`

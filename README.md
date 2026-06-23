# 🛡️ Prism Insurance Pvt. Ltd — Power BI Dashboard

An interactive Power BI dashboard built for **Prism Insurance Pvt. Ltd** that analyzes insurance policy performance, claim statuses, premium amounts, and customer demographics to support data-driven business decisions.

---

## 🔢 Key KPI Metrics

| Metric | Value |
|---|---|
| 💰 **Total Premium Amount** | 5.98M |
| 🛡️ **Total Coverage Amount** | 600.55M |
| 📋 **Total Claim Amount** | 16.91M |
| 👩 **Female Policyholders** | 5,001 |
| 👨 **Male Policyholders** | 5,003 |

---

## 📈 Visuals & Insights

### 1. 🔍 Slicers (Filters)
- **Policy Number** — filter dashboard by individual policy
- **Claim Number** — filter by specific claim
- **Customer ID** — filter by individual customer

---

### 2. 📊 Number of Claim Status by Claim Status (Bar Chart)
Shows the count of claims under each status:

| Status | Count |
|---|---|
| Rejected | 4.4K |
| Settled | 3.4K |
| Pending | 2.3K |

> **Insight:** Most claims are being rejected — this signals a need to review claim eligibility criteria or customer communication.

---

### 3. 📉 Premium Amount by Policy Type (Bar Chart)
Breakdown of premium collected across different policy categories:

| Policy Type | Premium Amount |
|---|---|
| Travel | 2.5M |
| Health | 1.2M |
| Auto | 1.0M |
| Life | 0.7M |
| Home | 0.6M |

> **Insight:** Travel insurance generates the highest premium revenue, followed by Health and Auto.

---

### 4. 📈 Claim Amount by Age Group (Line Chart)
Shows total claims filed by different age groups:

| Age Group | Claim Amount |
|---|---|
| Adult | 8.8M |
| Elder | 6.4M |
| Young Adult | 1.7M |

> **Insight:** Adults file the highest claims, while Young Adults file the least — possibly due to lower health risks.

---

### 5. 🍩 Count of Active vs Inactive Policies (Donut Chart)

| Status | Count | Percentage |
|---|---|---|
| Active | 5.82K | 58.13% |
| Inactive | 4.19K | 41.87% |

> **Insight:** Over 40% of policies are inactive — a significant churn rate that needs attention for retention strategy.

---

### 6. 📋 Claim Amount by Policy Type & Status (Matrix Table)
Detailed breakdown of Pending, Rejected, and Settled claim amounts per policy type:

| Policy Type | Pending | Rejected | Settled |
|---|---|---|---|
| Auto | 2,08,10,615 | 4,06,71,711 | 3,29,... |
| Health | 2,76,82,791 | 5,24,01,928 | 4,00,... |
| Home | 1,30,01,816 | 2,74,06,202 | 2,06,... |
| Life | 1,72,59,587 | 3,37,22,751 | 2,31,... |
| Travel | 5,72,47,694 | 10,73,95,611 | 8,61,... |
| **Total** | **13,60,02,506** | **26,15,98,205** | **20,29,...** |

> **Insight:** Travel has the highest rejected claim amount — worth investigating for fraud or policy misuse.

---

## 🗄️ Dataset — Key Columns

| Column | Description |
|---|---|
| `PolicyNumber` | Unique identifier for each policy |
| `ClaimNumber` | Unique identifier for each claim |
| `CustomerID` | Unique customer identifier |
| `Gender` | Male / Female |
| `Age Group` | Adult / Elder / Young Adult |
| `PolicyType` | Travel / Health / Auto / Life / Home |
| `PremiumAmount` | Premium paid by the customer |
| `CoverageAmount` | Total coverage provided |
| `ClaimAmount` | Amount claimed by the customer |
| `ClaimStatus` | Pending / Rejected / Settled |
| `PolicyStatus` | Active / Inactive |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design and visualization |
| **Power Query (M)** | Data cleaning and transformation |
| **DAX** | KPI measures and calculated columns |
| **Excel / CSV** | Source dataset |

---

## 🚀 How to Open This Project

1. Install **Power BI Desktop** → [Download here](https://powerbi.microsoft.com/desktop)
2. Clone or download this repository
3. Open the `.pbix` file in Power BI Desktop
4. Connect to your data source when prompted
5. Refresh the data — all visuals will populate automatically

---

## 💡 Key Learnings

- How to build an end-to-end insurance analytics dashboard
- Creating slicers for dynamic filtering by Policy, Claim, and Customer
- Using donut charts, bar charts, line charts, and matrix tables together
- Segmenting claims by age group, policy type, and claim status
- Identifying business insights like high rejection rates and policy churn

---

## 📌 Use Cases

- Monitoring insurance claim performance across policy types
- Identifying high-risk customer segments by age group
- Tracking active vs inactive policy trends for retention planning
- Supporting underwriting and claims teams with data-driven decisions

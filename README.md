# 👥 HR Analytics Dashboard — Power BI

A two-page interactive Power BI report delivering deep insights into **workforce composition** and **salary & cost analysis**. Designed with a **Corporate Blue Soft** theme for a clean, professional look suited for executive presentations.

---

## 📸 Report Pages

| Page | Description |
|------|-------------|
| **Executive Overview** | High-level workforce KPIs — headcount, attrition, gender distribution, and employee breakdown by nationality and job title |
| **Salary and Cost Analysis** | Salary benchmarking, cost composition, and median salary penetration ratio across branches |

---

## ✨ Features

- **KPI Cards** — Active employees, attrition rate, and average cost per employee at a glance
- **Active vs. Left Employees Over Time** — Line chart tracking workforce movement historically
- **Gender Distribution** — Pie chart showing workforce gender split
- **Employee Count by Nationality / Job Title** — Clustered bar chart for workforce diversity breakdown
- **Average Salary by Branch** — Column chart comparing compensation levels across locations
- **Salary Package Composition** — Donut chart breaking down salary components
- **Median Salary Penetration Ratio by Branch** — Bar chart for pay equity and benchmarking analysis

---

## 📐 Data Model — Fields & Measures

| Field / Measure | Type |
|-----------------|------|
| `Active Employees` | Measure |
| `Left Employees` | Measure |
| `Attrition Rate (%)` | Measure |
| `Average Total Cost per Employee` | Measure |
| `Total Cost` | Measure |
| `Total Salary` | Measure |
| `Basic Salary` | Field |
| `Food Allowance` | Field |
| `Medical Allowance` | Field |
| `Transportation Allowance` | Field |
| `Travel Allowance` | Field |
| `Vacation Allowance` | Field |
| `Penetration Ratio` | Measure |
| `Branch` | Dimension |
| `Gender` | Dimension |
| `Job Title` | Dimension |
| `Nationality` | Dimension |
| `Employee Number` | Dimension |

---

## 🗂️ Report Structure

```
Hr.pbix
├── Executive Overview        # KPI card · Line chart · Column chart · Pie chart · Bar chart
└── Salary and Cost Analysis  # KPI card · Column chart · Donut chart · Bar chart
```

---

## 🛠️ Built With

- **Power BI Desktop** (Report version 5.70, Theme: CY26SU02)
- **Custom Theme:** Corporate Blue Soft
- **Embedded Data Model** (5.9 MB)

---

## 🚀 Getting Started

1. **Clone or download** this repository.
2. Open `Hr.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Refresh the data source and map it to your HR system or Excel/database source.
4. Use the visuals to filter and explore workforce and compensation insights.

---

## 📁 File

| File | Description |
|------|-------------|
| `Hr.pbix` | Power BI report file — includes embedded data model, layout, and theme |

---

## 📬 Contact

For questions or contributions, feel free to open an issue or submit a pull request.

# 🏢 PropertyMgmtDB — Enterprise-Grade Property Management Platform

A full-scale, SQL + Python-based **Property Management System** with 100+ normalized tables, AI readiness, SaaS-level multi-tenancy, billing, compliance, IoT integration, international support, ESG tracking, and built-in dashboards.

---

## 📦 Project Overview

**PropertyMgmtDB** is a comprehensive SQL-backed platform that powers all aspects of property management, including:

- 🏘️ Units, leases, maintenance, payments
- 🧾 Subscriptions, billing, SLA compliance
- 📈 Advanced analytics & financial performance
- 🧠 AI scoring, sentiment analysis, forecasting
- 🌎 Multi-language, multi-currency, time zone
- 🔐 Audit trails, ESG regulation, disaster plans
- 🖥️ Full-stack intranet dashboard with Flask

This system is ideal for:
- Property management companies
- SaaS startups in PropTech
- SQL/Python developers building a real estate portfolio

---

## ⚙️ Technologies Used

- **Database:** MySQL / MariaDB  
- **Backend:** Python 3, Flask  
- **Frontend:** Bootstrap 5 (via Jinja templates)  
- **Other:** Chart.js, SQL Views, Session/Auth logic, Intranet deployment

---

## 📊 Schema Summary

| Category                  | Table Count |
|---------------------------|-------------|
| Core Property Mgmt        | 20+         |
| Financials & Payments     | 20+         |
| Compliance & Audit        | 15+         |
| Communication & Chat      | 10+         |
| AI, IoT, Blockchain        | 10+         |
| CRM, Marketing, Training  | 10+         |
| Localization & SaaS       | 15+         |
| ⚡ **Total Tables**         | **101**     |

---

## 🧱 SQL Phase

### ✅ Features
- Fully normalized schema with proper keys and constraints
- ENUMs, default values, cascading relationships
- Views for reports, dashboards, and alerts
- Sample data for all major tables
- Audit logs, triggers, and AI placeholders

### 🔨 Setup
```sql
-- Import full schema
SOURCE PropertyMgmtDB_Schema.sql;

-- (Optional) Load sample data
SOURCE PropertyMgmtDB_SampleData.sql;

## 🐍 Python / Flask Intranet Phase

Once the SQL phase is complete, we layer on a Flask-powered web app.

### 🔧 Flask Features

- Role-based login (Admin / Manager / Viewer)  
- Navigation to all major reports and views  
- Jinja2 templating with Bootstrap 5  
- Chart.js and DataTables integration  
- Modular structure (Blueprints)  

---

### 🗂️ Directory Layout


/propertymgmt/
├── app.py
├── models/
├── templates/
│ ├── base.html
│ ├── dashboard.html
│ ├── view.html
│ └── login.html
├── static/
│ ├── css/
│ └── js/
├── config.py
└── utils/

```
---

### 🚪 Login Page Example

```python
@app.route('/login', methods=['GET', 'POST'])
def login():
    # Basic email/password auth with session
    ...
```
## 📈 Dashboard & Views

Example: /dashboard
KPIs: Occupancy rate, Avg rent, Active leases

Top properties by ROI

Unpaid balances chart

Maintenance backlog

Example: /view/vw_OpenMaintenance
Filterable DataTable with export

Highlight urgent tickets

Drill-down link to request detail

---

## 🖼️ Screenshots (placeholder)

Add screenshots here after frontend is styled

login.png

dashboard.png

view_open_maintenance.png

property_profile.png

---

## 🚀 Future Enhancements

✅ REST API for external apps

⏳ Mobile-friendly PWA interface

🔄 Integration with Stripe or Plaid

🔐 OAuth 2.0 or JWT auth

📦 Docker deployment

---

## 👨‍💻 Author
Maurice Hazan
SQL | Python | Data Analyst | Full-stack Developer
📧 www.linkedin.com/in/mohazan | mauriceh01@hotmail.com | www.GitHub.com/mauriceh01 

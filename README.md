# 📊 SQL Job Market Analysis & Skill Intelligence

## 🚀 Overview
This project analyzes the job market using **SQL** to uncover high-value insights around **job salaries, skill demand, and career-optimal skills**.

The goal is simple:
> Identify which jobs and skills actually matter when targeting high-paying, in-demand roles.

All analysis is performed using **pure SQL**, following a structured, real-world analytical workflow.

---

## 🎯 Objectives
- Identify the **highest paying job roles**
- Discover **skills required for top-paying jobs**
- Find the **most in-demand skills** in the market
- Rank **skills by salary potential**
- Determine **optimal skills** combining high pay and high demand

---

## 🛠️ Tech Stack & Concepts
- SQL (Relational Databases)
- Database design & normalization
- Multi-table joins
- Aggregations (`GROUP BY`, `HAVING`)
- Subqueries & analytical logic
- Market-driven data analysis

---

## 🗂️ Project Structure

```text
sql-job-market-analysis/
│
├── Database Setup
│   ├── 1_create_database.sql
│   ├── 2_create_tables.sql
│   └── 3_modify_tables.sql
│
├── Analysis Queries
│   ├── 1_top_paying_jobs.sql
│   ├── 2_top_paying_job_skills.sql
│   ├── 3_top_demanded_skills.sql
│   ├── 4_top_paying_skills.sql
│   └── 5_optimal_skills.sql
│
└── README.md
````

---

## 🧱 Database Design (High-Level)

The database models a real job market scenario and includes:

* Job postings
* Companies
* Skills
* Job–skill relationships (many-to-many)

This structure enables realistic analytical queries similar to those used in industry-level HR and job-market analytics.

---

## 📈 Analysis Breakdown

### 1️⃣ Top Paying Jobs

Identifies job roles offering the highest salaries.

**Purpose:**
Highlights where compensation is concentrated across roles.

---

### 2️⃣ Skills Required for Top Paying Jobs

Maps high-paying roles to their associated skills.

**Purpose:**
Shows which skills directly contribute to higher pay.

---

### 3️⃣ Most In-Demand Skills

Ranks skills by how frequently they appear across job postings.

**Purpose:**
Measures real market demand instead of assumptions.

---

### 4️⃣ Top Paying Skills

Ranks skills based on the average salary of jobs requiring them.

**Purpose:**
Identifies high-value skills with strong salary impact.

---

### 5️⃣ Optimal Skills (High Pay + High Demand)

Finds skills that balance both:

* Strong market demand
* High salary association

**Purpose:**
Highlights skills with the best career ROI.

---

## 🔍 Key Insights

* High demand does not always mean high pay
* High pay does not always mean high demand
* Optimal career skills sit at the intersection of both
* SQL alone is powerful enough to answer real career-driven questions

---

## ▶️ How to Run

1. Create the database using the setup scripts
2. Create and modify tables
3. Run analytical queries sequentially
4. Interpret query outputs to derive insights

---

## 💡 Why This Project Matters

This project reflects **real-world SQL analytics work**, not toy examples.

It demonstrates the ability to:

* Think analytically
* Design and query relational databases
* Translate vague business questions into concrete insights
* Use SQL for decision-making, not just querying data

---

## 🔮 Future Improvements

* Add dashboards using Power BI or Tableau
* Automate analysis with Python
* Optimize performance with indexing
* Expand dataset for trend-based analysis

---

## 👤 Author

**Kanish**
SQL • Data Analysis • Market Intelligence

Say the word.
```

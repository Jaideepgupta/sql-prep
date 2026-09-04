# SQL Interview Prep

A practical interview preparation guide built around **SQL** and the modern analytics stack — Snowflake, dbt, data modeling, Git, Airflow, Fivetran, and Tableau.

Built as prep material for a Tableau Developer → Analytics Engineer / Data Engineering transition, but useful for anyone interviewing for a SQL-heavy analytics or data role.

## Live guides

| | |
|---|---|
| 📚 **[Preparation guide](https://jaideepgupta.github.io/sql-prep/)** | The full study guide — 68 questions across the whole role: SQL, dbt, Snowflake, data modeling, Git, Airflow, Fivetran, Tableau. Work through this to build understanding. |
| ⚡ **[Interview cheat sheet](https://jaideepgupta.github.io/sql-prep/sql-cheatsheet.html)** | A fast SQL reference — joins, window functions, CTEs, query execution order, indexing, and the traps interviewers test for. Use this for a last-look review right before an interview. |

## What's inside

- **68 interview questions and answers** in the preparation guide, organized by topic, each with a plain-language explanation, a diagram or example where useful, and a ready-to-say "interview version" of the answer.
- A dedicated **SQL cheat sheet** — 25 sections covering joins, aggregation, window functions, subqueries/CTEs, query execution order, optimization, indexing, NULL handling, and scenario-based questions.
- A closing framework — **Source → Grain → Transformation → Quality → Consumption** — for reasoning through any Analytics Engineer question on the fly, instead of reciting memorized answers.
- A 30-day study priority list (Tier 1–4) for what to focus on first.

## Topics covered

| Area | Examples |
|---|---|
| Role & stack fundamentals | Analytics Engineer vs. Data Engineer vs. Data Analyst, ELT vs. ETL |
| Tools | Snowflake, dbt, Fivetran, Airflow, Git, Tableau |
| Data modeling | Staging / intermediate / marts, star schema, fact & dimension tables, grain, cardinality, surrogate keys, SCDs |
| dbt specifics | Models, `ref()`, `source()`, macros, Jinja, snapshots, incremental models, tests, CI/CD |
| SQL | Joins & set ops, GROUP BY, window functions, subqueries & CTEs, query execution order, indexing, query optimization, NULL handling |
| Troubleshooting | Debugging a mismatched Tableau number, handling duplicates/NULLs, schema changes |
| Strategy | Data contracts, semantic layers, a 30-day prep priority list, and full interview-ready narrative answers |

## Files

| File | Description |
|---|---|
| `index.html` | Source for the preparation guide above |
| `sql-cheatsheet.html` | Source for the interview cheat sheet above |

## How to use this guide

Work through the **preparation guide** first — for each question, try answering out loud in your own words *before* reading the given answer. The "interview version" callouts are meant to be internalized as talking points, not memorized verbatim.

Keep the **cheat sheet** for the day of the interview — it's built for a quick scan, not a first read.

---

*Personal interview prep notes — not affiliated with Snowflake, dbt Labs, Fivetran, Airflow, or Tableau.*

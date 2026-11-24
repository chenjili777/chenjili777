# Hi, I'm chenjili777 👋

### AI Data Engineering | Data Agents | ML Infrastructure

I work with behavioral data in fintech. I build warehouse tables and define acquisition, conversion, and retention metrics. My current focus is **AI Agents × Data Engineering**. I’m building tools that can look up what a metric means, draft a query, and check whether the SQL answers the original question.

---

## 🔭 What I'm Working On

**AI-Powered Data Engineering**

- Give data agents access to table schemas, metric definitions, and worked SQL examples.
- Test generated funnel queries against two questions. Which users qualify? Did their events happen in the required order?

**Feature Engineering & ML Infrastructure**

- Define behavioral features once, including the events, lookback window, and treatment of missing activity. Generate daily and hourly SQL from those definitions.
- Explore how to keep training and serving features consistent when events arrive late or definitions change.

---

## 🚀 Selected Work

### [Text2SQL](https://github.com/chenjili777/Text2SQL)

A local prototype for asking questions about behavioral warehouse tables. It retrieves business definitions and example queries, drafts SQL, and checks table names, columns, grouping, and date partitions.

### [Behavioral Feature Engine](https://github.com/chenjili777/behavior_feature_engine)

A Python compiler that turns event definitions into Hive/Spark SQL. For a feature such as “exited within 30 seconds of viewing the payment page,” it generates the calculation, quality checks, and a record of the source fields.

### [Visual Tracking Map](https://github.com/chenjili777/VISUAL-TRACKING-MAP)

An interactive demo for reviewing analytics instrumentation. Select an event on a simulated app screen to compare its documented trigger and expected fields with examples of what the app reported.

---

## 🛠️ Technical Background

- **Data engineering** · Python, SQL, warehouse modeling, Hive/Spark SQL
- **Feature engineering** · Event sequences, lookback windows, data quality, feature lineage
- **AI engineering** · Retrieval over warehouse documentation, text-to-SQL, query validation

---

## ✍️ Topics I Explore

- How can we evaluate an agent when its SQL runs but answers the wrong business question?
- How can a feature store reproduce exactly what was known at prediction time?
- When does a behavioral feature need streaming updates, and when is an hourly batch enough?

---

## 🌐 Connect

[Explore my repositories on GitHub](https://github.com/chenjili777?tab=repositories). If you work on data agents or behavioral features, I’d be interested to hear how you test them.

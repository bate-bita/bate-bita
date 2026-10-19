# Bate Bita • Economics Analyst | Data Manager | Business Intelligence

Economics Analyst and Data Manager at the American Road & Transportation Builders Association (ARTBA), working on the data and research behind a subscription market intelligence service for the transportation construction industry.

I work across the whole life of a dataset: sourcing it, cleaning it, getting it into dashboards people rely on, and building the systems that keep all of that running on schedule.

**Tools:** Python | Sisense | Databricks | Excel | SAP | Power BI | SQL 

[LinkedIn](https://www.linkedin.com/in/bate-bita-tambe)

---
 
## What I am working on
 
**Market intelligence data**
Maintaining the datasets behind published research on contract awards, federal and state transportation funding, construction activity and state DOT budgets.
 
**Reporting systems**
Designing the tracking and reporting that runs subscriber management, from renewal cycles through to engagement reporting, and presenting it to the leadership team on a fixed cadence.
 
**Data platform migration**
Supporting a move from Stata to Databricks, with a focus on documenting transformation logic before it is migrated so the outputs stay defensible.
 
**Process design**
Building repeatable workflows where previously there were none, so the work survives whoever is doing it.
 
---

## Featured Projects

### 1. [NovaTech Business Performance Dashboard (SAP Analytics Cloud)](https://github.com/bate-bita/NovaTech-Business-Performance-Dashboard)

Built a five page executive BI dashboard in SAP Analytics Cloud analyzing 24 months of fictional business performance data for a global technology company across 5 regions and 4 product lines.

- Designed a structured data model in SAC Modeler with custom calculated measures for variance analysis, gross margin, net customer movement, and a RAG performance framework with defined revenue variance thresholds of greater than 3% Green, between -3% and 3% Amber, and below -3% Red.
- Built interactive dashboards with consistent filtering across all five pages, covering executive summary, revenue performance, cost performance, profitability analysis, and year over year trends.
- Solved SAC platform limitations including negative value color scaling in heatmaps, alphabetical month sorting, and a headcount aggregation error on scatter plots caused by residual chart configuration, all resolved through iterative model and design workarounds.
- Applied standard financial reporting conventions throughout, including cost variance directional logic where negative variance represents favorable underspend.

### 2. [SaaS Customer Churn Analysis (SQL + Power BI)](https://github.com/bate-bita/SaaS-Customer-Churn-Analysis)

Built a two-layer analytical project combining SQL data querying and Power BI dashboard visualization to analyze customer churn for PulseHQ, a fictional B2B CRM SaaS platform, identifying key churn drivers and quantifying revenue at risk.

- Wrote five SQL queries in SQLite covering monthly churn trends, churn rate by subscription plan, MRR loss by customer segment, a CTE-based behavioral risk scoring model to flag at-risk active customers, and a RANK() window function to prioritize customers by revenue value.
- Built a 3-page interactive Power BI dashboard with 10 custom DAX measures covering churn overview, revenue impact, and customer segment analysis, connected via a star-schema style data model.
- Identified that monthly contract customers churn at nearly 4x the rate of annual customers and that churned customers average an NPS of 3.24 versus 6.98 for active customers, providing actionable retention signals.
- Engineered a 500-row Python dataset with realistic churn narrative patterns including a Q3 spike, plan-level churn variation, and support ticket correlation with churn behavior.

### 3. [Hotel Cancellations Analytics (Python, scikit-learn, Pandas)](https://github.com/bate-bita/Predicting-Hotel-Booking-Cancellations.)

Predicted hotel booking cancellations using real-world data to support revenue optimisation decisions.

- Cleaned and merged multi-source booking data, handling bias by dropping nationality to ensure fairness.
- Analyzed correlations to identify the top five drivers of cancellations: lead time, prior cancellations, booking changes, parking requests, and special requests.
- Trained and compared four classification models: Logistic Regression, KNN, Decision Tree, and Random Forest.
- Achieved the best overall balance with Random Forest at 82% F1 score, while Decision Tree delivered highest recall at 78%, minimizing missed cancellations.
- Presented actionable insights for hotel revenue management and overbooking risk reduction.

### 4. [Understanding Text through Word Embeddings (Python, Natural Language Processing)](https://github.com/bate-bita/Word-Embeddings-Natural-Language-Processing-)

Analyzed how modern language models interpret word meaning through vector-based text representations.

- Implemented Skip-Gram and CBOW architectures using Word2Vec to compare how each learns context from surrounding words.
- Trained embeddings on a text corpus to visualize relationships between semantically related words.
- Applied dimensionality reduction techniques including PCA and t-SNE to show how similar words cluster in vector spaces.
- Analyzed learned embeddings to explain how algorithms capture linguistic context for downstream NLP tasks such as sentiment analysis and topic detection.
- Gained deeper understanding of data representation, vector similarity, and the logic behind modern language models.

---


### I build analytical systems that answer business questions, uncover patterns, and give decision makers what they need to make the right call.


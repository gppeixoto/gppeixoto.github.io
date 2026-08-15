# Guilherme Peixoto

**Email:** gpalmape@gmail.com  
**LinkedIn:** linkedin.com/in/guilhermepeixoto  
**Location:** São Paulo, Brazil  
**Languages:** English (Native/Bilingual), Portuguese (Native/Bilingual), French (Full Professional)

---

## Summary

Staff Data Scientist / ML Engineer with 9+ years of experience at the intersection of machine learning, causal inference, and experimental design in high-stakes financial systems. At Nubank, I own the core credit card limit policy — the decision engine governing 100M+ customers in Brazil alone, with a portfolio of tens of billions BRL in credit exposure, expanding across Mexico and Colombia. I operate as a technical leader and cross-functional advisor — shaping architecture, driving research roadmaps, and mentoring senior data scientists across multiple business units. Deep expertise in causal modeling, experimentation at scale, and ML system design.

---

## Experience

### Nubank — São Paulo, Brazil *(7+ years)*

**Staff Data Scientist / ML Engineer – Core Credit Card Limit Policy, Global**  
*February 2023 – Present*

- Own Nubank's **core credit card limit policy** — the decision engine governing every limit grant, increase, and decrease across Brazil (100M+ customers, tens of billions BRL in credit exposure), Mexico, and Colombia; responsible for portfolio valuation and market expansion strategy across all three geographies
- Designed and shipped **Camus v2 Second Order + BR PClip v18**: a joint causal risk model (limit-increase + default risk) projecting **+1.08B BRL NPV across 27.8M accounts** over 12 months under a +30% risk buffer; i18n-ready, enabling Mexico/Colombia expansion without experimental data dependency
- Authored **Hyoga Foundation v3** — credit limit application of Nubank's **billion-parameter transformer foundation model** trained on sequential transaction data across 100M+ customers (O(trillions) tokens); sequential-first, tabular-light architecture eliminates tabular feature hard-dependency; **+0.24pp Test AUC** vs. production (+0.51pp with Late Fusion); model family delivers **+1.20% AUC lift** (2–3x a typical mature model's annual release)
- Led the **Camus v2 Second Order refactor**: unified model classes, eliminated ~1,400 duplicated lines, enabling broader experimentation velocity (>55k lines pushed in cycle)
- Served as technical reference and strategic advisor to multiple BUs: Collections (causal models, experiment design), Lending (Aranix risk), CC Financing (causal spend model), Core BR (governance intervention)
- Co-developed the **ML system design interview** for DS hiring; member of the **Technical Bar Raiser (TBR)** program; active in US Staff+ (IC8) taskforce hiring; led and created new IC6 case for senior DS pipeline

**Lead Data Scientist – Financing & Global Collections**  
*December 2020 – February 2023*

- Built risk-based, willingness-to-finance **personalized interest rate pricing** for bill financing, replacing flat rates across the full credit portfolio and lowering average customer interest rates
- Designed the squad's data architecture to parametrize and A/B test financing product settings at ETL layer
- Delivered **account-level interest revenue model** used in production for targeting campaigns, product rollouts, and revenue projections
- Designed and executed multiple causal experiments to collect unbiased data on key financing parameters
- Lead/co-lead advisor for causal and predictive models: transactional fraud, spend, sensitivity to personal loan interest rates, initial credit line

**Senior Data Scientist – Credit Risk & Financing**  
*May 2019 – December 2020*

- Delivered Nubank's **main credit risk model**, used across all credit operations and key to adding millions to company valuation; core component of credit limit policy
- Founded and led **ML Academy**: in-house training program in data science and machine learning for business analysts and software engineers company-wide
- Led research team on new technologies applied to credit risk

---

### Incognia (formerly InLoco) — Recife, Brazil *(3+ years)*

**Data Scientist & Machine Learning Engineer**  
*August 2016 – April 2019*

- Researched and built production pipeline for **NLP-based deep learning venue categorization model** (100+ classes) using Keras, Gensim, PySpark, MLflow
- Technical lead on **data warehouse infrastructure** (S3, Hive, Presto, Airflow, Redash, Metabase) handling **15TB of new daily data**
- Built internal Java API for geoquerying (Redis, PostgreSQL, Elasticsearch) serving **1M requests/min** at daily peak
- Built distributed system to calculate **lift of mobile ads** on real-world venue visits
- Developed fraud detection API for digital bank account openings via historical geolocation validation

**Data Scientist & Software Engineer Intern**  
*February 2016 – August 2016*

- Cross-functional statistical analysis support across mobile, ops, marketing, product, and sales teams using Spark (Scala), Presto, Hadoop MapReduce, AWS EMR

---

### Motorola / CIn Partnership — Recife, Brazil
**Research Assistant** | *September 2015 – June 2016*

Applied NLP and ML to detect emerging product quality issues and customer dissatisfaction signals from crawled social media data.

---

### Arizona State University — Tempe, AZ
**Undergraduate Researcher** | *June 2015 – August 2015*

NLP and deep learning for Twitter sentiment analysis; contributed to the TweetTracker platform for tracking and understanding Twitter activity at scale.

---

### Federal University of Pernambuco — Recife, Brazil
**Research Assistant** | *August 2012 – August 2013*

Undergraduate research on facial recognition techniques and their applications.

---

## Education

**Master's Degree, Computer Science**  
Federal University of Pernambuco — 2020–2021

**Bachelor's Degree, Computer Science**  
Federal University of Pernambuco — 2012–2016

**Exchange Program, Computer Science**  
Stevens Institute of Technology — 2014–2015

---

## Skills

**Core Expertise:** Machine learning, causal inference, experimental design, statistical modeling, deep learning, NLP, credit risk modeling, ML system design, policy optimization

**Languages & Frameworks:** Python (pandas, numpy, scikit-learn, statsmodels, scipy, keras/tensorflow, fklearn), R (Shiny), Scala, Java, Go

**Data Engineering:** Apache Spark/PySpark, Apache Airflow, MLflow, Hive, Presto, Redash, Metabase

**Databases:** PostgreSQL, Cassandra/Scylla, Redis, Elasticsearch, MongoDB

**Infrastructure:** Kubernetes, AWS (S3, EMR), GCP

---

## Certifications

- Applied Causal Inference
- Inferring Causal Effects from Observational Data
- Building Web Applications with Shiny in R

---

## Honors & Awards

- BSMP Scholarship (Brazil Scientific Mobility Program)
- Young Talent for Science

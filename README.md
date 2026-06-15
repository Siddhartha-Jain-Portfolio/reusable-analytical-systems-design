# Reusable Systems

## Reusable Continuity Across ML and NLP Workflows

### Overview

Most analytical projects are built for a specific dataset and remain largely unchanged once the analysis is complete. When new market data, news data, or earnings data becomes available, parts of the workflow often need to be updated, rebuilt, or manually restructured before new insights can be generated.

This project explores whether previously developed Machine Learning (ML) and Natural Language Processing (NLP) workflows can function as reusable analytical systems capable of supporting future data continuity without rebuilding the underlying architecture.

---

## Why This Project Matters

Analytical systems become significantly more valuable when they can continue operating as new information becomes available.

Rather than creating new models or developing new NLP signals, this project focuses on understanding whether existing workflows can absorb future data while preserving operational continuity, structural stability, and analytical usefulness over time.

---

## Project Objective

To evaluate whether existing ML and NLP workflows can support future data integration through reusable processes, stable schemas, and preserved downstream continuity.

The project focuses on answering a simple question:

> Can future data enter the same analytical architecture without requiring the entire workflow to be rebuilt?

---

## Data Used

### Machine Learning Workflow

* Historical stock return data
* Nifty index return data

### Natural Language Processing Workflow

* Financial news dataset
* Earnings communication dataset

These datasets were used to test whether future compatible data could be integrated into the existing workflows while preserving downstream functionality.

---

## Project Approach

The project was executed through four stages:

### 1. System Structure Understanding

Understanding how the existing ML and NLP workflows were built, how their components interacted, and which parts of the architecture supported continuity.

### 2. Schema Continuity Evaluation

Identifying the structural conditions required for future data to enter the workflows without breaking downstream dependencies.

### 3. ML Workflow Continuity Testing

Building a reusable market-data ingestion framework and validating whether new market data could be appended while preserving views, models, predictions, and analytical outputs.

### 4. NLP Workflow Continuity Testing

Building reusable news and earnings data ingestion processes and validating whether NLP signals could be regenerated while maintaining compatibility with downstream analysis.

---

## Key Findings

* Schema continuity is the foundation of reusable analytical systems.
* The ML workflow supports continuity through a centralized dependency-connected architecture.
* The NLP workflow supports continuity through a modular signal-based architecture.
* Future compatible data can be integrated without rebuilding the overall workflow.
* Reusability depends on validation and operational discipline rather than complete automation.
* Human interpretation remains important, particularly within higher-level NLP theme analysis.

---

## Project Files

### Documentation

* `Reusable_Systems_Project_Report.pdf`  
  Final project report containing methodology, findings, interpretation, and conclusions.

* `Reusable_Systems_Project_Summary.pdf`  
  Concise summary of the project, findings, and key takeaways.

* `Reusable_Systems_Project_Working_Analysis.pdf`  
  Detailed working document containing the step-by-step analytical process followed throughout the project.

### Datasets

* `reusable_systems_ml_stocks_returns.csv`
* `reusable_systems_nlp_news_data.csv`
* `reusable_systems_nlp_earnings_data.csv`

---

## Tools & Technologies

* BigQuery SQL
* BigQuery ML
* Python
* Jupyter Notebook
* Pandas
* VADER Sentiment Analysis
* spaCy
* Google News RSS
* Microsoft Excel

---

## Final Insight

The most important outcome of the project is that reusable analytical systems are not created through complete automation. They are created through stable architectures, schema continuity, reusable ingestion processes, and controlled operational workflows that allow future compatible data to move through an existing system without rebuilding the entire analytical structure.

The project demonstrates that both ML and NLP workflows can evolve beyond one-time analytical projects and function as reusable analytical systems capable of supporting future data continuity.

---

## Author

**Siddhartha Jain**

PGDM Finance | AI/ML & Data Analytics Portfolio

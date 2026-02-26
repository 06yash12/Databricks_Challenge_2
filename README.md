<img width="1580" height="300" alt="image" src="https://github.com/user-attachments/assets/41ce34aa-ebf7-49c1-9545-8ca65807d2fe" />


<div align="center">

# Databricks 14-Days of AI Challenge - 2

</div>

After successfully completing Challenge 1, I’m stepping into Challenge 2 with deeper focus and higher intensity. This phase pushes me to build more production-ready pipelines, strengthen core concepts and think beyond basics.

Excited to sharpen my Databricks, Spark and AI engineering skills through real-world implementation — learning, building and leveling up every single day.

Grateful for the support and initiative by [Databricks,](https://databricks.com/) [Codebasics](https://codebasics.io/) and [Indian Data Club.](https://www.linkedin.com/company/indian-data-club/)

# Day 0 (19/02/26) – Setup & Data Loading  

Focused on building a strong data foundation before starting advanced engineering workflows.

What I completed:→ Configured Databricks workspace and cluster  → Set up Kaggle API credentials securely  → Created schema and managed volume for structured storage  → Downloaded and extracted the e-commerce dataset from Kaggle  → Loaded October & November 2019 data into Spark DataFrames  → Validated schema (9 columns) and verified row counts  

Setup complete. Data validated. Ready for engineering.

---

# PHASE 1: BETTER DATA ENGINEERING (Days 1–4)

# Day 1 (20/02/26) – Delta Conversion & Optimization  

Completed Day 1 of Challenge 2, focusing on production-style data engineering using Delta Lake.

What I Learned Today:→ Delta vs Parquet differences  → Small file problem in distributed systems  → Table optimization using OPTIMIZE  → Performance-first engineering mindset  

Tasks I Completed:→ Converted raw CSV data into Delta format  → Created managed Delta table  → Simulated small file problem using multiple appends  → Applied OPTIMIZE to improve table performance  

From raw data ingestion to optimized Delta tables — moving toward production-grade architecture.

<img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/0d52df26-35fd-4777-9e24-730a8d9a1a3d" />

<img width="1919" height="816" alt="image" src="https://github.com/user-attachments/assets/e51ddd5a-8d91-4c90-b528-71960038c8d3" />

# Day 2 (21/02/26) – Feature Table (Silver Layer Thinking)

Completed Day 2 focusing on production-style feature engineering and structured Silver layer design.

What I Learned Today:
→ Bronze → Silver → Gold data architecture and why layered systems matter
→ How feature engineering works in real production pipelines
→ User-level aggregation strategy for ML-ready datasets
→ Building clean, deduplicated feature tables for downstream modeling

Tasks I Completed:
→ Engineered user-level aggregated features from raw event data
→ Built a structured Silver layer feature table
→ Saved the table in Delta format for reliability and scalability
→ Validated feature quality and ensured zero duplicate user records

<img width="1919" height="905" alt="image" src="https://github.com/user-attachments/assets/e804d5ef-8ddd-4cad-a46e-a7f2e20d2a59" />

<img width="1916" height="907" alt="image" src="https://github.com/user-attachments/assets/0a3ad0d0-1a19-4d77-aad8-15b537b05840" />

<img width="1919" height="901" alt="image" src="https://github.com/user-attachments/assets/1aa34dd6-5816-45e8-83e2-9412a8a5b8b6" />

# Day 3 (22/02/26) –  Job Orchestration Basics

Completed Day 3 focusing on production-grade job orchestration and automation in Databricks.

What I Learned Today:
→ Difference between interactive notebooks and production jobs
→ How parameterized notebooks enable reusable, environment-driven pipelines
→ Basic job scheduling for automated daily execution
→ Structuring modular code for scalable data workflows

Tasks I Completed:
→ Added widget parameters to control notebook execution dynamically
→ Modularized feature engineering logic into clean reusable functions
→ Created a production Job in Databricks UI
→ Configured a daily scheduled run for automated pipeline execution

<img width="1919" height="897" alt="image" src="https://github.com/user-attachments/assets/71b8b4c4-3cfe-41d4-b6d2-ec15bcbee587" />

<img width="1918" height="901" alt="image" src="https://github.com/user-attachments/assets/ee934e17-ea98-4eac-b2db-890ef858497c" />

<img width="1916" height="908" alt="image" src="https://github.com/user-attachments/assets/54beaf05-01c8-45f1-ae0b-f90035310e81" />

# Day 4 (23/02/26) – Structured Streaming (Basic Simulation)

Completed Day 4 focusing on real-time data processing and streaming architecture in Databricks.

What I Learned Today:
→ How micro-batch processing works in Structured Streaming
→ The role of checkpointing in fault tolerance and recovery
→ Writing streaming outputs directly into Delta tables
→ How streaming pipelines differ from batch workflows

Tasks I Completed:
→ Simulated streaming ingestion from a folder source
→ Configured checkpointing for reliable state management
→ Wrote streaming aggregation output to a Delta table
→ Queried and validated streaming results using Spark SQL

<img width="1919" height="896" alt="image" src="https://github.com/user-attachments/assets/98faeffa-bc4f-4ea7-94a1-2803ed902fbe" />

<img width="1919" height="898" alt="image" src="https://github.com/user-attachments/assets/562b5e1f-f93a-4bd8-98be-cb4c2bb16b82" />

# Day 5 (24/02/26) – Production-Grade Feature Engineering

Completed Day 5 focusing on building clean, model-ready datasets for machine learning.

What I Learned Today:
→ How to create binary classification targets from raw event data
→ Joining engineered feature tables with target labels
→ Proper train-test splitting strategies
→ Detecting and validating class imbalance in datasets

Tasks I Completed:
→ Created a binary purchase label from event-level data
→ Joined label data with silver feature tables
→ Split dataset into training and testing sets
→ Validated label distribution across both splits

<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/9182788f-5436-4958-b7ae-56c5891e7682" />

<img width="1919" height="896" alt="image" src="https://github.com/user-attachments/assets/4ef62c44-d861-4ab9-92ca-25e4e2cc9eae" />

<img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/43047de9-e2c1-4139-a27d-2c280512a694" />

# Day 6 (25/02/26) – Model Training & Tuning

Completed Day 6 focusing on applied machine learning model training and evaluation.

What I Learned Today:
→ Logistic Regression fundamentals in Spark ML
→ RandomForest classifier implementation
→ Model evaluation using AUC (Area Under ROC)
→ Importance of training vs test evaluation

Tasks I Completed:
→ Trained a Logistic Regression model
→ Trained a RandomForest classifier
→ Evaluated both models using AUC
→ Compared performance to identify the stronger model

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/c26d23cd-c1fb-45a7-86dd-d4b9ec1f2f08" />

<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/02381272-e36c-4379-825c-6004ffb14533" />

<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/74936da6-02fe-47ac-82c9-be534b4e8af8" />

<img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/2823bccc-61ee-4813-9b98-17da780fe57d" />

<img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/551a3fa8-5b53-4c28-85ee-7441fd768beb" />

<img width="1919" height="865" alt="image" src="https://github.com/user-attachments/assets/6e8db758-98e8-4922-b1f6-9e13f8325616" />

# Day 7 (26/02/26) – MLflow Tracking

Completed Day 7 focusing on experiment tracking and model lifecycle management using MLflow.

What I Learned Today:
→ How MLflow tracks experiments and parameters
→ Logging metrics and artifacts programmatically
→ Comparing model runs inside MLflow UI
→ Basic model versioning concepts

Tasks I Completed:
→ Logged training runs into MLflow
→ Recorded evaluation metrics and parameters
→ Compared multiple model experiments
→ Registered model versions for reproducibility

<img width="1917" height="909" alt="image" src="https://github.com/user-attachments/assets/c5ea0d17-4bf2-43b2-98a7-f5f0f64acb09" />

<img width="1919" height="898" alt="image" src="https://github.com/user-attachments/assets/9f20da7e-5be8-4a1c-a08b-9af5fc1d22b7" />

<img width="1919" height="854" alt="image" src="https://github.com/user-attachments/assets/e1d915e9-4034-4c88-ace7-0b341558cd0d" />

<img width="1919" height="903" alt="image" src="https://github.com/user-attachments/assets/7fa6818e-05cb-491f-a6ca-d97dca9c2c5e" />

<img width="1919" height="861" alt="image" src="https://github.com/user-attachments/assets/03f2e183-56c1-46e7-950d-81aec4fd0438" />
















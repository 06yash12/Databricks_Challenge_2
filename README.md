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

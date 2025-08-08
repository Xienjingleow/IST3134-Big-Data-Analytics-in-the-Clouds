# IST3134 Big Data Analytics in the Clouds

This repository contains the source code, execution steps, and output files for the IST3134 Big Data Analytics group assignment (April 2025).

## Objective
Identify products with:
- Conversion Rate < 5%
- Revenue > 1000  
from a large e-commerce dataset.

## Implementations
- **Python** (MapReduce)
- **Java** (MapReduce)
- **Spark** (Non-MapReduce)

## Contents
- `.txt` – Step-by-step execution guides and source code.
- `.csv` – Output files from each implementation.
- `README.md` – Project overview and instructions.

## How to Use
1. Prepare HDFS environment (see `HDFS Environment Preparation.txt`).
2. Run the desired implementation (`Python.txt`, `Java.txt`, `Spark.txt`).
3. Check output CSV or upload to S3 as instructed in the steps.

## Dataset
E-commerce behavior data from multi-category store (Nov 2019).  
Original dataset size: **9.01 GB**.
Source: [Kaggle – E-Commerce Behavior Data from Multi-Category Store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store?select=2019-Nov.csv).

## Runtime Comparison

| Implementation | Approach      | Runtime      |
|----------------|---------------|--------------|
| Python         | MapReduce     | 4 min 43 sec |
| Java           | MapReduce     | 3 min 50 sec |
| Spark          | Non-MapReduce | 1 min 49 sec |

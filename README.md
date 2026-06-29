#  Movie Recommendation System using Apache Spark (ALS)

<div align="center">

#  Personalized Movie Recommendation System

A scalable movie recommendation system built with **Apache Spark MLlib** using the **Alternating Least Squares (ALS)** collaborative filtering algorithm and the **MovieLens 25M** dataset.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-MLlib-orange?logo=apachespark)
![PySpark](https://img.shields.io/badge/PySpark-Big%20Data-red)
![MovieLens](https://img.shields.io/badge/Dataset-MovieLens%2025M-green)

</div>

---

#  Project Overview

This project develops a personalized movie recommendation engine using **PySpark** and **Apache Spark MLlib**. It downloads the **MovieLens 25 Million** dataset, processes movie ratings, trains an **ALS (Alternating Least Squares)** collaborative filtering model, and recommends movies for users based on their rating history.

---

#  Objectives

- Build a scalable recommendation engine.
- Learn collaborative filtering using ALS.
- Process large datasets efficiently with Apache Spark.
- Recommend personalized movies for users.

---

#  Features

- Automatic MovieLens 25M dataset download
- Data loading with PySpark DataFrames
- Exploratory analysis of movies and ratings
- Average rating and popularity calculation
- Train/Test split
- ALS recommendation model
- Top-N personalized movie recommendations
- Big-data processing with Spark

---

#  Technologies Used

- Python
- Apache Spark
- PySpark
- Spark MLlib
- MovieLens 25M Dataset

---

#  Dataset

**Source:** GroupLens MovieLens 25M

Files used:
- movies.csv
- ratings.csv

---

#  Workflow

1. Install PySpark
2. Create Spark Session
3. Download MovieLens dataset
4. Load movie and rating data
5. Explore the datasets
6. Compute average ratings
7. Join movie metadata
8. Split training and testing data
9. Train ALS model
10. Generate Top-5 movie recommendations
11. Display recommended movie titles

---

#  Model Configuration

| Parameter | Value |
|-----------|-------|
| Algorithm | ALS (Alternating Least Squares) |
| maxIter | 5 |
| regParam | 0.01 |
| userCol | userId |
| itemCol | movieId |
| coldStartStrategy | drop |

---

#  Output

The notebook generates:

- Top-rated movies
- Personalized Top-5 movie recommendations
- Predicted movie ratings

---

#  Installation

```bash
pip install pyspark
```

---

#  Repository Structure

```text
.
├── Movie recommendation system.ipynb
└── README.md
```

---

#  How to Run

1. Install PySpark.
2. Run all notebook cells.
3. The dataset is downloaded automatically.
4. Train the ALS model.
5. View personalized movie recommendations.

---

#  Future Improvements

- Hyperparameter tuning with CrossValidator
- Deploy as a Streamlit web app
- Content-based recommendation
- Hybrid recommendation system
- Movie poster integration
- REST API deployment

---

#  Author

**Arijit Dasgupta**

Data Analytics | Machine Learning | Big Data

---



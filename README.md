# VisionZero – Accident Severity Predictor

## Urban Infrastructure & Public Safety Datathon Project

VisionZero is a machine learning-based accident severity prediction system designed to analyze road accident data and forecast accident severity levels using real-world post-crash reports.

The project addresses a critical public safety challenge by identifying the factors that contribute to severe accidents and providing data-driven recommendations for reducing serious injuries on roads.

---

## Problem Statement

Traffic accidents are rarely caused by a single factor. They result from a combination of road conditions, weather, lighting, vehicle defects, road alignment, driver behavior, and environmental conditions.

The objective of this project is to build a robust multi-class classification model capable of predicting:

**Accident Severity**

* Slight Injury
* Serious Injury
* Other severity categories

using historical road accident records.

In addition to prediction, the project aims to uncover the major causes of severe accidents and generate actionable recommendations for traffic authorities.

---

## Objectives

* Analyze accident records and identify key risk factors.
* Perform deep categorical data analysis.
* Build a multi-class accident severity prediction model.
* Handle class imbalance in accident data.
* Evaluate model performance using F1-based metrics.
* Provide infrastructure and policy recommendations to reduce severe accidents.

---

## Dataset

**Dataset File:** `Road.csv`

The dataset contains accident-related information including:

* Weather Conditions
* Road Surface Conditions
* Road Alignment
* Vehicle Types
* Lighting Conditions
* Environmental Factors
* Driver and Vehicle Information
* Accident Severity Labels

---

## Project Workflow

### 1. Data Understanding

* Explore accident records
* Study feature distributions
* Identify missing values
* Analyze target class distribution

### 2. Data Preprocessing

* Data cleaning
* Missing value handling
* Duplicate removal
* Feature transformation

### 3. Categorical Feature Encoding

The dataset contains several high-cardinality categorical features.

Encoding techniques used include:

* One-Hot Encoding
* Label Encoding
* Feature Transformation

Examples:

* Weather Conditions
* Vehicle Types
* Road Alignment
* Junction Details

### 4. Handling Class Imbalance

Accident severity datasets typically contain imbalanced class distributions.

Techniques considered:

* SMOTE
* Class Weighting
* Undersampling
* Balanced Training Strategies

### 5. Exploratory Data Analysis

* Severity Distribution Analysis
* Accident Trend Analysis
* Risk Factor Identification
* Correlation Analysis

### 6. Model Development

A Multi-Class Classification model was developed to predict accident severity based on accident attributes.

Possible algorithms explored:

* Random Forest
* Decision Tree
* XGBoost
* Gradient Boosting
* Other Classification Models

### 7. Model Evaluation

Since accuracy alone can be misleading for imbalanced datasets, evaluation focuses on:

* Macro F1 Score
* Micro F1 Score
* Precision
* Recall
* Confusion Matrix

---

## Key Insights

The project identifies critical factors contributing to severe road accidents, including:

* Poor weather conditions
* Road alignment issues
* Vehicle-related defects
* Unsafe road infrastructure
* Environmental and visibility challenges

These insights help prioritize road safety interventions.

---

## Policy & Infrastructure Recommendations

Based on data analysis, the project proposes evidence-based recommendations for traffic authorities:

### 1. Improve High-Risk Road Segments

* Redesign dangerous intersections
* Improve road alignment
* Upgrade road markings

### 2. Enhance Lighting & Visibility

* Install smart street lighting
* Improve visibility in accident-prone zones

### 3. Strengthen Traffic Safety Measures

* Targeted enforcement in high-risk areas
* Improved warning systems
* Public safety awareness initiatives

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Repository Structure

```text
VisionZero-Accident-Severity-Predictor/
│
├── data/
│   └── Road.csv
│
├── notebook/
│   └── VisionZero_Colab.ipynb
│
├── docs/
│   └── Datathon_ProblemStatement.docx
│
├── presentation/
│   └── VisionZero-Predictor.pptx
│
├── README.md
└── requirements.txt
```

---

## Real-World Impact

This project supports the Vision Zero initiative by leveraging machine learning to:

* Predict accident severity
* Improve emergency response planning
* Guide infrastructure investments
* Enhance urban traffic safety
* Support smart-city decision-making

---

## Learning Outcomes

* Advanced categorical feature engineering
* Handling real-world class imbalance
* Multi-class classification modeling
* Policy-oriented data analysis
* Data-driven public safety decision making

---

## Team

* Savanth G
* Pardeen
* Vikas
* Pasha

---

## License

This project is developed for educational and datathon purposes.

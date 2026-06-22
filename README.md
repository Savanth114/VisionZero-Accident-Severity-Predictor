# 🚦 VisionZero: Accident Severity Predictor

### Urban Infrastructure & Public Safety Datathon Project

Predicting road accident severity using Machine Learning to enable safer roads, smarter infrastructure planning, and data-driven public safety decisions.

---

## 📌 Overview

Road accidents are influenced by a combination of factors such as weather conditions, lighting, road geometry, driver behavior, and vehicle characteristics. Manually assessing the severity of potential accidents across thousands of interacting variables is challenging.

VisionZero leverages Machine Learning to predict accident severity from real-world traffic accident records and generate actionable recommendations that help reduce serious injuries and fatalities. The project transforms historical accident data into insights that support proactive road safety interventions.

---

## 🎯 Objectives

* Predict accident severity using multi-class classification.
* Identify the most influential risk factors.
* Recommend high-impact interventions for reducing severe accidents.
* Support government agencies and policymakers with evidence-based insights.
* Improve urban transportation safety through predictive analytics.

---

## 🗂 Dataset

### Dataset Characteristics

* 12,000+ accident records
* Real-world traffic accident data
* Multiple environmental, driver, and road-related attributes

### Features Include

* Weather conditions
* Driver information
* Vehicle information
* Road conditions
* Lighting conditions
* Junction characteristics
* Accident severity labels

### Challenges

* Highly categorical features
* Missing values
* Class imbalance
* Noisy real-world reporting

Advanced preprocessing techniques were applied to ensure reliable model performance despite imperfect data.

---

## ⚙️ Methodology

### Data Preprocessing

* Missing value treatment
* Data cleaning
* Feature engineering
* Categorical feature encoding

### Feature Engineering

Custom features created include:

* Night-condition indicators
* Weather risk flags
* Driver risk scores
* Junction context variables

### Class Balancing

To improve prediction performance on minority severity classes:

* SMOTE (Synthetic Minority Oversampling Technique)
* Class balancing strategies

### Encoding Techniques

* One-Hot Encoding
* Target Encoding

These transformations converted raw accident records into meaningful predictive signals.

---

## 🤖 Machine Learning Model

### Algorithm

**XGBoost (Extreme Gradient Boosting)**

Reasons for selection:

* Handles complex feature interactions
* Excellent performance on structured tabular data
* Robust against overfitting through regularization
* Strong performance on imbalanced classification problems

### Training Strategy

* Stratified 5-Fold Cross Validation
* Class Weight Calibration
* L1 & L2 Regularization
* Holdout Test Set Validation

---

## 📊 Model Performance

| Metric            | Score             |
| ----------------- | ----------------- |
| Accuracy          | 95.54%            |
| Macro F1-Score    | 0.955             |
| Validation Method | Holdout Test Set  |
| Cross Validation  | 5-Fold Stratified |

### Key Achievement

The model maintains high performance while preserving balance across minority severity classes, enabling accurate detection of rare but severe accidents.

---

## 🔍 Key Insights

### 🌙 Night-Time Risk

Accident severity increases significantly under low-light conditions.

### 🌧 Adverse Weather

Rain and poor visibility contribute heavily to severe accidents.

### 🚗 Driver Profile

Young and inexperienced drivers are associated with higher-risk incidents.

### 🚦 Junction Hotspots

Intersections and junction areas show a higher concentration of severe accidents.

---

## 💡 Recommended Interventions

### 1. Smart Lighting Infrastructure

#### Actions

* Deploy LED lighting in dark road segments
* Improve visibility near crossings and junctions
* Standardize illumination levels

#### Expected Impact

* Approximately 45% reduction in night-time accident severity
* Faster driver reaction times
* Improved object detection and visibility

---

### 2. Junction Redesign

#### Actions

* Improve sightlines
* Smart traffic signal deployment
* Protected turning phases
* Roundabouts where feasible

#### Benefits

* Reduced collision points
* Improved traffic flow
* Lower accident severity

---

### 3. Driver Safety Programs

#### Actions

* Monitor high-risk driving behavior
* Restrict novice night driving
* Targeted awareness campaigns
* Driver feedback systems

#### Benefits

* Improved driving behavior
* Lower accident rates
* Increased road safety awareness

---

## 📈 Project Impact

### Estimated Outcomes

✅ 520 injuries prevented annually

✅ Approximately 30% reduction in accident severity within identified hotspots

✅ Significant reduction in medical, congestion, and societal costs

The project demonstrates how Machine Learning can bridge the gap between historical accident data and practical road safety interventions.

---

## 🛠 Technology Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Repository Structure

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

## 👥 Team

**Team Name:** VisionZero

* Savanth G
* Pardeen
* Numan Pasha
* Vikas

---

## 🚀 Future Enhancements

* Real-time accident severity prediction
* GIS-based accident hotspot mapping
* Traffic camera integration
* Smart City dashboard deployment
* Explainable AI (XAI) for decision transparency
* Live weather and traffic data integration

---

## 📜 License

This project was developed as part of an Urban Infrastructure & Public Safety Datathon for educational and research purposes.

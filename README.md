# VisionZero: Accident Severity Predictor

## Overview

VisionZero is a machine learning-based accident severity prediction system developed to support road safety initiatives and help authorities identify high-risk accident scenarios. The project analyzes road accident data and predicts the severity of accidents based on various contributing factors.

The goal is to assist policymakers, traffic management authorities, and urban planners in making data-driven decisions to reduce road accidents and improve public safety.

---

## Problem Statement

Road accidents are a major cause of injuries and fatalities worldwide. Predicting accident severity before incidents occur can help authorities implement preventive measures, optimize emergency response systems, and improve road infrastructure planning.

This project aims to:

* Analyze historical road accident data
* Identify key factors influencing accident severity
* Build a predictive machine learning model
* Generate insights for accident prevention strategies

---

## Dataset

The dataset contains road accident records with multiple features related to:

* Road conditions
* Weather conditions
* Traffic information
* Vehicle-related factors
* Environmental conditions
* Accident severity labels

### Dataset File

```text
Road.csv
```

---

## Project Structure

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

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Machine Learning Workflow

### 1. Data Collection

* Import accident dataset
* Load data into Python environment

### 2. Data Preprocessing

* Handle missing values
* Remove duplicates
* Feature encoding
* Data cleaning

### 3. Exploratory Data Analysis (EDA)

* Severity distribution analysis
* Feature correlation analysis
* Accident trend visualization

### 4. Feature Engineering

* Selection of important attributes
* Data transformation
* Scaling and normalization

### 5. Model Development

* Train machine learning models
* Compare model performance
* Optimize prediction accuracy

### 6. Evaluation

Performance evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Key Features

* Road accident severity prediction
* Data visualization and analytics
* Risk factor identification
* Machine learning-based classification
* Decision-support insights for road safety

---

## Results

The developed model successfully identifies accident severity levels based on historical accident data and associated environmental factors.

The insights generated can help:

* Improve road safety planning
* Support emergency response prioritization
* Identify accident-prone conditions
* Assist traffic authorities in preventive measures

---

## Future Improvements

* Real-time accident risk prediction
* Integration with GIS mapping systems
* Deep Learning-based prediction models
* Weather API integration
* Smart city traffic management integration
* Explainable AI (XAI) implementation

---

## Presentation

Project presentation:

```text
VisionZero-Predictor.pptx
```

---

## Datathon Submission

This project was developed as part of a Datathon competition focused on leveraging data analytics and machine learning techniques to address real-world road safety challenges.

---

## Team

### Team Members

* Savanth G
* Pardeen
* Vikas
* Pasha

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/VisionZero-Accident-Severity-Predictor.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
VisionZero_Colab.ipynb
```

---

## License

This project is intended for academic and educational purposes.

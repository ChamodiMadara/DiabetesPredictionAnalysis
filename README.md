# **DiabetesPredictionAnalysis**

A Python-based project for analyzing diabetes risk factors and predicting diagnoses. This repository includes a clinical dataset and a detailed Jupyter Notebook for data exploration, feature analysis, and predictive modeling.

---

## **Contents**

- **`diabetes_data_upload.csv`**: The dataset used for analysis.
- **`Diabetes_Data_Exploration.ipynb`**: A Jupyter Notebook containing data exploration, feature summaries, and visualizations.

---

## **Dataset Overview**

The dataset contains clinical and demographic information used to predict diabetes risk. Key features include:

- **Age**: The age of the patient.
- **Gender**: Male/Female.
- **Polyuria**: Presence of excessive urination (Yes/No).
- **Polydipsia**: Presence of excessive thirst (Yes/No).
- **Sudden Weight Loss**: Experience of sudden weight loss (Yes/No).
- **Weakness**: Feeling of weakness (Yes/No).
- **Polyphagia**: Increased appetite (Yes/No).
- **Genital Thrush**: Occurrence of genital thrush (Yes/No).
- **Visual Blurring**: Instances of visual blurring (Yes/No).
- **Itching**: Presence of itching (Yes/No).
- **Irritability**: Presence of irritability (Yes/No).
- **Delayed Healing**: Slow healing of sores or wounds (Yes/No).
- **Partial Paresis**: Muscle weakness or paresis (Yes/No).
- **Muscle Stiffness**: Stiffness in muscles (Yes/No).
- **Alopecia**: Hair loss (Yes/No).
- **Obesity**: Obesity (Yes/No).
- **Class**: Target variable indicating diabetes diagnosis (Positive/Negative).

---

## **How to Use**

### Clone the Repository

```bash
git clone https://github.com/YourUsername/DiabetesPredictionAnalysis.git
cd DiabetesPredictionAnalysis
```

## **Install Dependencies**

Ensure you have Python installed on your system. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib tabulate
```
## **Run the Jupyter Notebook**
Open the notebook for data exploration and analysis:

```bash
jupyter notebook Diabetes_Data_Exploration.ipynb
```
---
## **Explore the Data**

- **View dataset samples and descriptive statistics**:  
  Understand the dataset by observing random samples and summarizing key statistics for each feature.

- **Analyze relationships and patterns between features**:  
  Investigate how features relate to one another to identify potential correlations and trends.

- **Use visualizations to understand the dataset better**:  
  Create plots such as histograms, bar charts, scatter plots, and boxplots to gain deeper insights into the dataset.
---
## **Project Features**

- **Data Cleaning**:
  - Missing values were handled and inconsistencies in the data were resolved to ensure high-quality inputs for analysis.
  - Categorical variables were encoded, and numerical variables were scaled as needed to prepare the data for visualization and modeling.
  - These steps were crucial for maintaining the accuracy and interpretability of the analysis.

- **Exploratory Data Analysis**:
  - Visual explanations were created to understand the structure of the data, uncover patterns, and identify trends:
    - **Histograms** were used to explore the distribution of numerical variables like `Age`.
    - **Bar charts** helped analyze categorical variables such as `Gender` and `Class`.
    - **Scatter plots** were used to examine relationships between features (e.g., `Age` vs. `Sudden Weight Loss`).
  - The purpose of these visualizations was to identify potential correlations, outliers, and imbalances in the dataset, which informed the subsequent modeling approach.
---
## **Technologies Used**

- **Python**: Core programming language.

- **Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `numpy`: For numerical computations.
  - `matplotlib`: For visualizations.
  - `tabulate`: For tabular data display.

---

## **Acknowledgments**

This project is based on an open-source dataset and is intended for educational purposes. Special thanks to the data providers and contributors from the open-source community.



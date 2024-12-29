# Heart-Failure-Prediction-and-EDA


This repository focuses on the **Exploratory Data Analysis (EDA)** and **predictive modeling** on patient health data, particularly aimed at analyzing cardiac conditions such as heart failure. Using statistical insights and machine learning algorithms, the project derives meaningful patterns and builds models to predict health outcomes.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Key Insights](#key-insights)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Project Overview
Healthcare data contains critical insights that can be leveraged to improve patient care and predict complications. This project includes:
- **EDA**: Visualization and analysis of trends in patient demographics and health outcomes.
- **Predictive Modeling**: Training multiple machine learning models to predict heart failure based on key health indicators such as Urea, HFREF, and HFNEF.

---

## Datasets
The project analyzes health-related data containing information such as:
- Age, Gender, and Duration of stay in the intensive care unit.
- Alcohol consumption and its relation to diabetes and hypertension.
- Presence of conditions such as Acute Kidney Injury (AKI), Acute Coronary Syndrome (ACS), and heart failure (HF).

**Features include:**
- `AGE`
- `GENDER`
- `DOCTORS NOTE`
- `HEART FAILURE`
- `DURATION OF INTENSIVE UNIT STAY`
- And more...

---

## Key Insights
1. **Gender and Age Distribution**: Analyzed gender-wise variation in Ejection Fraction (EF) and Age.
2. **Alcohol and Diabetes Correlation**: Observed how alcohol consumption influences diabetes in males and females.
3. **Longest ICU Stay Analysis**: Found the longest duration of stay and related details such as doctor's notes and admission dates.
4. **Health Risks**: Explored the combined impact of diabetes (DM) and hypertension (HTN) across age groups.

---

## Machine Learning Models
The following machine learning models were implemented to predict health outcomes:
1. **Logistic Regression**  
2. **K-Nearest Neighbors (KNN)**  
3. **Decision Tree Classifier**  
4. **Random Forest Classifier**  
5. **Naive Bayes**  
6. **Support Vector Machine (SVM)**  

Each model was evaluated using metrics such as:
- **Precision**
- **Accuracy**
- **Confusion Matrix**

---

## Results
| Model               | Precision | Accuracy |
|---------------------|-----------|----------|
| Logistic Regression | 1.000     | 100.%    |
| KNN                 | 0.986     | 98.4%    |
| Decision Tree       | 1.000     | 99.9%    |
| Random Forest       | 1.000     | 99.9%    |
| Naive Bayes         | 0.988     | 99.6%    |
| SVM                 | 0.557     | 67.5%    |


---

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Patient-Health-EDA-and-Modeling.git
    ```
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

---

## Usage
1. Open the Jupyter Notebook file `patientfinal.ipynb`.
2. Follow the EDA and modeling steps to analyze the dataset and build predictive models.
3. Customize the notebook or use your own dataset for analysis.

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Description of changes"`).
4. Push to the branch (`git push origin feature-name`).
5. Create a Pull Request.


---

## Acknowledgments
- Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn
- Tools: Jupyter Notebook, Python

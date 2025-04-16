# Heart Disease Prediction

<div align="left" style="line-height: 1;">
  <a href="https://github.com/kareem-ghazi/heart-disease-prediction/releases" target="_blank" style="margin: 2px;">
    <img alt="Latest Release" src="https://img.shields.io/badge/Latest%20Release-1.0-brightgreen" />
  </a>
  <a href="https://opensource.org/license/mit" target="_blank" style="margin: 2px;">
    <img alt="License" src="https://img.shields.io/badge/License-MIT-red" />
  </a>
  <a href="https://python.org/" target="_blank" style="margin: 2px;">
    <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" />
  </a>
  <a href="https://www.microsoft.com/windows" target="_blank" style="margin: 2px;">
    <img alt="Platform" src="https://img.shields.io/badge/Platform-Windows-blue?logo=windows" />
  </a>
</div>

## Introduction

Heart disease is a leading cause of death worldwide. Early detection and prediction of heart disease can significantly improve patient management and reduce mortality rates. This project aims to build a machine learning model to predict the presence of heart disease based on patient health data.

## Problem Definition

- **Problem Identification:** Heart disease occurs when the heart's blood supply is blocked or interrupted, often due to a build-up of fatty substances. Early prediction is crucial for timely intervention.
- **Impact Analysis:** Delayed diagnosis can result in severe complications, increased hospitalizations, higher medical costs, and reduced quality of life. Early prediction enables timely intervention and better patient outcomes.
- **Root Cause Exploration:** Diagnosing heart disease is challenging due to the complex nature of cardiovascular diseases, symptom variability, and the need for multiple diagnostic tests (e.g., ECG, echocardiography, biomarkers).
- **Scope Clarification:** This issue affects healthcare providers, cardiologists, patients with cardiovascular risk factors, and medical researchers, especially in areas with limited access to specialized cardiac care.
- **Stakeholder Involvement:** Key stakeholders include physicians, cardiologists, healthcare providers, researchers, and at-risk patients. Predictive models can assist professionals in making data-driven decisions.
- **Current Limitations:** Traditional diagnosis relies on symptoms, history, and imaging, which can be time-consuming and may miss early signs.
- **Desired Outcomes:** Develop a predictive model to assess heart disease risk based on patient data, providing early warnings and enabling timely intervention.
- **Constraints and Challenges:** Challenges include data availability/quality, dataset bias, model interpretability, and regulatory considerations for medical AI.
- **Potential Risks:** Inaccurate predictions may cause false alarms or missed diagnoses, impacting trust and decision-making. Ethical concerns include data privacy and model reliability.

## Technical Details

- **Type of Learning:** Supervised learning (binary classification using patient health data).
- **Dataset Type:** Tabular datasets with patient health records (age, blood pressure, cholesterol, ejection fraction, serum creatinine, etc.).
- **Deployment:** Desktop GUI application using CustomTkinter, allowing healthcare professionals to input patient data and receive risk predictions.

## Data Collection

We will be using the **Heart Failure Prediction Dataset** available on Kaggle, provided through the following link: [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)  

### Dataset Information  

This dataset was created by combining different datasets already available independently but not combined before. In this dataset, **5 heart datasets** are merged over **11 common features**, making it the **largest heart disease dataset** available for research purposes.  

The five datasets used for its curation are:  

- **Cleveland:** 303 observations  
- **Hungarian:** 294 observations  
- **Switzerland:** 123 observations  
- **Long Beach VA:** 200 observations  
- **Stalog (Heart) Data Set:** 270 observations  

**Total observations:** 1190  
**Duplicated observations:** 272  
**Final dataset size:** 918 observations

## Usage

1. Clone the repository.
2. Install the required Python libraries (see your notebook or requirements file).
3. Run the application or notebook to train and test the heart disease prediction model.
4. Use the GUI to input patient data and receive a risk prediction.

## License

This project is released under the [MIT](https://opensource.org/license/mit) license.

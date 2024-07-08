## Introduction
The goal of this project is to proactively address flight delays using predictive analytics, specifically leveraging deep learning techniques. By identifying patterns and factors contributing to delays, the airline aims to optimize scheduling and reduce disruptions. This project explores the effectiveness of deep learning models using both full and balanced datasets to predict delayed flights.

### 01 - Introduction to Flight Delay Prediction
- **Precision:**
  - Class 1: 0.65
  - Class 0: 0.82
- **Recall:**
  - Class 1: 0.04
  - Class 0: 0.99
- **F1-score:**
  - Class 1: 0.08
  - Class 0: 0.90

### 02 - Deep Learning with Full Dataset
- **Accuracy:** 81.40%
- **Precision:**
  - Class 1: 0.65
  - Class 0: 0.64
- **Recall:**
  - Class 1: 0.62
  - Class 0: 0.66
- **F1-score:**
  - Class 1: 0.64
  - Class 0: 0.65

### 03 - Deep Learning with Balanced Dataset
- **Accuracy:** 64.74%
- **Summary:**
  - **Full Dataset:** The model excels in overall accuracy and identifying non-delayed flights but struggles with identifying delayed flights.
  - **Balanced Dataset:** The model sacrifices some overall accuracy but significantly improves in identifying delayed flights, achieving a better balance in precision, recall, and F1-score for both classes.

### 04 - Conclusion: Full vs Balanced Datasets
From a business intelligence perspective, leveraging the balanced dataset model enhances customer satisfaction, operational efficiency, and proactive risk management despite the trade-off in overall accuracy.

### 05 - Comparative Analysis of Predictive Technologies
- **Unbalanced Dataset:**
  - MLP (Multi-layer Perceptron) for accuracy (81.69%)
  - Naive Bayes for sensitivity (100%)
  - LSTM for specificity (99%)
  - GLM (Generalized Linear Model) for precision (81.15%)
  - MLP for F1 Score (89.51%)
- **Balanced Dataset:**
  - LSTM for accuracy (64.74%)
  - Naive Bayes for sensitivity (88.80%)
  - Rpart for specificity (73.70%)
  - GLM for precision (60.14%)
  - Naive Bayes for F1 Score (66.20%)

### 06 - Strategies for Model Improvement
To enhance Accuracy, Sensitivity, Precision, Recall, and F1-score:
- **Improve Data Quality:** Include additional features like weather conditions and technical challenges.
- **Incorporate Time-related Data:** Factor in holidays and school vacations to uncover hidden patterns.
- **Experiment with Different Architectures:** Consider bidirectional LSTM and deeper models.
- **Apply Advanced Transformations:** Optimize data cleaning and preprocessing steps.
- **Utilize Various Techniques:** Implement early stopping, model ensembling, and hyperparameter optimization.

### 07 - Key Learnings of the Course
- **Balanced Datasets:** Enhance operational outcomes by mitigating bias.
- **LSTM Effectiveness:** Suitable for complex sequential data like flight schedules.
- **Importance of Data Preparation:** Critical for model success and feature engineering.
- **Model Selection:** Align models with performance needs and operational goals.
- **Continuous Improvement:** Essential for ongoing model refinement and real-world applicability.

## Conclusion
By strategically leveraging these insights, the airline can enhance its predictive capabilities, improve customer satisfaction, and optimize operational efficiency in managing flight delays.


<h2>Index:</h2>

<p align="center">
Figure 1: <br/>
<img src="https://i.imgur.com/7rzXMCe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Figure 2:  <br/>
<img src="https://i.imgur.com/Cb1hcyR.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />


Figure 3
![image](https://github.com/TomasMontoya1234455667889/Business-Intelligence-Project/assets/130658467/95049474-5037-4bb3-8ca3-4a3338a5f072)# Business Intelligence Final Module 7: Airline Flight Delay Prediction


Figure 4: <br/>
<img src="https://i.imgur.com/Cb1hcyR.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>




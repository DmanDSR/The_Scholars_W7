# The_Scholars_W7 - Predicting Student Dropout Rates Using Machine Learning

### By: Gian Villafane, Taisgaly Velez, Ricardo A. Torres, Dylan Sedeno

# Description

 Machine Learning project!

 [Trello](https://trello.com/invite/b/XPwTEmD7/ATTI9e7faf9f69c0139fca2cc4e9919246064C983571/the-scholars-week-7)

# Project Overview

Our main objective is to develop a predictive model that can accurately forecast the likelihood of students dropping out based on various indicators found within our dataset. These indicators include academic performance, attendance records, and socio-economic factors, among others. Implementing this model could significantly enhance educational institutions' ability to intervene proactively, offering targeted support to students who are most at risk.

# Data Selection and Preparation

### Selection 

**Source:** Collected from educational institutions over multiple academic years

- The dataset contains comprehensive academic and demographic information about students, including their grades, attendance records, and socio-economic backgrounds. Structured to highlight individual student trajectories, suitable for longitudinal analysis

- Data includes multiple academic years and is structured to highlight individual student trajectories, making it ideal for longitudinal analysis

### Preparation:

- **Verification of Data Integrity**: Checked for any missing values and inconsistencies; none were found.

- **Feature Selection**: Identified relevant features for predicting dropout rates based on educational insights and previous research.

- Our dataset required minimal preprocessing, allowing us to focus more on model selection and tuning to better predict student dropouts.

# Dataset Features Overview:

- **Socio-economic and Demographics:** Parental education, occupations, scholarship status, educational needs, marital status, nationality, age, gender.

- **Academic Performance and Admissions:** Qualifications, grades, semester-specific details (enrollments, approvals), application mode, order, and course type.

- **Financial and Economic Factors:** Debt status, tuition fee status, unemployment rate, GDP.

# Model Building and Evaluation 

- **Target Variable:** The target variable in our dataset is categorized into three distinct classes:
- **Dropout:** Students who have withdrawn from their courses.
- **Enrolled:** Students who are currently enrolled.
- **Graduate:** Students who have successfully completed their courses.

The model that yielded the best results was Random Forest, although its performance was closely matched by the other models used. Despite this, the differences in performance between the models were not significantly far apart. Logistic Regression was also employed for its simplicity and interpretability, providing a solid baseline for comparison. Additionally, we utilized Random Forest, which is celebrated for its robustness against overfitting and its effectiveness in handling unbalanced datasets.

**Gradient Boosting** gave the highest scoring in:

- **Accuracy:** 0.7988
- **Recall:** 0.7117
- **Precision:** 0.7517

<img width="429" alt="image" src="https://github.com/DmanDSR/The_Scholars_W7/assets/48893423/309a59e9-70ee-4927-9a8b-de4be37f8f41">

**Random Forests** resulted in:

- **Accuracy:** 0.7898
- **Recall:** 0.6790
- **Precision:** 0.7482

<img width="425" alt="image" src="https://github.com/DmanDSR/The_Scholars_W7/assets/48893423/3f8076ed-ac8a-42bd-af22-055af6beefea">


# Key Findings and Insights

The model used for this machine learning project was Gradient Boosting Machines (GBM), selected for their efficiency in handling complex and nonlinear relationships in data. Another model employed was Logistic Regression, appreciated for its simplicity and interpretability, which serves as an excellent baseline. We also utilized Random Forest, renowned for its robustness against overfitting and its capability to manage unbalanced datasets effectively.

# Real-World Application and Impact

- **Early Intervention**: Enables educational institutions to identify students at risk of dropping out early, allowing for timely and targeted interventions.
  
- **Resource Allocation**: Helps schools and universities allocate resources and support services more efficiently by focusing on at-risk students.
  
- **Policy Development**: Informs educational policy by providing insights into the factors contributing to student dropout, aiding in the creation of more effective educational strategies.
  
- **Long-Term Educational Outcomes**: Potentially improves overall student retention and graduation rates, contributing to better long-term educational and career outcomes for students.
  
- **Enhanced Student Support**: Facilitates the development of personalized support programs tailored to the specific needs of students, improving their chances of academic success and retention.

# First Heat Map

![image](https://github.com/DmanDSR/The_Scholars_W7/assets/48893423/5ac0003d-0718-4967-80ca-6ce9eb4ee94f)

# Second Heat Map
![image](https://github.com/DmanDSR/The_Scholars_W7/assets/48893423/ff98b605-bbdd-4c3b-ae44-818703f494e6)

# Challenges and Learnings

**Models:** Choosing which model to use and how to fine-tune it was the biggest challenge we had. Most of the models did give almost the same results.

**Dataset Features:**  Although the data did have valuable information that could help with the ML, the abundance of features could be a factor in why the results weren’t higher on each model. Overfitting became an issue for us due to the high amount of features available.  

**Hyperparameter Duration:** The amount of time it took for our Hyperparameter to finish calculating the results was over 29 minutes and resulted in almost the same results. This not only took valuable time from the project but also didn’t give us a better understanding of the data.

# Future Work and Improvements

- **Expand Feature Set**: Including more comprehensive variables such as mental health metrics and extracurricular activities could provide deeper insights into factors influencing student dropouts and enhance the model's predictive accuracy.
  
- **Ethical and Bias Evaluation**: Regularly evaluating the model for biases ensures it promotes fairness and equity, crucial for its acceptance and ethical use in educational settings.

- **Geographic Expansion**: Applying the model across different geographic and cultural contexts could help validate its universality and robustness, making it more adaptable to diverse educational systems.





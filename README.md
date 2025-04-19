# 🧑‍🎓 Student Depression Prediction using Naive Bayes

This project implements a **Student Depression Classifier** using the **Naive Bayes algorithm** with `scikit-learn`. The dataset contains various features related to students' academic and personal life, and the task is to predict whether a student is depressed or not.

---

## 🚀 Features

- Data preprocessing including encoding categorical variables with `get_dummies`
- Classification using **Multinomial Naive Bayes** model
- Heatmap visualization of the **Confusion Matrix**
- Achieved **80.6% accuracy** on test data
- High interpretability with a simple machine learning model

---

## 🧠 Algorithms Used

- **Data Preprocessing:** Encoding categorical features using `pd.get_dummies`
- **Classifier:** Multinomial Naive Bayes (Naive Bayes)

---

## 📁 Dataset

The dataset consists of the following columns:

| Column                       | Description                                             |
|------------------------------|---------------------------------------------------------|
| Age                          | Age of the student                                     |
| Academic Pressure            | Scale of academic pressure                             |
| Work Pressure                | Scale of work pressure                                 |
| CGPA                         | Cumulative Grade Point Average                          |
| Study Satisfaction           | Study satisfaction on a scale                           |
| Job Satisfaction             | Job satisfaction on a scale                             |
| Sleep Duration               | Duration of sleep (in hours)                           |
| Dietary Habits               | Dietary habits (Healthy, Moderate, Unhealthy)           |
| Have you ever had suicidal thoughts? | Indicates if the student has ever had suicidal thoughts |
| Work/Study Hours             | Work/study hours                                        |
| Financial Stress             | Financial stress (levels)                               |
| Family History of Mental Illness | Whether the student has a family history of mental illness |
| Depression                   | Target variable indicating whether the student is depressed (1) or not (0) |

---

## 📦 Dependencies
pip install pandas scikit-learn matplotlib seaborn

---

## 📊 Performance
The model achieves an accuracy of 80.6% on the test data, with a confusion matrix shown below:
[[2469 1061]
 [ 566 4275]]
True Positive (TP): 4275 (Depressed and predicted as Depressed)

True Negative (TN): 2469 (Non-depressed and predicted as Non-depressed)

False Positive (FP): 1061 (Non-depressed but predicted as Depressed)

False Negative (FN): 566 (Depressed but predicted as Non-depressed)
---

## 🔥 Visualization
The heatmap below represents the Confusion Matrix, providing a visual representation of the model's performance:

---

## 📌 Conclusion
This project demonstrates how to predict whether a student is depressed based on several academic and personal factors. The Naive Bayes classifier gives us a simple yet effective solution for this classification problem. The confusion matrix and accuracy provide insight into the model’s performance, and it can be a useful tool for educational institutions aiming to support student well-being.
---
## 📃 License

This project is open-source and available under the MIT License. You are free to use, modify.

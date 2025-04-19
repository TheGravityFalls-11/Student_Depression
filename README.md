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

## 📦 Dependencies
pip install pandas scikit-learn matplotlib seaborn

---

## 📊 Performance
The model achieves an accuracy of 80.6% on the test data, with a confusion matrix shown below:
[[2469 1061]
 [ 566 4275]]
True Positive (TP): 4275 (Depressed and predicted as Depressed)

True Negative (TN): 2469 (Non-depressed and predicted as Non-depressed)

False Negative (FN): 566 (Depressed but predicted as Non-depressed)

False Positive (FP): 1061 (Non-depressed but predicted as Depressed)

---

## 🔥 Visualization
The heatmap below represents the Confusion Matrix, providing a visual representation of the model's performance:
![Heatmap](https://github.com/user-attachments/assets/0b9a3c21-c93a-4053-810e-17a9c2262890)

---

## 📌 Conclusion
This project demonstrates how to predict whether a student is depressed based on several academic and personal factors. The Naive Bayes classifier gives us a simple yet effective solution for this classification problem. The confusion matrix and accuracy provide insight into the model’s performance, and it can be a useful tool for educational institutions aiming to support student well-being.
---
## 📃 License

This project is open-source and available under the MIT License. You are free to use, modify.

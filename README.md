# Student_Performance_Predictor
# Conclusion

The **Student Performance Predictor** project was developed to apply machine learning techniques to analyze and predict students' academic performance. The project used the UCI Student Performance dataset, which contains information about students' study time, absences, and previous examination grades. The data was checked and preprocessed before training the machine learning models.

Two machine learning algorithms were implemented: **Linear Regression** and **Logistic Regression**. Linear Regression was used to predict students' final examination marks, while Logistic Regression was used to classify students as Pass or Fail based on a passing threshold of 10 marks.

The Linear Regression model achieved an **R² score of 0.796**, which indicates that the model explains approximately 79.6% of the variation in final marks in the test data. Its Mean Absolute Error (MAE) was **1.313**, meaning that the model's predictions differed from the actual marks by approximately 1.31 marks on average.

The Logistic Regression model achieved an **accuracy of 89.87%**, showing that it correctly classified approximately 89.87% of the students in the test dataset. Its **precision was 0.958 (95.8%)**, indicating that most students predicted as passing were actually in the passing category. Its **recall was 0.885 (88.5%)**, meaning that the model identified 88.5% of the students who actually passed.

Overall, the results show that both models performed well for their respective tasks. Linear Regression provided useful estimates of final examination marks, while Logistic Regression effectively classified students into Pass and Fail categories. This project demonstrates how machine learning can support educational data analysis and help identify students who may need additional academic support. In the future, the project could be improved by testing more algorithms, using additional student-related features, and evaluating the models on larger and more diverse datasets.

**In conclusion,** the project successfully demonstrated the practical application of machine learning in education by predicting final marks and classifying student performance using appropriate evaluation metrics.

📊 Binary Classification Project – F1 Score Evaluation
📌 Task Description

The objective of this project is to train a machine learning classifier to predict a binary class (0 or 1) using a given dataset.
The model performance is evaluated using the F1-score, and the full workflow is documented through code and a presentation.

✅ Task Requirements & How They Were Addressed
1. Train a classifier to predict the class (0 or 1)

✔ Completed
Multiple classifiers were trained to solve the binary classification problem:

Logistic Regression (baseline model)

Random Forest

Support Vector Machine (SVM)

XGBoost

All models were trained to predict the target variable Class ∈ {0, 1}.

2. Use F1-score as the evaluation metric

✔ Completed

The F1-score was used as the primary evaluation metric because it balances precision and recall, providing a reliable measure of model performance.

\[
F1 = 2 \times \frac{\text{Precision} \times \text{Recall}}
{\text{Precision} + \text{Recall}}
\]


F1-score was calculated and compared for all models.

1. Use any programming language

✔ Completed

Programming language used: Python

4. Use any library

✔ Completed

The following libraries were used:

pandas, numpy – data handling

scikit-learn – modeling and evaluation

xgboost – gradient boosting model

matplotlib, seaborn – data visualization

5. Share the code and presentation explaining the details

✔ Completed

📓 Jupyter Notebook

Data exploration and cleaning

Class distribution visualization

Missing value handling

Outlier analysis

Model training

Evaluation using F1-score

Confusion matrices

Feature importance analysis

🎤 Reveal.js Presentation (Quarto)

Project objective

Dataset overview

Data preprocessing decisions

Model selection rationale

Evaluation metric explanation

Model comparison

Final conclusions

📂 Project Structure
project/
│── data.xlsx
│── notebook.ipynb
│── presentation.qmd
│── presentation.html
│── README.md
│── Assets/
│   ├── class_distribution.png
│   ├── boxplot.png
│   └── models_comparison.png

📈 Key Results

The dataset is balanced, reducing class bias.

Logistic Regression provided a strong and interpretable baseline.

Ensemble models (Random Forest, XGBoost) achieved higher performance.

XGBoost achieved a perfect F1-score on the test set, which may indicate overfitting and requires validation through cross-validation.

F1-score was effective in comparing models fairly.

⚠️ Limitations

Small dataset size

Single train–test split

Potential overfitting for complex models

🔮 Future Improvements

Cross-validation

Hyperparameter tuning (GridSearchCV)

Feature selection

ROC–AUC analysis

🏁 Conclusion

This project successfully fulfills all task requirements.
Multiple machine learning models were implemented and evaluated using F1-score, with clear justification for preprocessing choices and model selection. The results demonstrate the importance of model comparison and robust evaluation metrics in binary classification tasks.
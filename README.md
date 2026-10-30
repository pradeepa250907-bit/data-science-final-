# 🎓 Student Academic Success Prediction
### An End-to-End Data Science & Machine Learning Project

## 📌 Project Overview

This project focuses on analyzing student academic performance and developing Machine Learning models to predict student success.

Using a real-world dataset, I implemented a complete Data Science workflow, starting from data exploration and preprocessing to visualization, model training, evaluation, and prediction.

The aim is to explore patterns associated with academic performance and gain hands-on experience in building predictive models using Python.

## 🎯 Project Objectives

- Analyze a real-world Student Performance dataset.
- Perform data cleaning and preprocessing.
- Identify patterns and relationships through Exploratory Data Analysis (EDA).
- Create meaningful data visualizations.
- Build and compare multiple Machine Learning models.
- Predict student academic success (Pass/Fail).
- Evaluate model performance using appropriate classification metrics.

## 📂 Dataset Information

**Dataset:** Student Performance Dataset  
**Source:** UCI Machine Learning Repository  
**Records:** 395  
**Attributes:** 33

Dataset Link: https://archive.ics.uci.edu/dataset/320/student+performance

The dataset includes information about students' study habits, absences, previous grades, family background, and other educational factors.

### Target Variable

Student academic success is categorized based on final grade (G3):

- Pass: Final Grade ≥ 10
- Fail: Final Grade < 10

The final grade is excluded from the model's input features to prevent target leakage. The second-period grade (G2) is also excluded to focus on prediction using earlier information.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## 🔄 Project Workflow

1. Dataset Collection
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Visualization
6. Feature Selection and Encoding
7. Train-Test Split
8. Machine Learning Model Training
9. Model Evaluation and Comparison
10. Student Success Prediction

## 📊 Exploratory Data Analysis

The following visualizations were generated:

| Visualization | Purpose |
|---|---|
| Grade Distribution | Understand the distribution of final grades |
| Study Time Analysis | Compare study time with average grades |
| Absences Analysis | Explore relationships between absences and grades |
| Pass/Fail Distribution | Visualize academic outcome categories |
| Correlation Heatmap | Identify relationships between numerical variables |
| Model Comparison | Compare ML model accuracy |
| Confusion Matrix | Evaluate classification performance |

## 🤖 Machine Learning Models

Three supervised classification algorithms were implemented:

**1. Logistic Regression**

Used as a baseline classification model for predicting student outcomes.

**2. Decision Tree Classifier**

Used to learn decision rules from student-related features.

**3. Random Forest Classifier**

An ensemble learning algorithm that combines multiple decision trees to improve predictive robustness.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

## 📈 Model Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

The models were compared to identify their relative performance on the test dataset.

### Model Comparison Results

*Replace the values below with your actual notebook output.*

| Model | Accuracy |
|---|---|
| Logistic Regression | Add result |
| Decision Tree | Add result |
| Random Forest | Add result |

**Highest Test Accuracy Model:** Add model name

**Test Accuracy:** Add percentage

*Note: This is a beginner-level experimental comparison. Future improvements will include cross-validation and more rigorous model selection.*

## 📁 Project Structure

```text
Student-Academic-Success-Prediction/
│
├── Final_Data_Science_Project.ipynb
├── cleaned_student_data.csv
├── model_comparison_results.csv
├── README.md
│
└── images/
    ├── grade_distribution.png
    ├── studytime_analysis.png
    ├── attendance_analysis.png
    ├── pass_fail.png
    ├── correlation_heatmap.png
    ├── model_comparison.png
    └── confusion_matrix.png
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Download the Student Performance dataset from the UCI repository.
5. Run the notebook and upload `student+performance.zip` when prompted in Google Colab.
6. Execute the remaining code to generate visualizations and model evaluation results.

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

- Working with real-world datasets.
- Performing data cleaning and statistical analysis.
- Understanding feature selection and data preprocessing.
- Developing classification models using Scikit-learn.
- Evaluating and comparing Machine Learning algorithms.
- Interpreting model performance through visualizations.
- Building an end-to-end Data Science project.

## 🔮 Future Enhancements

- Implement cross-validation and hyperparameter tuning.
- Explore additional classification algorithms.
- Perform feature importance analysis.
- Develop an interactive prediction dashboard using Streamlit.
- Evaluate the model using larger and more diverse datasets.
- Improve model interpretability and examine potential bias.

## 📝 Conclusion

This project marks an important milestone in my Data Science learning journey.

By combining Exploratory Data Analysis, visualization, and Machine Learning, I gained a deeper understanding of how raw data can be transformed into meaningful insights and predictive models.

The project demonstrates a complete beginner-friendly Data Science workflow, from understanding a problem to developing and evaluating a Machine Learning solution.

This is an educational project and is not intended for making real-world academic decisions about individual students.

## 📚 Acknowledgement

**Dataset:** Student Performance Dataset  
**Authors:** Paulo Cortez and Alice Silva  
**Source:** UCI Machine Learning Repository

---

⭐ Thank you for exploring my project!

*Continuously learning, experimenting, and building through Data Science and Artificial Intelligence.*

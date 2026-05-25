# 🚢 Titanic Survival Prediction - Coding Samurai Internship(Project 1)

This repository contains my submission for the Titanic Classification project as part of my Data Science internship at Coding Samurai. The goal is to predict which passengers survived the Titanic shipwreck using Machine Learning.

## 📊 Project Overview
Using the classic Titanic dataset, I performed Exploratory Data Analysis (EDA) and built a classification model. The project focuses on data cleaning, feature engineering, and model evaluation.

### **Key Highlights:**
* **Accuracy Achieved:** 81.01%
* **Model Used:** Logistic Regression
* **Data Cleaning:** Handled missing values for 'Age' and 'Embarked' columns.
* **Feature Selection:** Focused on Pclass, Gender, Age, and SibSp/Parch to drive predictions.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib (KDE plots, Bar plots)
* **Machine Learning:** Scikit-learn

## 📈 Visual Insights
In this project, I visualized:
* **Survival Rate by Gender:** Identifying the "Women and children first" pattern.
* **Age Distribution:** Understanding the density of survivors across different age groups.
* **Class Impact:** Comparing survival rates between 1st, 2nd, and 3rd-class passengers.

## 🚀 How to Run
1. Clone this repository.
2. Install the required libraries:  
   `pip install pandas seaborn matplotlib scikit-learn`
3. Open `Titanic_Survival_Prediction.ipynb` in Jupyter Notebook.


---

# 📊  Social Media Sentiment Analysis(project 2)

## 📌 Project Overview
This project focuses on performing **Sentiment Analysis** on social media text data. Using Python and Natural Language Processing (NLP) techniques, the model analyzes textual data (posts/tweets) and classifies the underlying emotion into three distinct categories: **Positive**, **Negative**, or **Neutral**.

## 🛠️ Tech Stack & Libraries Used
- **Language:** Python
- **NLP Library:** TextBlob (for polarity score estimation)
- **Data Manipulation:** Pandas
- **Data Visualization:** Matplotlib & Seaborn

## 📈 Key Methodology
1. **Dataset Creation:** Built a sample social media text dataset reflecting various real-world student and tech-focused scenarios.
2. **Polarity Calculation:** Utilized `TextBlob` to extract semantic polarity values ranging from -1 (Extremely Negative) to +1 (Extremely Positive).
3. **Classification Logic:** 
   - Polarity > 0 $\rightarrow$ **Positive**
   - Polarity < 0 $\rightarrow$ **Negative**
   - Polarity == 0 $\rightarrow$ **Neutral**
4. **Visualization:** Plotted a categorical distribution count plot to clearly visualize the volume of each sentiment.

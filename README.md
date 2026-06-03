# Student Habits and Academic Performance Analysis

## 📌 Project Overview
This project analyzes how student lifestyle habits affect academic performance using a dataset of 1,000 students.  
It explores how daily behaviors such as study time, sleep, social media usage, diet, and mental health influence exam scores.

The project uses data analysis, visualization, and machine learning techniques to identify key factors and build a predictive model for academic performance.

---

## 🎯 Objectives
- To study student lifestyle patterns
- To analyze the relationship between habits and exam scores
- To identify the most important factors affecting academic performance
- To build a model to predict exam scores

---

## 📊 Dataset Information
- Total records: 1,000 students  
- Total features: 16 variables  

### Target Variable
- Exam Score

### Key Features
- Age
- Study hours per day  
- Sleep hours  
- Social media hours  
- Netflix hours  
- Attendance percentage  
- Mental health rating  
- Diet quality  
- Exercise frequency  
- Parental education level  
- Internet quality  
- Gender  
- Part-time job  
- Extracurricular participation  

---

## 🧹 Data Preprocessing
- Handled inconsistent values in categorical variables (parental education level contained "None", which was recoded as "Unknown")
- Checked for missing values and duplicates (none found)
- Encoded categorical variables into numerical format
- Prepared dataset for analysis and modeling

---

## 📈 Methodology
The analysis followed these steps:

1. **Descriptive Statistics**
   - Mean, median, and distribution analysis

2. **Exploratory Data Analysis (EDA)**
   - Histograms, box plots, and scatter plots
   - Identified patterns and outliers

3. **Correlation Analysis**
   - Measured relationships between variables and exam scores

4. **Multiple Linear Regression (MLR)**
   - Built a model to predict exam scores using multiple features
   - Some variables were found to be statistically insignificant

5. **Feature Selection (Forward Selection)**
   - Reduced the model by selecting only statistically significant variables
   - Improved model simplicity and interpretability

6. **Multicollinearity Check (VIF)**
   - Checked for correlation among independent variables
   - High VIF values indicated multicollinearity issues

7. **Ridge Regression**
   - Applied Ridge Regression as the final model
   - Reduced multicollinearity and improved model stability and reliability

---

## 🤖 Models Used
- Multiple Linear Regression (baseline model)
- Forward Selection (feature optimization)
- Ridge Regression (final model)

---

## 📌 Key Findings
- Study hours per day is the strongest positive factor affecting exam scores
- Mental health also has a positive impact on performance
- Social media and Netflix usage show negative effects on scores
- Most categorical variables have weaker influence on performance
- Ridge Regression provided the most stable and reliable model

---

## 📉 Model Interpretation
- More study hours → higher exam scores
- Higher mental health rating → better performance
- More screen time (social media/Netflix) → lower performance

---

## ⚠️ Limitations
- Dataset is simulated, not real student data
- Some important factors (stress, teaching quality, income) are not included
- Cannot prove causation, only relationships
- Results may not fully reflect real-world conditions

---

## 🚀 Future Improvements
- Use real student data for better accuracy
- Add more variables like stress and socioeconomic status
- Try advanced models like Random Forest or Gradient Boosting
- Use time-based (longitudinal) data for deeper analysis

---

## 🛠️ Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📌 Conclusion
This project shows that student lifestyle habits significantly influence academic performance.  
Among all factors, study habits and mental health are the most important predictors of exam success.

Machine learning techniques like regression can effectively help analyze and predict student performance.

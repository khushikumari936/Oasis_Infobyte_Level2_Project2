# Wine Quality Prediction using Machine Learning

## Project Overview

This project focuses on predicting wine quality using various machine learning classification algorithms based on the chemical properties of wine. The dataset contains physicochemical characteristics such as acidity, density, pH, alcohol content, sulphates, and chlorides.

The objective is to analyze the relationship between these chemical properties and wine quality and build predictive models capable of classifying wines as good or bad quality.

This project demonstrates the complete machine learning workflow, including:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Feature Engineering
- Model Building
- Model Evaluation

---

## Dataset

Dataset Source:  
https://www.kaggle.com/datasets/yasserh/wine-quality-dataset

The dataset includes:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality Score

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook / Google Colab

---

## Machine Learning Models Used

The following classification algorithms were implemented and compared:

1. Random Forest Classifier
2. Stochastic Gradient Descent (SGD) Classifier
3. Support Vector Classifier (SVC)

---

## Project Workflow

### 1. Data Collection
- Imported the wine quality dataset from Kaggle.

### 2. Data Cleaning
- Checked for missing values
- Verified data types
- Handled formatting issues

### 3. Exploratory Data Analysis (EDA)
Performed statistical and visual analysis using:
- Histograms
- Correlation Heatmaps
- Boxplots
- Countplots
- Scatterplots

### 4. Feature Engineering
- Selected relevant chemical features
- Converted quality into classification labels

### 5. Data Preprocessing
- Train-Test Split
- Feature Scaling using StandardScaler

### 6. Model Training
Trained multiple classification models:
- Random Forest
- SGD Classifier
- Support Vector Classifier

### 7. Model Evaluation
Evaluated models using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Feature Importance Analysis

---

## Visualizations Included

The project includes multiple visualizations to better understand the dataset:

- Wine Quality Distribution
- Correlation Heatmap
- Alcohol vs Quality Boxplot
- Volatile Acidity vs Quality
- Feature Importance Graph
- Confusion Matrix
- Model Comparison Chart

---

## Key Insights

- Alcohol content showed a positive correlation with wine quality.
- Volatile acidity negatively impacted wine quality.
- Random Forest Classifier achieved the best overall performance.
- Feature scaling significantly improved SVC performance.
- Some chemical properties had stronger predictive importance than others.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Skills Demonstrated

This project demonstrates skills in:
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning Classification
- Statistical Visualization
- Feature Engineering
- Model Evaluation

---

## Future Improvements

Possible future enhancements:
- Hyperparameter tuning
- Cross-validation
- Ensemble learning techniques
- Deep learning models
- Deployment using Flask or Streamlit

---

## Conclusion

This project successfully applied machine learning techniques to predict wine quality based on chemical characteristics. Among the implemented models, Random Forest Classifier provided the highest prediction accuracy and demonstrated strong performance in classification tasks.

The project highlights the importance of exploratory data analysis, feature scaling, and model comparison in building effective machine learning solutions.

---

## Author

Khushi Kumari

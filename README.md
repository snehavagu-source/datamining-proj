# Customer Churn Prediction and Sentiment Analysis

This project focuses on predicting customer churn by combining behavioral data with sentiment analysis of customer reviews using Python and WEKA.

## Project Overview
- **Objective:** To improve churn prediction accuracy by integrating sentiment scores.
- **Tools Used:** Python (Google Colab), WEKA Data Mining Tool.
- **Datasets:** Customer behavior data and sentiment-labeled review datasets.

## Implementation Steps
1. **Data Preprocessing:** Merging datasets and handling missing values using Python.
2. **Sentiment Analysis:** Performed using the **Random Forest** algorithm in WEKA.
3. **Churn Prediction:** Performed using the **J48 (Decision Tree)** algorithm in WEKA.

## Key Results
- **Sentiment Analysis Accuracy:** 91.6% (Random Forest)
- **Churn Prediction Accuracy:** 96.07% (J48 Algorithm)

## Repository Structure
- `Datamining_project_final1.ipynb`: Python code for data merging and preprocessing.
- `merged_data.csv`: The final preprocessed dataset used for mining.
- `Churn_Result_J48.png`: Screenshot of J48 classification results.
- `Decision_Tree_Visualization.png`: Graphical representation of the J48 tree.
- `Sentiment_Result_RF.png`: Screenshot of Random Forest sentiment analysis.

## Conclusion
The integration of sentiment analysis significantly helps in understanding customer dissatisfaction, leading to a highly accurate churn prediction model.

# Enhancing-Mental-Health-Interventions-in-the-USA-with-Emotion-Prediction
## Project Overview
This project focuses on analyzing and classifying the sentiment of tweets into categories such as positive, negative, and neutral using machine learning techniques. The dataset comprises **40,000 tweets** with attributes such as tweet ID, sentiment, and content. This project implements three machine learning classification models—**Logistic Regression**, **Random Forest**, and **Support Vector Machine (SVM)**—to determine the most effective model for sentiment analysis.

The project emphasizes preprocessing, feature extraction, model evaluation, and result visualization to ensure comprehensive analysis and insights.

## Features and Workflow
1. **Data Preprocessing**:
   - Removed missing or irrelevant data.
   - Tokenized text data for better handling.
   - Extracted features using **TF-IDF** for numerical representation.

2. **Machine Learning Models**:
   - Logistic Regression
   - Random Forest Classifier
   - Support Vector Machine (SVM)

3. **Evaluation Metrics**:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix for performance visualization

4. **Model Comparison**:
   - A bar plot comparing the accuracies of all three models to determine the best-performing one.

5. **Visualizations**:
   - Sentiment class distribution
   - Content length distribution
   - Model performance comparison using bar plots

## Results
The results of the model evaluations on the test set (**8,000 samples**) are as follows:

### Logistic Regression
- **Accuracy**: 0.35  
- **Highlights**:
  - Best recall for the 'neutral' class (**0.57**).
  - Struggled with smaller classes like 'anger' and 'boredom'.

### Random Forest
- **Accuracy**: 0.33  
- **Highlights**:
  - Best recall for 'neutral' (**0.53**).
  - Moderate performance in 'love' and 'happiness' classes.

### Support Vector Machine (SVM)
- **Accuracy**: 0.35  
- **Highlights**:
  - Similar recall performance as Logistic Regression for 'neutral' (**0.55**).
  - Slight improvement in 'worry' class recall (**0.49**).

Detailed classification reports for each model are included in the repository.

## Business Impact
Sentiment analysis is a critical tool for businesses and organizations to extract actionable insights from social media platforms like Twitter. It helps in:

- **Customer Feedback Analysis**: Identify trends in customer opinions to enhance products and services.
- **Brand Monitoring**: Detect shifts in public sentiment towards a brand or campaign.
- **Market Research**: Understand consumer behavior and improve marketing strategies.
- **Crisis Management**: Quickly respond to negative sentiment to mitigate risks.

This project demonstrates the potential of machine learning in automating sentiment analysis, saving time and resources while improving decision-making capabilities.


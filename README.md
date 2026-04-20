#  Sentiment Analysis on Smartphone Tweets

## (1) Problem Statement
Social media platforms like Twitter contain large amounts of user-generated content expressing opinions about products such as smartphones. Manually analyzing these opinions is time-consuming and inefficient. Therefore, there is a need to automatically classify tweets into sentiment categories (positive, negative, neutral) using machine learning techniques.

## (2) Objective
- To perform sentiment analysis on smartphone-related tweets
- To classify tweets into positive, negative, and neutral categories
- To compare the performance of different machine learning models
- To identify the best-performing algorithm for sentiment classification Define the goal.

## (3) Dataset
- Source: Kaggle
- Features: Tweets, Sentiment
- Size: 100 tweets

## (4) Methodology
1. Data Preprocessing  
2. EDA  
3. Model Building  
4. Evaluation  

## (5) Results
Model Performance Comparison
- Naïve Bayes Accuracy: 90%
- Logistic Regression Accuracy: 90%
- SVM Accuracy: 95%
  
Key Insights
- SVM performed best among all models
- Logistic Regression and Naïve Bayes showed similar performance
- Neutral tweets were classified with very high accuracy
- SVM achieved the best balance between precision and recall
  
Visualizations Used
- Sentiment distribution plot
- Accuracy comparison bar chart
- F1-score comparison chart
- Confusion matrix (SVM)

## (6) How to Run
```bash
pip install -r requirements.txt
python main.py
```

## (7) Conclusion
This project successfully demonstrates sentiment analysis on smartphone-related tweets using machine learning techniques. Among the three models tested, Support Vector Machine (SVM) achieved the highest performance with 95% accuracy and the best F1-score.

The study shows that SVM is most effective for text classification tasks using TF-IDF features, especially on small datasets.

## (8) Student's details
- Name: Azka Dalvi
- Roll No: 16
- UIN: 242A001
- YEAR: TE-AIDS

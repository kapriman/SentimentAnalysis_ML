# SentimentAnalysis_ML
Sentiment Analysis of “The Lion King (2019)” Movie Reviews

Problem Description:

In this Project, you are expected to create an end to end NLP framework to collect, analyse and perform sentiment analysis using supervised learning on user reviews about the latest Hollywood flick - “The Lion King (2019)”

Objectives:

In this project, you are expected to: 

1. Collect Audience reviews from "www.rottentomatoes.com" for the film:
“The Lion King (2019)”
2. Label the Review Sentiment (Target) – Refer to Main Tasks
3. Perform the Visualizations & EDA on the data gathered.
4. Perform Sentiment Classification using supervised learning
5. Clustering the Reviews – Comparing ‘Cluster Label’ with Train data Target ‘sentiment’

Data Information:

Test Data will be provided (columns: ‘ReviewID’, ‘Review’), which should be used for tool evaluations. Test data target distribution is 77% Positive Reviews and 23% Negative Reviews
Main Tasks: 

1. Collect Audience reviews from "www.rottentomatoes.com" for the film: “The Lion King (2019)” with at least the following features.

  a. ReviewID
  b. Reviewer Name
  c. Review
  d. Rating
  e. Date-of-Review

The feature names above may not match with the exact tags returned by the response object. Use your intuition to map them and create the above features accordingly.

 You are required to collect 3000 reviews only. 
 You are free to collect any other attributes/features that you think helpful. 


2. Label the Review Sentiment:

You must label the data based on the following condition on Rating:

 if ‘Rating’ > 3 then positive review else negative review – Create target attribute with the name: “sentiment” (binary class)

“Drop the Rating attribute once the Target is derived. It should not be part of model building as independent attributes.”

3. Exploratory Data Analysis using visualizations in R Notebook or Jupiter notebook format. (train data to be used for this)

  a. What is that the good and bad, people are talking about the film? 

   (Hint:  you may pick any meaningful n-grams and obtain their frequency to emphasize the importance of n-gram)
 
  b. Any other meaningful Insights 

4. Perform Sentiment Classification using supervised learning algorithms

a. Identify the best model using traditional Classification ML algorithms like NaiveBayes, Logistic Regression, SVM, Decision Trees, Ensembles etc.

b. Identify the best model using Deep Learning Classification ML algorithms like CNN, RNN/LSTM etc.

Choose the model that outperforms all others for your test predictions and in your submissions. 

5. Clustering the Reviews – Comparing ‘Cluster Label’ with Train data Target ‘sentiment’ 

a.  Take only ‘reviews’ attribute from train data and label them into two clusters using any clustering algorithm of your choice. 
b. compare the cluster labels with the train data target attribute - ‘sentiment’ and Write a brief comparison report with your observations.


Evaluation Metric: 

F1-score for Negative reviews.

Important Note for the results submission:  

Note: 
While evaluating the predictions submitted, the system will consider “1” as positive level in target attribute and hence please convert the target attribute accordingly   and submit the results.   It is very important for this problem as the error metric is “F1 statistic” for the target attribute level “negative review”.  Refer to the samplesubmission.csv file (‘0’: positive review and ‘1’: negative review).

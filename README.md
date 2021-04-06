# SENTIMENT ANALYSIS ON AMAZON FINE FOOD REVIEWS


Problem Statement:
In today’s world where online shopping has become the most important routine of our life, reviews play a very important role in deciding whether to purchase a product or not. 


Solution:

-> We have performed data preprocessing techniques and obtained the statistics of data.

-> We applied visual analysis in the beginning to find out overall dynamics of the data.

-> Implemented vectorization methods like Bag of Words and TF-IDF.

-> Executed supervised and unsupervised machine learning models.

-> Performed Sentiment analysis on the respective models.



The models that we have applied are:

      Decision tree
      
      Random Forest
      
      SVM
      
      KNN
      
      Logistic Regression
      


The following points are the results obtained from analysis:

-> Out of all models, Logistic regression turns out to have highest accuracy for both vectorization methods.

-> Both SVM and Logistic regression have performed well for the data as they have closest accuracy difference.

-> TF-IDF outperforms Bag-of-bigrams for all the models except for tree based classifiers like Decision Tree and Random Forest.

-> From the SVM feature importance, in the data ‘high recommend’ is the most positive word and ‘Worst’ is the highly negative word.

Classifier          | Bag of Words Accuracy | TF-IDF Accuracy

Random Forest       | 87.064                | 86.797

Decision Tree       | 88.347                | 87.992

SVM                 | 92.946                | 93.327

Logistic Regression | 93.138                | 93.384

KNN                 | 84.658                | 86.475


Conclusion:

The project results in a large feature file containing predictor variables determined with the techniques of Natural Language Processing and Sentimental evaluations of different words. Finally, we introduced a Logistic Regression based classifier and evaluated the output to differentiate between positive and negative reviews.

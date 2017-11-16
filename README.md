# liverprediction
Liver decease prediction 

Objective:
	Given a set of data, our main aim is to analyse it for each and every patient and determine whether or not He/She suffers from liver disease. In order to achieve this, we have used 4 models:
  
    Naïve Bayes Model 
    The Logistic Regression Model	
    K-Nearest Neighbors (KNN) Model
    Support Vector Machine(SVM)
    
 Reasons for choice of algorithms:

    All are Supervised Classification Methods and are classified based on features.

    Naive Bayes : It is very simple to implement. When assumption of independence holds, a Naive Bayes classifier performs better compared to other models like logistic regression and you need less training data.  

    KNN : The K-nearest neighbor algorithm is that is simple to understand and easy to implement. With zero to little training time

    Logistic Regression : Based on probabilistic results.

    SVM : It works really well with clear margin of separation
    
    
As we can see from the results :
  
    Naive Bayes has max Specificity out of all followed by KNN which implies that it has the best ability to classify people who don’t have the disease and are not patients and we can conclude it from these models.

    The sensitivity for the SVM classifier is very high (close to 1), thus we can conclude that it correctly classifies the people who have the disease and are patients. This measure is relatively lower in KNN and Logistic Regression. (Logistic being higher than KNN) and Naive Bayes has low sensitivity among all. 

    The Accuracy of Logistic Regression and SVM goes hand in hand with with very little difference where as KNN is slightly less and Naive Bayes Accuracy is very less compared to other models.

    All models have similar F-Square  values but Naive Bayes has very less value relatively to other models

    Other measures are roughly the same and hence you can’t make any conclusions based on them.   

     Also, SVM works extremely well for binary classification.


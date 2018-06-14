# SentimentAnalysisYelpDataset
This Project is based on Sentiment Analysis of a subset of the Yelp Dataset Movie Reviews.

IMP: This project was implemented for a private kaggle competition in which our Team(of 5 members) came in 3rd(out of 16) in the competition with an accuracy of 91.28% on the entire test set.


Dataset Contains:
           - Sample submission file
           - Sample Training dataset 
           - Original Training dataset(Subset)
           - Test set
           
NOTES:
  1. The train set contains some reviews in different languages which were not removed during building the model.
  2. Very less preprocessing was done, as it gave less test accuracy "RELATIVELY".
  
MODELS TRIED:
  1. Logistic Regression(Model which got us highest accuracy among all other models.)
  2. Multinomial Naive Bayes
  3. Random Forest Classifier
  4. LinearSVC
  5. XgBoost

Here is the performances of above mentioned model with the corresponding kaggle score:
![Screenshot] (http://tinypic.com/r/wlr3vd/9)

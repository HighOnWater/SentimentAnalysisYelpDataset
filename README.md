# SentimentAnalysisYelpDataset
This Project is based on Sentiment Analysis of a subset of the Yelp Dataset Movie Reviews.

IMP: This project was implemented for a private kaggle competition in which our Team(of 5 members) came in 3rd(out of 16) in the competition with an accuracy of 91.28% on the entire test set.

src:
   The .ipynb file for the project(Does not have code for Xgboost).

Dataset Contains:
           - Sample submission file
           - Sample Training dataset 
           
link to Test and Train dataset - https://www.dropbox.com/sh/671i5zo2yoyx24b/AAB4v2Tu-LUgV97mj8PalrTHa?dl=0          
           
NOTES:
  1. The train set contains some reviews in different languages which were not removed during building the model.
  2. Very less preprocessing was done, as it gave less test accuracy "RELATIVELY".
  
MODELS TRIED:
  1. Logistic Regression(Model which got us highest accuracy among all other models.)
  2. Multinomial Naive Bayes
  3. Random Forest Classifier
  4. LinearSVC
  5. XgBoost

Here is the image of performances above mentioned model with the corresponding kaggle score:
<a href="http://tinypic.com?ref=wlr3vd" target="_blank"><img src="http://i63.tinypic.com/wlr3vd.jpg" border="0" alt="Image and video hosting by TinyPic"></a>

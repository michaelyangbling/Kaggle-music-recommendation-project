# Kaggle-music-recommendation-project.

project: kkbox music recommendation
Data are in kaggle.com, about several GBs after decompressing with about 10 million row train data and 3 million row test data.

Here are personal python and R codes for the project.
 Submission file(csv) was created before the competition deadline  and score in top 30 of 1081 teams on Kaggle( with real-life test-set's AUC accuracy of about 0.71.
 Also, if you submit my submission file now, you can see the accuracy of about 0.71 and score in top 30 of 1081 teams.
 Submission file was created by picking some features in submit.ipynb (by making minor change to submit.ipynb).
 Feature_engineer.ipynb is similiar to submit.ipynb, except that feature_engineer.ipynb is for doing cross-validation.
 R codes(.Rmd) are mainly for exploratory data analysis and trying different machine learning models, 
 such as neutral networks, logistic regression and random forest, finally picking LightGBM.
 Some Rmarkdown chunks may need to be run in a different specific order to work properly.

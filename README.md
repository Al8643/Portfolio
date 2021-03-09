# Portfolio
Data Science Portfolio
# [Project 1: data science salary estimator: project overview](https://github.com/Al8643/Portfolio)
Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
Scraped over 1000 job descriptions from glassdoor using python and selenium
Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
Built a client facing API using flask

![](https://github.com/Al8643/Portfolio/blob/main/images/portfolio1.png)

# [Project 2: Ball Image Classifier](https://github.com/Al8643/Portfolio)
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results

![](https://github.com/Al8643/Portfolio/commit/d16493bba553464553c6b93c12ba3dbc76ebc607#diff-5c8c93358348a8fcabf691ceb248e4fe010b66d320648b12b0da1bcbb883998e)

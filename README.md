This research tries to compare different supervised regression  models to Productivity Prediction of Garment Employees. I have used ensemble models(decision trees,random forest and xgboosting,Gradient Boost) and traditional models(svm,linear regression ,lesso,Rifge, knn). Results show that all the models can be use for  performance but random forest , XGboost and Gradient boost were best with high accuracy and better result than others. 
 
dataset includes essential attributes of the garment manufacturing process and the employees’ productivity which had been collected manually and validated by industry experts and published in the UC Irvine Machine Learning Repository.Dataset has 15 features for 1197 instances. 11 variables are numerical and 4 are categorical. The dependent variable is Actual Productivity  that show The actual % of productivity that was delivered by the workers. It ranges from 0-1. (https://archive.ics.uci.edu/ml/machine-learning-databases/00597/garments_worker_productivity.csv) 

Result: I could see that there is not significant difference between ensemble methods and traditional methods for prediction customer credit at my data set. All the methods had good metrics for classification and prediction. Although, random forest and neural network had the highest accuracy.

Based on result, it appears that targerted_productivity can have a strong positive impact on actual_productivity, some sort of a self-fulfilling prophecy effect.
quarter is another factor that can influence actual productivity, with Quarter 5, 1, and 2 being the most productive respectively.
team can also affect actual productivity, with team 1, 12, and 3 being the most productive respectively.
no_of_workers can also play a role in influencing actual_productivity, even though its effect is more nuanced and not necessarily linear, as demonstrated through EDA and model development.
incentive is also another important factor that can be a meaningful predictor of actual_productivity.
I understand that date and time feauter has The least impact  on prodactivity. I don’t consider smv to be a key factor but I still included it in the main model because it is highly correlated with no_of_workers. This relationship can be captured with an interaction term.

# KaggleSF
Kaggle on San Francisco Crime

Several scripts are available :
- Visualization : shows exploratory graphs or maps
- Diverse scripts : miscellaneous scripts that could be helpful for the analysis 
- Feature selections : tests for selecting interesting features



Tests on Features : 

1) Year, Month, Day, DayOfYear, Time, DayofWeek, Holiday, X, Y, PdDistrict as binary (1 feature per district)
Random Forest with n=10 : score 0.12919355114267328
Features_importances_ : X, Y, Day, DayOfYear and Time had the best importances (>0.01)

2) Same with workhour (time between 8 and 17) : 
Feature importance of workhour is very low: 0.00589639

3) Only: Day, DayOfYear, Time, X, Y

Random forest with n=10 :
Cross_validation score : 0.06
Kaggle score : 32.34575

AdaBoost : 
Cross_validation score : 0.21
Kaggle score : 34.47175



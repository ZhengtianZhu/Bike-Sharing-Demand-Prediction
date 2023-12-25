# Bike-Sharing-Demand-Prediction
data-mining-2020-BUPT

It is the project from the competition in this link: https://www.kaggle.com/c/bike-sharing-demand/data,
and I have improved the prediction accuracy by eliminating the input factor named seasons.

This paper eliminates the input factor of the season for prediction and finds that using the RandomForest model can achieve a score equal to 0.40399, which is better than before. However, using the decision tree model can only achieve a score equal to 0.53742, meaning the performance has decreased. The reason why I do this is because the temperature and humidity change according to the month rather than the season.

Reference:  <br>
Python: predict the bike-sharing-demand：
https://www.jianshu.com/p/d311e6e4a00f

# Linear Regression Model to Predict Future Tournament Prize Pool
###### _Also found at our website link_: https://microrunnyoutput.sonofb.repl.co/index.html

## Baseplot at 70% confidence interval
![baseplot](/images/linreg/baseplot.png)
* 2D scatterplot with overlaid regression line. 
* Helps compare prizepool vs. year information. 
* Our results show that there are more tournaments with prizepool from 2010+ and that X-Y show a positive correlation. 

## Test Predictions
* The following predictions are based on our linear regression model.
  * Year 2014: 108350.86608123
  * Year 2020: 245537.62458836
  * Year 2021: 268402.08433955
  * Year 2022: 291266.54409075
* _We can see that the prize pool predictions increase gradually according to year._
  
## Plotting Prediction Model
![model](/images/linreg/model.png)
* Visual representation of our test predictions
* Overall, predicts higher prizepools for esport tournaments according to year._

## Model Evaluation
* r2 score: -9.86656
  * _Did not set an interept therefore the calculation of RSS, TSS, ESS is to achieve r2 was caused it to be negative. From the nature of how r2 is calculated, it does not neccessarily mean that our model fits very badly.
* RMSE: 146227.976587
  * _This score represents how concentrated our data is to the best-fit line. Our test set was relatively small therefore RMSE is high and slightly inaccurate upon different models._ 
  
  
## Future Improvements
* One major improvement I see is gathering more public data outside the TL API to provide a larger subset of train, validation, and test sets.

  

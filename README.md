Hello readers!

This is a linear regression ML model aiming to to identify which advertising channels provide the highest return on investment (ROI). Additionally, we aim to determine which channels exhibit the most forecasting reliability

In terms of preprocessing, nothing was really needed aside from transforming the CSV into a pandas dataframe. The dataset had no null values, and already had our desired format.

When viewing our data before feeding it to the ML model, we can easily see that TV ROI data had much less variance, and a more defined positive correlation between money spent and sales, than both Radio and Newspaper. This will become relavent when assessing the forecasting reliability of our model in relation with each advertising channel.

After creating and feeding the Linear Regression model, and displaying the model's trendlines, we can see that Radio advertising is shown to have the highest ROI, followed by TV, and then Newspaper. However, after retrieving the R2 score and MSE for each channel, we can see that the model's predictive reliability for TV advertising is much higher than that of Radio and Newspaper.

This shows us that while Radio advertising may have the largest ROI on average, TV may be more practical due to being more conistent and reliable (Newspaper advertising is both unreliable and has the lowest average ROI, so it's mostly impractical).

The biggest limitation of this project is its low R2 score and MSE for Radio and Newspaper advertising. This is because of the high variance in the dataset for Radio and Newspaper ROI, so overfitting for TV data is probably not the issue here.

Overall, because of the high variance for Radio and Newspaper, linear regression may not be the best ROI forecasting approach for Radio and Newspaper, although the model seems to do quite well with predicting TV.

In terms of impact, this project allows us to truly see the advertising potential in various media. Radio advertising is often overlooked, but according to our model, there is some real potential in the medium as long as risk is accounted for.
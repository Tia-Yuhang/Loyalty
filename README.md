# Project: Predicting Supermarket Loyalty Spending

International Essentials is an international supermarket chain.

Shoppers at their supermarkets can sign up for a loyalty program that provides rewards each year to customers based on their spending. The more you spend the bigger the rewards. 

The supermarket would like to be able to predict the likely amount customers in the program will spend, so they can estimate the cost of the rewards. 

This will help them to predict the likely profit at the end of the year.

It appears that the number of years in the loyalty scheme is the biggest driver of spend. Customers with at least one year in loyalty program are the highest in number and total spending compared to other categories. Any other columns or features appears to have little relationship with customer's spending and may have negative effects in predicting customer's spending.

We also found that promotion event has little positive or negative effect on average customer's spending.

To evaluate model accuracy, we use coefficient of determination $R^2$, with $R^2=1$ the highest score. Starting with lieanr regression as a baseline model, we obtain a score of $R^2=0.90$.

Finally, we use random forest regression as a more complex model where feature selections and hyperparameter tuning are present to make our model more accurate. With a score of $R^2=0.99$, our model is ready for deployment.

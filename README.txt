# The price of furniture
## Why these furniture can be sold for more than 1000?

We will use dataset from  IKEA Saudi Arabia to find out what are the factors that affect the price of furniture over 1000.
The data includes the following variables:
• item_id – Unique item ID for item of furniture  
• category – The furniture category the item belongs to  
• price – The current price in Saudi Riyals (as recorded on 20/04/2020)  
• sellable_online – Is the item available to purchase online?  
• other_colors – Is the item available in other colours  
• depth – Depth of the item in cm  
• height – Height of the item in cm  
• width – width of the item in cm  

We use price as the response variable. Investigate which remaining variables significantly affect the price by building a GLM model.  

1. we perform a preliminary test on the data set to observe whether the data set has null values and outliers. Then use the mean value to fill in the nulls and remove outliers.  
2. choose whether the model is binomial or poisson
according to the AIC minimum criterion, we choose the Binomial model.  
3. Choose which model is better: probit, cloglog or logit in Binomial.  
according to the AIC minimum criterion,the logit model is better than others.  
4. Detailed analysis of the logit model.
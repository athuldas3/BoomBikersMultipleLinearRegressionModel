# Boombikes-LinearRegression-Assignment 
> Linear Regression performed on the Boombikes bike rental dataset as part of an assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore. 

## Note : 
Run the jupyter notebook line by line

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework in the Machine Learning module. 
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc. 
- The Boombikes bike rental dataset is being used. 


### Conclusion:

The summary of the model after data interpretation, visualisation, data-preparation, model building and training, residual analysis and evaluation of test model are as follows-

- The R-squared value of the train set is 82.1% whereas the test set has a value of 80.88% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model. 

- Our developed model's mean squared error is close to 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set.

- The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.  

- We can conclude that the bike demands for the BoomBikes is company is dependent on the temperature and whether it is a workingday or not. 

- Additionally more rentals seem to be demanded on the winters as compared to the summer and spring. 

- We had observed that the months of September and October had higher use of rentals. 

- In terms of days the maximum focus was on days like Wed, Thurs and Sat and more on holidays. 

### Recommendations:

- These interpretations help us derive meaningful insights in the bike rental market and the behaviour of the people. 

- One of the recommendations based on this model are that there should be aggressive marketing in the summer and spring season to drive up rentals. 

- Since the summer months also show low rental levels, a strong marketing strategy for the first 6 months of the year can assist in driving up the rental numbers. 

- There has to be an approach required to introduce more users on days where the weather is less clear, perhaps with incentives or strategic deals. 

- Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed to this idea and there has to a strong analysis done to retain the repeat customers. 



## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy


## Contact
Created by Athul Das 


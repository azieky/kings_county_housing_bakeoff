# Kings County Housing Bake-off

For the Kings County Housing Bake-off, we were tasked with the goal to predict houses prices given a dataset of information. This could be beneficial in a business setting for many reasons. For example, if a customer wanted to buy a house, they could be able to put in some relevant data about the location, square footage, bedroom, etc. And be able to get an estimate of what the house is worth. On the other side if someone is selling a house, they would be able to do put in similar data to see what a fair price would be. It is also good to get this practice because similar modeling processes could be used in many different aspects of business. For example, a business professional could use a similar modeling process to valuate a business, or stock prices. 

  
- **Exploratory Data Analysis (EDA):** 

The start, I began performing EDA (Exploratory Data Analysis). I first want to look at the statistical features of our target variable “Price”. 
![alt text](Price_vs_Frequency.png)




- **Feature Engineering:** You must create **at least 3 new features** to test in your model. Those features do not have to make it into your final model, as they might be removed during the feature selection process. That is expected, but you still need to explain the features you engineer and your thought process behind why you thought they would explain the selling price of the house.  

- **Statistical Tests:** Your notebook must show **at least 3 statistical tests** that you preformed on your data set. Think of these as being part of your EDA process; for example, if you think houses with a view cost more than those without a view, then perform a two-sample T-test. These can be preliminary evidence that a feature will be important in your model.  

- **Feature Selection:** There are many ways to do feature selection: filter methods, P-values, or recursive feature elimination (RFE). You should try multiple different techniques and combinations of them. For your final model, you will **settle on a process of feature selection**; this process should be **clearly shown in your final notebook**.

- **Model Interpretation:** One of the benefits of a linear regression model is that you can **interpret the coefficients** of the model **to derive insights**. For example, which feature has the biggest impact on the price of the house? Was there a feature that you thought would be significant but was not? Think if you were a real estate agent helping clients price their house: what information would you find most helpful from this model?

## GitHub Repository

A GitHub repo is a good way to keep track of your work, but also to display the work you did to future employers. Your GitHub should contain the following:

- A `README.md` that briefly describes the project and the files within the repo.
- Your cleaned and annotated notebook showing your work.
- A folder with all of your 'working' notebooks where you played around with your data and the modeling process.

## Data Set Information

This data set contains information about houses that were sold in the Seattle area during the last decade. Below is a description of the column names, to help you understand what the data represents. As with most real world data sets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions relating to what the data means. 

Like every data set, there are some irregularities and quirks. Trust me, there wasn't a house sold with 33 bedrooms, even though the data says there was. *You have to decide how you want to handle that example*. Also, some houses were sold more than once within the time frame of this dataset. Think about how that can be useful information in predicting the selling price.

As you go through this modeling process, think about what determines how much someone will pay for a house.  For example, the larger the house is, the more people will pay for it. If you understand why certain houses cost more than others and represent that in your model, it will be a more accurate model.  

Have fun!

# Column Names and descriptions for Kings County Data Set
* **id** - unique ID for a house
* **date** - Date day house was sold
* **price** - Price is prediction target
* **bedrooms** - Number of bedrooms
* **bathrooms** - Number of bathrooms
* **sqft_living** - square footage of the home
* **sqft_lot** - square footage of the lot
* **floors** - Total floors (levels) in house
* **waterfront** - Whether house has a view to a waterfront
* **view** - Number of times house has been viewed
* **condition** - How good the condition is (overall)
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house (apart from basement)
* **sqft_basement** - square footage of the basement
* **yr_built** - Year when house was built
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip code in which house is located
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors

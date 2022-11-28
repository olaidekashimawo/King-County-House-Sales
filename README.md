# King-County-House-Sales
# Movie analysis

![image](https://user-images.githubusercontent.com/82849694/203416288-515b5a5c-657b-4885-974c-0ef53a4c2b1a.png)

 ### Name: Olaide Kashimawo
 
 ## Project Overview.
 
 The King County House Dataset contains a wealth of information about the price, size, location, condition, and other features of houses in King County, Washington.
 
 ## Business Problem.
 I'll show you how I used Python to create a multiple linear regression model to predict house prices.

 ## Data Analysis and Understanding.
 In this step, I gathered data, a csv spreadsheet, then load it into a dataframe to assess its quality.
 I will be looking for missing value and problems in quality  and/or structure. We will be removing extraneous data and making modifications, 
 such as replacing information and removing duplicates, to ensure our dataset is trim and clean for analysis
 
 ![image](https://user-images.githubusercontent.com/82849694/204338052-c2156bc2-9c51-400a-94a1-908bced20a04.png)
There appears to be a strong positive correlation between sqft living, sqft above, and sqft living15 and price. This is not the case for sqft basement, sqft lot, and sqft lot15. It is self-evident that larger houses are more expensive. The graphs also show that the majority of houses lack a basement and land space, despite the fact that the price does not increase linearly with larger basement and land space. I discovered that sqft living is the sum of sqft above and sqft basement.
 
 ## Final Result and Conclusion.
 ![image](https://user-images.githubusercontent.com/82849694/204337390-a5676ab5-af7c-46fb-9f7e-77273e543f2f.png)

 Since the model can only explain 0.699-0.656% of the variance in house prices (R-squared), there is still some room for error.
 The projections will need to be double-checked to verify they make sense given what is known about the house.
 The resulting model is multicollinear, but the metrics show that it is not overfitting and can estimate house prices on unseen test data with accuracy.

 ## Next Step.
 Future work would need more insight into how zipcode influenced house prices, as the amount of houses in specific zipcodes have higher sales prices.
 To determine the  validity of the data further, I will use the polynomial regression model.
 
 ## For Additional Information
 The full analysis can be found the Jupyter Notebook.

## Outilne
- title
- Project Overview
- Business Problem
- Data Anaysis and Understanding
- Final Results
- Conclusion

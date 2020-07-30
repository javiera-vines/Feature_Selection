# Feature Selection in Python

In general, we understand that Feature Selection is one of the most important steps when we create a Machine Learning model. For example, if a feature (or variable) is not relevant for our model, this could impact our output variable. Therefore, if we have irrelevant features in our model, it will make our model not very accurate. 
 
Feature selection can be done in multiple ways, but here in this notebook we can observe 3 methods:
1. Filter Method
2. Multilinear Regression
3. Embedded Method
 
The data here is about energy consumption, weather conditions and the amount of visitors inside a building. These three datasets were in different formats which needed to standardize first, to finally merge them together.
 
The main purpose here is to improve the Energy Efficiency in the building, by trying to identify which are the most relevant variables for the Hvac Energy Consumption.
 
Finally, I also did some visualizations that you can check in my **Tableau portfolio**, where I show the distribution of the variables and it’s relationships:  https://public.tableau.com/profile/javiera.vines#!/vizhome/EnergyConsumptionHVACSystem/EnergyConsumption
 
>*If you would like to learn more about Feature Selection, I recommend you to review this article, which helped me a lot in this task:* 
https://towardsdatascience.com/feature-selection-with-pandas-e3690ad8504b
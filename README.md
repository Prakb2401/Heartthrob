# Education for income

### Background and Goal:
The relationship between income and Education level is well established but remains sometimes poorly understood
Our goal on this project is to Use Machine Learning and analyze the relationship between income per Capita on the number of  Bachelors percentage and postsecondary degree holding by State in the US

### Variables for Exploration: 
Per Capita Income (by State), Bachelor's degree Percentage and post secondary percentage (by State)

### Period: 2012-2017

### Tools Used:
Pandas, Matplotlib, Tableau, Scikit-Learn, HTML, CSS, Bootstrap

### Machine Learning Trends:

Pandas, get_dummies, and feature engineering was utilized to get a better fit model due to our dataset size. States and years were transformed into categorical data. Testing and training data was preprocessed through scaling to normalize the data within a smaller range

<img width="728" alt="table get" src="https://user-images.githubusercontent.com/100292828/187718726-ebd4a5d4-d0d8-4422-b042-44b0adf9faaf.png">

We ran our analysis to get our residual plot. Prior to that, we decided to run linear regressions to see the correlation between income, bachelor’s degree and post-secondary degree. Actual and predicted data was plotted on the same scatterplot.

![Incomevpostsecondary](https://user-images.githubusercontent.com/100292828/187719051-4c6401c7-ef38-469c-9136-0facc462850e.png)
![IncomevsBachelors](https://user-images.githubusercontent.com/100292828/187719306-83a33e31-6f54-4b15-a332-20ac0ba660ba.png)

The R2 of .80 indicates that the model explains about 80% of the variability of the data around the mean. The mean scored error, which shows the averaged squared difference between the predicted and actual values was .09, close to the desired 0 range. 

<img width="302" alt="last s" src="https://user-images.githubusercontent.com/100292828/187720027-e078254f-a8f2-4d47-829e-fd2d26179c66.png">

Tableau: <br>
For the Tableau portion of this project we created several visualizations based on our dataset.
* Visualization 1- We have a map of the country and it shows average income and percentage of bachelors by state per year. We also added a filter so you can change which year you want to see and the color of the state changes accordingly.

* Visualization 2- We have average income per year per state.

* Visualization 3 - We have percentage of bachelor graduates by year per state.

* Visualization 4 - We show trends in average income per year and we a filter for state and year.

Tabluea Public Links: <br>
https://public.tableau.com/app/profile/elton.cummings.iii/viz/shared/XMNYPGBF5

https://public.tableau.com/app/profile/prak.bagavatula/viz/Dataframe/Sheet5

### Sources: 

https://apps.bea.gov/iTable/iTable.cfm?reqid=70 

https://ncses.nsf.gov/indicators/states/indicator/bachelors-degree-holders-per-25-44-year-olds 







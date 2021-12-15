# World-Happiness-Report-2019
Top countries have highest and lowest Happiness Score. Correlation between Happiness Score and other variables. Linear regression of the Happiness Score. To what extent are factors such as Social support, Health life expectancy,… associated with Happiness Score?

1. Dataset explanation: 
- The dataset has 156 observations and 9 variables.
<br />     + 156 observations are: 156 countries.
<br />     + 9 variables are: Ranking, Country, Score, GDP per capita, Social support, Health life expectancy, Freedom to make life choices, Generosity, Perception of corruption.
- I chose this dataset because of the reasons in the description. Besides, is economic development only a part of the story. To what extent are factors such as Social support, Health life expectancy,… associated with Happiness Score?

2. Problems:
- Which are the top 5 countries which have the highest and lowest Happiness Score?
- The correlation between Happniess Score and GDP per capita, Social support and Health life expectancy, and the correlation coefficients of those.
- Linear regression of the Happiness Score. 
- Predict a country's Happiness Score with some numeric values.

3. Explaination analyses that lead to final conclusions:
- Read the dataset. I set 'happiness' as the name of the new dataset.
- Chang the names of variables to easier name for using.
- 1. Top 5 countries which have highest and lowest Happiness Score:
<br />      + Top 5 highest countries with highest Happiness Score: head(happiness, n=5)
<br />      + Top 5 highest countries with lowest Happiness Score: tail(happiness, n=5)
<br />      + Draw a graph of those 10 countries. I did create a new dataframe that only has those 10 countries
- 2. Calculate the Average Happiness Score of all countries. 
<br />      + I did add a new feature called 'level' to see if that country is above or below the Average Happiness Score.
- 3. Draw a plot of correlation between Happiness Score and GDP per capita, Social Support and Health life expectancy. 
<br />      + I also calculate the correlation coefficients of those 3 graphs. 
<br />      + Besides, the graph show the linear model of those plots.
- 


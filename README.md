# Witchcraft-Trials-Data-Analytics-and-Visualization-Final-Class-Project
## Executive Summary:
Using Python's Jupyter Notebook, I collaborated with two other students in order to clean and organize the data and create visualizations using packages such as numpy, pandas, seaborn, and matplotlib in order to answer some of the research questions we came up and found that:
1. Trials were at their peak during the 17th century . 
2. Trials occurred at a higher rate in colder weather and with less precipitation and so lack of crops from farms could've been a motivating factor.
3. Determined most that were accused of being a witch were those of lower and middle class.

## Business Problem:
The witch trials were widespread in many different countries in the early modern period and through data we wanted to understand the witchcraft trials in more detail. We wanted to understand what were some driving factors that led to the witchcraft trials , what contributed to leading to the verdict of execution. Were there weather factors? Did gender play a role? Did economic class play a role? How did the trials change over time and by geography? Were there differences among countries in approaching the trials?

## Methodology:
1. Cleaned the two data sets that were used by removing missing data and creating consistent formatting .
2. Used packages such as pandas to group related columns together in a subset of the data set for analysis .
3. Used visualization packages such as matplotlib and seaborn to create visualizations to answer research questions.

## Skills:
Python: Pandas, Matplotlib, Numpy, Seaborn, Plotly, Scikit Learn

## Results:
 We were able to answer our research questions:
How did witchcraft trials change over time and geography?

In our various plots, we looked at how the amount of trials changed over many centuries. From these plots, we can see that the highest peaks of witchcraft trials occurred during the 17th century, with the trials mostly occurring in Germany, Switzerland, Scotland, and Spain.

How did population and urbanization affect witchcraft trials?

To find whether or not population and urbanization had an affect on witchcraft trials, we used KMeans clustering to see if countries with similar population and urbanization statistics had a comparable number of trials. In the clustering plots there wasn't any significant evidence to suggest that population and urbanization affected witchcraft trials.

What factors were most likely to result in an execution?

Using the Scottish witchcraft survey data identified a variety of variables that impacts execution rates and showed the relation between each of these. Most notably torture was very unlikely to result in execution and were ordeals. The involvements of storms as evidence in the trial however was likely to result in a conviction. Further more we looked at socioeconomic factors and the gender and count of the accusers.

Did climate or weather conditions drive witchcraft trials?

From the four scatterplots detailing, trials vs weather, trials vs temperature, trials.mil vs weather, and trials.mil vs temperature we observed that a higher measure of trials occured in weather with negative values which represented less precipitation and a higher measure of trials occured in colder temperatures. We also observed a higher frequency of trials and trials.mil occured in colder temperatures and in weather with less precipitation. So from this we insinuated that perhaps the witchcraft trials occured during weather that brought drought and in temperatures creating cold enough temperatures that may have destroyed crops and hence food supplies. We know from the Scottish witchcraft survey dataset that storms in witchcraft trials were likely (~75%) to result in an execution, so there is a relationship between witchcraft trials and the weather. With the correlation found among cold temperatures and trials, detrimental effects of cold weather may have been blamed on witch

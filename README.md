# AM10 Group9's Project

## Topic idea: Life expectancy in different parts of the world 


### What is your topic? 

Blue zones are regions in the world where people are speculated to live longer than average; the term was coined by Gianni Pes, Michel Poulain and Dan Buettner. There are five blues zones: Okinawa (Japan), Sardinia (Italy), Nicoya (Costa Rica), Icaria (Greece) and Loma Linda (California). 


Our goal is to analyze different factors, such as; nutrition, lifestyle, exercise, climate, genetics, hygiene,... and the impact they have on longevity in different parts of the world. 


### What issues or questions are you addressing? 

More specifically we aim to answer these questions: 

-In what countries do people tend to live longer?
- Why do people living in blue zones live longer than others ? 
- How and why did longevity change over time for these countries ? 
- Which factors have the biggest influence on life expectancy and why?


### What is the source of the data you will be using? 
We will use: 
- [Gapminder dataset](https://www.gapminder.org/data/)
- [World Bank's health nutrition and population statistics](https://databank.worldbank.org/source/health-nutrition-and-population-statistics)
- [The world bank’s life expectancy at birth dataset](https://data.worldbank.org/indicator/SP.DYN.LE00.IN)


### What is the source of the data you will be using? 
We will use hypothesis testing to check correlations between factors affecting life expectancy and life expectancy. We will use linear regressions with LASSO and k-fold cross-validation to estimate life expectancy of certain countries and how different parameters impact it. Logistic regressions for categorical variables. 


### What statistical techniques do you think you may be using? Be as specific as possible; your github repo readme.md should be about a couple of paragraphs.

We used hypothesis testing to check correlations between factors affecting life expectancy and life expectancy. We used linear regressions to identify  variables that are significantly impacting life expectancy in a particular country in different time points, and then we adjusted the regression model based on the initial regression result to increase its explaining power. 

In this process, we noticed two unexpected points. (1). Alcohol is positively impacting a particular country's life expectancy; (2). GDP does not significantly impact life expectancy. Based on these two findings, We also used cluster analysis based on GDP and life expectancy to investigate it.



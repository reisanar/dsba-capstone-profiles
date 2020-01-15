### Senior Capstone: Directed Research

Below is a short description of the different projects students worked on during the Spring 2019 semester. 


_Twitter 2020 Political Sentiment_ by _**Kahlil Wehmeyer**_

This app was created with the intention of getting a better understanding of the sentiment towards and surronding presedential candidates of the 2020 election for the Unites States of America.

This app is, in a way, tracking the candidate popularity. Favorite and retweet counts are a somewhat reasonable measure of how the public feels about a candidates message.
References, [Text Mining with R](https://www.tidytextmining.com),
[Shiny Apps](https://shiny.rstudio.com/),
[R for Data Science](https://r4ds.had.co.nz), and 
[Twitter Developer](https://developer.twitter.com/content/developer-twitter/en.html). Some of the key packages for this project are as follows:
- [Tidyverse](https://www.tidyverse.org/)
- [Plotly](https://plot.ly/r/)
- [Tidytext](https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html)
- [Topic Models](https://cran.r-project.org/web/packages/tm/index.html)
- [igraph](https://igraph.org/r/)
- [ggraph](https://cran.r-project.org/web/packages/ggraph/index.html)

***

_Undergraduate Completion Rates Analysis_ by _**Jarrod Merriman**_

The purpose of this project is to build a model to predict the completion rate of undergradute students at universities who complete their degree in four years or less than four years. The data being used is the [CollegeScoreCard dataset](https://collegescorecard.ed.gov/data/) from the U.S. Department of Education. The predictive model will be built using the tool [Weka](https://www.cs.waikato.ac.nz/ml/weka/).

***

_Relocation Station_ by _**Natalie Brum and Erich Mengore**_

This project aimed to help a new Data Science graduate find the best city to relocate based on economic factors like cost of living and average salary as well as natural factors like the climate and the natural disasters in an area. 

**Data Sources**:

- Cost Of Living 2018 - [Numbeo.com] (https://www.numbeo.com/cost-of-living/) - Cost of Living Data for 2018 obtained by Professor Sanchez-Arias from numbeo.com, which was retrieved from github.
- 2016 Regional Price Parity and Per Capita Personal Income - [BEA.gov] (https://www.bea.gov/) - Regional price parity, and Per Capita Personal Income in 2016 compiled by the Bureau of Economic Analysis(BEA)
- Natural Disaster Map - [thereadystore.com] (https://www.thereadystore.com/) - Natural Disaster Locations, the data found here was manually entered into csv format.
- R Packages such as `Geonames` and `GSODR` 

**Final Product:**

Results from this project will be showcased in the form of a [Shiny App](https://shiny.rstudio.com/)

***

_Sleep Studies_ by _**Luke Rhon, Marc Burstein, and Kenneth Williams**_

The main goal of this project is to build a predictive model that explores student sleep behavior or performance based on input values. Using the findings from the 2012 study we can test those results by creating a model. Our findings so far have been trying to identify variables for our linear regression models. Although we established the main variables for each regression model it doesnt explain most of the variance. The next step was trying out decision trees to see if we can increase the predictive power. Models have been built, but additional investigatigation is required to improve the accuracy and do some fine tuning.

**Key Packages for the project**

- [tidyverse](https://www.rdocumentation.org/packages/tidyverse/versions/1.2.1)
- [scales](https://www.rdocumentation.org/packages/scales/versions/0.4.1)
- [gridExtra](https://www.rdocumentation.org/packages/gridExtra/versions/2.3)
- [dplyr](https://www.rdocumentation.org/packages/dplyr/versions/0.7.8)
- [rpart](https://www.rdocumentation.org/packages/rpart/versions/4.1-13)
- [rpart.plot](https://www.rdocumentation.org/packages/rpart.plot/versions/3.0.6)

**Data Sources:**

- Data from a study of sleep patterns for college students. Original study: Onyper, S., Thacher, P., Gilbert, J., Gradess, S., ["Class Start Times, Sleep, and Academic Performance in College: A Path Analysis"](https://www.ncbi.nlm.nih.gov/pubmed/22390245)

- Surveys from the [National Sleep Foundation](https://www.sleepfoundation.org/professionals/sleep-america-polls) 

- [Student Life Dataset](https://studentlife.cs.dartmouth.edu/) from Dartmouth


***

_Forecasting Florida Incarceration Trends_ by _**Jordan Douglass and Oliver Bennett**_

The initial goal of the project was to measure and reflect upon healthcare in the Florida Prison Systems. Unfortunately, Florida does not require a lot of data reporting in terms of healthcare for inmates.

That being explained, we began correlating the incarceration data, recidivism rates and social determinants of health between the years 2012-2017 for all counties in the state of Florida. Some of the social determinants included have been graduation rates, median household income, race and children in poverty. In our data exploration, we found many correlations within counties for these determinants and have been creating forecasting models using linear regression to determine what the next five years may look like for these specific couties given this data and how rates may be impacted if the data changed. For example, a question we are asking is, will Polk County have lower incarceration rates if the graduation rate goes up?

Upon creation of the static regression models, we hope that we may be able to create a web application that can be more insightful and interactive for users.

## Tools used:
- Tableau 
- Microsoft Excel


## References: 
Articles:
[Health Care Contracts Under Scrutiny](https://www.palmbeachpost.com/news/state--regional/lucrative-florida-prison-healthcare-contract-under-increasing-scrutiny/slh8FmmxdWpH7TnHyW5HFN/)
[Privatizing Prisons](https://www.palmbeachpost.com/news/privatizing-prison-health-care-leaves-inmates-pain-sometimes-dying/hiJMRmNG9YhE9JFTxfnZaN/)
[Overburdened Prison Systems in Florida](http://www.crj.org/news-article/new-report-shows-path-forward-floridas-overburdened-prison-system/)


# Data Sources:
[List of Florida Institutions](http://www.dc.state.fl.us/ci/index.html)
[Costs/Quality of Prison Care](https://www.pewtrusts.org/en/research-and-analysis/reports/2017/10/prison-health-care-costs-and-quality)
[Recidivism Report 2018](http://www.dc.state.fl.us/pub/recidivism/RecidivismReport2018.pdf)
[General Heath Outcomes in Florida Downloads](http://www.countyhealthrankings.org/app/florida/2018/downloads)
[General Health Outcomes and Social Determinants Overview](http://www.countyhealthrankings.org/app/florida/2018/overview)
[Urbanicity Trends and Incarceration Data](https://www.vera.org/projects/incarceration-trends)


***

_Making Money With Houses_ by _**Geoffrey Ruiz**_

This project helps people decide where to purchase a property to be able  to then rent out that property for a profit, this could help with retirement or just some passive income on the side as an investment. In  this project to gain insight on the housing market I used data from  Zillow. I then linked the data from Zillow to the Bureau of Labor Statistics using the `BLSApi` package in R. I transformed the data from both sources using STATA because that is the program that I am the most 
comfortable with. I also used STATA to do any of the statistical analysis to determine what cities were in the better positions for which market situation, meaning if you are in the market for a 2 bedroom then which city is the most ideal. 

[Zillow](https://www.zillow.com/research/data/)
[BLSApi](https://www.bls.gov/developers/api_r.htm)
[STATA](https://www.stata.com/)


***

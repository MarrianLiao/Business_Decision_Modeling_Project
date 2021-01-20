# Business Decision Modeling Projects
The two projects are team projects using Pyomo concrete models to:
1. Estimate the cost of shipping of Covid-19 vaccines from Yale New Haven Hospital, Hartford Hospital, and Lawrence and Memorial Hospital to 10 selected towns in the Tolland county. We will build 3 models to come up with the most cost-efficient distribution approach:

* Minimal Cost Flow Model
* Monte Carlo Simulation with the constraint that at least 30% supply comes from each hospital
* Monte Carlo Simulation with the constraint that at least 10% supply comes from each hospital
(The notebook file name is P1_COVID_ShortestPathforTolland.ipynb, the data for this project is P1_Data.csv)

and

2. Calculate estimation of total return for year 2020 based on using following steps:
* Implement Exploratory Analysis using Python on daily stock prices data in Oct.2019 of consumer staple categories from S&P 500 to select 10 best stocks out of 35 stocks
* Use yahoo stock API to get monthly price data in 2020, and analyze stock allocation for optimal risk level based on efficient frontier 
* Calculate the return of our porfolio based on the risk level we chosed  
(The notebook file name is P2_StockPorfolio.ipynb, the data for this project is P2_consumer staples raw data.xlsm)

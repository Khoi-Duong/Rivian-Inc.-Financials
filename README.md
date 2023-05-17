# Project Overview
For this project, you will analyze a dataset of your choice.

For this project, you can focus your efforts within a specific industry, as detailed in the following examples.

### Finance
Exploratory data analysis is used by many individuals within the finance industry, including investment banking professionals, private equity analysts, lending analysts, financial administrators, and real estate professionals.

Exploratory data analysis is used for the following tasks in the financial sector:

* Identifying deals

* Analyzing private equity markets

* Researching arbitrage opportunities

* Evaluating liquidity

* Keeping up to date with finance and refinance trends

### Project Examples
* Equity Trading: While working for a large equity-trading company, you’re tasked with researching a client’s portfolio. Your client wants to invest in telecom stocks and needs expert analysis to make the right decision. Using the Nasdaq Data API (https://data.nasdaq.com/tools/api), pull a year’s worth of trading data for the major cell phone providers: AT&T, T-Mobile, and Verizon. Which stocks are trending upward? Which are trending downward? Based on the data, what would you recommend to your client?

* New-Car Loan Analysis: People have been financing higher car values over longer amounts of time. Explore what is driving this trend. Search for answers by using data collected from the Federal Reserve Economic Data (FRED) (https://fred.stlouisfed.org/series/DTCTLVENANQ). What other questions can you answer with the data? What do your results suggest about the time value of money? What about the impact of these loans as time goes on?

### Healthcare
Exploratory data analysis is used by many individuals within the healthcare field, including clinical data analysts, pharmaceutical testers, healthcare-economics researchers, senior policy analysts, compliance operations analysts, and public health informatics scientists.

Exploratory data analysis is important for understanding the following healthcare considerations:

* Predicting and diagnosing illnesses

* Improving patient safety

* Reducing time to diagnosis

* Increasing our understanding of disease risks and causes

* Developing stronger prevention strategies

### Project Examples
* Mental Health in Tech: People working in tech are often at their desks for extended amounts of time. Explore how this trend correlates with mental health. Examine the data collected through surveys (https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) and search for trends. Find out if there is a link between mental health and companies that offer wellness programs. What do the results show you about the state of mental health in tech? Can you suggest steps that companies can take to help their employees?

* Personal Fitness Analyst: Research whether working out helps a person become more active overall. Use data collected by the Samsung Health application (https://www.kaggle.com/datasets/aroojanwarkhan/fitness-data-trends) to uncover relevant trends. What do the results tell you about individuals using this app? Have their lifestyles become more active? Less? Remained the same?

### Custom
We’ve only specified healthcare and finance, but any industry can benefit from exploratory data analysis.

The following professionals also use data and can benefit from exploratory data analysis:

* Natural and environmental scientists

* Marketing professionals

* Information security analysts

* Business intelligence analysts

### Project Examples
* Private Investigator: Use aggregate crime data (https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i) from different police precincts in a city to uncover criminal activity patterns. Consider that most crime in New York City takes place in the summer (https://www.nydailynews.com/new-york/nyc-crime/daily-news-analysis-reveals-crime-rankings-city-subway-system-article-1.1836918). Find out if you are able to uncover similar patterns in your city. What do your results suggest about how police should plan their patrols? What do your results suggest about how law enforcement resources should be distributed over the calendar year?

* Uber Rides and Weather: No one likes to walk in subzero temperatures or scorching heat. Do people use Uber more when the weather is uncomfortable? Using Uber ride data from Kaggle (https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city) and data from a weather API, find out if people take Uber more during summer and winter months, and if there are relationships between daily temperature and ride frequency. What do the results tell you about surge-pricing strategies and commuter habits?

### Project Proposal
Before you start writing any code, your group should outline the scope and purpose of your project. This will help provide direction and safeguard against **scope creep** (the tendency for projects to become more complex after work begins).

The proposal is essentially a brief summary of your interests and intent. Be sure to include the following details:

* The kind of data you’d like to work with and the field you’re interested in (finance, healthcare surveys, etc.)

* The questions you’ll ask of the data

* Possible source for the data

Use the following example for guidance:

The aim of our project is to uncover patterns in credit card fraud. We’ll examine relationships between transaction types and location, purchase prices and times of day, purchase trends over the course of a year, and other related relationships derived from the data.

### Finding Data
Once your group has written a proposal, it’s time to start searching for data. We recommend the following curated sources of high-quality data:

* data.world (https://www.data.world/)

* Kaggle (https://www.kaggle.com/)

* Data.gov (https://www.data.gov/)

* Awesome Public Datasets (https://github.com/awesomedata/awesome-public-datasets)

* Public-APIs (https://github.com/n0shake/Public-APIs)

* Awesome API (https://github.com/Kikobeats/awesome-api)

* Medium API List (https://benjamin-libor.medium.com/a-curated-collection-of-over-150-apis-to-build-great-products-fdcfa0f361bc)

**IMPORTANT**:

Whenever you use a dataset or create a new dataset based on other sources (such as existing datasets or information scraped from websites), make sure to use the following guidelines:

1. Check for copyright protections, and make sure that the way you plan to use this dataset is within the bounds of fair use.

2. Document how you intend to use this dataset now and in the future. Find any licenses or terms of use associated with the dataset, and review them to confirm that your intended use is in compliance.

3. Investigate how the dataset was collected. Identify any indicators that the data was obtained from a source that the compilers were not authorized to access.

You’ll likely have to adjust your project plan as you explore the available data. That’s okay! This is all part of the process. Make sure that your datasets are not too large for your personal computer. Big datasets are difficult to manage locally, so consider using data subsets or different datasets altogether.

### Data Cleanup and Analysis
Now that you’ve picked your data, it’s time to tackle development and analysis. This is where the fun starts!

The analysis process can be broken into two broad phases: (1) exploration and cleanup, and (2) analysis.

As you’ve learned, you’ll need to explore, clean, and reformat your data before you can begin answering your research questions. We recommend keeping track of these exploration and cleanup steps in a dedicated Jupyter notebook to keep you organized and make it easier to present your work later.

After you’ve cleaned your data and are ready to start crunching numbers, you should track your work in a Jupyter notebook dedicated specifically to analysis. We recommend focusing your analysis on multiple techniques, such as aggregation, correlation, comparison, summary statistics, sentiment analysis, and time-series analysis. Don’t forget to include plots during both the exploration and analysis phases. Creating plots along the way can reveal insights and interesting trends in the data that you might not notice if you wait until you’re preparing for your presentation.

# Rivian Inc. Financials
**1. Project Title:**
Rivian Inc. Financials Analysis

**2. Project Description/Outline:**
Rivian Automotive Inc is a developing player in the electric automobile market. The market for electric pickup trucks is definitely strong, but investors may wonder if this company’s management is using Rivian’s assets in a beneficial way for the company’s shareholders. By gathering the company’s financial information, an investor is able to perform certain ratio calculations and compare the company’s annual balance sheets, income statements, and statements of cash flows. This will give any investor a clear idea of whether or not Rivian is a company worth investing in.

**3. Research Questions to Answer:**
* Is it worth it to invest in Rivian?

* What do Rivian’s liquidity ratios suggest about the company’s ability to repay short-term and long-term obligations?

* How do Rivian’s leverage financial ratios help evaluate the company’s debt levels?

* How do Rivian’s efficiency ratios help measure how well the company utilizes its assets and resources?

* Are Rivian’s profitability ratios having a growth rate?

* Do Rivian’s market value ratios show favorable trends?

**4. Datasets to Be Used:**
* Rivian’s Balance Sheet, Income Statement. Statement of Cash Flows For The Past 4 Years

* https://site.financialmodelingprep.com/developer/docs/#Financial-Statements-List

**5. Rough Breakdown of Tasks:**
* Use Pandas to clean and format your dataset or datasets.

* Create a Jupyter notebook describing the data exploration and cleanup process. 

* Create a Jupyter notebook illustrating the final data analysis. 

* Use Matplotlib to create 6 to 8 visualizations of your data (ideally, at least 2 visualizations per “question” that you ask your data). 

* Save PNG images of your visualizations to distribute to the class and instructional team—and for inclusion in your presentation. 

* Create a write-up summarizing your major findings. This should include a heading for each “question” that you asked your data as well as a short description of your findings and any relevant plots. 

* **Bonus:** Use at least one API—if you can find one with data pertinent to your primary research questions.

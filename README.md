# Project_1
Group 5 - Alvin, Fatema, Bradley and Wendy

## Introduction
For Project 1, you will work with your group to find and analyze a dataset of your choice. You can focus your efforts within a specific industry, as detailed in the examples below.

## Industries and Applications

### Finance
Exploratory data analysis is commonly used in the finance industry by professionals such as investment bankers, private equity analysts, and real estate professionals. Key applications include:

- Identifying deals
- Analyzing private equity markets
- Researching arbitrage opportunities
- Evaluating liquidity
- Keeping up to date with finance and refinance trends

#### Project Examples
- **Equity Trading:** Analyze a year’s worth of trading data for major cell phone providers using the [Nasdaq Data API](https://data.nasdaq.com/tools/api) to recommend investment strategies.
- **New-Car Loan Analysis:** Use data from the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/series/DTCTLVENANQ) to explore trends in car financing and their implications on the time value of money.

### Healthcare
Exploratory data analysis supports healthcare professionals in:

- Predicting and diagnosing illnesses
- Improving patient safety
- Reducing time to diagnosis
- Increasing understanding of disease risks
- Developing stronger prevention strategies

#### Project Examples
- **Mental Health in Tech:** [Examine survey data](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey) to explore the correlation between desk jobs in tech and mental health issues.
- **Personal Fitness Analyst:** Use data from the [Samsung Health application](https://www.kaggle.com/datasets/aroojanwarkhan/fitness-data-trends) to analyze trends in personal fitness and activity levels.

### Custom Applications
Any industry can benefit from exploratory data analysis, including natural sciences, marketing, information security, and business intelligence.

#### Project Examples
- **Private Investigator:** Analyze [crime data](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i) and [other](https://www.nydailynews.com/new-york/nyc-crime/daily-news-analysis-reveals-crime-rankings-city-subway-system-article-1.1836918) to uncover patterns and suggest improvements in police patrolling strategies.
- **Uber Rides and Weather:** Investigate how weather conditions affect [Uber ride](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city) frequencies to inform surge-pricing strategies.

## Team Collaboration
- **Communication:** Establish a Slack channel and share contact information.
- **Project Management:** Use [GitHub Projects](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/managing-project-boards) to track tasks and milestones.
- **Regular Updates:** Ensure regular communication and support among team members.

## Project Requirements

### Analysis
- **Visualizations:** Create 6–8 visualizations of data with clear labeling and detailed explanations.
- **Analysis and Conclusion:** Provide a professional-level summary of findings supported by statistical analysis.

### Presentation
- **Slide Deck:** Prepare slides that are clean, professional, and maintain audience interest.
- **Group Presentation:** All members must participate in the final presentation, demonstrating thorough preparation and relevance to the project material.

### Evaluation
Projects will be graded based on the completeness and quality of analysis, presentation, and documentation, with the following grading scale:
- **A (+/-):** 90+
- **B (+/-):** 80–89
- **C (+/-):** 70–79
- **D (+/-):** 60–69
- **F (+/-):** < 60

# Project Guidelines

The following project guidelines focus on teamwork, your project proposal, data sources, and data cleanup and analysis.

## Collaborating with Your Team

Remember that these projects are a group effort. The experience of close collaboration will create better project outcomes and help you in your future careers. Specifically, you’ll learn collaborative workflows that will enable you to approach and solve complex problems. Working in groups allows you to work smart and dream big. Take advantage!

## Project Proposal

Before you start writing any code, your group should outline the scope and purpose of your project. This will help provide direction and safeguard against scope creep (the tendency for projects to become more complex after work begins).

The proposal is essentially a brief summary of your interests and intent. Be sure to include the following details:

- The kind of data you’d like to work with and the field you’re interested in (finance, healthcare surveys, etc.)
- The questions you’ll ask of the data
- Possible source for the data

### Example Proposal

The aim of our project is to uncover patterns in credit card fraud. We’ll examine relationships between transaction types and location, purchase prices and times of day, purchase trends over the course of a year, and other related relationships derived from the data.


## Finding Data
Once your group has written a proposal, it’s time to start searching for data. We recommend the following curated sources of high-quality data:

- [data.world](https://www.data.world/)

- [Kaggle](https://www.kaggle.com/)

- [Australian Bureau of Statistics](https://explore.data.abs.gov.au/)

- [Data.gov.au](https://data.gov.au/)

- [Data.gov](https://www.data.gov/)

- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)

- [Public-APIs](https://github.com/n0shake/Public-APIs)

- [Awesome API](https://github.com/Kikobeats/awesome-api)

- [Medium API List](https://benjamin-libor.medium.com/a-curated-collection-of-over-150-apis-to-build-great-products-fdcfa0f361bc)


⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺  
 **IMPORTANT**   
⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺⸺


Whenever you use a dataset or create a new dataset based on other sources (such as existing datasets or information scraped from websites), make sure to use the following guidelines:

- **Check for copyright protections**, and make sure that the way you plan to use this dataset is within the bounds of fair use.
  
- **Document how you intend to use this dataset** now and in the future. Find any licenses or terms of use associated with the dataset, and review them to confirm that your intended use is in compliance.
  
- **Investigate how the dataset was collected**. Identify any indicators that the data was obtained from a source that the compilers were not authorised to access.

You’ll likely have to adjust your project plan as you explore the available data. That’s okay! This is all part of the process. Just make sure that everyone in the group is aligned on the project’s goals as you make changes.

Make sure that your datasets are not too large for your personal computer. Big datasets are difficult to manage locally, so consider using data subsets or different datasets altogether.

## Data Cleanup and Analysis

Now that you’ve picked your data, it’s time to tackle development and analysis. This is where the fun starts!

The analysis process can be broken into two broad phases: 
1. **Exploration and Cleanup**
2. **Analysis**

As you’ve learned, you’ll need to explore, clean, and reformat your data before you can begin answering your research questions. We recommend keeping track of these exploration and cleanup steps in a dedicated Jupyter notebook to keep you organized and make it easier to present your work later.

After you’ve cleaned your data and are ready to start crunching numbers, you should track your work in a Jupyter notebook dedicated specifically to analysis. We recommend focusing your analysis on multiple techniques, such as aggregation, correlation, comparison, summary statistics, sentiment analysis, and time-series analysis. Don’t forget to include plots during both the exploration and analysis phases. Creating plots along the way can reveal insights and interesting trends in the data that you might not notice if you wait until you’re preparing for your presentation. Presentation requirements will be further explained in the next module.

## Presentation Day

It’s crucial that you find time to rehearse before presentation day.

On the day of your presentation, each member of your group is required to submit the URL of your GitHub repository for grading.

### NOTE
Projects are requirements for graduation. While you are allowed to miss up to two Challenge assignments and still earn your certificate, projects cannot be skipped.

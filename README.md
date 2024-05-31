# US_Honey_Analysis

### Project Overview
- This data analysis project aims to provide insights into the US Honey consumption, including the average price of honey over the years. My aim is to explore and analyze this data to identify the trends and patterns in the average honey price and gain insights into its fluctuation over time.

### Data Sources
- Dataset: The dataset used for this analysis is the `US_honey_dataset.csv` file, containing detailed information about average price of honey and honey production states in US.

#### Dataset - `US_honey_dataset.csv` Column Data Description

|Column Name|Description|
|-----------|-----------|
|Unnamed |This column is giving us only index|
|state|Represents the states name of US|
|Colonies_number|Colonies of bee in the states|
|yield_per_colony| Total count the bee inside a colony|
|production|Production of honey|
|stocks |Total stock of the honey in state|
|average_price|Average value of the honey per year in different state|
|value_of_production|Value of honey production per year|
|year|Year of productions|

### Tools
- **Programming Language:** Python
- **IDE/Code Editor:** Jupyter Notebook
- **Libraries**
  - `pandas`
  - `matplotlib`
  - `seaborn`

### Data Cleaning / Preparation
- In the initial data preparation phase, we performed the following tasks:

   - Familiarizing with data and inspected data.
   - Data cleaning and formatting.

### Exploratory Data Analysis
- Performed an exploratory data analysis to visualize and analyze the trends.
  
#### EDA involved exploring the data to answer the key questions, such as:

1. Which states are rarely contributing to honey production for the last 27 years?
2. Which are the top 5 Honey producing states in the US?
3. What is the change in mean average price of Honey from 1995 to 2021?
4. Which was the year when production of Honey in whole US was the highest?
5. Which state was having the highest contribution in the year 2000?
 
### Insights
**Top Contributing States in honey production:**
- Over the last 27 years, honey production in the United States has been dominated by a few key states. The top 5 states consistently contributing to honey production are:

  - North Dakota
  - California
  - South Dakota
  - Florida
  - Montana

**Less Contributing States in honey production:**
- Conversely, there are states that have consistently been among the least contributors to honey production. These states are:

  - Maryland
  - Oklahoma
  - South Carolina
  - Kentucky
  - Maine

**Continuous Increase in the average price of honey:** 
- From 2005 to 2017, there was a continuous and substantial increase in the average price of honey. 

**Dramatic Drop in the average price of honey:**
- Starting from 2018 onwards, there was a dramatic drop in the average price of honey. 

**Highest Honey Production Year:**
- The year with the highest honey production in the U.S. over the given period is 2000, with a production volume of 220,320,000 pounds.

**Highest Contributing State in the Year 2000:**
- In the year 2000, the state with the highest contribution to honey production in the United States was North Dakota, with a production volume of 33,350,000 pounds.
- The year 2000 marked the peak of honey production in the U.S. at 220,320,000 pounds, with North Dakota playing a crucial role in achieving this record high. 


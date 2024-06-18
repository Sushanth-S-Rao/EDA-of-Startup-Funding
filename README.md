# Exploratory Data Analysis of the Capital Funding received by the Startups

## Exploratory Data Analysis:
Exploratory Data Analysis is a foundational approach serving as a preliminary step to understand the structure, patterns, and relationships within a dataset. By employing a combination of data visualization, descriptive statistics, and exploratory techniques, it aims to uncover insights, detect anomalies, and formulate hypotheses that guide further analysis. Through this, analysts gain a deeper understanding of the dataset's characteristics, identifying trends, outliers, and potential correlations between variables. This process not only aids in data cleaning and preparation but also informs subsequent modeling, hypothesis testing, and decision-making

## Technology Stack:
* Jupyter Notebook
* Python
* Libraries Used:
| Function                        | Libraries                                         | 
| :-------------------------------| :------------------------------------------------:|
| Data Processing and Computing   | pandas, numpy                                     |
| Visualization                   | seaborn, matplotlib, plotly, squarify, wordcloud  |
| Hypothesis Testing              | scipy                                             |

## Dataset
Dataset comprises 10 columns and 2372 rows with each tuple containing Serial Number, Date, Startup Name, Industry Vertical, Sub Vertical, City and Location, Investors Name, Investment Type, Amount in USD, and Remarks about the funding. The information is sourced from [trak.in](https://trak.in/india-startup-funding-investment-2015/)

Trak.in is a mission to uncover the truth: We are India’s leading news portal, covering business, technology, ecommerce, startups, and mobile ecosystem

## Methodology

### Data Preprocessing and Cleaning
* Handling missing data
* Typecasting the columnar data into suitable datatypes
* Removing redundant, duplicate values

### Hypothesis Testing
Hypothesis testing is a statistical method that allows us to make inferences or draw conclusions about a population based on a sample of data. It is crucial phase that allows us to test assumptions, compare groups, and determine the statistical significance of the patterns and relationships observed in the dataset.

* Shapiro-Wilk Test for normality
* Levene's Test for homoheneity of variances
* Kruskal-Wallis H Test

### Exploratory Data Analysis

* Characteristics of funding received over time
* Look into maximum funding invested (Unicorns - Flipkart, Paytm)
* Look into minimum and average funding
* Industries or Domain of the startups that are a popular investment choice
* Influence of Location of the startups base in receiving the funds
* Important Investors in the startup ecosystem
* Investment type favoured on startups (seed funding and private equity)

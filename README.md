# DS-Blog

### Introduction

Every year, Stack Overflow conducts a massive survey of people on the site, covering all sorts of information like programming languages, salary, code style and various other information. This year, they amassed more than 64,000 responses fielded from 213 countries. In this blog, I aimed to look at the data gathered as part of 2017 developer survey and see what the developer community has to say. 

### Data

The data is downloaded from Kaggle link [here](https://www.kaggle.com/stackoverflow/so-survey-2017) and it is  made up of two files:

`survey_results_public.csv` - CSV file with main survey results, one respondent per row and one column per answer
`survey_results_schema.csv` - CSV file with survey schema, i.e., the questions that correspond to each column name

### Analysis

Exploratory Data analysis has been done with the data provided to draw useful insights. The data includes an array of questions which are responsed by the developers. Majority of the features are categorical and the responses in most of them are in an ordinal fashion. As part of the EDA, extensive data wrangling was done to derive inferences using the responses and it may be noted that data wrangling process itself was sufficient enough to answer some interesting questions without having to do further modeling.

The analysis has led to answers for the following 3 questions:

* What are the most popular programming languages?
* Once a coder, always a coder - or is it?
* What Skills are perceived as most important to get hired by a Tech firm

Please follow the blog [here](https://medium.com/@myemailidus.9/what-the-software-developer-community-has-to-say-f314c2b848da) for the  details.


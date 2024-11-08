# Data-exploration-and-analysis
Movie and Titanic datasets  
Solution done in R and the rendered rmarkdown is here: https://weightliftinggeek.github.io/Data-exploration-and-analysis/  

## Task 1 of 2: Correlation
### The Dataset for task 1: Movies  
The film industry or motion picture industry is one of the largest sources of entertainment in the world. The industry produces thousands of films annually and rakes in billions of dollars in revenue. As a consultant, your tasks are to analyze the Dataset obtained from IMDB. An online database of information related to films, television programs, and video games, including cast, production crew, fictional characters, biographies, plot summaries, trivia, and reviews.  

### Dataset Description:
The movie dataset gathers data on movies and a few attributes about its structure, like movie duration in minutes, release year, director, and actors, and so on. Besides these variables, there are a few columns of interest regarding the movie evaluation, such as IMDB score, reviews, audience’s votes, and Facebook’s likes.  
The goal is to bring a perspective in one of these variables (e.g. profit) and its relationship with the other variables in the Dataset. Exclude variables of non-interest (if applicable).  
For the Dataset, complete the following tasks:  
1) Missing Values:  
o Remove or impute all missing values? Support the method you would like to use (remove or impute) with an appropriate argument.  
2) Exploration:  
o Based on the Dataset, calculate “Profit” and determine the relationship between “Profit” and other variables (e.g. IMDB score). Hint: Profit = Gross – Budget. Use line plot or scatter plot to find the relationship.  
o Calculate the correlation between the variable(s) used in the Dataset.  
o Based on the correlation matrix, list and plot Strong and Weak Correlations. Provide appropriate reasoning about the findings.  

## Task 2 of 2: Association Rule mining
### The Dataset for task 2: Titanic
Many organizations generate a large amount of transaction data daily. For example, a store like “Coles” stores customer shopping information on a large scale using check-out data. Association rule mining is one of the major techniques to detect and extract useful information from large scale transaction data. But it can also throw up some interesting survival patterns such as the case of the Titanic.  
For the Titanic dataset, complete the following tasks:  
1. Missing Values:  
o Remove or impute all missing values? Support the method you would like to use (remove or impute) with an appropriate argument.  
2. Association rule mining:  
o Perform Association rule mining on the dataset provided, for “Survived = Yes” constraint only. Exclude rule where “Survived = No”. Use parameter = list(minlen=2,supp=0.005,conf=0.8).  
o Based on the generated rules and analysis, which pairs of entries have the highest lift value? List the top 3. You first need to sort the rules and then use a graph   to plot the top 3 as follows:  
o Based on the generated rules, is there any difference between “Children” travelling first class, second class, and third class? Support your answer with an appropriate argument.  
o Based on these results, what other value-added observations can you make (if applicable)? (E.g. the crew, first-class passengers and women had the same chance of survival than men and third-class passengers?  


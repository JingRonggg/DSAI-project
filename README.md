# Welcome to instagram-data-analysis repository 

## About 

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Instagram data from [Statso](https://statso.io/instagram-reach-analysis-case-study/). For detailed walkthrough, please view the source code in order form: 

1. [Data Extraction](https://github.com/JingRonggg/DSAI-project/blob/main/Data%20Extraction.ipynb)
2. [Data Resampling](https://github.com/JingRonggg/DSAI-project/blob/main/Data%20Resampling.ipynb)
3. [Linear Regression](https://github.com/JingRonggg/DSAI-project/blob/main/linear-regression.ipynb)
4. [Words-correlation](https://github.com/JingRonggg/DSAI-project/blob/main/Words-correlation.ipynb)

## Contributors 

- @Ayyriel - Natural Language Processing 
- @JingRonggg - Data Extraction, Data Visualisation, Multi-Output Regressor
- @negnij - Boot Strapping, Linear Regression  

## Problem Definition 
- Which hashtag, captions and caption length yield the highest impression and engagement(likes, comments, shares)?
- Is there any correlation between Caption Length and engagement(likes, comments, shares) & impression?

## Models Used 

1. Linear Regression
2. Multi-Output Regressor
3. Natural Language Processing (LLM)

## Conclusion 
- There is no correlation between caption length and engagement(likes, comments, shares) & impression
- Likes and Shares are correlated to Impressions
- Bootstrapping our data resulted in the sample being too random and hence, unable to find the correlation
- Linear Regression did not perform well with our bootstrapped 
- Captions with the words 'certified', 'solved' and 'explain' will likely result in the highest impression and engagement(likes, comments, shares)
- Using #datascience, #datascienceeducation, #datasciencejob will likely result in the highest impression and engagement(likes, comments, shares)


## What did we learn from this project? 
- Handling insufficent data using bootstrapping methods 
- Natural Language Processing, Use of nlkt library
- Usage of Multi-Output regressor to check for non-linear relationship
- Concepts about Stemming, Lemmatization and Tokenizing under Natural Language Processing
- Collaborating using GitHub 

## References 
- https://statso.io/instagram-reach-analysis-case-study/
- https://realpython.com/nltk-nlp-python/
- https://www.analyticsvidhya.com/blog/2022/06/stemming-vs-lemmatization-in-nlp-must-know-differences/
- https://allendowney.github.io/ElementsOfDataScience/12_bootstrap.html
- https://scikit-learn.org/stable/modules/generated/sklearn.multioutput.MultiOutputRegressor.html

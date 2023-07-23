# Amazon Review Sentiment Analysis

## Overview
In this repository, we will be doing a detailed analysis on Amazon review data. The goal is to do a Sentiment Analysis,<br> which comes under Natural Language Processing (NLP). As you know, NLP is a brach of Data Science which<br> is in high demand now a days and as a Data Scientist, its important to know the basics of the algorithm and how it<br> works. We are given the data, which are the Amazone reviews. the idea here is to predict the sentiment of each of the comments. That is whether its Negative or Positive.

Please make sure you have **forked** the repo and set up a new virtual environment.<br>

For this purpose you use following commands:

```
pyenv local 3.9.12
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
<br>
The added [requirements file](<./requirements.txt>) contains all libraries and dependencies we need to execute Pandas and <br>Numpy.
<br>
In case of any error using the above commands, try removing the version number of the packages from the ```requirements.txt``` file. For me, it worked like that only.
<br>

## Stakeholder info
- Stakeholders can be any online selling company which sells certain products and have to deal with the reviews of the customers for<br> their better performances.

## Data Structure
The data here are the customer reviews from Amazon. And is stored in the ```data```folder in this repository. We first have to filter the required data and then do the analysis.
- Input: Amazone reviews (text data)
- Output: Sentiment (0 or 1)

## Exploratory Data Analysis (EDA)
In the notebook, `EDA.ipynb` I have done a detailed analysis with on the given text data and tried to visualize the data to get more idea on the data. 

## Evaluation metric
- Since it is a `classification problem` the suitable evaluation matric would be to get the `Evaluation matrix`<br> 
and see the `Evaluation matrix`. <br>
---------------------------------------------

## Machine Learning model and Results
- This is a classification peoblem. So I decided to try Naive Bayes model.
- The model gave pretty good result at the end which was a total accuracy of 0.94
- Other models didn't do well, we can do further analysis on these data. 

## Outlook
- We can try out other classification model such as Random Forest or XGBoost classifier and can check the performance again.
- Try to optimise the model hyperparameter tuning and see if it improve the results.
## Recommendations for stakeholders
- I think you can already use Naive Bayes model to classify the data, since it give an accuracy of 0.94.
- Then try using models such as Random Forest or XGBoost classifier and use it, if it predicts even better
Okay! Lets start :):)


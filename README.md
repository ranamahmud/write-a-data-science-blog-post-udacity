# Project 1: Write A Data Science Blog Post Udacity

# Table of Contents

1. [Libraries used](#libraries)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Description](#files)
5. [Summary of the results](#results)
6. [Licensing, Authors, and Acknowledgements](#acknowledgements)

## Libraries used <a name="libraries"></a>
The following python libraries were used in this project.
* certifi==2019.11.28
* chardet==3.0.4
* cycler==0.10.0
* deap==1.3.1
* idna==2.8
* joblib==0.14.1
* kiwisolver==1.1.0
* matplotlib==2.2.5
* numpy==1.18.1
* pandas==0.25.3
* pyparsing==2.4.6
* python-dateutil==2.8.1
* pytz==2019.3
* requests==2.22.0
* scikit-learn==0.22.1
* scipy==1.4.1
* six==1.13.0
* tqdm==4.41.1
* update-checker==0.16
* urllib3==1.25.8
* Xgboost
* tpot
* xlrd
* torch

## Installation <a name="installation"></a>
You need python 3.7.7 or above to work with this project.
You can install the necesary libraries by the following code in terminal. 

`pip install -r requirements.txt`

To run the jupyter notebook you have to cd into the project directory. Then run the following command to open the jupyter notebook

`jupyter notebook`

It'll open the notebook server.
The project file is "Project 1 Write A Data Science Blog Post.ipynb"

![Image of Project Notebook](/jupyter_notebook_view.png)

## Project Motivation <a name="motivation"></a>

I was interested to analyze this data set to find out what set apart the happily married and divorced couples. In this project I tried to answer the following questions using Divorce Predictors data:

1. Is there a significant difference between Happily Married and Divorced couples?
2. What are the most agreed and disagreed things between the couples?
3. What couples need to focus most to prevent divorce?
4. How accurately we can predict a future divorce?

## File Description <a name="files"></a>
* [**Project 1 Write A Data Science Blog Post.ipynb**](/Project%201%20Write%20A%20Data%20Science%20Blog%20Post.ipynb): 
Notebook contains the data analysis.
* [**divorce.xlsx**](/divorce.xlsx): Divorce Predictors data set
* [**requirements.txt**](/requirements.txt): Text file containing list of packages used.
* [**LICENSE.txt**](/LICENSE.txt): Project LICENSE file.

## Summary of the results <a name="results"></a>

1. There exists a significant difference between married and divorced couples in all the topics of the scale.

2. Divorced and married couple's top 5 disagreed topics were discussion, humiliating during the discussion, insulting during the discussion, sudden discussion, breaking calm during the discussion. 
On the other hand, the top 5 most similar opinionated topics were having time at home for partners, acting like strangers in terms of sharing environment at home. Married couples agreed on average they have more time at home and act less like strangers about family and environment than divorced couples.
The other two topics where married couples were neutral but divorced couples agreed that they mostly stayed silent and felt right in their discussion.
Based on this we can say that married couples are more careful about their discussion, acts less like strangers in terms of sharing environment at home, and gives more time to their partners.

3. Divorced couples and married couples top 10 deciding questions we can see divorced couples and married couples gave opposite answers.

4. Using 70% data as training and 30% data logistic regression model performs best and it can 98.03% accurately predict divorce between couples.

## Licensing, Authors, and Acknowledgements <a name="acknowledgements"></a>

* **Data Source:** [Divorce Predictors data](https://archive.ics.uci.edu/ml/datasets/Divorce+Predictors+data+set)
* **Acknowledgements**: 

Dataset credit  

Yöntem, M , Adem, K , İlhan, T , Kılıçarslan, S. (2019). DIVORCE PREDICTION USING CORRELATION BASED FEATURE SELECTION AND ARTIFICIAL NEURAL NETWORKS. Nevşehir Hacı Bektaş Veli University SBE Dergisi, 9 (1), 259-273. 

* [**License**](/LICENSE.txt) MIT License


README.md file that communicates the 
libraries used
the motivation for the project
the files in the repository with a small description of each
a summary of the results of the analysis
necessary acknowledgements
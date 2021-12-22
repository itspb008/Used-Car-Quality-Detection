# Used-Car-Quality-Detection

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Theroretical Aspect](#theoretical-aspect)
  * [Installation](#installation)
  * [To Do](#to-do)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Credits](#credits)


![](https://wtop.com/wp-content/uploads/2015/11/Auto-Sales1.jpeg)

## Overview
This model is used to classify if a used car is a good buy or a bad buy. Descriptive and Inferential statistics concepts are used to explore and find relationship between the independent variables and dependent variable. Feature Engineering and Feature Selection is also done on this Kaggle dataset. Two machine learning algorithms, Logistic Regression and Random Forest Classifier, are used to check which perform better on this dataset. 

## Motivation
After completing different courses on Data Science and Data Analytics. I wanted to work on a open source project all by myself and use my Data Science expertise in practical field. I downloaded the dataset from the Kaggle(<a href = "https://www.kaggle.com/c/DontGetKicked/overview/description">here</a>).

## Technical Aspect
1. The entire project is completed on Google Colab, which provide a Jupyter notebook environment that runs entirely in the cloud.
2. For visualization Matplot, Seaborn, Plotly libraries are used.
3. For statistics Scipy.stats is used.
4. For Feature Engineering 
     * Sklearn.preprocessing is used
     * Category_encoders is used
5. For Model Building
     * Sklearn.linear_models for Logistic Regression
     * Sklearn.ensembles for Random Fprest
6 For Model Evaluation sklearn.metrics is used

## Theoretical Aspect
1. For Exploratory Data Analysis Destcriptive Statistics is used.
2. Statistical Analysis
     * For Discrete Features Chi-Square test and Crammey's V test is used
     * For Continuous Features Analysis of Variance is used


## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```


## To Do
1. Using other different ML algorithms to find the accuracy of the prediction.
2. Add a better vizualization chart to display the predictions.

## Bug / Feature Request
If you find a bug (the model couldn't handle the query and / or gave undesired results), kindly open an issue [<a href = "https://github.com/itspb008/Used-Car-Quality-Detection/issues/new">here</a>] by including your search query and the expected result.


## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://www.software.ac.uk/sites/default/files/images/content/jupyter-main-logo.svg" width=300>](https://jupyter.org/)    [<img target="_blank" src = "https://www.bgp4.com/wp-content/uploads/2019/08/Scikit_learn_logo_small.svg_-840x452.png" width=170>](https://scikit-learn.org/stable/)                     [<img target="_blank" src="https://miro.medium.com/max/3880/1*ddtqWGkJz1TUCg1WM9qKeQ.jpeg" width=280>](https://colab.research.google.com/) 



[<img target="_blank" src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width=200>](https://seaborn.pydata.org/)                  [<img target="_blank" src="https://blueorange.digital/wp-content/uploads/2019/12/logo_matplotlib.jpg" width=200>](https://matplotlib.org/stable/index.html) 


## Team
Prashant Bharti


## Credits
- https://jovian.ai/learn/machine-learning-with-python-zero-to-gbms
- Machine Learning Course by Andrew NG on Coursera
- Analytics Vidhya Blogs 
- Krish Naik Youtube Channel
- StatQuest with Josh Stramer Youtube Channel
- Kaggle.com

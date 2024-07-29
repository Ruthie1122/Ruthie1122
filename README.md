 Task
TODO - What is the problem? And where is the challenge?
For this project, i used a somewhat de-identified dataset of credit card transactions in Europe. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
The dataset is highly unbalanced. The positive class (frauds) accounts for 0.172% of all transactions.

## Description
TODO - How have you solved the problem?
Learning outcomes: the five stages of the project

Data Collecting / Cleaning (see below)
Data Exploration
Data Visualization
Machine Learning
Communication

## Installation
TODO - How to install your project? npm install? make? make re?
I pip install imbalanced-learn and imported the libraries to use like 
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from imblearn.under_sampling import RandomUnderSampler
from imblearn.over_sampling import RandomOverSampler, SMOTE, BorderlineSMOTE

## Usage
TODO - How does it work?
It To install the project, please follow these steps:

Clone the repository Install the required dependencies. Preferable to github
```
./my_project argument1 argument2
My Paypal
```

### The Core Team

Ruth Musa Sunama

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>

<!---
Ruthie1122/Ruthie1122 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

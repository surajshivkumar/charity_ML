# Charity_ML

In this project, I employ different supervised learning algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, we can infer this value from other publically available features. 
The data can be found in the *census.csv* file
Visuals.py is a script to generate visuals for our data.This can be found in the repo as well.

## Requirements
- Python 3
- Numpy
- Pandas
- Matplotlib
- Sklearn

## To Run
Firstly you'll need to have installed Jupyter to open the .ipynb file.
Open Jupyter->navigate to the charity_ML folder that you have cloned->open the .ipynb file <br>
OR <br>
Run the following command on your terminal.Make sure you're in the ./charity_ML directory.
<br>
`jupyter notebook finding_donors.ipynb` or `ipython notebook finding_donors.ipynb`


## Features
- *age* : Age
- *Workclass* : Working class (Private,State-gov..)
- *education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th,          
- *education-num* : Number of educational years completed
- *marital-status* : Marital status (Married-civ-spouse, Divorced..)
- *occupation* : Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial..)
- *relationship* : Relationship Status (Wife, Own-child, Husband, Not-in-family..)
- *race* : Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- *sex* : Sex (F/M)
- *capital-gain* : Monetary Capital Gains
- *capital-loss* : Monetary Capital Losses
- *hours-per-week* : Average Hours Per Week Worked
- *native-country* : Native Country (United-States, Cambodia, England,..)

## Target-Variable
- *income* : Income more than 50,000 $ (>50K) or at-most 50,000 $ (<=50K)

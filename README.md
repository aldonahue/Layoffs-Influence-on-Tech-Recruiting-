# Layoffs Influence on Tech Recruiters
***
Capstone project for the AI academy 

All final products, including the [presentation](https://github.com/aldonahue/Layoffs-Influence-on-Tech-Recruiting-/blob/main/Future%20of%20Tech%20Recruiting.pdf), [Final Juptyer notebook](https://github.com/aldonahue/Layoffs-Influence-on-Tech-Recruiting-/blob/main/Layoffs%20Influence%20on%20Tech%20Recruiting%20Final%20Notebook.ipynb), [Initial cleaning & exploratory notebook](https://github.com/aldonahue/Layoffs-Influence-on-Tech-Recruiting-/blob/main/Initial%20Exploratory%20and%20Cleaning.ipynb), [official cleaning notebok](https://github.com/aldonahue/Layoffs-Influence-on-Tech-Recruiting-/blob/main/Official%20clean.ipynb), [Data](https://github.com/aldonahue/Layoffs-Influence-on-Tech-Recruiting-/blob/main/layoffs.csv), and  [capstone proposal](https://github.com/aldonahue/Layoffs-Influence-on-Tech-Recruiting-/blob/main/AI%20academy%20capstone%20Proposal.pdf) are in the main repository.


## Project Description
***
For this project, Deloitte was contracted by a tech recruiting company (fictitious client) to help them gain the ability to project layoffs trends and use it to their advantage. Our business task was to research recent trends in Tech industry layoffs and develop and integrate a supervised machine learning model in to their business strategy.

I examined a variety of factors pertaining to recent layoffs (2020-present). Of particular interest were the Percentage laid off over time and across subindsutries with in the United Sates..

### Data Sources
***
* [Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022)
* [Layoff.fyi Tracker](https://layoffs.fyi/)

### Presentation
***
https://github.com/cLineman/CapStoneProject/blob/main/Capstone_Presentation.pdf


### Data Interpretation and Regression Modeling
***
I build multiple regression models in order to accurately predict the trend of future layoffs across the tech industry with in the United States. After importing and cleaning the data I engineerred several featurs for convience inlcuding date calulations, Location IDs, Sub industry IDs, and the creation of dummy variables. These along with several other data elements within data set were used to train, split and test the data set and were ran through our models as well. These ultimately informed our business recomendations for the client regarding a supervised machine learning model integrations.

### Findings and Recommendations
***
Through the overall investigation of the availble data it is clear that inegrating a linear regression model is the best choice for the client to integrate into their strategy. The linear regression model was the most accurate and consistent out of all three models that I ran. As well I was able to further validate its accuracy through calculating the R-Squared and RSME. This model ulitmately ran with a score of .795, R-squared of .795, RSME of .012. 

Moving forwad with this model I recomend the client periodically retrain the model with new and more current data to avoid model drift/rot. 

#### Acknowledgements
***
https://github.com/python/cpython/blob/3.10/Lib/warnings.py  
https://github.com/python/cpython/blob/3.10/Lib/zipfile.py  
https://jupyter.org/  
https://matplotlib.org/  
https://matplotlib.org/  
https://numpy.org/  
https://pandas.pydata.org/  
https://plotly.com/python/  
https://plotly.com/python/  
https://plotly.com/python/  
https://plotly.com/python/  
https://pypi.org/project/tabulate/  
https://scipy.org/  
https://seaborn.pydata.org/  
https://www.sqlite.org/index.html  
https://www.statsmodels.org/stable/index.html

[Python 3.9.12](https://www.python.org/) Copyright ©2001-2022. [Python Software Foundation](https://www.python.org/psf-landing/)
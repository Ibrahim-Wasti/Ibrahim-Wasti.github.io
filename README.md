## Data Analytics Portfolio by Ibrahim Wasti

This portfolio is a compilation of notebooks which I used for exploratory data analysis, dashboard creation, and building models. Each section will have different projects.

----

## Exploratory Analytics Projects

### Sales Analysis 
[nbviewer](https://nbviewer.jupyter.org/github/Ibrahim-Wasti/Sales-Data-Analysis/blob/main/Sales_Analysis.ipynb)  [Repo](https://github.com/Ibrahim-Wasti/Sales-Data-Analysis)

Project done for class, an analysis of sales for 2019 of an e-commerce company. Merged 12 files of sales data into one dataframe using the OS and Pandas libraries. Visualizations were created using MatPlotLib. Answered different questions to gain insights into the data and come to conclusions that would effect the company's strategy in marketing and staffing.

<p><img src="https://github.com/Ibrahim-Wasti/Ibrahim_Wasti_Portfolio/blob/main/images/SalesAnalysis.png" width="500" height="400" /></p>

![](https://github.com/Ibrahim-Wasti/Ibrahim_Wasti_Portfolio/blob/main/images/SalesAnalysis.png)

### Netflix: Movies & TV Shows 
[nbviewer](https://nbviewer.jupyter.org/github/Ibrahim-Wasti/Netflix-Movies-and-TV-Shows-EDA/blob/main/Netflix%20TV%20Shows%20%26%20Movies%20EDA.ipynb) [Repo](https://github.com/Ibrahim-Wasti/Netflix-Movies-and-TV-Shows-EDA)

This was a dataset which provided information on different aspects of the content on Netflix, from the director and cast to the availability by country. Tasks were to show top acotrs/directors, top countries by number of productions, amount of content for each age group, etc. All these questions were answered uding a combination of Pandas, Seaborn, and Matplotlib. The general datset and more information can be found on [Kaggle](https://www.kaggle.com/shivamb/netflix-shows).

<p><img src="https://github.com/Ibrahim-Wasti/Ibrahim_Wasti_Portfolio/blob/main/images/NEtflix-g.png" width="500" height="400" /></p>

### Sales & Marketing Dashboard using Power BI
[Repo](https://github.com/Ibrahim-Wasti/Dashboard-with-PowerBI)

Created a Power BI dashboard in accordance with businees request from client:
- Visualizing KPIs
- Sales analysis of total revenue, revenue by product, and revenue by employee
- Customer analysis by region and sales
Extracted the data from Microsoft SQL Serever (Queries can be fouind in the repo). Created a data model in Power BI and prepared the data for visualization and analysis. Visualized the different parameters and metrics using a variety of charts, graphs, and other tools available through Power BI.

<p><img src="https://github.com/Ibrahim-Wasti/Ibrahim_Wasti_Portfolio/blob/main/images/Dashboad.PNG" width="475" height=275" /></p>

----

## Regression Problems

### NBA Hollinger Player Efficiency Rating - Prediction
[nbviewer](https://nbviewer.jupyter.org/github/Ibrahim-Wasti/NBA-Hollinger-Player-Efficiency-Rating/blob/main/Exploratory%20Analysis%20and%20Modeling.ipynb)  [Repo](https://github.com/Ibrahim-Wasti/NBA-Hollinger-Player-Efficiency-Rating)

Used BeautifulSoup4, requests, and regex libraries to scrape the ESPN Hollinger website to create a dataset of players with 12 features, Player Efficiency Rating (PER) being the target variable. The scraper can be viewed [here](https://nbviewer.jupyter.org/github/Ibrahim-Wasti/NBA-Hollinger-Player-Efficiency-Rating/blob/main/NBA%20Player%20Stats%20Scraper.ipynb). Saved the data as a list of dictionaries to a json file for easy loading in and conversion to a dataframe when conducting data exploration, analysis, and modelling. Used Pandas, Seaborn, MPL, SK-Learn, and XGBoost for the above stated exploration, analysis, and modelling.

- Feature selection for the SK-Learn model done using Pearson Correlation as this was Linear Regression probelm.
- Used seaborn and IQR to get rid of outliers in the dataset, this increased the accuracy of the final model.
- Modelled using SK-Learn for a base accuracy score (measured by RMSE) to see if XGB would give better results.
- XGB Regressor performed with a higher accuracy (lower RMSE) than the SK-Learn model.

<p><img src="https://github.com/Ibrahim-Wasti/Ibrahim_Wasti_Portfolio/blob/main/images/NBA_PER_PC.png" width="400" height="400" /></p>

----

## Classification Problems

### HR Analytics: Data Scientists who change their jobs - Classification
[nbviewer](https://nbviewer.jupyter.org/github/Ibrahim-Wasti/DataScience-HR-Analytics/blob/main/Data%20Science%20HR%20Analytics%20EDA.ipynb)  [Repo](https://github.com/Ibrahim-Wasti/DataScience-HR-Analytics)

Analysis of Data Scientists who changed their jobs. Created a classifier with an overall accuracy of 80% and high recall and precision for target group. The dataset had many features such as, city, experience, education level, etc. I used XGBoost to create the model, and Pandas and Seaborn to visualize and explore the data.  The general datset and more information can be found on [Kaggle](https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists). 

<p><img src="https://github.com/Ibrahim-Wasti/Ibrahim_Wasti_Portfolio/blob/main/images/HR-Analytics-cm.png" width="500" height="300" /></p>

<p><hr style="border:2px solid black" /></p>

_Further detail for all projects can be found by clicking their respective **Repo** links found beneath the title of every project. To view the notebooks where the code was written please click on the **nbviewer** link which will show you the notebook using JupyterLab's online interface._ 

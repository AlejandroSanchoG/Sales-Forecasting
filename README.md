# Inditex - Sales Forecasting

## This project was created at the IE Business School in the Master in Business Analytics & Big Data from the April 2022 intake

## This project was done by:
* Camilo Pinzón Castellanos
* Xavier Hernan Samper
* Jose Ignacio Orlandi Hein
* Alejandro Sancho Gil

One of the biggest challenges for the company is to be able to determine, in advance, what levels of sales each item will have in the different stores it operates. The company’s internal data is used to build predictive models with this aim, but this is not sufficient, as the sale of an item will be affected by different factors beyond the company in different markets. Those factors could be features from the market, or even from the location itself, having an impact on the level of sales.

The aim of this project is to determine what type of external information is relevant when making a sales forecast in units, and to propose an algorithm that uses this information to estimate the sales of each item by market and / or location.

The project utilizes three different datasets provided by INDITEX, which were imported into the notebook using appropriate libraries. There are two main documents included. The premodeling one, including all the required treatments for the data. And the modeling one, including different models. Both of them are zipped as its size is bigger than accepted by Github.

The first step of the project is Exploratory Data Analysis (EDA), where the team analyzed the basic information of the data, including possible errors and everything that should be included in the EDA step. Then we identified and handled any missing values in the dataset, either by deleting or filling them as needed. We also managed any outliers present in the data.

The next step of the project was Feature Engineering, where we manage to create many new features using external APIs and also engineered the current data we had. Some examples of these new features are temperature, GDP, habitants, etc.

After that, we did a Train-Test split of the data and handled categorical variables by using both one hot encoding and target encoding. Finally, the data  had been scaled to prepare it for modeling.

Finally, three different models, including Random Forest Regressor, XGBoost and Light GBM, have been tested and evaluated. One of these different models has beens selected by considering the outputs recieved and the bussines case we worked on.

Overall, the project includes detailed comments and explanations for every step taken in the notebook, making it easy to understand and follow the process.

# Sales-forecasting
Sales forecasting for FMCG stores

Sales forecasting involves estimating future sales by analyzing historical data and market trends. It plays a pivotal role in helping businesses make well-informed decisions, effectively allocate resources, and prepare for anticipated shifts in customer demand.

Sales forecasting is invaluable because it reduces uncertainty, enabling businesses to align production and inventory levels with expected demand. It also aids in optimizing marketing strategies, ensuring that efforts are targeted where they matter most. In the long term, it empowers organizations to set realistic goals, fostering sustainable growth and financial stability.

If you're interested in gaining insights into the practical implementation of sales forecasting in a real-world project, take a closer look at the detailed analysis featured in this blog.


## Overview:
Our project revolved around forecasting retail sales quantities for the next six months, utilizing data stored in Snowflake's database. We harnessed Snowpark, a Python-based tool, for data analysis and applied the XGBoost regressor model to generate accurate predictions. These forecasts were seamlessly integrated back into Snowflake for easy access. This project showcases the power of data analysis, Snowflake's infrastructure, and the user-friendly features of ThoughtSpot for improved decision-making.


## Approach
In our journey to forecast sales effectively, we've harnessed the power of Snowpark and XGBoost. Here's a glimpse of our approach:

### Connection Establishment: 
We've initiated a successful connection to the Snowflake database using Snowpark Python, paving the way for seamless data access.

### Data Selection: 
We handpicked a historical sales dataset rich in sales and store demographics from various locations.

### Data Transformation: 
This data was elegantly transformed into a Pandas DataFrame, primed for thorough analysis and modeling.

### Data Organization: 
Our meticulous approach involved organizing data around 'Transaction_Date' and encoding categorical columns for a clean, understandable dataset.

### Model Selection: 
The highly capable XGBoost Regressor was our model of choice. We intricately tuned its parameters, including the learning rate, maximum depth, and number of estimators.

### Streamlined Training: 
A Stored Procedure (SPROC) was implemented to optimize the model training process.

### Testing and Foundation: 
Rigorous testing over a three-month dataset formed the strong foundation upon which our evaluation is built.

### Sales Forecasting: 
The trained model is now poised to provide precise sales forecasts for the next six months, aiding in strategic decision-making.

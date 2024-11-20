<h2>Title: "CarbonSmart: AI Solutions for Sustainable Energy"</h2>

<h3>Machine Learning for Sustainable Development Goal 13: Climate Action:</h3>
<h3> Introduction:</h3>
<p><h4>Project Objective:</h4> The primary objective of this project is to develop a machine learning 
model that analyzes energy consumption patterns to recommend optimal energy usage that 
minimizes carbon emissions. By identifying trends in energy consumption and emissions, 
this project aims to contribute towards actionable strategies that support carbon footprint 
reduction, aligning with global sustainability goals. <br>
<h4>Motivation:</h4>This project is inspired by the United Nations Sustainable Development Goals 
(SDGs), especially the goal centered on climate action. As global energy demands rise, there 
is an urgent need to adopt efficient energy practices that reduce carbon footprints and 
foster sustainable resource management.</p>
<h3>Data Collection:</h3>
Dataset Description: 
The dataset combines monthly data on energy consumption, renewable energy production, 
and carbon emissions, helping to identify patterns that reduce emissions: <br>
1. Date: Month and year of each record. <br>
2. Energy Consumption :Residential, Commercial, Industrial: Energy use in different 
sectors. <br>
3. Renewable Production (MWh): Solar, Wind: Renewable energy generation metrics. <br>
4. Carbon Emissions (metric tons):Coal, Natural Gas, Oil: Emissions from each energy 
source.<br>
<h3>Exploratory Data Analysis (EDA):</h3>
- Distribution and Outliers: Histograms revealed general distribution trends, while box plots 
identified outliers, especially in industrial energy consumption and emissions.<br> <br>
- Correlation Analysis: Scatter plots showed strong correlations between 
commercial/industrial energy use and coal emissions, indicating these sectors as major 
contributors.
<h3>Data Preprocessing:</h3>
- Splitting Data: The data was divided into training and testing sets to ensure that the model 
could generalize to new, unseen data. Typically, 80% of the data was used for training, and 
20% for testing. <br><br>
- Features and Target Variable: Key energy consumption features (e.g., Residential, 
Commercial, and Industrial energy usage) and renewable energy production data (e.g., Solar 
and Wind production) were used as input features (X), while Coal Emissions was the target 
variable (y).

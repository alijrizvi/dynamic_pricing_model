# Dynamic Pricing Model
(Link to the complete breakdown and story of this project; its "Project Article": 

## Background
This project utilizes datasets for fictional stores located in different regions to analyze and make predictive models to optimize future sales and pricing strategies. The datasets not only include information on features like Store Size and Weekly Sales ($), but also on external factors which might influence customer purchasing decisions [e.g., Consumer Price Index (CPI) of the time, Unemployment (%), etc.).

There were 3 datasets (.csv files) web-scraped in and joined together into one Dataframe for proper analysis and modeling, and each specialized in certain information.
- "Stores": Anonymized information about the 45 stores, indicating the type and size of store.
- "Features": Contains additional data related to the store, department, and regional activity for the given dates.
- "Sales": Historical sales data, which covers from 2010-02-05 to 2012-11-01

## Purpose
As a Data Science professional, I consider it obligatory to perpetually refine my skills and knowledge and keep on honing my versatile craft; as such, wanting to especially build skills in the massive domain of Retail, with its huge potential, I decided to embark on this project and undertake a more creative venture and go beyond just traditional Machine Learning and into truly "revolutionary" realms such as Dynamic Price Modeling, etc.

Also, crucially, integrating **Generative AI** tools and methodologies into your skillset is of paramount importance, and thus this project was another source of applying my Generative AI skills too.

Lastly, I also decided to work on my **Data Engineering** skills and, hence, implemented a light ETL (Extract, Transform, and Load) Pipeline in Databricks.

## Tools
- Python was the main tool used for web-scraping, data cleaning & management, advanced analytics, machine learning and predictive modeling, and statistical testing.
- Databricks for ETL Pipeline and Data Wrangling.
- Tableau for specialized visual analysis (Calculated Fields, Rolling Calculations) and interactive dashboards.

## Methodology & Techniques Used
In addition to Exploratory Data Analysis (EDA) and Data Visualization with a wide range of plots including line graphs, pairplots (scatterplots for all combinations of numerical features), boxplots, and bar graphs with trendlines, an unsupervised learning algorithm in the form of a K-Means Clustering model was implemented for customer segmentation on the basis of revenue generated, frequency of purchases, and recency.

Finally, there was statistical testing conducted in the form of ANOVA (Analysis of Variance) followed by Tukey's HSD test to compare pairwise differences between Month of the Year and average Weekly Sales ($).

Once it was confirmed that there are significant differences in average Weekly Sales by Month, thr project moved on to the ultimate part: Time Series Analysis & Forecasting to build the Dynamic Pricing Model.

A significant amount of Data Wrangling and Analysis was also done in Databricks, using SQL, and an ETL Pipeline was also made there to ensure smooth import and storage of related data files for this project.

## Results & Interpretation

Time Series Analysis allowed the forecasting of the next Year-and-a-half's (18 months') Weekly Sales ($) by Month, predict percentage sales change by month, and then use the latter to suggest pricing strategy shifts: this will be the Dynamic Pricing Model in and of itself.

## Highlights

Store Sizes were Categorized by Store Size Measures' Quantiles, and an Analytical Insight:
<img width="570" height="453" alt="image" src="https://github.com/user-attachments/assets/e68f78b6-0dae-4df2-86b9-1f4e8001eb27" />

How much does each Significant Measure within a Store Impact its Weekly Earnings ($)?
<img width="1406" height="895" alt="image" src="https://github.com/user-attachments/assets/5e18e84e-dc04-4008-97ca-35922271e8e1" />

Violin Plots for Cluster Analysis from the K-Means Clustering Algorithm:
<img width="1400" height="1600" alt="violinplot_kmeansclusters" src="https://github.com/user-attachments/assets/426a9824-9f9f-407e-8ff4-3bdc3416dfee" />

# Dynamic Pricing Model

## Background
This project utilizes datasets for fictional stores located in different regions to analyze and make predictive models to optimize future sales and pricing strategies. The datasets not only include information on features like Store Size and Weekly Sales ($), but also on external factors which might influence customer purchasing decisions [e.g., Consumer Price Index (CPI) of the time, Unemployment (%), etc.).

There were 3 datasets (.csv files) web-scraped in and joined together into one Dataframe for proper analysis and modeling, and each specialized in certain information.
- "Stores": Anonymized information about the 45 stores, indicating the type and size of store.
- "Features": Contains additional data related to the store, department, and regional activity for the given dates.
- "Sales": Historical sales data, which covers from 2010-02-05 to 2012-11-01

## Purpose
As a Data Science professional, I consider it obligatory to perpetually refine my skills and knowledge and keep on honing my versatile craft; as such, wanting to especially build skills in the massive domain of Retail, with its huge potential, I decided to embark on this project and undertake a more creative venture and go beyond just traditional Machine Learning and into truly "revolutionary" realms such as Dynamic Price Modeling, etc.

Also, crucially, integrating **Generative AI** tools and methodologies into your skillset is vital, and thus this project was another source of applying my Generative AI skills too.

Lastly, I also decided to work on my **Data Engineering** skills and, hence, implemented a light ETL (Extract, Transform, and Load) Pipeline in Databricks.

## Tools
- Python was the main tool used for web-scraping, data cleaning & management, advanced analytics, machine learning and predictive modeling, and statistical testing.
- Databricks for ETL Pipeline and Data Wrangling.
- Tableau for specialized visual analysis (Calculated Fields, Rolling Calculations) and interactive dashboards.

## Methodology & Techniques Used
In addition to Exploratory Data Analysis (EDA) and Data Visualization with a wide range of plots including line graphs, pairplots (scatterplots for all combinations of numerical features), and horiznotal bar graphs, there were two Machine Learning andtechniques applied: Time Series Analysis and Multiple Linear Regression, along with conducting a core statistical analysis of A/B testing in the form of ANOVA (Analysis of Variance) followed by Tukey's HSD test to compare pairwise differences between Store Size Categories and average Weekly Sales ($).

A significant amount of Data Wrangling and Analysis was also done in Databricks, using SQL, and an ETL Pipeline was also made there to ensure smooth import and storage of related data files for this project.

## Results & Interpretation

Time Series Analysis allowed us to Forecast the next Quarter's (3 months') Weekly Sales ($) and plan accordingly, by each Store Size Category.
- Multiple Regression: Allowed us to Quantify and Single out the Distinctive Effect of each... [**FINISH UP HERE!**]
- MOST IMPORTANT for "Dynamic Pricing": The Results from the ANOVA test confirmed that Store Size indeed affected Weekly Sales, and Tukey's HSD test was used to extract out the Omega-Squared value to devise a complex algorithm - details will be in the Notebook, with code - which would result in dynamically calculated prices for each row (Store performance recording), taking all of its features in to account.

## Highlights

Store Sizes were Categorized by Store Size Measures' Quantiles, and an Analytical Insight:
<img width="570" height="453" alt="image" src="https://github.com/user-attachments/assets/e68f78b6-0dae-4df2-86b9-1f4e8001eb27" />

How much does each Significant Measure within a Store Impact its Weekly Earnings ($)?
<img width="1406" height="895" alt="image" src="https://github.com/user-attachments/assets/5e18e84e-dc04-4008-97ca-35922271e8e1" />

# Customer Segmentation Using RFM Analysis and K-Means Clustering

## Project Overview

This project uses customer transaction data to identify meaningful customer segments based on purchasing behavior. The goal is to help a business better understand its customers, improve retention strategies, and support targeted marketing decisions.

## Business Objective

The objective of this project was to segment customers using Recency, Frequency, and Monetary value, also known as RFM analysis, and then apply K-Means clustering to identify groups of customers with similar purchasing patterns.

## Tools and Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Tableau
- GitHub
- ChatGPT/OpenAI for documentation support, debugging discussion, and code review

## Dataset

The dataset contains online retail transaction records, including invoice numbers, customer IDs, product descriptions, quantities, invoice dates, unit prices, and country information.

## Data Preparation

Before analysis, the data was cleaned and prepared by:

- Removing canceled transactions
- Removing records with missing customer IDs
- Filtering invalid or negative prices
- Creating a total sales variable
- Aggregating customer-level purchasing behavior
- Calculating Recency, Frequency, and Monetary values
- Scaling features before clustering

## Methodology

RFM analysis was used to summarize customer behavior:

- Recency measures how recently a customer purchased
- Frequency measures how often a customer purchased
- Monetary measures how much a customer spent

K-Means clustering was then used to group customers with similar purchasing patterns. These clusters helped identify customer groups that could be used for targeted marketing and retention strategies.

## Key Results

The analysis identified distinct customer groups, including high-value customers, average customers, and customers at risk of churn. These segments can help a business prioritize outreach, personalize marketing campaigns, and improve customer retention.

## Business Recommendations

- Reward high-value customers with loyalty incentives
- Create targeted promotions for average customers to increase engagement
- Develop retention campaigns for at-risk customers
- Monitor customer behavior over time to identify changes in purchasing patterns
- Improve data quality practices so customer-level analysis remains reliable

## Skills Demonstrated

- Data cleaning
- Exploratory Data Analysis
- Feature engineering
- Customer segmentation
- RFM analysis
- K-Means clustering
- Data visualization
- Business analytics
- Technical documentation
- AI-assisted development with independent review and validation

## AI-Assisted Development Statement

This project was developed using standard data analysis tools and AI-assisted support for documentation, debugging discussion, and technical review. All data preparation, analysis, modeling decisions, interpretation, and business recommendations were independently reviewed and validated by the author.

## Future Improvements

Future improvements could include adding customer demographics, testing additional clustering methods, creating an automated ETL pipeline, and developing a predictive churn model based on customer segment behavior.

# PowerBI-Banking-Campaign-Analysis
An interactive Power BI dashboard analyzing telemarketing campaign data to identify key drivers of customer conversion for a term deposit subscription.

# Banking Telemarketing Campaign Analysis

## Project Objective
This project analyzes data from a Portuguese banking institution's direct telemarketing campaigns. The primary objective was to build an interactive Power BI dashboard to identify the key characteristics of customers who are most likely to subscribe to a term deposit, thereby providing actionable insights for future marketing strategies.

## Dashboard Screenshot

Banking Campaign Dashboard![image](https://github.com/user-attachments/assets/db9330d4-f8e7-4e04-a73a-ac7fffb55b1e)



## Key Findings & Recommendations

The analysis revealed several key factors that significantly influence campaign success:

* **Finding 1: Job Type is a Major Factor:** The analysis shows that customers who are **students** and **retired** have the highest conversion rates, making them prime targets for future campaigns.

* **Finding 2: Call Duration Strongly Correlates with Success:** There is a direct positive relationship between the length of the phone call and the conversion rate. This indicates that call duration is a strong proxy for customer interest.

* **Finding 3: Previous Campaign Success is a Powerful Predictor:** Customers who have subscribed to a product in a past campaign are a highly receptive and valuable segment for re-engagement.

**Actionable Recommendations:**

1.  **Prioritize High-Value Segments:** Focus marketing efforts and budget on the segments most likely to convert: students, retired individuals, and those with a history of successful conversions.

2.  **Optimize Call Center Strategy:** Use call duration as a key performance indicator for customer interest. Train agents to recognize engagement and nurture longer conversations.

3.  **Re-evaluate Low-Performing Segments:** Re-evaluate or reduce telemarketing efforts towards segments with consistently low conversion rates (e.g., 'blue-collar'), reallocating that budget to more effective channels or more promising customer segments.

## Data Source
The analysis was performed on the "Banking Dataset - Marketing Targets" from Kaggle, specifically the `train.csv` file. This dataset is based on real-world telemarketing campaigns.

[Banking Dataset - Marketing Targets on Kaggle](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)

## Tools Used
* **Power BI Desktop:** Utilized for data import, transformation (Power Query), data modeling, creating calculated measures (DAX), and building all dashboard visualizations.
* **DAX (Data Analysis Expressions):** Implemented to create core metrics:
    * `Total Contacts`
    * `Successful Conversions`
    * `Conversion Rate`
* **Grouping/Binning:** The `duration` feature was binned within Power BI to effectively analyze its impact on conversion rates.
* **(Python/Jupyter Notebook):** Used for initial data exploration and to verify data structure before importing into Power BI. *(This is optional to include but shows more of your process).*

## Skills Demonstrated
* Data Analysis & Visualization (Power BI)
* DAX for KPI Creation
* Data Modeling & Transformation (Power Query)
* Dashboard Design for Actionable Insights
* Marketing Campaign Effectiveness Analysis
* Deriving Business Recommendations from Data

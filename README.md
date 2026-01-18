
Supply Chain Performance Analysis: SCM Practices & Technology Integration
This repository contains the analytical workflow for identifying the best Supply Chain Management (SCM) methodologies and technology combinations to optimize Lead Time and Customer Satisfaction across various industries.


📌 Project Overview
The study analyzes data from 774 unique companies  to determine how different strategic choices impact operational performance. A key focus is placed on the synergy between advanced technologies (AI, Robotics, Blockchain) and established SCM practices like JIT, Agile, and Lean.



🛠 Methodology (Python & Power BI)
The project follows a rigorous data science workflow to ensure integrity and reproducibility:

1. Data Cleaning & Preprocessing (vis.ipynb)
The Jupyter Notebook included in this repo handles the technical preparation of the dataset:


Handling Unrealistic Values: Columns such as 'Supplier Count' and 'Environmental Impact Score' were excluded due to data quality issues.


Data Transformation: Fixed data types for financial columns (COGS) and standardized the "Technology Utilized" strings to prevent misclassification.


Outlier Management: Identified and addressed outliers in inventory turnover and revenue growth rates.


2. Data Enrichment & Verification

AI-Assisted Labeling: ChatGPT was utilized to categorize companies by industry and country.


Quality Assurance: To ensure data integrity, AI-generated labels were cross-referenced and verified against industry reports and LinkedIn profiles for a 10% sample of the data.

🚀 Key Insights

Lead Time Reduction: The integration of AI, Robotics, and Blockchain resulted in the most significant performance boost, reducing average lead times to 2.33 days.

Sector-Specific Excellence:


Tech & Software: Just-in-Time (JIT) emerged as the most effective practice, reaching a satisfaction score of 91.67.


Agri & Chemicals: Efficient Consumer Response (ECR) proved superior, significantly outperforming the general average.


Automotive: Cross-Docking provided the highest customer satisfaction.

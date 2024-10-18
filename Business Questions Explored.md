# Movie Industry Profitability and Market Trends Analysis

## Overview
This project analyzes a dataset of 6,820 movies released between 1986 and 2016, sourced from Kaggle, to extract actionable insights for the entertainment industry. The dataset includes key information such as movie budgets, gross revenues, production companies, countries, genres, IMDb scores, and more. The primary goal is to uncover trends and provide insights into profitability and market preferences in movie production.

## Problem Statement
In a rapidly evolving entertainment landscape, understanding profitability drivers and audience preferences is crucial for industry stakeholders. This analysis aims to explore key factors influencing movie success, including budget allocations, market preferences by genre, and geographic trends in movie production.

## Key Questions Explored
1. **What is the average runtime of movies across all films in the US??**
   - **Objective:** Determine the average length of movies.
   - **Business Insight:** Align movie runtimes with audience expectations and optimize scheduling for theaters.
  
   <img width="337" alt="image" src="https://github.com/user-attachments/assets/b37c674c-4064-4d46-a275-a2af81df35bb">


2. **Do higher budgets lead to increased revenues?**
   - **Objective:** Investigate the relationship between production budgets and box office revenues.
   - **Business Insight:** Inform budget allocation strategies by identifying if larger budgets typically result in higher revenues.

   

3. **Which year had the highest average movie rating?**
   - **Objective:** Identify the year with the highest average movie rating.
   - **Business Insight:** Understand historical peaks in film quality to predict shifts in industry standards and audience preferences.

   <img width="469" alt="image" src="https://github.com/user-attachments/assets/384eab41-a708-4de9-96bc-6c9a7f2869fd">


4. **What is the average gross revenue of films by each rating category?**
   - **Objective:** Determine the financial performance of films in different rating categories (e.g., PG, R).
   - **Business Insight:** Help target specific audience segments by analyzing the most commercially successful rating categories.

   <img width="241" alt="image" src="https://github.com/user-attachments/assets/db0152e6-1798-4a50-9d62-ddccf84ab29b">


5. **Which director has worked with the most actors?**
   - **Objective:** Identify directors who have collaborated with the most unique actors.
   - **Business Insight:** Highlight versatile and influential directors for strategic casting and production planning.

   <img width="318" alt="image" src="https://github.com/user-attachments/assets/5b23a553-26a6-4f10-a2ce-b595977de9b9">


6. **How many movies did each company produce in each country?**
   - **Objective:** Analyze movie production volumes by country for each company.
   - **Business Insight:** Assist in understanding geographic production trends and guiding market expansion strategies.
   - <img width="249" alt="image" src="https://github.com/user-attachments/assets/9a4c9333-d001-4fc2-aae9-3e23ffbda359">


7. **What are the top 5 most profitable genres in terms of average gross minus average budget?**
   - **Objective:** Identify the most financially successful movie genres.
   - **Business Insight:** Guide production companies in making investment decisions based on genre profitability.
   <img width="202" alt="image" src="https://github.com/user-attachments/assets/42e25cd6-2f4a-42e9-ac00-8fb7afae3bbe">


8. **Is there a correlation between a movie’s budget and its score?**
   - **Objective:** Explore the relationship between a movie's budget and its IMDb score.
   - **Business Insight:** Provide insights into how budget impacts perceived movie quality.

   

## Challenges and Solutions
Several challenges were encountered during data import and preparation:
1. **Formatting and Data Type Mismatches**:
   - **Solution:** Used MySQL functions like `STR_TO_DATE()` to handle inconsistent date formats and adjusted data types (e.g., changing `INT` to `BIGINT`) to accommodate large numeric values.
2. **Local File Loading Restrictions**:
   - **Solution:** Enabled the `local_infile` setting and used `secure_file_priv` to allow local file uploads.
3. **Inconsistent Name Formatting**:
   - **Solution:** Applied SQL string functions to split names into first and last names, handling variations like middle initials.
4. **File Access Errors**:
   - **Solution:** Converted CSV files to SQL using an online tool, allowing for direct import into MySQL.

## Conclusion
This project provides valuable insights into the factors that drive movie profitability and market success. By understanding the relationships between budget, revenue, genre, and audience preferences, production companies can make data-driven decisions to enhance their strategic planning, resource allocation, and market expansion efforts.

---

### Dataset
The dataset for this analysis was sourced from [Kaggle](https://www.kaggle.com).

---

### Author
**Gustavo Quintero**  
Data Management  
UC Davis MBA/MSBA 2024  

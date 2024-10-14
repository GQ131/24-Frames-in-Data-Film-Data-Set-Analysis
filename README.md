# 24-Frames-in-Data

## Case Study: Movie Industry Profitability and Consumer Preference Analysis

### Purpose:

The purpose of this project was to analyze a dataset of 6,820 movies released between 1986 and 2016, sourced from Kaggle, to extract actionable insights regarding profitability and market preferences in the entertainment industry. The dataset contained a range of information including budget, gross revenue, production company, country, genre, IMDb score, and more.

### Benefit:
The analysis provided insights into the correlation between movie budgets and gross revenue, as well as shifts in audience preferences across genres and ratings over three decades. By structuring the data into a normalized relational database, querying was optimized for efficiency, making the process of data retrieval and updates seamless and effective for generating business insights.

### Impact:
This study delivered valuable findings for stakeholders in the entertainment industry, including production companies, distributors, and marketers. Specifically, it helped identify financial patterns linked to budget sizes and revenue outcomes, as well as evolving trends in consumer preferences regarding movie genres and ratings.
Project Background:

To begin the analysis, I worked with a comprehensive dataset that incorporated 15 key attributes for each movie. The attributes spanned financial, production, and audience-related factors, which allowed for an in-depth analysis of the industry from multiple perspectives. The dataset’s attributes included:

- Budget
- Gross revenue
- Production company
- Country of origin
- Director
- Genre
- Rating (e.g., R, PG)
- Release date
- IMDb score
- Number of votes
- Main actor/actress
- Writer
- Runtime
- Year of release

Given the complexity of the dataset, I transformed the original single file into a structured database with eight distinct but interconnected tables. These were:

- **Movies:** Central table containing core details of each movie.
- **Companies:** Data about production companies involved in each film.
- **Countries:** Information on the countries where films originated.
- **Directors:** Details on directors linked to each movie.
- **Genres:** Genres associated with each film.
- **Actors:** Cataloging the main actor or actress featured.
- **Ratings:** Classifying movies by rating type (R, PG, etc.).
- **Writers:** Documenting the writers credited for each film.

These specialized tables were linked to the central Movies table using foreign keys, which allowed for robust relational database capabilities. For example, the company_id field in the Movies table was linked to the company_id in the Companies table, which facilitated efficient querying on production companies and their financial performance.

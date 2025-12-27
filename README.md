# Exploratory-Data-Analysis-EDA-Movies-Dataset-Python-
This project involves individual, end-to-end exploratory data analysis (EDA) on a comprehensive movies dataset covering films released between 1916 and 2016. The objective is to extract data-driven insights related to movie profitability, ratings, genres, directors, actors, and audience engagement using Python.
The project demonstrates practical application of Python, Pandas, NumPy, and structured EDA techniques to explore large datasets, clean raw data, engineer features, and generate insights suitable for business and analytical decision-making.

**Business & Analytical Problem**

The entertainment industry generates large volumes of historical data, but extracting meaningful insights requires systematic data analysis. The key analytical questions addressed in this project include:

Which movies are the most profitable, considering both budget and gross revenue?

Which genres and genre combinations consistently generate higher revenue?

Which directors deliver strong average IMDb ratings?

How do audience preferences compare with critic reviews?

Which actors show high engagement across both critic and user metrics?

Which non-English movies feature among top IMDb-rated films?

**Objectives**

Perform structured data inspection and validation.

Clean and preprocess raw movie data by handling:

A) Missing values.

B) Irrelevant columns.

C) Duplicate records.

D) Retain a statistically significant portion of data (~75%) post-cleaning.

E) Engineer new analytical features such as Profit.

F) Conduct profitability, rating, genre, director, and actor-based analysis.

G) Generate interpretable insights using aggregation and filtering techniques.

**Dataset Overview**

Time period: 1916–2016

Records: ~5,000 movies

Data format: CSV / Excel

**Key variables:**

**Financial:** Budget, Gross, Profit

**Ratings:** IMDb Score, Number of Votes

**Content:** Genres, Language, Year

**Talent:** Director Name, Lead Actor

**Engagement:** Critic Reviews, User Reviews

**Tools & Technologies (ATS Keywords)**

Python.

Pandas.

NumPy.

Jupyter Notebook.

Data Cleaning.

Data Preprocessing.

**Exploratory Data Analysis (EDA)**

Feature Engineering.

GroupBy & Aggregation.

Data Validation.

Business Analytics.

**Analytical Methodology**
**Data Preparation & Cleaning**

Inspected dataset structure, schema, and data types.

Calculated column-wise and row-wise missing value percentages.

Dropped non-essential columns based on analytical relevance.

Removed rows with excessive missing values while maintaining data integrity.

Handled missing categorical values using domain assumptions.
.
Identified and removed duplicate records

**Feature Engineering**

Converted financial metrics into standardized units (Million USD).

Created a Profit metric (Gross − Budget) to enable profitability analysis.

**Data Analysis Performed**

Top 10 most profitable movies analysis.

IMDb Top 250 extraction with minimum vote threshold.

Identification of top-rated non-English movies.

Director-wise performance analysis using average IMDb ratings.

Genre and genre-combination profitability analysis

Actor-wise comparison of critic and audience preferences.

**Key Insights**

High production budgets do not guarantee higher profitability.

Certain genre combinations (e.g., Family + Sci-Fi) generate significantly higher average revenue.

Several non-English films rank among the IMDb Top 250, indicating strong global appeal.

Some directors demonstrate consistent high IMDb ratings across multiple films.

**Leonardo DiCaprio** ranks highest across both critic and audience engagement metrics.

**Business Recommendations**

Evaluate projects using profit-based metrics, not revenue alone

Prioritize genre combinations with historically strong financial performance.

Apply vote-count thresholds to ensure reliable rating analysis.

Incorporate director and actor performance trends into decision-making.

Use audience–critic alignment to assess market reception risk.

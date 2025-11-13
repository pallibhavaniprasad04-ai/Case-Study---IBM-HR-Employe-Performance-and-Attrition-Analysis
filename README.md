# Case-Study---IBM-HR-Employe-Performance-and-Attrition-Analysis
🎬 Movie Dataset Analysis – Python Project
📌 Project Overview
This project focuses on analyzing a movie dataset to uncover insights related to movie characteristics, genres, ratings, revenues, and trends over time. The analysis incorporates data cleaning, univariate/bivariate/multivariate analysis, and visualization to understand relationships among variables such as budget, revenue, runtime, votes, ratings, and genres.

The goal is to apply Python data analysis techniques and generate insights into what makes a movie successful, how trends have evolved over time, and how genres perform across different metrics.

🛠️ Tech Stack & Libraries
The following libraries are used in this project:

pandas → For data loading, cleaning, and manipulation

numpy → For numerical operations and summary statistics

matplotlib & seaborn → For data visualization (histograms, scatter plots, bar charts, heatmaps, etc.)

scipy → For correlation and statistical analysis

datetime → For handling release dates and trends over time

📂 Project Tasks & Key Questions
1. Project Setup and Data Loading
✔ Load dataset into pandas DataFrame. ✔ Identify dataset shape (rows = movies, columns = attributes).

Key Questions:

What libraries are required, and why?

What is the dataset shape and meaning of rows/columns?

2. Data Overview and Basic Exploration
✔ Used .info() to check data types & missing values. ✔ Used .describe() for statistical summary.

Key Questions:
What issues exist in data types/missing values?

What do mean, median, and distribution tell us?

3. Data Cleaning
✔ Handled missing values appropriately. ✔ Converted columns like release dates, ratings into correct formats. ✔ Detected and treated outliers in budget/revenue.

Key Questions:
Which columns have missing values?

Which columns need type conversion and why?

4. Univariate Analysis
✔ Explored runtime distribution with histograms. ✔ Checked most frequent genres with bar plots.

Key Questions:
What is the distribution of runtimes?

What are the most common genres?

5. Bivariate Analysis
✔ Scatter plots to check runtime vs rating. ✔ Boxplots to compare ratings across genres. ✔ Correlation analysis between votes, budget, and revenue.

Key Questions:
Relationship between runtime & rating?

Do ratings vary by genre?

Is there correlation between votes, budget, and revenue?

6. Genre-Specific Analysis
✔ Average rating calculated per genre. ✔ Trend analysis of genre popularity over time.

Key Questions:
Which genre has the highest average rating?

How does genre popularity vary over time?

7. Year & Trend Analysis
✔ Plotted ratings over the years. ✔ Plotted number of movie releases per year.

Key Questions:
How has average rating changed over the years?

Which years had highest & lowest movie releases?

8. Multivariate Analysis
✔ Genre popularity by decade. ✔ Heatmaps/pairplots of budget, revenue, and scores. ✔ Grouped by genre & year for rating comparisons.

Key Questions:
Which genres dominate in each decade?

How do budget/revenue/scores relate?

Are certain genres/years linked to higher ratings?

📊 Insights & Findings
Runtimes → Most movies cluster around 90–120 minutes.

Genres → Drama and Comedy dominate in frequency, but Action/Adventure contribute more revenue.

Ratings → Documentaries and niche genres often receive higher ratings despite fewer releases.

Revenue & Budget → Strong correlation between budget and revenue, but outliers exist (low-budget hits, high-budget flops).

Trends → Movie releases peaked in the 2010s and surged post-2020 due to streaming platforms.

🔎 Insights and Summary
Drama’s Consistent Dominance → Drama has been the most released genre since the 1990s, reflecting its strong and enduring global appeal.

Genre Growth Post-2000 → After 2000, all major genres — especially Comedy, Thriller, and Action — saw a sharp rise in releases, driven by digital platforms and global distribution.

2023 Decline & 2022 Peak → 2022 marked the peak in genre releases, possibly due to a post-COVID backlog, followed by a noticeable dip in 2023, likely due to industry disruptions or incomplete data.

❓ Future Exploration
Additional questions to explore with this dataset:
Does release season (month or quarter) affect ratings or genre performance?

Do genres with more releases also tend to receive higher or lower average ratings?

How have niche genres (e.g., Sci-Fi, Documentary, Animation) evolved over time in terms of both popularity and ratings?

🚀 Future Improvements
Add ML models to predict movie success.

Explore NLP on reviews to connect sentiment with ratings.

Build interactive dashboards (Plotly/Power BI) for dynamic trend analysis.

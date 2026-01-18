Netflix Exploratory Data Analysis (EDA)
This project focuses on analyzing Netflix’s content library to understand its evolution, genre investments, and potential strategic risks in the current streaming market. This analysis was performed using Python and libraries like Pandas.

1. Project Overview
The dataset consisted of a comprehensive list of movies and TV shows available on Netflix, including details like:
- Show ID and Type (Movie vs. TV Show).
- Title, Cast, and Director.
- Country of Origin.
- Date Added to the platform and original Release Year.
- Rating (e.g., TV-MA, PG-13) and Duration.
- Listed In (Genre) and Description.

2. Data Cleaning Process
Before analysis, the dataset required significant cleaning to ensure accuracy:
- Handling Null Values: The director column was removed due to excessive missing data.
- Missing Labels: Empty cells in the cast and country columns were filled with the placeholder "Unknown".
- Standardization: Missing values in the rating column were filled using the most frequent rating (Mode).
- Date Conversion: The date_added column was converted from text to a proper datetime format to allow for year-over-year trend analysis.

3. Analysis Methodology
The analysis was conducted across 12 columns of data using Exploratory Data Analysis (EDA). We focused on:
- Volume Distribution: Measuring the ratio of movies to TV shows.
- Temporal Trends: Identifying when Netflix hit its peak for adding new content.
- Geographic Reach: Determining which countries produce the most content.
- Content Maturity: Evaluating the target audience through rating distributions.

4. Visualizations & Plots
To tell the story of the data, the following visualizations were created:
- Content Distribution: A pie chart showing that Movies dominate the library at 69.7% compared to 30.3% for TV Shows.
- Growth Trends: A line chart tracking the sharp rise and recent dip in content additions since 2019.
- Geographic Bar Chart: A comparison of content production across the Top 10 countries, led by the United States and India.
- Rating Analysis: A bar chart highlighting TV-MA as the most frequent rating on the platform.
- Genre Heatmap: A visual matrix showing shifting investments in genres like "International Movies" and "Dramas" over time.
- Content Age Density: A plot showing that the majority of Netflix's library consists of very recent releases.

5. Key Findings & Strategic Insights
- Strategic Risk: Netflix faces a risk due to its heavy reliance on "one-and-done" movies (69.7% of the library).
- Audience Limitation: The platform is heavily skewed toward mature audiences, with 3,205 TV-MA titles dwarfing family-friendly options like TV-G (220 titles).
- Investment Shift: Investment in top-tier genres like International Movies peaked in 2018 (668 titles) and has since declined, suggesting a shift in content acquisition strategy.

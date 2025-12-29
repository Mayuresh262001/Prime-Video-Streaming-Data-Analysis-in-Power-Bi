Amazon Prime Video Content Analysis Dashboard
📊 Project Overview
This project focuses on analyzing the vast content library of Amazon Prime Video. By processing a dataset of over 9,600 titles, the dashboard uncovers insights into the balance between movies and TV shows, the growth of content over the decades, and the geographical distribution of productions.

The goal is to provide a visual narrative of how Prime Video’s catalog has evolved and which genres dominate the platform.

🛠️ Technical Stack
Data Source: Amazon Prime Video Titles (CSV).

Analysis Tool: Power BI Desktop.

Data Transformation: Power Query (used for cleaning missing ratings, standardizing date formats, and splitting multi-value genre strings).

Modeling: Star Schema with a centralized fact table and dimensional lookups for dates and categories.

🔍 Key Performance Indicators (KPIs)
Total Titles: 9,668 (comprising both Movies and TV Shows).

Content Split: Insights into the ratio of Movies vs. TV Shows.

Release Timeline: Analysis of content growth from the early 1920s to 2021.

Rating Insights: Distribution of content maturity ratings (e.g., 13+, 18+, All).

📈 Dashboard Features
Content Distribution: A donut chart showing the percentage split between Movies and TV Shows.

Top Genres: A bar chart identifying the most popular genres (Drama, Comedy, Action).

Global Mapping: A map visualization highlighting the primary countries of origin for the content.

Yearly Trends: A line chart showing the surge in content additions over the last decade.

Detailed Search: A tabular view allowing users to filter and search for specific directors or actors.

💡 Key Business Insights
The "Movie" Giant: Unlike competitors who focus heavily on episodic TV, Amazon Prime maintains a massive volume of standalone movies.

Genre Dominance: Drama and Comedy consistently lead as the top-produced genres on the platform.

Production Hubs: While the US is the leader, there is a significant and growing footprint of content from India and Canada.

📂 Repository Structure
Prime Video Analysis.pbix: The complete Power BI dashboard file.

amazon_prime_titles.csv: The raw dataset used for the project.

Screenshots/: Visual previews of the dashboard pages.

🚀 How to Use
Clone this repository.

Open Prime Video Analysis.pbix in Power BI Desktop.

Use the Type (Movie/TV Show) and Rating slicers to filter the data.

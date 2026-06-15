# Netflix Content Dashboard — Power BI



## Introduction



This dashboard was created to explore and analyze the Netflix content library using a real-world dataset. This project allowed me to work through the full data analytics routine: from cleaning raw messy data to building interactive dashboard.


## Skills Showcased



-   Data Transformation (ETL) with Power Query: Cleaned raw CSV data by trimming whitespace from multi-value columns, handling nulls in country and date fields, extracting year and month from text-based date columns, and splitting the genre column into separate rows to enable accurate counting.

-   Data Modeling: Built a junction table "netflix\_genres" to handle the many-to-many relationship between titles and genres, connected it to the main table via show\_id, and configured bidirectional cross-filtering to enable genre-based filtering across the whole dashboard.

-   DAX Measures: Written measures for Most Common Age Rating, Average Movie Duration, and Average TV Show Duration.

-   Core Charts: Used Bar, Area, Treemap, Pie, and Line charts to answer specific analytical questions rather than just display data.

-   KPI Cards: Displayed key metrics: Total Movies, Total TV Shows, Most Common Rating, Avg Movie Duration, and Avg TV Show Seasons.

-   Dashboard Design: Designed a single-page dark-theme dashboard inspired by Netflix's own color panel and rounded card borders



## Interactive Reporting:



-   Slicers: Movie / TV Show toggle and Year dropdown to dynamically filter all visuals at once.

-   Cross-filtering: Clicking any visual — including the treemap and bar chart — filters the entire page.

-   Sync Slicers: Type and Year slicers affect all visuals simultaneously.



## Dashboard Overview

Single Page Dashboard

<img width="1292" height="717" alt="Netflix Dashboard" src="https://github.com/user-attachments/assets/894f360b-926c-4a71-b726-40772533ff6d" />

The dashboard answers six core questions at a glance:

-   How big is the library? — KPI cards show 6,127 Movies and 2,676 TV Shows.

-   What are the most popular genres? — Top 10 genres bar chart, led by International Movies at 3,000+ titles.

-   Where does content come from? — Country treemap showing the US dominates but India is the fastest growing.

-   How has the library grown? — Yearly area chart showing explosive growth from 2016 to 2019 followed by a decline post-2020.

-   Is there a seasonal pattern? — Monthly line chart revealing July and December as peak content addition months. Almost steady line between July and December shows that the most amount of content is being released during the summer, autumn and winter holiday periods.

-   Who is the target audience? — Age rating pie chart showing TV-MA at 36.45% and TV-14 at 24.55%, meaning over 60% of content targets adult audiences.



## Key Findings



-   Netflix added the most content in 2019 which is over 1,400 movies in a single year before scaling back significantly post-2020.

-   International Movies is the single largest genre category, reflecting Netflix's aggressive global expansion strategy.

-   Over 60% of all content carries an adult rating (TV-MA or TV-14), despite Netflix being known as a family platform.

-   The average movie on Netflix runs 100 minutes and the average TV show lasts 1.76 seasons suggesting that Netflix cancels most shows early.

-   Content additions peak in July and December, likely tied to summer and holiday periods.



## Conclusion

This project demonstrates my ability to explore, clean, and visualize data in a way that uncovers meaningful insights and trends. It's perfect for anyone interested in content strategy, viewer preferences, or general data storytelling about how one of the world's largest streaming platforms has built and shaped its content library over 15 years.


# Amazon Prime PowerBI Dashboard

![Screenshot 2024-09-24 221340](https://github.com/user-attachments/assets/0db07034-ee17-4208-8d1d-0c01dadb5462)

## Problem Statement

Amazon Prime Video offers a vast and diverse library of shows and movies, but there is a need for a centralized, data-driven approach to understand content performance and distribution. The challenge lies in analyzing the ratings of all shows to identify which content resonates most with viewers, determining areas for improvement in lower-rated shows. Additionally, there is a need to assess the distribution of shows across genres to better understand audience preferences and content variety.

Geographic distribution is another area of focus, as tracking the total show count available in each country can reveal regional gaps and opportunities for expansion. Furthermore, understanding the contribution share between movies and TV shows is critical for shaping content investment strategies. Finally, visualizing the total shows by release year will help uncover trends in content production and identify key periods of growth.

By addressing these areas, the dashboard will provide Amazon Prime with actionable insights for optimizing content strategy, enhancing user engagement, and identifying future growth opportunities.


### Steps followed 

- Convert CSV to Dataframe: Imported the CSV files containing show data into a Pandas DataFrame for easier manipulation and analysis.

- Handling Missing Values: Identified and filled or removed missing values in critical columns such as genre, release year, and country to ensure data completeness and accuracy.

- Removing Duplicates: Detected and removed duplicate records from the dataset to avoid skewed results and ensure data integrity.

- Data Type Conversion: Converted data types, such as ensuring release year and numeric columns (like ratings) were in the correct format for analysis in Power BI.

- Data Cleaning: Standardized inconsistent text formats (e.g., genre and country names) and ensured uniformity across the dataset.
           
- Refine genre data by consolidating subgenres, analyze genre-rating correlation to identify popular genres, and focus on underrepresented genres to enhance content diversity.

- Segment data by country and region, compare show count with engagement metrics, and prioritize adding content in regions with fewer offerings to boost market engagement.

- Segment between original and licensed content, correlate viewership with content type (movies vs. TV shows), and balance content strategies based on format preference by region.

- Cross-analyze release year trends with ratings and engagement, compare annual show additions with subscription growth, and adjust production/release strategies based on audience demand trends.


# Key insights

- Evaluated the ratings of over 1,200 shows, identifying that 70% received ratings above 7/10,highlighting viewer preferences for high-quality content. 
  
- Analyzed a total of 150 genres, revealing that Drama and Comedy accounted for 40% of all available shows, indicating strong viewer engagement in these categories. 
 
- Compiled show counts across 10 countries, with the USA leading with 253+ shows, while countries like India with 229+ shows, showcasing regional content distribution. 

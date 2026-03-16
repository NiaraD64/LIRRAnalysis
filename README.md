# LIRR Major Incidents Analysis from 2020 - 2025
This personal project analyzes five years of Long Island Railroad (LIRR) operational data to identify trends in delays, cancellations, and service disruptions. 
The goal is to extract actionable insights and highlight patterns that could support operational decision-making.

# Tools Used 
-Python (Pandas, Matplotlib, Seaborn)

# Key Task
-Conducted descriptive statistics and exploratory data analysis
-Performed aggregations to summarize service performance with peak and off peak trains
-Created visualizations to highlight trends and patterns
-Drew insights to inform potential operational improvements

# The Process
I started by importing the necessary tools for analysis in Jupyter Notebook. The dataset was pre-cleaned before import, but I double-checked for duplicates to ensure accuracy. Outliers were retained as they represent real operational data, not errors.

Analysis 1: Examined weather-related cancellations (tropical storms and snow storms) for AM peak, PM peak, and off-peak trains. Descriptive statistics were used to summarize the results, and a boxplot was created to visualize the five-number summary and highlight outliers.

Analysis 2: Calculated the mean number of late trains caused by trespassers for AM peak, PM peak, and off-peak periods. A horizontal bar chart was used to visually compare the means across time periods.

Analysis 3: Compared total cancelled and terminated trains during peak hours from 2020–2025. A grouped bar chart was used to illustrate the totals for AM and PM peak trains.

Analysis 4: Determined the maximum number of late trains per month in 2024 for AM peak, PM peak, and off-peak periods. A line graph was created to visualize monthly trends.

# What I Learned
Analysis 1: The boxplots show that off-peak trains had the highest number of cancellations, while AM and PM peak cancellations were relatively low but had outliers. This suggests that off-peak operations may need additional attention.

Analysis 2: The horizontal bar chart shows that off-peak trains experience the most delays due to trespassers.

Analysis 3: The grouped bar chart shows AM and PM peak trains are more likely to be cancelled than terminated, meaning trains often stop mid-route rather than failing to depart. Many factors contribute to cancellations, including operational constraints and staffing.

Analysis 4: The line chart shows that AM peak trains experienced a significant increase in lateness in December 2024, likely due to weather-related conditions.

# Course of Action
Recommendation 1: MTA should consider strategies to reduce off-peak cancellations (prepare for bad weather), as they impact many passengers and could improve overall service reliability.

<img width="897" height="663" alt="Image" src="https://github.com/user-attachments/assets/58b43434-17dc-42ea-bb9f-957ac54f4b6e" />

Recommendation 2: MTA should increase security checks during off-peak hours to ensure passengers have valid tickets, helping reduce intentional delays and improve overall punctuality.

<img width="805" height="565" alt="Image" src="https://github.com/user-attachments/assets/4766e78b-4a50-4582-b940-c6a1e3c2c205" />

Recommendation 3: MTA should consider hiring more conductors or expanding track capacity to reduce cancellations during peak hours, ensuring more trains can complete their routes even if delays occur on one track.

<img width="882" height="572" alt="Image" src="https://github.com/user-attachments/assets/5a2f2507-7d4e-4422-88ae-8b6c18f54bb2" />

Recommendation 4: MTA should prepare in advance for potential weather-related disruptions during AM peak hours, such as adjusting staffing or operational plans, to reduce delays and improve service during rush hour.

<img width="1040" height="613" alt="Image" src="https://github.com/user-attachments/assets/05787bcd-fc79-4fdb-beae-32394b746c40" />

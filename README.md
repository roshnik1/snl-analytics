# SNL Cast Tenure & Gender Dynamics: A Data-Driven Exploration of Longevity and Representation

## Overview

This project delves into the tenure of cast members on Saturday Night Live (SNL), with a special focus on analyzing cast dynamics over the years. The analysis includes examining cast tenure trends, identifying key patterns, and exploring how gender influences cast turnover and representation on the show. Using the Saturday Night Live dataset from Kaggle, alongside Python and Tableau, this project provides visualizations and insights into cast longevity and gender diversity throughout SNL's history. By understanding the tenure and gender breakdown of the cast, the project aims to highlight shifts in representation and how these trends may correlate with other factors, such as the show's popularity.

## Initial Questions

- Which cast members have had the longest and shortest tenures on SNL?  
- Are there any notable trends in cast turnover over time?  
- How does a cast member's tenure influence the show's popularity or ratings?  
- What are the gender dynamics of cast turnover across different decades?  
- Have gender representation trends improved over time on the show?  
- What patterns emerge when comparing tenure and gender by decade or SNL season?  

## Data

All datasets used in this project were sourced from the SNL Dataset available on Kaggle. The raw data files were downloaded as CSVs and processed to remove any unnecessary formatting. These CSV files were then uploaded to GitHub for easy access and loading into the analysis environment. Upon loading, each dataset underwent a thorough cleaning process, including handling missing values and standardizing column names. Only relevant data points were retained for analysis to ensure clarity and focus on key insights.

## Findings

Through the analysis of Saturday Night Live (SNL) cast tenure data, several key insights were uncovered:

### Longest and Shortest Tenures:
- Kenan Thompson holds the record for the longest tenure in SNL history, spanning over 20 seasons, while many cast members, especially those from earlier seasons, had relatively short stints, often lasting only one season.  
- The show has seen higher turnover in the early seasons, with cast members staying longer in recent decades.
  <img src="https://github.com/roshnik1/SNL-Analytics/blob/main/images/Cast%20Tenure%20Dashboard.png" alt="Dashboard" width="900" height="400"/>

### Trends in Cast Turnover:
- There are clear patterns of cast turnover that align with the start of new decades or when new producers, such as Lorne Michaels, took charge. Significant cast shake-ups often coincide with creative shifts on the show.  
- Certain periods in SNL’s history, such as the mid-1990s and early 2000s, saw a more stable cast with fewer exits, likely contributing to the show's continuity and creative consistency during those eras.
  <img src="https://github.com/roshnik1/SNL-Analytics/blob/main/images/turnover_rate.png" alt="Dashboard" width="700" height="400"/>

### Gender Representation Over Time:
- Gender representation on SNL has shifted significantly over time. In the early years, the cast was predominantly male, with fewer female cast members staying for multiple seasons.  
- However, starting in the 1990s and particularly in the 2000s, the gender gap began to close. Notable female cast members like Tina Fey, Amy Poehler, and Kate McKinnon have had long and impactful tenures, signaling an improvement in female representation on the show.  
- Despite these improvements, the data reveals that male cast members, on average, still tend to have longer tenures compared to their female counterparts.  
  <img src="https://github.com/roshnik1/SNL-Analytics/blob/main/images/gender_analytics.png" alt="Dashboard" width="800" height="400"/>

### Shifts in Gender Dynamics:
- There is a clear upward trend in gender diversity, with the cast becoming more balanced in recent seasons. This shift aligns with broader societal pushes for more representation and diversity in media.
- However, there remains room for improvement, particularly in ensuring equal opportunities for long-term cast tenures across genders.

### Key Cast Trends and Notable Departures in Season 46 (2020-2021)
- Beck Bennett had the highest number of appearances during Season 46, making him one of the standout cast members for the season.  
- Despite his prominent presence throughout the season, Beck Bennett left the show at the end of Season 46, marking the end of an eight-season tenure on SNL.  
- Kenan Thompson and Kate McKinnon also had strong showings, continuing their roles as long-standing cast members with significant appearances.  
- Newer cast members like Bowen Yang and Chloe Fineman had a notable rise in screen time, reflecting their growing prominence on the show.  
- Ego Nwodim also saw increased appearances, indicating a larger role compared to earlier seasons.
- Overall, the data highlights a mix of veteran cast members dominating screen time, while newer cast members gained more visibility, signaling potential future shifts in the cast lineup.  
  <img src="https://github.com/roshnik1/SNL-Analytics/blob/main/images/season_46_summary.png" alt="Dashboard" width="650" height="400"/>
>**Note:** You can explore cast trends for other seasons by running the `season_summary.ipynb` file. Simply adjust the season variable to analyze different seasons and generate corresponding visualizations. The analysis seasons 44 and 45 is provided in the code for a reference.

## Conclusion
Overall, this analysis highlights the evolving nature of SNL’s cast in terms of tenure and gender representation. While certain long-tenured cast members have been pivotal to the show's success, the increasing representation of women in more recent decades suggests positive progress towards gender diversity. Further research could explore other factors like race, age, or background in shaping cast dynamics.

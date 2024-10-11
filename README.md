![video_game](https://github.com/user-attachments/assets/72a86871-373c-45be-92c5-390a84c0cc31)


# Video Game Analysis: Exploring the Golden Age of Gaming

## Project Overview
Video games are a massive industry, with the global gaming market projected to exceed **$300 billion by 2027**. With so much at stake, game publishers are continuously striving to create the next big hit. But have video games improved over time, or has the golden age of gaming already passed?

In this project, I analyzed video game critic and user scores, as well as sales data for the top 400 video games released since 1977. The goal was to identify the best-selling games, determine the top 10 years according to critics, and discover when the golden era of gaming occurred based on both critic and user feedback.

## Dataset Information
The analysis was conducted using several tables:
1. **game_sales**:
   - **name**: Name of the video game (varchar)
   - **platform**: Gaming platform (varchar)
   - **publisher**: Game publisher (varchar)
   - **developer**: Game developer (varchar)
   - **games_sold**: Number of copies sold (in millions) (float)
   - **year**: Release year (int)

2. **reviews**:
   - **name**: Name of the video game (varchar)
   - **critic_score**: Critic score according to Metacritic (float)
   - **user_score**: User score according to Metacritic (float)

3. **users_avg_year_rating**: Contains the average user scores and number of games released per year.
4. **critics_avg_year_rating**: Contains the average critic scores and number of games released per year.

## Key Insights

### 1. Best-Selling Games
The outcome of this query lists the top 10 best-selling games based on the number of copies sold:
- **Wii Sports** for the Wii is the best-selling game, with **82.9 million** copies sold (2006).
- Other top-selling games include **Super Mario Bros.**, **Counter-Strike: Global Offensive**, **Mario Kart Wii**, and **Minecraft**.

**Insight**: The data shows that Nintendo's Wii platform dominated sales with multiple entries in the top 10. **Wii Sports**, in particular, leads by a large margin. This suggests the platform’s popularity during its peak years, with many successful titles contributing to its dominance.

### 2. Top 10 Years According to Critics
The outcome of this query reveals the top years based on average critic scores:
- **1998** tops the list, with an average critic score of **9.32** for 10 games.
- Other highly regarded years include **2004**, **2002**, **1999**, and **2001**, all with average scores above **8.8**.

**Insight**: The late 1990s and early 2000s appear to have been strong years for critically acclaimed video games. **1998** stood out as a golden year for gaming, with an average critic score of 9.32, showcasing legendary titles that defined the era.

### 3. Golden Era of Gaming: Critics vs Users
This query compares critic and user scores to identify potential discrepancies and agreement on what constitutes the golden years of gaming:
- **1997** had a notable difference, where user scores (**9.5**) were much higher than critic scores (**7.93**), a **+1.57** difference.
- **1998** showed near agreement between critics and users, with only a **0.08** difference (critic score: **9.32**, user score: **9.4**).
- Some years, such as **2004**, saw users being slightly harsher than critics, with a **-0.48** difference.

**Insight**: 
- **1998** is likely the consensus golden year for gaming, as both critics and users rated games very highly with near-equal scores.
- The discrepancy in **1997** suggests that users may have appreciated games that critics were not as favorable towards, indicating potential differences in perception between critics and players.
- Overall, the early 2000s remain a strong period for video games, but users and critics occasionally differed in their ratings.

## Overall Conclusion
The analysis suggests that **1998** may indeed be considered the "golden age" of gaming, with critically and commercially successful games released that year. The **Wii platform**’s dominance in terms of sales is clear, with multiple top-selling titles, further emphasizing **Nintendo's** impact on the industry during key periods.

## Technologies Used
- PostgreSQL
- SQL
- Data Analysis

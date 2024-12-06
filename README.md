# Steam Games Popularity Analysis

## Team Members:  
- Lifu (Leaf) Li **(Team Leader)**
- Bei Su  
- Chenhui (Ryan) Shen 
- Wenxin (Freya) Liang 
- Zehui (Grace) Wang  

## **Report Summary**

This report provides an exploratory analysis of Steam games popularity using data from the Steamspy platform. It begins with a detailed overview of the data cleaning and merging process for three primary datasets: steamspy_data_2024, steamspy_data_2019, and steam_reviewer_rating.

We then utilized SQL to explore the dataset and define a "popularity" index for Steam games, based on key metrics such as number of owners, total reviews, concurrent users (CCU), and playtime, to assess each game's popularity level. This is followed by an in-depth analysis of the correlation between popularity and other features, including developers, publishers, genres, pricing, DLC quantity, and reviewer score. The analysis focuses on comparing similarities and differences between industry benchmarks and the performance of the top 1% most popular games.

Additionally, we compare data from 2019 and 2024 to evaluate the overall progress of the gaming industry. The report concludes with a summary of findings, challenges encountered, recommendations for future research, and references.

## **Key Finding**:

**Popularity Definition:** We use metrics like owners, reviewers, CCU, and playtime to measure game's popularity. "Popular games" are defined as the top 1%, in line with industry norms.

**Genres of Games:** Only 17 of 28 genres are in the top 1% of popular games, showing limited appeal for genres like Education. Action, Adventure, Indie, Free to Play, and RPG dominant the industry.

**Price:** Free games attract players but high-priced games yield better engagement. Games priced above $75 are absent from the popular list, indicating pricing as a barrier.

**DLC:** Moderate DLC quantity (5–35) drives higher popularity. Small DLCs are favored for enhancing without overwhelming, while very large DLCs face diminishing returns.

**Reputation of Games:** High-reputation games have strong engagement, though not always leading to high playtime. Medium-reputation games favor solo play, while low-reputation games perform well in multiplayer appeal.

**Stakeholders:** Only 1.2% of developers and 1.1% of publishers are responsible for top games, emphasizing the competitiveness. Companies with a "small but refined" strategy like Amazon Games succeed, while others struggle to maintain quality across many releases.

**Emerging Trends (2019 vs. 2024):** The player base grew from 3.63 billion to 5.23 billion, with increased engagement driven by lower prices and better satisfaction. Positive reviews grew significantly, reflecting higher player satisfaction.


## **Recommendations**:

To drive future growth, developers should focus on high-potential genres like Action, Adventure, and RPG, which show strong appeal and engagement potential. A "quality over quantity" strategy, as demonstrated by top developers like Valve, can lead to long-term success. Leveraging Free-to-Play models or offering free trials can help build an initial player base, which can then be monetized through DLCs or in-game purchases. A well-timed, moderate DLC strategy also helps maintain player interest without overwhelming them. Improving multiplayer experiences in community-driven games can boost satisfaction, making these titles more competitive. Consistent quality across all releases is key to sustaining relevance in the highly competitive gaming market.

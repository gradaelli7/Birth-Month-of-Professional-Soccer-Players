Welcome to my Repository for my analysis on professional soccer players!
I created two medium posts that go along with this project which can be found here:

What Impacts the Success of a Professional Soccer Player - https://medium.com/@giacorada/what-impacts-the-success-of-a-professional-soccer-player-14a2ab4f852a

The Fascinating Birth Trend Among Professional Soccer Players - https://medium.com/@giacorada/the-fascinating-birth-trend-among-professional-soccer-players-b2a48d015e7d

There are 10 total Jupyter Notebooks for this project:
1. Player_Birthdays.ipynb
This notebook contains the exploratory analysis on the birth trend of male professional soccer players.
All visualizations found in the respective Medium blog post can be found in this notebook.
Data was collected from FootballManager 2023 Kaggle dataset.

3. fbref_scrape.ipynb and fbref_scrape_gk.ipynb
Two scripts created to scrape in-game statistics on professional soccer players from Fbref.com.
Data from past five seasons was collected of players from 17 top professional soccer leagues around the world.

5. Male_Birth_Rates.ipynb
Notebook that created to process birth rate data from data.un.org. Since data.un.org did not have datasets for
monthly male birth rate, I utilized two datasets containing information on yearly sex ratio and monthly birth rate
to compute average monthly male birth rate. Computed average male monthly birth rate worldwide as well as for certain
specific countries: Italy, Spain, Brazil, Argentina, US, and UK.

6. Feature_Analysis notebooks (4 notebooks)
Each of these notebooks were created to perform separate machine learning algorithms, one for each position group in soccer:
Attackers, Midfielders, Defenders, and Goalkeepers. These models utilized player data that was prepared in Data_Preparation_Merging.ipynb.
Models created with the intention of defining a success function for specific player roles. Then, SHAP values were utilized to
investigate feature importance and determine most influential features for each player position.

7. Data_Preparation_Merging.ipynb
This notebook merged player information dataset from Players_Birthdays.ipynb with scraped data from fbref_scrape.ipynb to prepare data for ML analysis.

8. NCAA_bball_data.ipynb
Script created to scrape NCAA men's basketball birth data from RealGM. Used in order to compare birth distribution in NCAA basketball with US professional
soccer players. Analysis is explained in more detail in Medium blog post regarding birth trend in professional soccer players.



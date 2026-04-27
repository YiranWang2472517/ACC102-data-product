# ACC102-data-product
A Python-based analysis of how price, genre, and player reviews relate to the success of games on Steam.
# Factors Influencing the Success of Games on Steam
# 1. Problem & User
This project explores which factors (price, genre and player reviews) relate to Steam game success using review-based performance proxies. Findings support practical decision-making for indie developers, game publishers and industry investors.
# 2. Data
Source: Kaggle Steam Games Dataset  
URL: https://www.kaggle.com/datasets/artermiloff/steam-games-dataset  
Access date: 24 April 2026  
Key fields: name, price, genres, positive reviews, negative reviews.  
Full dataset is not included due to file size; users must download the CSV file manually.  
# 3. Methods
Performed data cleaning: removed duplicates, missing values, zero-review games and top 1% price outliers.  
Built feature engineering: created total review count, positive review ratio and four price-band categories.  
Simplified genre analysis by extracting the first listed main genre and filtering for top 12 frequent genres.  
Used median for skewed review count and mean for bounded positive ratio to ensure robust comparison.  
Produced histograms, bar charts and scatter plots to visualise relationships between variables.  
# 4. Key Findings
# 13. Key Findings
- Price has a clear association with typical game popularity and positive review rate.  
  High-priced games tend to have higher popularity and positive review rates, followed by mid-priced games.
- game genres also affect a game’s success, and catering to players’ preferences is very important.
- There is a moderate positive correlation between a game’s positive review rate and its review count. 
# 5. How to run
To reproduce the full analysis, you need the full dataset file `games_march2025_full.csv`.  
(1) Download `games_march2025_full.csv` from the original source: https://www.kaggle.com/datasets/artermiloff/steam-games-dataset  
(2) Place `games_march2025_full.csv` in the same working directory as `steam_games_success_analysis.ipynb`.  
(3) Open the notebook in Jupyter Notebook.  
(4) Run all cells from top to bottom.  
# 6. Demo
# 7. Limitations
- This approach simplifies multi-genre titles and brings limitations to the final results.  
- The analysis shows correlation, not causation.  
- Review-based metrics are proxies and do not directly represent revenue or profit. Meanwhile, external factors such as marketing are not taken into account.  
- Results reflect historical patterns and may not perfectly predict future performance. 

# Task
- Applying the knowledge that I have learned in 'Social Network Analysis' course (using API to explore data).
- Analyzing video data and verify the factors that makes a popular video in Youtube:
   - Does the number of likes and comments affect the number of views? 
   - Does the video duration affect the views and interactions?
   - Does the video length have an impact to the views and interactions?
   - Does title with the most popular words have more views and interactions?
   - Does the uploading time affect the number of views?
- Applying approriate types of charts to compare and form the concusions

# Methods
1. Collect video meta data via Youtube API for the top 10 channels in fitness  (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
2. Prepocess data and engineer additional features for analysis
3. Exploratory data analysis
4. Conclusions

# Result
- **There is a correlation between the number of views and the number of interactions** (likes and comments). 
- Most-viewed videos tend to have average title length of 30-70 characters. Titles with the most popular words such as **body, full, workout, hiit** tends to have more views than other types of title, except for two channels growingannanas and fitness_kaykay
- Most videos have between 20 and 40 tags. **There is no clear corelation between number of tags and number of views**.
- **Videos are usually uploaded on Mondays and Wednesday**. Friday and Saturday are not the popular time to post a new video.
- **Comments on videos are generally positive**, with many appreciation and compliment words.

# References
[1] Youtube API. Avaiable at (https://developers.google.com/youtube/v3)
[2] Exploratory Data Analysing Using Youtube Video Data from Most Popular Data Science Channels. (https://github.com/thu-vu92/youtube-api-analysis/blob/main/Sample_project_youtube_videos_EDA.ipynb)

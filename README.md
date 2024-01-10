# Task
- Applying the knowledge that I have learned in the 'Social Network Analysis' course (using API to explore data).
- Analyzing video data and verifying the factors that make a popular video on Youtube:
   - Does the number of likes and comments affect the number of views? 
   - Does the video duration affect the views and interactions?
   - Does the video length have an impact on the views and interactions?
   - Does the title with the most popular words have more views and interactions?
   - Does the uploading time affect the number of views?
- Applying appropriate types of charts to compare and form the conclusions

# Methods
1. Collect video metadata via Youtube API for the top 10 channels in fitness  (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
2. Prepocess data and engineer additional features for analysis
3. Exploratory data analysis
4. Conclusions

# Result
![image](https://github.com/han-nguyen97/youtubeapi/assets/83593831/7d34c197-bf35-43ea-9397-1907fdc0ff46) <br/>

- **There is a correlation between the number of views and the number of interactions** (likes and comments).
- **Short videos tend to get more interactions than long videos.**
- Most-viewed videos tend to have an average title length of 30-70 characters. **Titles with the most popular words such as **body, full, workout, hiit** tend to have more views than other types of titles**, except for two channels growingannanas and fitness_kaykay
- Most videos have between 20 and 40 tags. **There is no clear correlation between number of tags and number of views**.
- **Videos are usually uploaded on Mondays and Wednesdays**. Friday and Saturday are not the popular time to post a new video.
- **Comments on videos are generally positive**, with many appreciation and compliment words.

# References
[1] Youtube API. Available at (https://developers.google.com/youtube/v3) <br/>
[2] Exploratory Data Analysing Using Youtube Video Data from Most Popular Data Science Channels. (https://github.com/thu-vu92/youtube-api-analysis/blob/main/Sample_project_youtube_videos_EDA.ipynb)

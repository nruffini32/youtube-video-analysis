# Youtube Video Statistics Data Science Project
This project is an exploration of Youtube Statistics using Machine Learning. 

## About Dataset
This dataset contains two files with statistics on 1,881 YouTube videos and their comments.

### video-stats.csv
Title: Video Title
Video ID: The Video Identifier.
Published At: The date the video was published in YYYY-MM-DD.
Keyword: The keyword associated with the video.
Likes: The number of likes the video received. If this value is -1, the likes are not publicly visible.
Comments: The number of comments the video has. If this value is -1, the video creator has disabled comments.
Views: The number of views the video got.

### comments.csv:
Video ID: The Video Identifier.
Comment: The comment text.
Likes: The number of likes the comment received.
Sentiment: The sentiment of the comment. A value of 0 represents a negative sentiment, while values of 1 or 2 represent neutral and positive sentiments respectively.
## Purpose
The purpose of analyzing this dataset was to explore what makes a "good" video and see if we could predict whether a video performed well or poorly based on its video and comment statistics. A good video and a bad video were determined besed upon its like to view ratio (like_conversion_rate). We thought this would be the best way to determine the quality of the video because it does depend on viral status or high view count to determine the quality of the video. Before we began the project we knew we would have some limitations with the dataset and would need more metrics to fit an accurate model. For example, we knew that you can only like a video once where as you can watch the video multiple times. With that being said, another one of our goals was to be able to add features that are highly correlated to like_conversion_rate to the dataset that would help improve the overall accuracy of our model and assist in determining what is a good, nuetral, or bad video.

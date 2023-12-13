# FinalProject_EVPolicy_YouTube

This project delves into the analysis of public opinions regarding Electric Vehicle (EV) Policy by examining comments posted on YouTube.

## Data

- **video_data**: Contains information about videos related to EV policy, encompassing variables such as 'video_id,' 'channel_title,' 'channel_id,' 'video_publish_date,' 'video_title,' 'video_description,' 'video_category,' 'video_thumbnail,' and 'collection_date.'
  
- **comments_data_raw**: Encompasses comment data for each video, including variables like 'video_id,' 'commenter_channel_url,' 'commenter_channel_id,' 'commenter_channel_display_name,' 'comment_id,' 'comment_like_count,' 'comment_publish_date,' 'text,' 'commenter_rating,' 'comment_parent_id,' 'collection_date,' 'reply_count,' and 'sentiment.'

- **comments_data_clean**: Represents filtered data after removing entries where 'video_id' is NA and comments with a text length smaller than 100 characters.

## Code

The project code comprises five files:

- **01 and 02**: These files are used for data scraping and cleaning, containing credentials required to access an API.
  
- **03**: Involves the BertTopic model analysis.
  
- **04**: Concerns sentiment analysis.
  
- **05**: Includes tfidf analysis.

## Output

The project generates the following output:

- **3 tables** containing analyzed data.
  
- **8 figures** presenting various visualizations and insights derived from the data analysis.

## Docs

- **01_Project_Proposal**: Outlines the initial project proposal.
  
- **02_Project_Presentation**: Contains the project presentation.

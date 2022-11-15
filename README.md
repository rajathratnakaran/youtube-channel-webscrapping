# youtube-channel-webscrapping
YouTube Channel scrapping using YouTube API. Extract different snippets, statistics and content details.

This is a personal project done for handsown experience on webscrapping.
This project is done referring to Tech TFQ youtube channel video.
MKBHD, one of the most popular tech YouTube channnel is used for webscrapping in this project. 
You can download the dataset, MKBHD every videos till 14-11-2022 here https://www.kaggle.com/datasets/rajathratnakaran/mkbhd-dataset-1486-video-details.

In this project, the YouTube Channel details were scrapped using YouTube API.

This data extraction is done in 5 steps.

Step 1: Loading necessary libraries, generating API key and setting up the service.

Step 2: Extracting overall channel details. Extracted the playlistId, which is a key under which every video is listed for a channel in YouTube.

Step 3: Using the Playlist ID, extracted the Video ID of every video under the channel. Video Id is a unique key for each video. 

Step 4: Necessary details of every video is excrated individually and stored as a dictonary, which is then moved to become a dataframe.

Step 5: Download the dataframe to a csv. 

Thanks :)

# FF_youtube_metrics
Working with YouTube API to extract and transform data for one of my favourite youtube channels, Foresty Forest (FF)

## Version 1
- Creating and deploying the Youtube API.
- Extracting and transforming data. Fields include comment count, views, likes, dislikes and curation
- Created a function to change the format of the duration field from PTHMS (default) to H:i:s format, used REGEX in some parts for this.  
- Loading and organizing the extracted data into a pandas data frame


## Version 2
- Updated the code to get data for more than one channel
- Creating a library of channel IDs to host multiple channel IDs
- Implementing a for loop to run through all channel IDs in the channel ID library 
- The dataframe can be exported to CSV

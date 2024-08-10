# Youtube Data Scraping and Analysis

## Introduction

This project is designed to scrape data from YouTube channels using the YouTube Data API, load it into a Pandas DataFrame for analysis, and create visualizations using the Seaborn library. The aim is to provide insights into the performance of specific YouTube channels, such as Bhajan Marg, Bagheshwar Dham, Pradeep Mishra, and Aniruddhacharya Ji.

## Project Overview

 - Data Extraction: Using the YouTube Data API, I extract key metrics from channels like Bhajan 
   Marg, Bagheshwar Dham, Pradeep Mishra, and Aniruddhacharya Ji. This includes video titles, 
   views, likes, comments, and more.

 - Data Loading: The extracted data is loaded into a Pandas DataFrame for easy manipulation and 
   analysis.

 - Data Analysis: Using Pandas, I perform various data analysis tasks to gain insights into the 
   content and engagement of these channels.

 - Data Visualization: I utilize Seaborn to create visualizations that help in understanding 
   trends and patterns in the data from these channels.

## Features

- Youtube Data Extraction:
  
     - The project utilizes the **google-api-python-client** library to interact with the 
       YouTube Data API.
     - Then create a youtube service using channel IDs of channels "Bhajan Marg", 
       "Aniruddhacharya ji", "PradeepMishra", "BagheswarDham".
     - Then create a function to get the channel statistics of each channel.

       ![](channel_statistics_image.png)

- Data Handling and Conversion:

     - The extracted data is loaded into a Pandas DataFrame for easy manipulation and analysis.
       
       ![](channel_data_image.png)
       
     - Convert relevant columns to numeric types to facilitate accurate analysis and computations.
       
       ![](datatypes_image.png)

- Visualizations:

     - Created 3 bargraphs consisting of subscribers per channel, views per channel and total videos per channel.

         - subscribers per channel
           
            ![](subscribers_barplot.png)
           
         - views per channel
           
            ![](views_barplot.png)
           
         - total videos per channel
           
            ![](videos_image.png)

- Data retrieval and video ids extraction:
  
     - Using the loc method to get playlist ID of channel name "Bhajan Marg"

     - Create a function to get all videoIDs of "Bhajan Marg" using its playlistID.
 
     - retrieved all videoIDs of channel name "Bhajan Marg".

       ![](video_id_image.png)

- Video details extraction:

     - Retrieve detailed statistics for each video, including title, published date, views, likes, and comments.
       
     - Process video details in batches to handle large numbers of videos efficiently.

- Data Post-Processing and Translation:

     - Convert video details into a DataFrame and process date and numeric columns for accurate representation.

     - Retrieve and display the top 10 videos based on views, and translate video titles from Hindi to English.

       ![](top10_video_image.png)

- Monthly video and publication analysis:

     - Extracting the month from the published date of each video and aggregate the number of videos published per month.

       ![](video_permonth_image.png)

     - Using **Seaborn**, a bar plot was generated to visualize the distribution of video publications per month, highlighting trends in content release over time.

       ![](video_permonth_barplot.png)



 # TOOLS USED:

    - JupyterNotebook, Google API, Python, Pandas and Seaborn

  

                 

       
  
  

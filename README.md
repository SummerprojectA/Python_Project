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

- Youtube Data Extraction
  
     - The project utilizes the **google-api-python-client** library to interact with the 
       YouTube Data API.
     - Then created a youtube service using channel IDs of channels "Bhajan Marg", 
       "Aniruddhacharya ji", "PradeepMishra", "BagheswarDham".
     - Then created a function to get the channel statistics of each channel.
  
  

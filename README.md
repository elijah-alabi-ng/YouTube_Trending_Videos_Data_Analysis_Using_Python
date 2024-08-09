<div align='center'>
    <h1>YouTube Trending Videos Analysis Using Python</h1>
</div>

## Introduction

YouTube is a leading video streaming platform in terms of popularity. This project aims to analyze, using Python packages like Pandas, Matplotlib, and Seaborn, a dataset of YouTube trending videos that was collected over 205 days to uncover patterns and insights into what makes a video trend. For each of those days, the dataset contains data about the trending videos of that day. It contains data about more than 37,000 trending videos. The analysis covers various aspects including the number of views, likes, comments, and the impact of video attributes like title length and publication time on a video's trending status. The insights from this analysis will be of immense value to those who want to increase the popularity of their videos on YouTube.


Downoad the dataset [here](https://github.com/ashutoshkrris/YouTube-Trending-Videos-Analysis/blob/master/dataset/INvideos.csv). It contains data about trending videos for many countries. Here we will analyze trending videos in India.

## Goals of the Analysis

1. **Views Analysis:**
   - Determine the distribution of views among trending videos.
   - Investigate whether a large number of views is necessary for a video to become trending.

2. **Likes and Comments Analysis:**
   - Analyze the distribution of likes and comment counts.
   - Explore the relationship between likes, comments, and a video's trending status.

3. **Trending Duration:**
   - Identify which video remained on the trending list for the longest duration.

4. **Title Analysis:**
   - Count how many trending videos contain fully-capitalized words in their titles.
   - Examine the lengths of video titles and their correlation with trending status.

5. **Correlation Analysis:**
   - Investigate how views, likes, dislikes, comment count, title length, and other attributes correlate with each other.

6. **Common Words in Titles:**
   - Identify the most common words used in the titles of trending videos.

7. **Channel and Category Analysis:**
   - Determine which YouTube channels have the largest number of trending videos.
   - Identify the video categories with the largest and smallest number of trending videos.

8. **Publication Time Analysis:**
   - Analyze when trending videos are published, including the day of the week and time of the day.

## Libraries Used

The following Python libraries were used for this analysis:

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating static, animated, and interactive visualizations.
- `seaborn`: For making statistical graphics.
- `numpy`: For numerical operations.
- `collections`: For counting the frequency of elements.

# Data Visualization Project Report

---

## **Introduction**

This project explores the visualization of music streaming data for the most streamed Spotify songs in 2024. The dataset includes a rich variety of metrics from multiple streaming platforms, offering an opportunity to analyze and visualize patterns in music popularity. 

Key objectives include comparing streaming numbers across platforms, identifying platform-specific trends, and uncovering correlations between various metrics. 

---

## **Dataset Overview**

The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data), contains information about individual tracks, their performance across platforms, and other related metadata.

### **Key Features**
- **Track Information:** Track Name, Album Name, Artist, Release Date, ISRC.
- **Popularity Metrics:** All-Time Rank, Track Score, Spotify Popularity, TIDAL Popularity.
- **Streaming Data:** Spotify Streams, YouTube Views, TikTok Views, Pandora Streams, Soundcloud Streams.
- **Platform-Specific Reach:** Spotify Playlist Count, Apple Music Playlist Count, Deezer Playlist Count.
- **Engagement Metrics:** TikTok Posts, TikTok Likes, YouTube Likes, Shazam Counts.
- **Explicit Content Indicator:** Whether the track contains explicit content.

This diverse range of metrics enables a comprehensive analysis of song performance across different music platforms.

---

## **Research Objectives**

The project aims to address the following questions:
1. **Cross-Platform Comparison:** How do the number of streams for top-ranked songs compare across Spotify, YouTube, and Pandora?
2. **Platform-Specific Trends:** Are there songs popular on TikTok but with lower engagement on YouTube?
3. **Correlations:** What relationships exist between track popularity metrics across platforms?

---

## **Visualizations**

### **Scatterplot: YouTube Views vs. TikTok Views**

![Scatterplot](https://github.com/JiarongF/dataviz-project-proposal/blob/master/scatterplot.png)

**Purpose:** To explore whether songs popular on YouTube also perform well on TikTok.

---

### **Bar Chart: Streaming Numbers for Top 10 Tracks**

![Barplot](https://github.com/JiarongF/dataviz-project-proposal/blob/master/barplot.png)

**Purpose:** To compare the performance of the top 10 most popular tracks across platforms.


---

### **Heatmap: Correlation Matrix**

![Heatmap](https://github.com/JiarongF/dataviz-project-proposal/blob/master/heatmap.png)

**Purpose:** To uncover relationships between different variables in the dataset.

---

## **Prototypes**

### **Scatterplot Prototype**

[![Scatterplot Prototype](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20scatterplot.png)](https://vizhub.com/JiarongF/songs-scatter-views)

This interactive scatterplot visualizes YouTube Views vs. TikTok Views, with color coding for artists. Hover functionality reveals artist names, offering deeper insight into individual track performance.

**Key Insight:** TikTok tends to drive higher viewership for tracks compared to YouTube, with many tracks achieving TikTok virality while underperforming on YouTube.

### **Bar Chart Prototype**

[![Bar Chart Prototype](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20barplot.png)](https://vizhub.com/JiarongF/02f045b471f6419d903804bc5086ab54)

The bar chart highlights TikTok's leading role in music discovery. Tracks such as "Flowers" show massive TikTok-driven engagement, while YouTube lags in contribution.

**Key Insight:** TikTok emerges as the dominant platform for driving music engagement, with Spotify streams coming second. YouTube consistently shows lower numbers compared to the other platforms.

### **Heatmap Prototype**

[![Heatmap Prototype](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20heatmap.png)](https://vizhub.com/JiarongF/35197c9881a947ffaf9a0efcf9b20b1a?mode=embed)

This correlation heatmap reveals strong, moderate, and weak relationships between various features, helping identify key factors driving track popularity.

**Key Insight:** 
  - Strong positive correlations include TikTok Likes and TikTok Views (0.99).
  - Moderate correlations are observed between Apple Music Playlist Count and Pandora Streams (0.48), as well as Deezer Playlist Count (0.79).
  - Weak or negligible correlations, such as Explicit Track with most features, indicate minimal influence on song performance.

---

## **Conclusion**

This project provides a comprehensive visualization of the most streamed Spotify songs in 2024, revealing:
- TikTok's dominant role in driving song virality.
- Moderate platform overlap for certain metrics.
- Key correlations, such as the strong alignment between TikTok Likes and Views.

--- 

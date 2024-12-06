# **Data Visualization Project Report**

---

## **Introduction**

Music streaming has become a cornerstone of the entertainment industry, with platforms like Spotify, TikTok, and YouTube shaping the way listeners discover and engage with songs. This project visualizes data from 2024’s most-streamed Spotify tracks, examining how these songs perform across multiple platforms.

By exploring patterns in streaming, platform-specific trends, and cross-platform correlations, the project uncovers insights into how music popularity manifests in a digital, multi-platform ecosystem.

---

## **Dataset Overview**

The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data), provides an extensive look at music performance metrics across various platforms. It includes metadata, engagement statistics, and platform reach, providing a robust foundation for analysis.

### **Key Features**
- **Track Information:** Track Name, Album Name, Artist, Release Date, ISRC.
- **Popularity Metrics:** All-Time Rank, Track Score, Spotify Popularity, TIDAL Popularity.
- **Streaming Data:** Spotify Streams, YouTube Views, TikTok Views, Pandora Streams, Soundcloud Streams.
- **Platform-Specific Reach:** Spotify Playlist Count, Apple Music Playlist Count, Deezer Playlist Count.
- **Engagement Metrics:** TikTok Posts, TikTok Likes, YouTube Likes, Shazam Counts.
- **Explicit Content Indicator:** Whether the track contains explicit content.

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

This interactive scatterplot visualizes YouTube Views vs. TikTok Views, with color coding for artists. Hover functionality reveals artist names, offering deeper insight into individual track performance. The zoom-in and zoom-out feature helps to check overlapping circles.

**Key Insight:**  
- **TikTok's Role in Virality:**  
  The scatterplot demonstrates TikTok’s exceptional ability to generate engagement. Many tracks with high TikTok Views are relatively underrepresented on YouTube, suggesting TikTok is a pivotal platform for driving music virality, especially for emerging or trendy tracks.  
- **For example:** Tracks with millions of TikTok views often show a stark contrast in YouTube viewership, emphasizing the platform's different user base and content consumption behavior.

---

### **Bar Chart Prototype**

[![Bar Chart Prototype](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20barplot.png)](https://vizhub.com/JiarongF/02f045b471f6419d903804bc5086ab54)

**Key Insight:**  
Tracks like *"Flowers"* emerge as standout performers, with TikTok driving the bulk of the engagement, as shown in the bar chart. Spotify, while showing significant streams, plays a secondary role in driving engagement for such tracks.


### **Heatmap Prototype**

[![Heatmap Prototype](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20heatmap.png)](https://vizhub.com/JiarongF/35197c9881a947ffaf9a0efcf9b20b1a?mode=embed)

This correlation heatmap reveals strong, moderate, and weak relationships between various features, helping identify key factors driving track popularity.

**Key Insight:**  
- **Strong positive correlations:** TikTok Likes and TikTok Views (0.99).  
- **Moderate correlations:** Apple Music Playlist Count with Pandora Streams (0.48), as well as Deezer Playlist Count (0.79).  
- **Weak or negligible correlations:** Explicit Track has minimal influence on song performance.

---

## **Conclusion**

- **TikTok as the Kingmaker:**  
  The platform's dominance in driving music virality surpasses that of Spotify and YouTube, especially for emerging artists or viral tracks.  

- **Strategic Opportunities for Artists:**  
  For artists and record labels, focusing on TikTok campaigns may yield greater results in engagement and virality compared to traditional platforms like YouTube.  

- **Cross-Platform Synergy:**  
  While TikTok remains a central driver, Spotify and Apple Music continue to play key roles in sustaining long-term listenership, reflected in moderate correlation patterns.  

- **Data-Driven Insights for Marketing:**  
  By leveraging strong correlations between TikTok metrics, marketing campaigns can be better targeted for higher ROI, particularly focusing on Likes and Views for predictive success.

---

## **Limitations and Future Opportunities**

- **Underrepresentation of Regional Trends:**  
  The dataset does not account for geographic differences, which could provide more nuanced insights into platform-specific dominance in different regions.

- **Temporal Insights:**  
  A time-series analysis could reveal how trends evolve over time, particularly for tracks that gain sudden virality on platforms like TikTok.

---

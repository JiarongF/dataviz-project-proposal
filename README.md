# Data Visualization Project

## 🎵 Data

The data I propose to visualize for my project is [most streamed Spotify songs in 2024](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data). This dataset contains information about various tracks, including metrics from different streaming platforms.

The dataset includes the following columns:

- **Track Name**: Name of the song.
- **Album Name**: Name of the album the song belongs to.
- **Artist**: Name of the artist(s) of the song.
- **Release Date**: Date when the song was released.
- **ISRC**: International Standard Recording Code for the
  song.
- **All Time Rank**: Ranking of the song based on its
  all-time popularity.
- **Track Score**: Score assigned to the track based on
  various factors.
- **Spotify Streams**: Total number of streams on Spotify.
- **Spotify Playlist Count**: Number of Spotify playlists
  the song is included in.
- **Spotify Playlist Reach**: Reach of the song across
  Spotify playlists.
- **Spotify Popularity**: Popularity score of the song on
  Spotify.
- **YouTube Views**: Total views of the song's official
  video on YouTube.
- **YouTube Likes**: Total likes on the song's official
  video on YouTube.
- **TikTok Posts**: Number of TikTok posts featuring the
  song.
- **TikTok Likes**: Total likes on TikTok posts featuring
  the song.
- **TikTok Views**: Total views on TikTok posts featuring
  the song.
- **YouTube Playlist Reach**: Reach of the song across
  YouTube playlists.
- **Apple Music Playlist Count**: Number of Apple Music
  playlists the song is included in.
- **AirPlay Spins**: Number of times the song has been
  played on radio stations.
- **SiriusXM Spins**: Number of times the song has been
  played on SiriusXM.
- **Deezer Playlist Count**: Number of Deezer playlists the
  song is included in.
- **Deezer Playlist Reach**: Reach of the song across Deezer
  playlists.
- **Amazon Playlist Count**: Number of Amazon Music
  playlists the song is included in.
- **Pandora Streams**: Total number of streams on Pandora.
- **Pandora Track Stations**: Number of Pandora stations
  featuring the song.
- **Soundcloud Streams**: Total number of streams on
  Soundcloud.
- **Shazam Counts**: Total number of times the song has been
  Shazamed.
- **TIDAL Popularity**: Popularity score of the song on
  TIDAL.
- **Explicit Track**: Indicates whether the song contains
  explicit content.



## Questions & Tasks

 * Compare the number of streams on Spotify, YouTube, and Pandora for top-ranked songs.
 * Identify songs that are popular on TikTok but have lower popularity on YouTube.
 * Check if there is correlation of track popularity across different platforms.

## Sketches

![Scatterplot](https://github.com/JiarongF/dataviz-project-proposal/blob/master/scatterplot.png)


This scatterplot visualizes the relationship between the number of views on YouTube and TikTok for various tracks. It aims to explore whether there is a positive correlation, indicating that songs popular on YouTube also tend to receive a higher number of likes on TikTok.


![Barplot](https://github.com/JiarongF/dataviz-project-proposal/blob/master/barplot.png)


This bar plot displays the streaming numbers for the top 10 most popular songs across different platforms. Each bar represents a specific platform, and the height indicates the total stream count for a particular song. This visualization provides a comparative view of how these top tracks perform across multiple platforms, highlighting which platforms contribute the most to a song's overall popularity.


![Heatmap](https://github.com/JiarongF/dataviz-project-proposal/blob/master/heatmap.png)


This plot visualizes the correlation of different variables in this dataset. The color's intensity represents the correlation's strength, with darker shades indicating stronger positive or negative correlations.


## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot and it shows YouTube views vs TikTok views. Different color represents different artist. When you hover over each circle, the artist's name is displayed.


[![vizscatter](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20scatterplot.png)](https://vizhub.com/JiarongF/songs-scatter-views)


This scatter plot reveals interesting patterns in the viewership of music tracks across YouTube and TikTok. Most tracks cluster in the lower-left corner, indicating relatively low view counts on both platforms, with only a few achieving substantial visibility. TikTok shows a broader range of high-view tracks, with some reaching up to 45,000 (in tens of thousands) views, while their YouTube views remain comparatively low. Scattered points in the upper region show tracks that perform well on YouTube, but these are less common. Overall, the plot suggests that while a few tracks gain traction on both platforms, many tend to achieve popularity primarily on either TikTok or YouTube, highlighting TikTok’s stronger role in driving high viewership for music content.

This is plot visualizes the top 10 most popular tracks based on their YouTube Views, TikTok Views, and Spotify Streams.

The legend has been updated to be interactive, making it easier to focus on specific data series. When you hover over a legend item, the corresponding bars in the chart are highlighted, allowing you to quickly compare values across categories.

[![Barchart](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20barplot.png))](https://vizhub.com/JiarongF/02f045b471f6419d903804bc5086ab54)


This chart really highlights TikTok's influence on music discovery right now. For most of the tracks, TikTok views are way ahead, showing just how powerful the platform is for getting songs out there. "Flowers" is a standout, with a huge spike in TikTok views that suggests it went viral in a big way. Other songs like "MILLION DOLLAR BABY" also do well on TikTok, though not quite to the same level. Spotify streams come in second for most tracks, with songs like "Gata Only" balancing strong numbers on both TikTok and Spotify. Meanwhile, YouTube views are consistently lower, hinting that people might be turning to other platforms to discover and engage with new music. Overall, this chart gives a snapshot of how TikTok is leading the way in music engagement, with Spotify still holding its own, while YouTube seems to be falling behind.

This is the heatmap showing the correlation between different variables

[![Correlation Heatmap](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20heatmap.png)](https://vizhub.com/JiarongF/35197c9881a947ffaf9a0efcf9b20b1a?mode=embed)

This correlation heatmap provides an overview of the relationships between various music-related features, showing the strength and direction of their correlations. Darker shades of blue indicate stronger positive correlations, while darker shades of red highlight stronger negative correlations. For instance, TikTok Likes and TikTok Views have a very high positive correlation (0.99), suggesting that more likes on TikTok strongly align with more views.


This correlation heatmap provides an overview of the relationships between various music-related features, showing the strength and direction of their correlations. Darker shades of blue indicate stronger positive correlations, while darker shades of red highlight stronger negative correlations. For instance, TikTok Likes and TikTok Views have a very high positive correlation (0.99), suggesting that more likes on TikTok strongly align with more views. Similarly, Apple Music Playlist Count shows moderate positive correlations with Pandora Streams (0.48) and Deezer Playlist Count (0.79), hinting that songs featured on more Apple Music playlists tend to perform better on other streaming platforms as well.

On the other hand, there are some weaker or near-zero correlations, like Explicit Track with most features, indicating that a track's explicit status doesn't strongly correlate with other performance metrics. Negative correlations, though limited, include YouTube Likes with Explicit Track (-0.10), suggesting that explicit content may slightly affect YouTube engagement.

## Open Questions

Thanks for the valuable feedback from Curran! I really like the idea of text embedding, and I think the log transformation would be a great addition to my project. It's a very insightful suggestion, and I’ll definitely try to incorporate it once I get past midterms (a bit tied up with those at the moment).

## Milestones

- **Week 8** - Experiment with text embedding and log transformation
- **Week 9** - Barchart implementation
- **Week 10** - Heatmap implementation
- **Week 11** - Add hover effect to bar chart
- **Week 12** - Add tooltips to heatmap
- **Week 13** - Finalize plots
- **Week 14** - Write the report

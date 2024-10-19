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


![vizscatter](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20scatterplot.png)


[Vizhub](https://vizhub.com/JiarongF/songs-scatter-views)

This is plot visualizes the top 10 most popular tracks based on their YouTube Views, TikTok Views, and Spotify Streams.

![vizbar](https://github.com/JiarongF/dataviz-project-proposal/blob/master/vizhub%20barplot.png)


[Vizhub](https://vizhub.com/JiarongF/02f045b471f6419d903804bc5086ab54)

## Open Questions

Thanks for the valuable feedback from Curran! I really like the idea of text embedding, and I think the log transformation would be a great addition to my project. It's a very insightful suggestion, and I’ll definitely try to incorporate it once I get past midterms (a bit tied up with those at the moment).

## Milestones

- **Week 8** - Experiment with text embedding and log transformation
- **Week 9** - Check if incorporating other music datasets from different years is necessary
- **Week 10** - Bar plot implementation
- **Week 11** - Heatmap implementation
- **Week 12** - Add tooltips if necessary
- **Week 13** - Finalize plots
- **Week 14** - Write the report

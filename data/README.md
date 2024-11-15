# Instructions for the data folder

## Data Dictionary
| Column Name       | Data Type    | Source         | Description                                                                         |
|-------------------|--------------|----------------|-------------------------------------------------------------------------------------|
| **track_Name**    | Text         | Both           | The name of the track.                                                              |
| **artist_Name**   | Text         | Both           | The name of the artist or band associated with the track.                           |
| **genre**         | Categorical  | Kaggle         | The genre or genres associated with the track.                                      |
| **danceability**  | Numeric      | Kaggle         | A measure of how suitable a track is for dancing.                                   |
| **energy**        | Numeric      | Kaggle         | The energy level of the track.                                                      |
| **key**           | Categorical  | Kaggle         | The key of the track (e.g., C, D, E).                                               |
| **loudness**      | Numeric      | Kaggle         | The overall loudness of the track in decibels (dB).                                 |
| **mode**          | Numeric      | Kaggle         | The modality of the track (1 = major, 0 = minor).                                   |
| **speechiness**   | Numeric      | Kaggle         | The presence of spoken words in the track.                                          |
| **acousticness**  | Numeric      | Kaggle         | The acousticness of the track.                                                      |
| **instrumentalness** | Numeric  | Kaggle         | The probability of the track being instrumental.                                    |
| **liveness**      | Numeric      | Kaggle         | A measure of the presence of a live audience in the track.                          |
| **valence**       | Numeric      | Kaggle         | The musical positiveness or happiness conveyed by the track.                        |
| **tempo**         | Numeric      | Kaggle         | The tempo of the track in beats per minute (BPM).                                   |
| **duration_ms**   | Numeric      | Kaggle         | The duration of the track in milliseconds.                                          |
| **time_signature** | Numeric     | Kaggle         | The time signature of the track.                                                    |
| **total_streams** | Numeric      | Kworb          | Total amount of Spotify streams all time.                                           |
| **daily_streams** | Numeric      | Kworb          | Total amount of daily Spotify streams.                                              |
| **stream_rank**   | Numeric      | Kworb/Calculated | New field to reindex/re-rank after join.                                          |


## raw
Original, unmodified data.


## final
Data after all cleaning and analysis.

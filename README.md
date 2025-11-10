# Spotify_EDA
It is a Exploratory Data Analysis Challenge

By Ankan Sadhu

📊 My mission was to analyze the provided dataset to uncover actionable insights for Spotify Dataset, focusing on optimizing new songs for popularity.

🚀 Install Dependencies and rerun the notebook :

Pandas numpy matplotlib seaborn sklearn mpl_toolkits.mplot3d scipy

🔍 Key Insights & Findings

Our analysis of the Spotify dataset led to the following key insights:

[Insight 1]: The Library is a "Long-Tail" of Undiscovered Content: The most critical insight is that popularity is not correlated with any single audio feature. The library consists of a massive "long-tail" of unpopular songs at every energy, danceability, and acousticness level. This means discovery is the most important product feature. Success depends on using audio features (tempo, energy, acousticness clusters) to build personalized "radio" stations and discovery engines that surface relevant, unpopular tracks to the right users.

[Insight 2]: The "Hit" Profile Has Changed (The "TikTok Effect"): Today's popular music is fundamentally different from "classics." The data shows a clear trend: modern hits are significantly shorter, more danceable, and less instrumental (more vocal-focused) than tracks from the 70s, 80s, and 90s. This confirms that "decade" or "era" is a critical feature for building playlists, as a "70s Hits" station and a "Today's Hits" station will have completely different audio profiles and pacing.

[Insight 3]: The Library is a Mix of Distinct "Sub-Products": The data consistently shows the library is not one single collection of music. It is segmented into distinct "sub-products" that define different user experiences: it's bimodal in tempo (~125 vs. ~170 BPM), clearly split between music and spoken-word (speechiness), and groups into four unique audio profiles (Acoustic, Pop, Instrumental, Rap/Spoken). These segments are the key to building "pure" radio stations (e.g., "Acoustic," "Workout") that match user intent.

For a more detailed breakdown, please refer to our full analysis in the Jupyter Notebook and the accompanying presentation.

📁 Repository Structure

README.md (This file)

spotify_tracks.csv and spotify_data_description (The raw datasets used for the challenge)

spotify_eda.ipynb (The main Jupyter Notebook with all our code and analysis)

presentation.pptx (A summary of our findings and recommendations)

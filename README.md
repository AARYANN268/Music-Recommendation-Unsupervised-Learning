# Music-Recommendation-Unsupervised-Learning
# 🎵 Amazon Music Smart-Clustering AI

> **An AI project that automatically groups 95,000+ songs into 5 musical "moods" based on how they sound.**
## 📖 What is this project?
When you have millions of songs, it's hard to label them all by hand. This project uses **Machine Learning** to listen to the "DNA" of a song (like its speed, energy, and mood) and group similar songs together automatically.
## 🛠️ How it works
1. **Cleaning the Data:** We took 95,000 songs and looked at features like how "danceable" or "loud" they are.
2. **Teaching the AI:** We used a method called **K-Means Clustering**. It’s like a digital sorting machine that finds patterns we can't see.
3. **Simplifying:** We used a trick called **PCA** to turn complex data into a 2D map so we can actually see the song groups.
## 📊 The 5 Music "Vibes" Found
By looking at the results, the AI created these 5 specific categories:

* 🌿 **The Acoustic Vibe:** Quiet, organic songs with real instruments.
* 🎹 **Focus Mode:** Instrumental music with almost no singing.
* 🎙️ **The Lyricist:** Songs where the words and vocals are the most important part.
* 🌙 **Deep Chill:** Very slow, relaxing music for sleeping or resting.
* ⚡ **High Energy:** Fast, loud, and happy music for the gym or parties.

## 🚀 Why this matters
This system can be used to build:
1. **"Smart Playlists":** Automatically create a "Chill" or "Party" playlist.
2. **Better Recommendations:** If you like one song, the AI finds 5 others from the same group!
## 📂 What’s inside this folder?
* `Amazon_Music_Clustering.ipynb`: The Python code (the engine).
* `amazon_music_final_clusters.csv`: The list of songs with their new AI labels.
* `Analysis_Report.pdf`: A simple summary with charts and pictures.

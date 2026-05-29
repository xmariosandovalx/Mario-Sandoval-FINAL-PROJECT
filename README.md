# Loudness and Dynamic Range Analysis in Modern Hip-Hop and EDM Production

## Project Overview

This project combines Audio Engineering concepts with Data Science and Machine Learning techniques to analyze loudness, dynamic range, and audio characteristics in modern music production.

Using a Spotify dataset containing over 114,000 tracks, the project explores relationships between audio features such as loudness, energy, danceability, tempo, and genre classification. Additionally, real-world loudness measurements were performed inside Ableton Live using professional audio metering tools.

---

## Objectives

* Analyze audio features from modern music tracks.
* Compare loudness and dynamic range across genres.
* Explore relationships between audio characteristics.
* Apply machine learning techniques for clustering and classification.
* Validate dataset findings using DAW-based measurements.
* Combine Audio Engineering and Data Science methodologies.

---

## Dataset

Spotify Tracks Dataset

Main features used:

* Danceability
* Energy
* Loudness
* Tempo
* Popularity
* Acousticness
* Valence

Selected genres:

* EDM
* House
* Techno
* Hip-Hop

---

## Technologies Used

### Data Science

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

### Audio Engineering

* Ableton Live
* Youlean Loudness Meter
* FabFilter Pro-L2

---

## Machine Learning Methods

### K-Means Clustering

Used to identify groups of tracks with similar audio characteristics.

### Principal Component Analysis (PCA)

Used to visualize genre relationships and feature distributions.

### Random Forest Classification

Used to classify genres based on selected audio features.

---

## DAW-Based Loudness Analysis

Commercial tracks were analyzed inside Ableton Live using:

* Youlean Loudness Meter
* FabFilter Pro-L2

Measurements collected:

* Integrated LUFS
* Loudness Range (LRA)
* True Peak

The Ableton Live measurements were used to validate trends identified through dataset analysis.

---

## Key Findings

* Electronic genres generally exhibited higher loudness and energy values.
* Lower LRA values indicated stronger dynamic compression.
* Loudness and energy showed strong positive correlation.
* Machine learning models successfully classified genres using audio features.
* DAW measurements supported findings from the Spotify dataset.

---



---

## Future Improvements

* Expanded genre analysis
* Spectral and frequency-domain analysis
* Deep learning approaches
* Streaming normalization comparisons
* Additional DAW-based measurements

---

## Author

Mario Sandoval

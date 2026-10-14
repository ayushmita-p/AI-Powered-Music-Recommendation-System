<div align="center">

# 🎵 AI-Powered Music Recommendation System

**Discover your next favorite song with data, not guesswork.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-F7931E?logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</div>

---

## 📖 About the Project

With millions of songs available on streaming platforms, the real challenge is **discovery**. This project builds a music recommendation system on **Spotify audio-feature data**, taking a song and returning similar songs.
I developed it as an **internship project** that covers the full data science workflow: data exploration, visualization, genre grouping, and recommendation.

## 🎯 Objectives

- Explore and visualize Spotify audio features to understand what makes songs similar or different
- Group songs by genre and sound characteristics
- Recommend songs similar to a track the user already likes

## ✨ Highlights

| | Feature | Description |
|---|---|---|
| 📊 | **Data Visualization** | Charts and plots that reveal patterns and relationships across audio features |
| 🎼 | **Genre Grouping** | Songs organized by genre and audio characteristics |
| 🤖 | **Recommendation Engine** | Personalized song suggestions based on audio-feature similarity |
| 📓 | **Reproducible Notebooks** | Step-by-step Jupyter notebooks that anyone can run end to end |

## 🛠️ Tech Stack

- **Language:** Python
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📂 Repository Structure

```
AI-Powered-Music-Recommendation-System/
│
├── Spotify_Data_Visualization.ipynb          # Exploratory data analysis and visualizations
├── Spotify_Recommendation_System.ipynb       # Recommendation engine
├── Project 2 - Spotify Genre Grouping.docx   # Genre grouping documentation
├── spotify dataset.csv                       # Main Spotify dataset
├── spotify_part1.csv                         # Dataset (part 1)
└── README.md
```

## ⚙️ How It Works

```
Raw Spotify Data  →  Cleaning & Preprocessing  →  Exploratory Analysis
                                                          ↓
         Song Recommendations  ←  Similarity Search  ←  Genre Grouping
```

1. **Data Preparation:** Load the dataset, clean it, and select the relevant audio features.
2. **Exploratory Analysis:** visualize distributions and correlations between features such as danceability, energy, valence, tempo, and acousticness.
3. **Genre Grouping:** organize songs into groups based on their characteristics.
4. **Recommendation:** For a chosen song, find and rank the most similar tracks.

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/ayushmita-p/AI-Powered-Music-Recommendation-System.git

# Move into the project folder
cd AI-Powered-Music-Recommendation-System

# Install the required libraries
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Start Jupyter Notebook
jupyter notebook
```

### Usage

1. Open **`Spotify_Data_Visualization.ipynb`** and run all cells to explore the data.
2. Open **`Spotify_Recommendation_System.ipynb`** and run all cells to build the recommender.
3. Change the input song in the recommendation cell to get suggestions for your own favorite track.

## 🔮 Future Improvements

- [ ] Deploy as an interactive web app using Streamlit
- [ ] Add collaborative filtering using user listening history
- [ ] Build a hybrid recommender combining content-based and collaborative approaches
- [ ] Integrate the Spotify API for live data and album artwork
- [ ] Add evaluation metrics to compare recommendation strategies

## 💡 Key Learnings

- Applying machine learning to a real-world recommendation problem
- Cleaning, scaling, and visualizing large audio-feature datasets
- Turning raw data into insights through effective visualization
- Structuring and documenting a project so others can reproduce it

## 👩‍💻 Author

**Ayushmita**

[![GitHub](https://img.shields.io/badge/GitHub-ayushmita--p-181717?logo=github&logoColor=white)](https://github.com/ayushmita-p)

---

<div align="center">

⭐ If you found this project helpful, please consider giving it a star!

</div>

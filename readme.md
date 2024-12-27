# Lyrics Dataset Analysis and Sentiment Project

## Dataset Overview 🎵
This dataset contains song lyrics of popular artists from various genres. Each file represents an artist and includes the following structured information:

### Files 📂:
- `ArianaGrande.csv`
- `BTS.csv`
- `Beyonce.csv`
- `BillieEilish.csv`
- `CardiB.csv`
- `CharliePuth.csv`
- `ColdPlay.csv`
- `Drake.csv`
- `DuaLipa.csv`
- `EdSheeran.csv`
- `Eminem.csv`
- `JustinBieber.csv`
- `KatyPerry.csv`
- `Khalid.csv`
- `LadyGaga.csv`
- `Maroon5.csv`
- `NickiMinaj.csv`
- `PostMalone.csv`
- `Rihanna.csv`
- `SelenaGomez.csv`
- `TaylorSwift.csv`

### Columns 📊:
- **Artist**: Name of the artist.
- **Title**: Title of the song.
- **Album**: Album in which the song is featured.
- **Year**: Year the song was released.
- **Date**: Specific release date.
- **Lyric**: Full song lyrics.

## Objective 🎯
The primary goal of this project is to analyze song lyrics using sentiment analysis and build models for advanced lyric-based tasks, such as text generation and artist comparison.

## Analysis Conducted 📈
1. **Individual Sentiment Analysis**:
   - Performed sentiment analysis for each artist using their respective files.
   - Extracted insights such as the polarity and emotional tone of the lyrics.

2. **Combined Sentiment Analysis**:
   - Merged all artists' data into a single file for overall sentiment analysis.
   - Identified trends and variations in lyrics sentiment across different artists and genres.

## Planned Model: Deep Learning Lyrics Generator 🤖
### Features:
- **Input**: Initial words or phrases.
- **Output**: Generates song lyrics in the style of a specific artist or general tone.

### Steps:
1. Preprocess data (tokenization, removing stopwords, and padding sequences).
2. Train a recurrent neural network (e.g., LSTM/GRU-based model).
3. Fine-tune the model for each artist using their lyrics dataset.

## Usage 🎵
1. Sentiment analysis of individual or merged datasets.
2. Text generation based on artist-specific lyrical styles.

## Tools and Libraries Used 🛠️
- **Python Libraries**:
  - `pandas` (for data manipulation)
  - `numpy` (for numerical operations)
  - `matplotlib`, `seaborn` (for visualization)
  - `nltk`, `spaCy` (for text processing)
  - `TensorFlow`/`PyTorch` (for model training)
  - `scikit-learn` (for sentiment analysis)

## Inspirations 🌟
This dataset and project can be used for:
- Sentiment Analysis of songs.
- Artist-wise lyrical style comparison.
- Building personalized lyric generators for music enthusiasts.

## Contribution 🤝
Feel free to extend the dataset by adding more artists or suggesting enhancements. Let us know your ideas in the discussion thread! 🎤
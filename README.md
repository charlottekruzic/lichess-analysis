# LiChess data analysis
## 🔎 Overview
This project involves analyzing a large dataset from LiChess, the second most visited chess website worldwide with over 3 million games played daily.

The dataset consists of approximately 3.74 million games played in September 2020, annotated by the Stockfish chess engine, containing detailed game metrics and player information, with 40 columns describing different elements of chess games.

## 📝 Methodology
To process this large-scale dataset efficiently, we leveraged Apache Spark as our primary data processing framework.

Our analysis began by addressing the three core questions posed in the [project assignment](./ressources/project-assignment.pdf): analyzing error rates by ELO category in Blitz games, calculating win probabilities based on opening selection, and building predictive models for game outcomes. We then expanded our investigation with additional research questions examining the relationship between openings and draw rates, as well as exploring potential correlations between ELO differences and game duration.

The comprehensive analyses conducted throughout this project not only answered the original questions but also opened interesting perspectives through our supplementary investigations. Our findings are supported by detailed visualizations and interpretations provided in the [lichess.ipynb](lichess.ipynb) notebook (or its [HTML](lichess.html) and [PDF](lichess.pdf) exports), offering deeper insights into the dynamics of chess games on LiChess.

## 🗂️ Dataset
The dataset used in this project is available on [Kaggle](https://www.kaggle.com/datasets/noobiedatascientist/lichess-september-2020-data) and includes games analyzed by Stockfish with the following key information:

- Player ELO ratings
- Game time controls (Blitz, Fast, Classic)
- Chess openings with ECO codes
- Engine analysis data (blunders, mistakes, inaccuracies)
- Time pressure errors
- Long move counts
- Game advantage shifts

## 🛠️ Technologies used
The analysis was conducted using the following libraries and frameworks:
- **Apache Spark** (via PySpark) for large-scale data processing
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for data visualization
- **KaggleHub** for dataset access
- **Python collections** for data handling

## 📝 Documentation
All analysis details, code, and results are available in the [Jupyter notebook](lichess.ipynb) (in French), along with [HTML](lichess.html) and [PDF](lichess.pdf) exports of the notebook for easier viewing.

## 🎓 Academic context
This project was developed during the first year of the Master’s program in Data Science and Complex Systems at the University of Strasbourg. It is part of the common curriculum shared by all Computer Science tracks.

The [original project assignment](./ressources/project-assignment.pdf) is also available for reference.

## 👷 Contributors
- Zoé Marquis
- Charlotte Kruzic
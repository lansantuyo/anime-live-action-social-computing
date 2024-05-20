# Anime Live-Action Adaptations: Deciphering Success Factors

## Overview

This repository contains Jupyter notebooks and supporting files for the project **"Anime Live-Action Adaptations: Deciphering Success Factors"**. The project aims to identify and analyze the factors contributing to the success or failure of anime live-action adaptations through computational methods such as sentiment analysis, term frequency-based analysis, and topic modeling.

## Repository Structure

```
Anime-Live-Action-Adaptations
│
├── Computational Outputs/
├── Datasets/
├── api_key.txt
├── Ling_Salas_Santuyo_Project_COA.pdf
├── Ling_Salas_Santuyo_Project_Slides.pdf
├── Computational Methods.ipynb
└── Text Scraper.ipynb

```

### Folders

-   **Computational Outputs/**: Contains output files and visualizations from the computational analyses.
    -   **LDA Tuning/**: Contains the tuning results for LDA topic models.
    -   **LDA Visualizations/**: Contains visualizations of the LDA topic models.
    -   **sentiment_analysis/**: Contains sentiment analysis results.
    -   **term_frequency/**: Contains term frequency analysis results and word clouds.
-   **Datasets/**: Contains the raw data files used for the analysis.
    -   **imdb_reviews/**: CSV files of reviews scraped from IMDB.
    -   **rotten_tomatoes_reviews/**: CSV files of reviews scraped from Rotten Tomatoes.
    -   **youtube_comments/**: CSV files of comments scraped from YouTube.
-   **api_key.txt**: Contains the API key for accessing YouTube data.
-   **Computational Methods.ipynb**: Jupyter notebook for preprocessing and performing computational analysis.
-   **Ling_Salas_Santuyo_Project_Paper.pdf**: Full project paper detailing the methodology, analysis, and results.
-   **Ling_Salas_Santuyo_Project_Slides.pdf**: Presentation slides summarizing the project.
-   **Text Scraper.ipynb**: Jupyter notebook for scraping text data from IMDB, Rotten Tomatoes, and YouTube.

## Jupyter Notebooks

### 1. Text Scraper.ipynb

This notebook contains the code for extracting user reviews from Rotten Tomatoes and IMDB, and YouTube comments. It utilizes `Selenium` for web scraping and the `YouTube API` for fetching comments from YouTube videos.

#### Key Functions:
- **IMDB and Rotten Tomatoes Scraper**: Uses Selenium WebDriver to navigate and extract reviews.
- **YouTube API Scraper**: Uses YouTube API to fetch comments from videos.

### 2. Computational Methods.ipynb

This notebook contains the code for preprocessing the extracted text data and performing various computational analyses, including sentiment analysis, term frequency-based analysis, and topic modeling using `NLTK`, `SciKit Learn`, and `Gensim`.

#### Key Sections:
- **Data Cleaning and Preprocessing**: Language detection, regular expression cleaning, lemmatization, stop word removal, and bigram/trigram model generation.
- **Sentiment Analysis**: Using NLTK’s VADER to assess the emotional tone of reviews and comments.
- **Term Frequency-Based Analysis**: Using CountVectorizer and TF-IDF to determine the significance of terms.
- **Topic Modeling**: Using Gensim’s LDA to extract common themes from the text data.


## Results

The results of the analyses will be saved as output files and visualizations within the notebooks, helping to answer the key research questions about the success factors of anime live-action adaptations.

## Authors

- Duncan Xenos Ling
- Jose Gabriel Salas
- Lance Dominic B. Santuyo

## Acknowledgments

Special thanks to our project advisor Lance Calvin L. Gamboa for his guidance and support.



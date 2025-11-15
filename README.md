# EmoTweetID: Indonesian Emotion Tweet Dataset

This repository contains the full workflow and scripts used to construct the **EmoTweetID** dataset, including tweet scraping, preprocessing, annotation, and word embedding training.

## Repository Contents

The repository includes the following Jupyter notebooks and supporting files:

- **`01-main-scraper.ipynb`**  
  Script for scraping Indonesian tweets from X (formerly Twitter) using the `snscrape` library with emotion-related keywords.
- **`02-merge-tweet.ipynb`**  
  Notebook for merging multiple scraped tweet files into a single dataset.
- **`03-tweet-processor.ipynb`**  
  Preprocessing pipeline for cleaning, normalizing, and preparing tweets for annotation and embedding training.
- **`04-lexicon-labeling.ipynb`**  
  Automatic emotion annotation using the Indonesian NRC Emotion Lexicon (`nrc_id.json`).
- **`05-word-embedding-training.ipynb`**  
  Training scripts for Word2Vec and fastText models using the cleaned tweet corpus.
- **`06-word-embedding-visualization.ipynb`**  
  Visualization of trained word embeddings using dimensionality reduction techniques (e.g., t-SNE).
- **`nrc_id.json`**  
  Indonesian NRC Emotion Lexicon used for lexicon-based annotation.

## How to Cite This Dataset
Setyo Nugroho, Kuncahyo; Abdurrachman Bachtiar, Fitra; Firdaus Mahmudy, Wayan; Martianus Henry, Matthew; Isnan, Mahmud; Pangestu, Gusti; Pardamean, Bens (2025), *EmoTweetID: Indonesian Emotion Tweet Dataset*, Mendeley Data, V2,  doi: [10.17632/jzgnjsff9f.2](https://doi.org/10.17632/jzgnjsff9f.2)

## Acknowledgment
1. Intelligent Systems Lab, Faculty of Computer Science, Brawijaya University, Indonesia
2. NVIDIA AI Research & Development Center, Bina Nusantara University, Indonesia

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
# Hoax News Classification

A machine learning / natural language processing project for classifying Indonesian news articles as **hoax (fake) or valid (real)**.

This repository contains data preprocessing, model evaluation, and experimentation with multiple approaches to detect hoax news from Indonesian news sources using linguistic features and deep learning techniques.

## 🧠 Project Overview

With the rapid spread of misinformation and hoax news online, especially on social media and news portals, automatic classification systems are useful to help filter unreliable content. Hoax (fake) news refers to false or misleading information presented as factual news with an intent to deceive or confuse readers. :contentReference[oaicite:0]{index=0}

This project explores text classification techniques to distinguish between hoax and valid Indonesian news articles using machine learning and language models.

## 📁 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `tribunnews_politik_full.csv` | Raw news dataset (Indonesian news articles) to evaluate model. |
| `turnbackhoax.xlsx`, `kompas.xlsx`, `tempo.xlsx`, `cnn.xlsx` | Source news data from multiple news platform to train model. |
| `WRS_model_eval.ipynb` | Jupyter notebook evaluating Weighted Random Sampling (WRS) pre-trained model. |
| `cut_model_eval.ipynb` | Jupyter notebook evaluating cut dataset pre-trained model. |
| `hoaxvalid_cut.ipynb` | Build model with cut dataset. |
| `hoaxvalid_wrs.ipynb` | Build model with Weighted Random Sampling (WRS) dataset. |
| `scrap_tribun.ipynb` | notebook for scrapping to collecting news data. |
| `.gitattributes` | Git attributes configuration. |

## 🚀 Key Features

✔ Indonesian news classification based on scraped & collected news datasets  
✔ Exploratory data analysis for hoax and valid news  
✔ Multiple model experiments for text classification  
✔ Support for transformer-based language models (e.g., IndoBERT)

## 📊 Models & Techniques

This project uses a combination of methods including:

- **Data scraping & preprocessing** (cleaning, tokenization, labeling)
- **Feature extraction** (text processing for natural language)
- **Transformer-based language models** (IndoBERT variations for improved text representation)

> Note: Model design and performance may vary depending on preprocessing and dataset balance.

## 🛠 How To Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/sherlyoktavia/hoax-news-classification.git
   cd hoax-news-classification

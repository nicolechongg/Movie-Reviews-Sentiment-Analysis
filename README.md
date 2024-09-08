# Movie Reviews Sentiment Analysis

This repository contains the code and resources for our project on movie reviews sentiment analysis. This project aims to classify the sentiment of movie reviews as positive, negative or neutral based on text analysis using natural language processing techniques.

## Repository Structure
```
The repository is organized as follows:
├── code
│   ├── group49_report+notebook.ipynb  # Jupyter notebook with code and analysis
│   ├── requirements.txt               # List of Python dependencies for the project
├── group49_slides.pdf                # Slides summarizing the project
├── README.md                          # This README file
```

## Project Description

Sentiment analysis in the realm of movie reviews has become a game-changer in our digital age. As movie enthusiasts incerasingly turn to online reviews for guidance in their cinematic choices, the demand for accurate sentiment predictions has surged. 

The primary objective of this project is to build a robust machine-learning model capable of making predictions in the form of sentiment classification for movie reviews. By classifying each textual review into one of the several predefined categories (positive/neutral/negative), the project aims to enhance the accuracy of sentiment predictions in the domain of movie reviews and explore collecting data from well-established movie review webpages through web scraping.

Key steps in the project include:
- Obtaining raw data through web scraping
  - As the raw dataset size is too big to upload, do contact Nicole (nicole.chong2002@gmail.com) if you wish to have access to it.
- Data Cleaning and Preprocessing
- Text Vectorization using TF-IDF
- Model Training
  1. Linear Models (Naive Bayes, linear SVM, logistic regression)
  2. Ensemble Learning (Random Forest)
  3. Deep Learning (CNN-BiLSTM)
- Model Evaluation
  1. Accuracy
  2. Recall
  3. Precision
  4. F1-score
- Model Hyperparameter Tuning
- Visualization of results

The full code and detailed explanations are available in the Jupyter notebook (`group49_report+notebook.ipynb`).

## Requirements

To replicate the analysis, you can install the required packages listed in the `requirements.txt` file. Run the following command to install them:

```bash
pip install -r code/requirements.txt
```

## How to Run the Notebook
1. Clone the repository:

```
git clone https://github.com/nicolechongg/Movie-Reviews-Sentiment-Analysis.git
```
3. Navigate to the code directory:

```
cd Movie-Reviews-Sentiment-Analysis/code
```
5. Launch the Jupyter Notebook:
```
jupyter notebook group49_report+notebook.ipynb
```

## Project Slides
The project slides, summarizing the key results and findings, can be found in the `group49_slides.pdf` file.






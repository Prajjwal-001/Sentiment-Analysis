# Sentiment-Analysis

This project focuses on sentiment analysis using the VADER model, enhanced by lemmatization for improved performance and operations. The spaCy library is used to speed up the lemmatization process. The project was developed and executed in a Jupyter Notebook environment. The dataset used for this project was obtained from Kaggle and can be found here: https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial/input.

Table of Contents:

1. Introduction
2. Dataset
3. Installation
4. Project Structure
5. Results
6. Conclusion
7. Acknowledgements

Introduction
Sentiment analysis is a crucial part of understanding opinions expressed in textual data. This project leverages the VADER (Valence Aware Dictionary and sEntiment Reasoner) model for sentiment analysis, incorporating lemmatization to enhance the accuracy and efficiency of the analysis. By using spaCy for lemmatization, we improve the processing speed significantly.Both the standard VADER model and the enhanced version are utilized in this project to compare their effectiveness.

Dataset
The dataset for this project was sourced from Kaggle and contains a variety of text samples suitable for sentiment analysis. You can find the dataset here:  https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial/input.

Installation
To run this project, you will need to install several Python libraries. Below is the list of required packages:

Code:
  pip install pandas numpy nltk spacy vaderSentiment jupyter
  python -m spacy download en_core_web_sm

Project Structure
The project structure is as follows:
├── data

│   └── sentiment_analysis_dataset.csv

├── notebooks

│   └── sentiment_analysis.ipynb

├── README.md

data/: Directory containing the dataset.
notebooks/: Directory containing the Jupyter Notebook with the project code.
README.md: This file.

Results
The results section of the notebook demonstrates the performance improvements achieved through lemmatization and the use of spaCy. Sentiment scores for the dataset are calculated and visualized, showing the effectiveness of the VADER model with enhanced preprocessing.

Conclusion
This project showcases an efficient approach to sentiment analysis by integrating the VADER model with lemmatization using spaCy. The enhancements lead to better performance and faster processing times, making it suitable for large-scale text analysis tasks.

Acknowledgements
VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text (https://github.com/cjhutto/vaderSentiment)
spaCy: Industrial-Strength Natural Language Processing (https://spacy.io/)
Kaggle Dataset: Sentiment Analysis (https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial/input.)
Feel free to contribute to this project by submitting issues or pull requests. Your feedback is highly appreciated!

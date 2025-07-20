# 🧠 Emotion & Sentiment Analysis using Python
This project performs basic Natural Language Processing (NLP) to analyze emotions and sentiment from a text file. It utilizes the nltk library to tokenize, clean, and filter words, maps them to emotions using a custom emotion lexicon, and uses VADER sentiment analysis to determine the overall polarity. The results are visualized in a bar chart.

🚀 How It Works
Step-by-Step Breakdown
- Read and preprocess the input:
- Converts text to lowercase.
- Removes punctuation.
- Tokenizes words.
- Removes English stopwords.
- Emotion extraction:
- Matches cleaned tokens with a custom emotion lexicon.
- Counts and stores the detected emotions.
- Sentiment analysis:
- Applies VADER to calculate sentiment scores (positive, negative, neutral).
- Prints the dominant sentiment.
- Visualization:
- Displays a bar graph of the detected emotions using matplotlib.


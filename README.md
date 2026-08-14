# Survey-sentiment-analysis
A rule-based Natural Language Processing project that analyzes survey responses using WordNet and SentiWordNet. The system calculates positive and negative sentiment scores and provides question and respondent level sentiment insights. 

The project focuses on:
- Text preprocessing
- Tokenization
- Bigram generation
- Sentiment scoring using SentiWordNet
- Bigram-based negation handling
- Question-wise sentiment analysis
- Respondent-wise sentiment analysis
- Data visualization

## Technologies Used
- Python
- Pandas
- NLTK
- WordNet
- SentiWordNet
- Matplotlib
- Jupyter Notebook

## Methodology
The sentiment analysis follows these steps:

1. Load the survey responses.
2. Convert text to lowercase.
3. Tokenize the responses into individual words.
4. Generate bigrams from consecutive words.
5. Use WordNet and SentiWordNet to obtain positive and negative sentiment scores.
6. Apply bigram-based handling for negation words such as "no", "not", and "never".
7. Calculate the overall sentiment score.
8. Perform question-wise and respondent-wise analysis.
9. Visualize the sentiment results.

## Sentiment Calculation
The system calculates an overall sentiment score using:

```text
Overall Score = Positive Score - Negative Score

```text
Overall Score = Positive Score - Negative Score

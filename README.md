
# Aspect Based Sentiment Analysis using Embeddings

### Blog Post [Article link](https://linktodocumentation)

---

The project plan for conducting aspect-based sentiment analysis on customer reviews is a comprehensive plan that involves several steps.

## Step 1: Obtaining a dataset

- Collect data using the Google Place API
- Dataset contains 109923 records and has no labeled output
- Data cleaning: remove null and duplicate comments, expand contractions, lowercase the reviews, remove digits and words containing digits, remove punctuations, and change emoticons with words

## Step 2: Performing data cleaning and feature extraction

- Analyze comments using various techniques, including word count and character count, box plot of word length, stop word counts, word cloud, unigram analysis, bigram analysis, trigram analysis, and polarity analysis

## Step 3: Creating models for aspect extraction, inference, and sentiment detection

- Aspect extraction model: hybrid model combining frequency-based and syntactic-relation based approaches
- Aspect inference model: uses pre-trained embeddings to infer the most appropriate aspect for each sentence of the comments
- Sentiment detection model: uses pre-trained BERT models to find the sentiment of a sentence and its corresponding aspect

## Step 4: Evaluating the models using various metrics

- Aspect extraction model: ability to extract all the semantically related aspects and eliminate all the irrelevant aspects
- Aspect inference model: ability to assign the closest aspect to the sentence if the similarity score is greater than the threshold
- Sentiment detection model: ability to calculate the sentiment of a sentence and its corresponding aspect accurately

## Step 5: Proposing future work

- Label some data with domain experts and use supervised learning-based approaches
- Supervised learning-based approach: use span-level interactions for aspect sentiment triplet extraction

## Step 6: Creating a DataStudio dashboard

- Showcase results of the analysis
- Includes several interactive features that allow the user to select a location ID and calculate each aspect’s average sentiment score

## Conclusion

Overall, the project plan provides a comprehensive approach for conducting aspect-based sentiment analysis on customer reviews. It involves several techniques and models that are designed to extract the most relevant information from the data and provide accurate results.



## Screenshots

![App Screenshot](https://github.com/adityaadarsh/aspect-based-sentiment-analysis/blob/main/screenshot/report.png)

![App Screenshot](https://github.com/adityaadarsh/aspect-based-sentiment-analysis/blob/main/screenshot/dasboard_homepage.png)


## Authors

- [@adityaadarsh](https://github.com/adityaadarsh)


# Zindi: Sentiment-Analysis_Tunisian-Arabizi
Can you classify sentiment in the Tunisian Arabizi dialect?

## Problem Statement
On social media, Arabic speakers tend to express themselves in their own local dialect. To do so, Tunisians use ‘Tunisian Arabizi’, where the Latin alphabet is supplemented with numbers. However, annotated datasets for Arabizi are limited; in fact, this challenge uses the only known Tunisian Arabizi dataset in existence.

Sentiment analysis relies on multiple word senses and cultural knowledge, and can be influenced by age, gender and socio-economic status.For this task, we have collected and annotated sentences from different social media platforms. The objective of this challenge is to, given a sentence, classify whether the sentence is of positive, negative, or neutral sentiment. For messages conveying both a positive and negative sentiment, whichever is the stronger sentiment should be chosen. Predict if the text would be considered positive, negative, or neutral (for an average user). This is a binary task.

Such solutions could be used by banking, insurance companies, or social media influencers to better understand and interpret a product’s audience and their reactions.

## Data Understanding
TUNIZI is the first 100% Tunisian Arabizi sentiment analysis dataset, developed as part of AI4D’s ongoing NLP project for African languages. Tunisian Arabizi is the representation of the Tunisian dialect written in Latin characters and numbers rather than Arabic letters.

iCompass gathered comments from social media platforms that express sentiment about popular topics. For this purpose, we extracted 100k comments using public streaming APIs.

Tunizi was preprocessed by removing links, emoji symbols, and punctuations.

The collected comments were manually annotated using an overall polarity: positive (1), negative (-1) and neutral (0). The annotators were diverse in gender, age and social background.

### Variable definition:

text_id: Unique identifier of the text
text: Text
label: Sentiment of the tweet (-1 for negative, 0 for neutral, 1 for positive)
Files available for download are:

### <a href="https://zindi.africa/competitions/ai4d-icompass-social-media-sentiment-analysis-for-tunisian-arabizi/data">Datasets</a>

Train.csv - contains text on which to train your model.
Test.csv - contains text on which you must classify using your trained model.
SampleSubmission.csv - is an example of what your submission file should look like. The order of the rows does not matter, but the names of the ID must be correct. Values in the 'label' column should -1, 0 or 1.


## Technologies Used
> Sklearn
> Nltk
> Keras
> Matplotlib
> Numpy
> Seaborn
> Python
> Jupyter Notebook

## Known Bugs.
{There are no known bugs}

## Support and contact details
{Any issues, questions, ideas, concerns or contributions to the code are highly encouraged. Contacts: paulmwaura254@gmail.com}

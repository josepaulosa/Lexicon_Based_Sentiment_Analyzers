<h3 align="center">Two lexicon-based sentiment analyzers: TextBlob and Vader</h3> 

> Reviews on a product, service, movie or texts about persons or events (political, social, etc.), are very important to get a clear picture of what the end users/general public think, namely, to understand what the reasons (key aspects/features) are for being satisfied or not with the purchase of a product or service, the reasons for liking or disliking a given movie or person, and so on. 
>
> **Sentiment analysis can help us gather insightful information regarding reviews/texts by deciphering what people like/dislike, what they want and what their major concerns are**.<br>

>There are mainly two approaches to extract the sentiment from given reviews/texts and classify the result as positive or negative: 
>- Lexicon Based Approach 
>- Machine Learning Approach  

&#8594; The lexicon-based approach is further divided into dictionary-based and corpus-based approaches.

> **TextBlob and Vader belong to the lexicon-based approaches and are dictionary-based sentiment analysis tools. A sentiment is defined by its semantic orientation and the intensity of each word in the sentence; this requires a pre-defined dictionary classifying negative and positive words**.

> - Textblob: when we use TextBlob to calculate the sentiment of a text, we get numeric values for polarity and subjectivity. 
Polarity is a float value within the range [-1.0, 1.0] and indicates how negative or positive the sentiment of a text is. 
Subjectivity, on the other hand, refers to how objective or subjective a text is; subjective sentences usually refer to personal opinions, emotions, or judgements, whereas objective sentences refer to facts. Subjectivity is also a float value within the range [0.0, 1.0], where 0.0 is very objective and 1.0 is very subjective.

> - Vader: produces four sentiment measurements (all floats):
>   - pos, neu and neg scores add up to 1 and show the proportion of text/content that falls into each of those three categories.
>   - Compound: aggregated score within the range [-1.0, 1.0], in which -1 shows the most negative sentiment and 1 the most positive sentiment.

&#8594; **While Vader is tailored for sentiments on social media, Textblob performs better with more formal language usage**.
- - - 
&#8594; The notebook addresses the sentiment analysis of the restaurant reviews from YELP dataset using the two lexicon-based sentiment analyzers mentioned above: TextBlob and Vader.
> - Tasks:
>     - Preprocessing
>     - Sentiment Analysis with TextBlob (including computing the top 20 most common words in positive reviews and in negative reviews) with comments/conclusions
>     - Sentiment Analysis with Vader with comments/conclusions
>     - Final conclusions: compare the performance of both sentiment analyzers

- - - 
- **The two datasets (review and business) that we need from YELP dataset can be found** → [here](https://www.yelp.com/dataset)
- For an interactive preview &rarr; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/josepaulosa/NLP_Sentiment_Analysis/blob/main/BERT.ipynb)

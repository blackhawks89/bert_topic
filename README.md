# bert_topic
lead_squared
There are two keys aspects we are looking from reviews text

- Key topics from set of reviews
- apart from just key topics contextual similarity of these reviws and hence the key topics within same context


the Attention Mechanism addresses the issue of emphasing of contextual importance of a word in different sentences.

BERT is the first popular model comes to our mind thinking of above problems hence we will use the pre trained BERT model to extract meaningful topics as required and we shall do it in following key steps

- Preprocess and clean the data using regex
- get bert topics using pre trained Model
- Extract top n keywords(2-3 grams)

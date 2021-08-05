Tweet Sentiment Extraction --

>> Extract support phrases for sentiment labels
>> construct a model that can look at the labeled sentiment for a given tweet and figure out what word or phrase best supports it.
>> What words in tweets support a positive, negative, or neutral sentiment? How can you help make that determination using machine learning tools?

format of solution --
>> predict the string that best supports the sentiment for the tweet in question.
>> example --
	textID,selected_text
	2,"very good"
	5,"I don't care"
	6,"bad"
	8,"it was, yes"

Evaluation metric  --
>> The evaluation metric is the word-level Jaccard score.
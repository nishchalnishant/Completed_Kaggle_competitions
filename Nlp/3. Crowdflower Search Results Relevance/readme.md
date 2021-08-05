Crowdflower Search Results Relevance --

goal of this competition is to create an open-source model that can be used to measure the relevance of search results.
this will help in enabeling small business owners to match the experience provided by more resource rich competitors .
it will also provide more established businesse a model to test against.
Given the queries and resulting product descriptions from leading eCommerce sites, this competition asks you to evaluate the accuracy of their search algorithms.

what is what --

search algorithms -- 
>> algorithms in search engine which are used to search the web.


format of solution --
>> Results have 4 possible ratings, 1,2,3,4. 
should contain the predicted probability that a question is in each of the five classes. 
>> each row should sum to 1 (if the rows aren't normalized as submitted
>> example --
	id,prediction
	1,3
	3,2
	4,1
	5,4

Evaluation metric  --
>> The evaluation metric is quadratic weighted kappa, which measures the agreement between two ratings. >> This metric typically varies from 0 (random agreement between raters) to 1 (complete agreement between raters).
>> In the event that there is less agreement between the raters than expected by chance, the metric may go below 0. 
>> The quadratic weighted kappa is calculated between the scores assigned by the human rater and the predicted scores.
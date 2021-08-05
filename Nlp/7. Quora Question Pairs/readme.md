Quora Question Pairs --

>> identify question pairs that have the same intent?
>> Currently, Quora uses a Random Forest model to identify duplicate questions.
>> tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. 

what is what --

Quora -- 
>> place to gain and share knowledge—about anything. 
>> It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. 
>> This empowers people to learn from each other and to better understand the world.

canonical questions -- 
>>  broad question/answer pair that is intended to be a duplicate target for commonly asked questions, or address a commonly found problem (for Meta Stack Overflow). 


format of solution --
>>predict the probability that the questions are duplicates (a number between 0 and 1)
should contain the predicted probability that a question is in each of the five classes. 
>> each row should sum to 1 (if the rows aren't normalized as submitted
>> example --
	test_id,is_duplicate
	0,0.5
	1,0.4
	2,0.9

Evaluation metric  --
>> The evaluation metric is log loss between the predicted values and the ground truth.
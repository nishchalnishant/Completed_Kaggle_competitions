Predict Closed Questions on Stack Overflow --

>> Detect toxic content to improve online conversations
>> develop models that identify and flag insincere questions. 


format of solution --
>> predict whether the corresponding question_text is insincere (1) or not (0).
>> Predictions should only be the integers 0 or 1
>> each row should sum to 1 (if the rows aren't normalized as submitted
>> example --
	qid,prediction
	0000163e3ea7c7a74cd7,0
	00002bd4fb5d505b9161,0
	00007756b4a147d2b0b3,0


Evaluation metric  --
>> The evaluation metric is F1 Score between the predicted and the observed targets.
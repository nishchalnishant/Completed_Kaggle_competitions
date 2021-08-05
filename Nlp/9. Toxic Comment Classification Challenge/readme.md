Toxic Comment Classification Challenge--

>> Identify and classify toxic online comments
>> build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. 

format of solution --
>> you must predict a probability for each of the six possible types of comment toxicity (toxic, severetoxic, obscene, threat, insult, identityhate).
>> example --
	id,toxic,severe_toxic,obscene,threat,insult,identity_hate
	00001cee341fdb12,0.5,0.5,0.5,0.5,0.5,0.5
	0000247867823ef7,0.5,0.5,0.5,0.5,0.5,0.5

Evaluation metric  --
>> The evaluation metric is evaluated on the mean column-wise ROC AUC.
>> score is the average of the individual AUCs of each predicted column.
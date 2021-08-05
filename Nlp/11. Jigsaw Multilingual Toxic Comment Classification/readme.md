Use TPUs to identify toxicity comments across multiple languages --

>> Develop strategies to build effective multilingual models and you'll help Conversation AI and the entire industry realize that potential.
>> extension of previous 2 competitons 
	2018 Toxic Comment Classification Challenge,
		built multi-headed models to recognize toxicity and several subtypes of toxicity. 
	2019 Unintended Bias in Toxicity Classification Challenge
		worked to build toxicity models that operate fairly across a diverse range of conversations. 

what is what --

toxicity 
>> anything rude, disrespectful or otherwise likely to make someone leave a discussion. 


format of solution --
>> predict a probability for the toxic variable.
>> example --
	id,toxic
	0,0.5
	1,1
	2,0
	3,0.5
	4,0.75	
	5,0.5
	6,1
	7,0.5
	8,0

Evaluation metric  --
>> The evaluation metric is evaluated on area under the ROC curve between the predicted probability and the observed target.
Predict Closed Questions on Stack Overflow --

>> goal is to build a classifier that predicts whether or not a question will be closed given the question as submitted, along with the reason that the question was closed.  
>> Additional data about the user at question creation time is also available.

what is what --

stack overflow -- 
>> programmers use Stack Overflow website to get high quality answers to their programming questions.
>> these answers are submitted by other programmers.

Closing Questions -- 
>> question which is answered by none. 
>> currently 6% of new question end up closing.

there can be many reason for closing of a question --
>> off topic
>> not constructive
>> not a real question
>> too localized.

format of solution --
>> produce a probability (between 0 and 1) of a given question not being closed and the probabilities of being closed as each of the four close reasons.
should contain the predicted probability that a question is in each of the five classes. 
>> each row should sum to 1 (if the rows aren't normalized as submitted
>> example --
	id,not a real question,not constructive,off topic,open,too localized
	11768878,0.05,0.05,0.05,0.8,0.05
	11768880,0.73,0.05,0.01,0.20,0.02
	11803678,0.02,0.03,0.01,0.75,0.19
	11803496,0.01,0.02,0.83,0.12,0.02

Evaluation metric  --
>> The evaluation metric is Multiclass Logarithmic Loss.
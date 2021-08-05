Predict Closed Questions on Stack Overflow --

>> goal is to predict short and long answer responses to real questions about Wikipedia articles.

what is what --

TensorFlow -- 
>>  open source platform for machine learning. With TensorFlow 2.0
>> tf.keras is the preferred high-level API for TensorFlow, to make model building easier and more intuitive. 

QA systems -- 
>> emulate how people look for information by reading the web to return answers to common questions. >> Machine learning can be used to improve the accuracy of these answers.

format of solution --
>> There may be up to five labels for long answers, and more for short. If no answer applies, leave the prediction blank/null.
>> metric in this competition diverges from the original metric in two key respects: 1) short and long answer formats do not receive separate scores, but are instead combined into a micro F1 score across both formats, and 2) this competition's metric does not use confidence scores to find an optimal threshold for predictions.
>> TP = the predicted indices match one of the possible ground truth indices
>> FP = the predicted indices do NOT match one of the possible ground truth indices, OR a prediction has been made where no ground truth exists
>> FN = no prediction has been made where a ground truth exists
>> example --
	-7853356005143141653_long,6:18
	-7853356005143141653_short,YES
	-545833482873225036_long,105:200
	-545833482873225036_short,
	-6998273848279890840_long,
	-6998273848279890840_short,NO

Evaluation metric  --
>> The evaluation metric is evaluated using micro F1 between the predicted and expected answers.
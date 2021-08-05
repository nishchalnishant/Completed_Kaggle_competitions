StumbleUpon Evergreen Classification Challenge --

>>mission is to build a classifier which will evaluate a large set of URLs and label them as either evergreen or ephemeral.

what is what --

StumbleUpon -- 
>> user-curated web content discovery engine that recommends relevant, high quality pages and media to its users, based on their interests.
>> some pages we recommend, such as news articles or seasonal recipes, are only relevant for a short period of time, others maintain a timeless quality and can be recommended to users long after they are discovered.
>> based on ratings form the community.

ephemeral -- 
>> pages which are no longer relevant.

evergreen --
>> pages which will always be in trend.

format of solution --
>> Each line of your submission should contain an urlid and a label.
should contain the predicted probability that a question is in each of the five classes. 
>> you may submit any real-valued number as a prediction, since AUC is only sensitive to the ranking.
>> example --
	urlid,label
	5865,0
	782,0
	6962,0

Evaluation metric  --
>> The evaluation metric is area under the ROC curve.
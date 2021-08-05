Cdiscount’s Image Classification Challenge --

>> Categorize e-commerce photos.
>> building a model that automatically classifies the products based on their images.
>> The data set Cdiscount.com is making available is unique and characterized by superlative numbers in several ways:

Almost 9 million products: half of the current catalogue
More than 15 million images at 180x180 resolution
More than 5000 categories: yes this is quite an extreme multi-class classification!

what is what ---
Cdiscount.com 
>> generated nearly 3 billion euros last year, making it France’s largest non-food e-commerce company.
>> applies machine learning algorithms to the text description of the products in order to automatically predict their category. As these methods now seem close to their maximum potential, 

format of solution --
>>  you must predict a category_id.
>> predict the category of a product based on its image(s).
>> example --
	_id,category_id
	2,1000000055
	5,1000016018
	6,1000016055

Evaluation metric  --
>> The evaluation metric is evaluated  on the categorization accuracy of your predictions (the percentage of products you get correct).
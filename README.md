# food_vision_101
<ul>
<li>project to help classify 101 different foods based on their image</li>
<li>the data was a part of tensorflow_datasets library</li>
<li>after performing some basic data analysis and understanding the data</li>
<li>we preprocess it so that all the images are of the same size
and we also use the tf.data module to pipeline the loading of data so that it is done
 efficiently</li>
<li>then we set up mixed presion training</li>
<li>it is a technique were the type of the input data which is usually float32
	dips to float16 when being used by the model to find errors and update weights
	so that it can run the epochs at almost 2X the speed</li>
<li>we have also used the efficientnetB0 transfered learning model to reach higher accuracies
as from previous experiences i learnt that building a model layer by layer from scratch
usually isnt that good wen predicting and require more layers of neurons and higher no
of epochs to reach a certain level of accuracy which was a waste of resorces</li>
</ul>

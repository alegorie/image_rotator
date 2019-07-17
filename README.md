# image_rotator
NN solving the task: of turning image of right orientation - upright, rotated_left, rotated_right, or upside_down



Image rotator
(deep-learning computer vision task)
///Before you start reading, open Notebook and follow comments as well///
First of all I tried to analyse data, if format is correct and so on. For this purpose I was using pandas. As it was written in task, there were two columns of names and labels of images. 
So next step was data preparation. I could use function in eval.py but I decided to declare dict of labeled names. After that I have started preparing my dataset for training. To do this I had to separate images into different folders (by label).
	Then randomly choosing them, I created array with train data, which I divided into two datasets (train+test).
	After data preparation I started creating neural network model following Keras documentation. After finishing setting of all the parameters I began training of model. After 10 epochs I had 98% accuracy on train data and 96% on test data. Saving model.
	Next step was prediction on test data and saving it to .csv-file for submission as shown in example.
	I also created function who rotates images as they should be turned. And saved as .png file.
	Last step was creating numpy-file of correctly turned images.



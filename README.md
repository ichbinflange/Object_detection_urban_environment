# Object_detection_urban_environment
final project udacity

#PROJECT OVERVIEW

Object detection udacity final project using waymo dataset


The training was done with two experiments before and after augmentation was added.
The object detection was carried out on 3 image classes vehicles,pedestrians and cyclists
![Alt text](results/eda.PNG?raw=true "datavisualization")

A barchart was used to show the distribution of the the three classes with respect to their total count

![Alt text](results/chart.PNG?raw=true "Data visualization")

The augmentation were choosen specifically to handle absurb camera conditions
such as occlusion, noise or even particles at the surface of the camera hence 
random brightness,contrast,saturation, and color distortion were used for the 
training.
![Alt text](results/aug.png?raw=true "augmented image brightness on night image")
![Alt text](results/aug1.png?raw=true "color distortion")
![Alt text](results/aug3.png?raw=true "brightness")
![Alt text](results/aug4.png?raw=true "contrast")

After training and evaluating, the train and evaluation events were too large for project submission hence were removed,
The training was done using 2000 steps and from the evaluation on the tensorboard it can be seen that the loss was slowly 
converging and a little difference between the training and evaluation loss was observed.
![Alt text](results/Screenshot(344).png?raw=true "Training loss")
![Alt text](results/Screenshot(352).png?raw=true "Evaluation loss")
![Alt text](results/Screenshot(353).png?raw=true "Evaluation")
the trained model was saved and exported for inference therefore saved model was used for inference.
The inference video is shown below



![](results/animation.gif)

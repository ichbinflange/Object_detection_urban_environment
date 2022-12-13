# Object_detection_urban_environment
final project udacity

#PROJECT OVERVIEW

Object detection udacity final project using waymo dataset


The training was done with two experiments before and after augmentation was added.
The augmentation were choosen specifically to handle absurb camera conditions
such as occlusion, noise or even particles at the surface of the camera hence 
random brightness,contrast,saturation, and color distortion were used for the 
training

After training and evaluating, the train and evaluation events were too large for project submission hence were removed,
the trained model was saved and exported for inference therefore saved model was used for inference

The ffolder results contains all results from training,evalaution and inference. The two pythong scripts Exploratory Data Analysis.ipynb
and Explore_augmentations.ipynb contain results for tasks described in the scripts



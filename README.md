#### **Overview** 
This repository contains the instructions to build a traffic light classification and detection pipeline, which is to be integrated into the final capstone project of the [Udacity Self Driving Car Nanodegree program](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).

For training the traffic light classifier model, a basic version of [google colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) is used in this work. Google colab offers a free GPU access to users up to 15GB RAM. Additionally, users can gain extra GPU memory up to 25GB on purchasing an account in [Colab Pro](https://colab.research.google.com/signup). 

The repository contains a jupyter notebook [TL_Classifier_simulator.ipynb](https://github.com/saikrishnachada/Traffic-Light-Classification-and-Detection/blob/master/TL_Classifier_simulator.ipynb), which uses the tensorflow object detection API to train a model on camera images obtained from the udacity simulator. The main goal is to classify the traffic light states into three categories: green, yellow and red based on the input images. 

The trained model is then evaluated on test images and the code is given in [TL_Detection.ipynb](https://github.com/saikrishnachada/Traffic-Light-Classification-and-Detection/blob/master/TL_Detection.ipynb).

##### Datasets:   
Both training and evaluation datasets of [this repo](https://github.com/marcomarasca/SDCND-Traffic-Light-Detection) have been used to train and evaluate the model.    
[train.record](https://drive.google.com/file/d/1-glmsZA6CwjnsAJXtPJelMwLFNlNAK2V/view?usp=sharing)  
[eval.record](https://drive.google.com/file/d/14552KT0s9W34DIvi9dlGanCLPhra2_XB/view?usp=sharing)

##### Label file used:  
[label_map_simulator.pbtxt](https://drive.google.com/file/d/13Xbq_XHqHSJmB-uFLFBh0gkhg7X1CriJ/view?usp=sharing)

##### Configuration file used:  
[ssd_inception_v2_coco_simulator.config](https://drive.google.com/file/d/1GhfaMRBEdUc-8ViO7t_she8c2EUGU3G_/view?usp=sharing)

##### Trained model: 
[frozen_inference_graph.pb](https://drive.google.com/file/d/11gUJkJnwAqdFu5LlCnm3FPj727XdAM7R/view?usp=sharing)

<!--- Upload the dataset, label and config files to google drive and their respective file IDs are copied and used in the [TL_Classifier.ipynb](https://github.com/saikrishnachada/Traffic-Light-Classification-and-Detection/blob/master/TL_Classifier.ipynb).  
train_file_id = '1orq0y-8GtfOWl1tBko03rSZT7b3sVfBf'   
eval_file_id = '18nLlxkdJtwfbOaFvpdLhJXrknfzwNNKw'  
pbtxt_file_id = '1Dgz6t1fTvhNaxrmfXaPFB4-BYG6XVVXd'  
config_file_id = '15PYisbZr1tzcEJQtI6Z-qtlhWZysHIuP'  

##### Datasets:   
Both training and evaluation datasets of [this repo](https://github.com/ilopezfr/Traffic_Light_Detection) have been used to train and evaluate the model.    
[mixed_train.record](https://drive.google.com/file/d/1orq0y-8GtfOWl1tBko03rSZT7b3sVfBf/view)  
[mixed_eval.record](https://drive.google.com/file/d/18nLlxkdJtwfbOaFvpdLhJXrknfzwNNKw/view)

##### Label file used:  
[udacity_label_map.pbtxt](https://drive.google.com/drive/u/0/folders/1ilXi4lO3f1hP6gFBtwYhYb8taEefdoYq)

##### Configuration file used:  
[ssd_inception_v2_coco_udacity.config](https://drive.google.com/file/d/15PYisbZr1tzcEJQtI6Z-qtlhWZysHIuP/view)
-->

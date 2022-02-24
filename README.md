# Computer_Vision_Project---Automated-Pathology-Detection-for-Medical-Images

### The goal is to design models and methods to predictively detect pathological images and explain the pathology sites in the image data.

### Data for this project is taken from a Kaggle contest: https://www.kaggle.com/c/vietai-advance-course-retinal-disease-detection/overview

#### Explanation of the data set: The training data set contains 3435 retinal images that represent multiple pathological disorders. The patholgy classes and corresponding labels are included in the 'train.csv' file and each image can have more than one class category (multiple pathologies). The labels for each image are

#### -opacity (0) 
#### -diabetic retinopathy (1)
#### -glaucoma (2)
#### -macular edema (3)
#### -macular degeneration (4)
#### -retinal vascular occlusion (5)
#### -normal (6)

#### Task 1: Built a classification model for Diabetic Retinopathy and Glaucoma vs normal images.

#### Task 2: Generated the heatmaps using any using Grad-CAM method to demonstrate what regions of interest are contributing to Diabetic Retinopathy and Glaucoma, respectively.

#### Task 3: Using the unlabelled data set in the 'test' folder augmented the training data (semi-supervised learning) and reported the variation in classification performance on the unseen test data set.

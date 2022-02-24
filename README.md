# Computer_Vision_Project---Automated-Pathology-Detection-for-Medical-Images

### The goal is to design AI model to detect pathological images and explain the pathology sites in the image data.

### Data for this project is taken from a Kaggle contest: https://www.kaggle.com/c/vietai-advance-course-retinal-disease-detection/overview

#### Explanation of the data set: The training data set contains 3435 retinal images that represent multiple pathological disorders. The patholgy classes and corresponding labels are included in the 'train.csv' file and each image can have more than one class category (multiple pathologies). The labels for each image are

#### -opacity (0) 
#### -diabetic retinopathy (1)
#### -glaucoma (2)
#### -macular edema (3)
#### -macular degeneration (4)
#### -retinal vascular occlusion (5)
#### -normal (6)

#### •	Data for this project is taken from a Kaggle contest. 
#### •	Built a classification model for Diabetic Retinopathy and Glaucoma vs normal images.
#### •	Visualized the heatmaps/features using GRD-CAM method to demonstrate what regions of interest contribute to Diabetic Retinopathy and Glaucoma, respectively.
#### •	Semi-supervised learning was performed to label the unlabeled test data and reported the variation in classification performance on the augmented data.

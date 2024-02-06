Melanoma-CNN-Prediction Problem Statement In this assignment, you will
build a multiclass classification model using a custom convolutional
neural network in tensorflow.

Problem statement: To build a CNN based model which can accurately
detect melanoma. Melanoma is a type of cancer that can be deadly if not
detected early. It accounts for 75% of skin cancer deaths. A solution
which can evaluate images and alert the dermatologists about the
presence of melanoma has the potential to reduce a lot of manual effort
needed in diagnosis. The dataset consists of 2357 images of malignant
and benign oncological diseases, which were formed from the
International Skin Imaging Collaboration (ISIC). All images were sorted
according to the classification taken with ISIC, and all subsets were
divided into the same number of images, with the exception of melanomas
and moles, whose images are slightly dominant. The data set contains the
following diseases:

Actinic keratosis Basal cell carcinoma Dermatofibroma Melanoma Nevus
Pigmented benign keratosis Seborrheic keratosis Squamous cell carcinoma
Vascular lesion

Data Acquisition and Understanding: Begin by accessing and comprehending
the dataset, which contains 2357 images of various oncological diseases,
including melanoma, sorted from the International Skin Imaging
Collaboration (ISIC). Each disease category has a comparable number of
images, with melanomas and moles slightly outnumbering others.

Dataset Preparation: Create train and validation datasets from the
provided images directory, ensuring a batch size of 32 and resizing
images to 180x180 pixels.

Data Visualization: Develop a code snippet to visually represent one
instance from each of the nine disease classes present in the dataset.

Model Construction and Training: Construct a custom Convolutional Neural
Network (CNN) capable of accurately classifying the nine disease
classes. Normalize pixel values to fall within the range (0,1) while
building the model. Select an appropriate optimizer and loss function
for training and train the model for approximately 20 epochs.

Evaluation and Analysis: After model fitting, analyze for signs of
overfitting or underfitting and provide insights into the model\'s
performance.

Data Augmentation: Implement a suitable data augmentation strategy to
address any observed underfitting or overfitting issues.

Model Refinement and Retraining: Rebuild and retrain the CNN model using
the augmented dataset, adhering to the same normalization, optimization,
and training parameters. Again, assess the model\'s performance and
determine if previous issues persist or are alleviated.

Class Distribution Examination: Investigate the distribution of classes
within the training dataset, identifying any imbalances.

Imbalance Resolution: Utilize the Augmentor library to rectify any class
imbalances present in the training dataset.

Final Model Training: Reconstruct and train the CNN model using the
rectified class-balanced data, maintaining the normalization,
optimization, and training settings. Extend the training duration to
around 30 epochs.

Evaluation of Final Model: Assess the model\'s performance
post-training, noting any improvements or persisting issues compared to
earlier iterations.

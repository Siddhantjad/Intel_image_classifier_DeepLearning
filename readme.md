 Intel Image Classification CNN model with transfer Learning with Deployment
 
 ![image](https://user-images.githubusercontent.com/90169527/153900910-6ba30231-37f8-4e14-a3a2-c57eb3d3283e.png)

 
The model was deployed on Heruko with help of Flask app
 Deployed App link - https://intel-image-classify.herokuapp.com/
 
 
 Here i trained the Convolution Neural Network with Intel image dataset having 6 classes namely: 
1. Mountain
2. Sea 
3. Glacier, 
4. Forest, 
5. Street, 
6. Buildings

DataSet was downloaded from Kaggle.com 
link to Dataset - https://www.kaggle.com/puneet6060/intel-image-classification


First I trained the model in CNN with tensorflow  which gave the accuracy of 85%.
CNN_Trained_model.ipynb            
is code for trained model -https://github.com/Siddhantjad/Intel_image_classifier_DeepLearning/blob/main/CNN_Trained_model.ipynb

Then used the Transfer learning model VGG16 to train model which gave the accuracy of 99% on validation data.
Transfer_learning_VGG16_model.ipynb  
is a code of Transfer learning-  https://github.com/Siddhantjad/Intel_image_classifier_DeepLearning/blob/main/Transfer_learning_VGG16_model.ipynb


STEPS FOLLOWED FOR MODEL TRAINING:
1. libraries was imported
2. Data was downloaded to dir with keras.ImageFlowFromDirectory()
3. image Scaling and Normalization was done.
4. image Augmentation was done, with keras.ImageDataGenerator()
5. Model was trained and saved as intel_model.h5 file
6. App Deployed on Heruko link- https://intel-image-classify.herokuapp.com/



https://user-images.githubusercontent.com/90169527/154010865-ffa6ee90-6529-42b5-91f3-796b12bd32fe.mp4



![1_Y1y83HN7oI98EJT3LQgv-g](https://user-images.githubusercontent.com/90169527/153884075-d23112c9-a327-4b76-a1f4-0d033c392140.png)

SCOPE:
Image Classification app can be used for classification of images.

CONCLUSION:
Image Scaling, Normalisation and Augmentaion is important step in training CNN model
Transfer learning VGG16 pretrained model was selected for deployment with accuracy of 99%.


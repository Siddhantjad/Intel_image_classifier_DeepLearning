 Intel Image Classification CNN model with transfer Learning
 
 ![Screenshot (32)](https://user-images.githubusercontent.com/90169527/153885899-0f199b8e-e9ac-4188-8e4b-3a818640d374.png)
 
 
 Here i trained the Convolution Neural Network with Intel image dataset having 6 classes namely: 
1. Mountain
2. Sea 
3. Glacier, 
4. Forest, 
5. Street, 
6. Buildings

DataSet was downloaded from Kaggle.com 


First I trained the model in CNN with tensorflow  which gave the accuracy of 85%.

   CNN_Trained_model.ipynb            is code for trained model - https://github.com/Siddhantjad/Intel_image_classifier_DeepLearning/blob/main/CNN_Trained_model.ipynb

Then used the Transfer learning model VGG16 to train model which gave the accuracy of 99% on validation data.

   Transfer_learning_VGG16_model.ipynb            is a code of Transfer learning-  https://github.com/Siddhantjad/Intel_image_classifier_DeepLearning/blob/main/Transfer_learning_VGG16_model.ipynb


The model was deployed on Heruko with help of Flask app
 Deployed App link - https://intel-image-classify.herokuapp.com/

![1_Y1y83HN7oI98EJT3LQgv-g](https://user-images.githubusercontent.com/90169527/153884075-d23112c9-a327-4b76-a1f4-0d033c392140.png)



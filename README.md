# Handwritten-Digit-Recogniser

MNIST Handwritten Digits dataset is used for training and testing the model.<br>
The zip-file contains the datasets in csv format.<br>
The model uses knn-classifier to classify digits(0-9)<br><br>
1. main1:<br>
   i) For feature engineering, I have used Keras' ImageDataGenerator to augment the images.<br>
      Parameters-Used: rotation_range, height_shift_range, zoom_range, shear_range.<br>
   ii) Here i haven't calculated accuracy score. Just visual verification.<br><br>
2. main2:<br>
   i) I have used k as 3, as model was more accurate for k=3.<br>
   ii) Accuracy is around 96.9%
   iii) Furthermore, I applied PCA, but it negatively affected the accuracy.<br>
Thankyou (^_^)

# Face-Mask-Detection---CNN
----------------------------------------------
The Dataset contains images of people wearing masks and people not wearing masks. The database contains 10000 colored images in the training folder, 800 images in the validation folder, and 992 images in the test folder. To create a CNN model for identifying whether a person in the image is wearing a mask or not.
----------------------------------------------
----------------------------------------------
Perform the following tasks:
----------------------------------------------
 - Create test, train, and validation directory variables
 - Create train and validation data generator with target size (128,128)
 - Train a CNN model
----------------------------------------------
----------------------------------------------

![image](https://user-images.githubusercontent.com/68370376/135508651-06222309-861a-46be-8359-191cf993bba4.png)

![image](https://user-images.githubusercontent.com/68370376/135508688-fa032310-9d8d-4c4b-baf6-2298ae3970bb.png)

![image](https://user-images.githubusercontent.com/68370376/135508730-2a9b0763-0d95-4ab2-9d82-24be195f9139.png)

![image](https://user-images.githubusercontent.com/68370376/135508772-bd900007-cb88-452d-adf8-4f118db5e285.png)

![image](https://user-images.githubusercontent.com/68370376/135508819-7f072cc7-6162-484a-ab51-e6d3ac3cfa7d.png)

![image](https://user-images.githubusercontent.com/68370376/135508857-5f3a0f53-2a75-4484-b99a-6b63b8838f33.png)

Observation : there is no such  difference between training_acc and validation_acc, val_acc oscilating around 98%, train_acc oscilating around 99% and increasing with each epoch. Graph shows there is no Overfitting in the model

After testing on test dataset :
Accuracy --> 0.9879

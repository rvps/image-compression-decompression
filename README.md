# project

Model is trained on https://www.kaggle.com/nikhilpandey360/chest-xray-masks-and-labels dataset.

We have preprocessed the data by running 'preprocess.py'.
It will convert all images into specific dimensions.

'train/*' means all training images are placed in the 'train' folder.

For training the model,we have converted the dataset into .h5 file.
To convert into .h5 file, I have uploaded createh5.py file.

Pretrained Model -
  https://drive.google.com/file/d/1RDoVQmxNbJESOBkmXH6T_3T811Zq0K2s/view?usp=sharing
  
After training the model download the checkpoint and save it in the directory where app.py is stored.

Run command -
  python app.py
  
Go to browser and type http://localhost:5000/  to get the view of the system.

For uploading image you should upload the preproccesed image only.

Output image will be stored in the 'output' folder.

Hope you will enjoy it!!!


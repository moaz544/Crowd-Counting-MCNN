data set:https://www.kaggle.com/tthien/shanghaitech


# Crowd-Counting-MCNN
This notebook aims to develop a machine learning model for crowd number estimation from a single image at random crowd density and arbitrary perspective. We have proposed a multi- column convolutional neural network (MCNN) architecture to map Image of a crowd density map. MCNN allows the input image to be of any size or resolution. through the use of filters with receptive fields of different sizes, And also, regardless of the size of the people. Moreover, the true density map is calculated precisely based on engineering adaptation kernels. We have collected and classified a group of 300 images and created a data Augmentation of images, bringing the training data to 2439 images and verification data of 261 images, we are conducting extensive trials to verify the effectiveness of the proposed model and method. In particular, with the proposed simple MCNN model, our method It beats all existing styles. In addition to the experiments Show that our model, once trained on it. show that our model, once trained on one dataset, can be readily transferred to a new dataset
![download](https://user-images.githubusercontent.com/73136710/108855542-c9508e80-75f1-11eb-978b-08cda53e8d56.png)
![2021-02-23_161335](https://user-images.githubusercontent.com/73136710/108855885-20eefa00-75f2-11eb-899b-66dc952dd76b.png)

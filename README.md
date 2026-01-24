# Ball Image Classifier
An image classifier model that distinguishes nine different ball types used in nine sports.
## Image Dataset
Download [here](https://drive.google.com/drive/folders/1hB3zzjvQc3nrz2_TAo_ptPs9YznYEIzr?usp=drive_link). Then put the `ball-images` folder at the root of this repository.

The nine subfolders are taken from this dataset on Kaggle:
https://www.kaggle.com/datasets/dimensi0n/imagenet-256
## Personal note
In this commit, the code trains a model with the test accuracy is around 65%. I will try to improve the accuracy to above 70% or even 80%. Perhaps I will try implementing data augmentation, k-fold cross validation and global average pooling in the future.

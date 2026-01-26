# Ball Image Classifier
An image classifier model that distinguishes nine different ball types used in nine sports.
## Image Dataset
Download [here](https://drive.google.com/drive/folders/1hB3zzjvQc3nrz2_TAo_ptPs9YznYEIzr?usp=drive_link). Then put the `ball-images` folder at the root of this repository.

The nine subfolders are taken from this dataset on Kaggle:
https://www.kaggle.com/datasets/dimensi0n/imagenet-256
## Personal note
In this commit, I added three more ball types to the dataset. Initially, the test accuracy is only around 55%. After implementing data augmentation, K-fold cross validation and global average pooling, the model performs a little better, with the test accuracy around 60%. I will try to improve the accuracy to above 70% or even 80%. Maybe I will try modifying the CNN structure a little bit and try more hyperparameter values (e.g. learning rate, num epochs,...).

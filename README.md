# Spot-the-mask-challenge-ZindiWeekendz

Can you predict whether a person in an image is wearing a face mask? #masks4all

The data have been split into a test and training set. The training set contains ~1300 images and the test set contains 509 images. There are two types of images in this dataset, people or images with face masks and people or images without.

Your task is to provide the probability that an image contains at least one mask. For each unique image ID you should estimate the likelihood that the image contains at least one mask, with an estimated probability value between 0 and 1.

The files you have for download here are:

images.zip (~193mb): zip file containing all the images, train and test images. You will need to use train_labels.csv to split the data into the train and test sets.
train_labels.csv: This is the list of images in the train set, 1 indicates an image with a person with a mask, 0 indicates a person without a mask.
sample_submission.csv: is an example of what your submission file should look like, including a list of unique image IDs. Your submission file should have all of the Image IDs in this file along with estimates of the corresponding probabilities of observing a person with a mask.

Dataset Link: https://zindi.africa/competitions/zindiweekendz-learning-spot-the-mask-challenge/data

Leaderboard Position-10

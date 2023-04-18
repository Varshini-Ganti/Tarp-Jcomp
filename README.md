# Tarp-Jcomp
This code represents our work for the j-component for subject CSE1901 - Techincal Answers For Real World Problems. 
We developed Prooduct detection model for products placed in Grocery store shelves using image processing.
We tried 3 algorithms like YOLOv3, TFOD API and SIFT algorithms to find out the best algorithm 
SIFT algorithm worked best for our project. 
It has 3 stages: In the first stage we will detect different products; in the next stage we will detect multiple products when kept together in the same rack and in the last stage we detect different products which are placed in different racls of same shelf.
We are using SIFT(Scale-Invariant Feature Transform) algorithm to extract the features of an image and FLANN(Fast Library for Approximate Nearest Neighbors) Matcher with KNN to match the extracted features of sifferent products

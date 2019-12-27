# Character_digit_recognition-task
All predictions are done using SVM model trained.
You are given a dataset containing 28x28 grayscale images. Each image is either a handwritten letter or digit. The dataset can be downloaded from here: https://drive.google.com/file/d/12OYCKGQp1VybvLM157ioLU4Bjt7PWpt-/
Format of dataset: The dataset is well-balanced and contains 47 classes, as described (10 digits, 26 capital letters and 11 small letters). The dataset is present as a CSV file. You’ll find two CSV files: Train-set and Test-set. Supposed to train only using the train-set and use test-set only for calculating accuracy.
Number of samples: Train set	: 112,800	(2400 images per class), Test set	: 18,800	(  400 images per class)
CSV format:Each line in the csv file corresponds to 1 sample. Each line will contain 785 values. The first value in all lines indicate the label ID, and the remaining 784 values corresponds to the individual pixel values of the 28*28 image (serialized in column-major order)
The ASCII value of each label ID can be found in the mapping.txt file. For example, a label ID of 10 has an ASCII value of 65, which means that it corresponds to the character ‘A’.
Supposed to use all the train samples (lines) to complete the following tasks:
Task 1: Letter/Digit Classifier (Easy)--Given an image, you must be able to classify whether the image is a letter or a digit. Expected outcome:  You are expected to use a ML-based model to solve the problem with a reasonably high accuracy.
Task 2: Vowel/Consonant and Even/Odd Classifier (Moderate)--Given an image, you are supposed to design model(s) which does the following: 1) If the image is a letter, you are supposed to predict if it is a vowel or consonant. 2) If the image is a digit, you are supposed to predict if it is an even or odd number.
Task 3: Character Classifier--Given an image, you are supposed to predict what digit or letter the image contains. That is, you will be doing a classification task for 47 classes.

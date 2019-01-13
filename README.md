# Facial-Exp-recognition
The dataset used for this is [FERC-2103](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)
<br>
>
**To run this on a machine:**

Install tensorflow

Install keras

Install numpy

Install scikit learn

And run the file

Or

Run the file on Google colab with gpu support

For that train.csv and test.csv should be saved in your google drive and the links to them should be inserted in the proper position in code.

For usage on local server remove the first and last cell update the file paths.

File loading model can be used to run testing part only on a already trained model.

**Architectures of CNN used**

Conv = convolution layer

FC= fully connected layer

Maxpool = maxpooling layer

Dropouts = 0.5 (in both the fully connected layers)

No of epochs = 100

Batch size = 256

Optimizer = Stochastic Gradient descent

Momentum = 0.9

Steps:

1. Data Preprocessing and Normalization:

Divide the pixel values by 255 to normalize



2. Data Augmentation:

  Mirroring the images

  Random rotation in the range of -45 to 45 degrees

  Set the mean of the images to 0

3. Split the train.csv into train and validation sets

4. Run the CNN model on the training set

5. Plot the loss curve and accuracy curve

6. Test with the public test

7. Print the results table.

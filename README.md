# COVID-19_lungscan
The python notebook uses neural networks for classification of lung scan images as a covid and non-covid patient.
Step 1: We import the required libraries.
Step 2: Import the images which are saved on the drive by mounting google drive on colab.
Step 3: Read each image in the folder using for loop. 
Step 4: Convert the RGB image to black and white image, resize the images so each image has the same             dimension, reshape the images into a 1-D array for easy classification.
Step 5: Add labels to each image. This will be the response variable or the Y for the input to neural           network.
Step 6: After converting each image to 1-D array join all these columns to form a data frame.
Step 7: Take a transponse of the above dataframe so that the rows of X correspond to number of images           and number of columns of X correspond to the number of features of each image.
Step 8: Split the data into test and train.
Step 9: Apply PCA to find the number of observations required, thus reducing the number of features for         easy computation.
Step 10:Feed the X and Y to neural network.
Step 11: Optimize neural network by adding different layers and changing number of parameters.

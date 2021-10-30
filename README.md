# Plant-Identification-using-Tensorflow


This is a simple machine learning project, where the program detects the plant of a particular fruit or vegetable species from the image of its leaf.

The dataset used is the PlantVillage dataset from Kaggle which can be found here - https://www.kaggle.com/abdallahalidev/plantvillage-dataset

To start with, create a folder named "data" in the working directory of python and create a folder for each plant data - I have only taken 5 plants which are Apple, Cherry, Grape, Potato and Tomato but you cam take as many as you want. Just make sure you update the utils.py and myclassifier.py file with the names of the plants in the variable 'category' so that you get the required results.

Working: 
First run the utils.py file to create the .pickle file which stores our data and it also displays the number of images in our dataset. Next, run the myclassifier.py file to create the model and determine its accuracy and finally run the detect.py file for testing the results and displaying the output.

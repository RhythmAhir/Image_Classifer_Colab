**SVM Image Classification**

Colab notebook performing image classification with sklearn.svm.

**Dataset**

Image files used are from https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset

**Objective:**

In this project, I have selected a Fashion Product Images Dataset. I divided the data into small groups and created an image classification model using the data.

**Challenges:**

Major challenge I faced was cleaning the data so that it would fit into various models. When I created the training and testing data matrices for the models, I ran into an issue where some models were not working properly. Additional data cleaning was required to categorize the data into different sets from those created data sets. 

In an effort to improve the score, I tried to add more features. However, when we predicted the best performing model, SVM, the performance best.. So, I have used them in the final model creation.

**Research:**

This steps to build the model involved - 
Learned about image classification and feature extraction
Learned about 3 different classification models.
Identified the method of extracting the data and cleaning data

**Functional specification and Data Cleaning:**

The Data we are using consists of Fashion product images. It contains data consisting of different shirts and accessories. 

**Data Cleaning**

I divided all of the data into different categories ('Apparel', 'Accessories', 'Footwear', 'Personal Care','Free Items', 'Sporting Goods', 'Home') and put them into separate folders using the CSV file which has all the records
will select the Id, masterCategory.
Using shutil copied all the data to the designated folders
After that I resized every picture in (150, 150,3). So that every picture is in the same size and we can run test them properly

**Model Selection**

I evaluated 3 different models. The accuracy of the SVM was 70% which is the best among all the other models we evaluated. That is why we choose the SVM. 

**Model Implementation**

I implemented the model and tested the prediction. I saved the model using pickle for further use. Then I can take any picture from the internet and the model will observe the url jpg and classify the image according to categories.


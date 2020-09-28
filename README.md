

# [Capstone-Proposal](https://docs.google.com/document/d/1GdNBu1Ffc_6zh14RJXWYPZbCWR0QpPJXGqD_4BCVKQw/edit#heading=h.z1tfgr9i9opn)





# Dog Breed Classifier




## Project Overview



Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.









![Sample Output](https://github.com/nancyalaswad90/Predicting-Bike-Sharing-Data/blob/master/sample_dog_output.png)





Along with exploring state-of-the-art CNN models for classification and localization, you will make important design decisions about the user experience for your app. Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. Your imperfect solution will nonetheless create a fun user experience!




## Project Instructions



### Instructions



1. Clone the repository and navigate to the downloaded folder.

	    > git clone https://github.com/udacity/deep-learning-v2-pytorch.git
        cd deep-learning-v2-pytorch/project-dog-classification
        
        
        
**NOTE:**  if you are using the Udacity workspace, you **DO NOT** need to re-download the datasets in steps 2 and 3 - they can be found in the ` /data`  folder as noted within the workspace Jupyter notebook.


2. Download the dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.


3. Download the human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.


4. Make sure you have already installed the necessary Python packages according to the README in the program repository.

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.


	    > jupyter notebook dog_app.ipynb




**NOTE:** While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. Unless requested, do not modify code that has already been included.



**NOTE:** In the notebook, you will need to train CNNs in PyTorch. If your CNN is taking too long to train, feel free to pursue one of the options under the section Accelerating the Training Process below.




# Color-Identification-in-an-Image-using-Machine-Learning
Color Recognition through OpenCV is a Simple but very effective Project which involves in identifying color on a particular thing, this is useful in various applications, especially for the people who are having difficulty in recognizing colors and for the blind people, if we add Text to Speech Library. In order to identify the colors, the model is trained on various colored images using KNN Classifier which is a popular Machine Learning Algorithm and whenever we pass a new image to the model it will try to predict that particular color by comparing the color code within its database whcih the model is trained and then it displays it on the Screen.

# Algorithm Description
Color recognition api has been used in order to train and test the colour a specific image given. In the color recognition API we have color histogram feature extarction methodology and KNN classifier has been used to train the model. Color histogram feature extraction is a method of extracting or generating histograms for an image color channels (blue, green, red) i.e **cv2.calcHist()**. K-Nearest Neighborclassifier is basically non-parametric supervised leaarning algorithm, which can be used for both classification and regression problem. The classification over here is done basically by making cluster of classes.

**Reference link:**

https://www.ibm.com/topics/knn

![KNN Classifier](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmiro.medium.com%2Fmax%2F405%2F0*a3bVVcWFwWBUtZnc.png&f=1&nofb=1)

# How to Execute?
So, before execution we have some pre-requisites that we need to download or install i.e., anaconda environment, python and a code editor. 
**Anaconda:** Anaconda is like a package of libraries and offers a great deal of information which allows a data engineer to create multiple environments and install required libraries easy and neat.

**Download link:** https://www.anaconda.com/

**Python:** Python is a most popular interpreter programming language, which is used in almost every field. Its syntax is very similar to English language and even children and learning it nowadays, due to its readability and easy syntax and large community of users to help you whenever you face any issues.

**Code editor:** Code editor is like a notepad for a programming language which allows user to write, run and execute program which we have written. Along with these some code editors also allows us to debug, which usually allows users to execute the code line by line and allows them to see where and how to solve the errors. But I personally feel visual code is very good to work with any programming language and makes a great deal of attachment with user.

**Download links:** https://code.visualstudio.com/Download, https://www.jetbrains.com/pycharm/download/#section=windows

# Steps to execute.
1. Install the prerequisites mentioned above.
2. open anaconda prompt and create a new environment.
  - conda create -c conda-forge -n sca python=3.8 numpy gdown scanpy pytorch pandas matplotlib seaborn pillow scipy=1.8.1
  - conda activate "sca"
3. Install necessary libraries from requirements.txt file provided.
4. Run pip install -r requirements.txt or conda install requirements.txt (Requirements.txt is a text file consisting of all the necessary libraries required for executing this python file. If it gives any error while installing libraries, you might need to install them individually.)
5. Run main_image.py, if you pass an image;
6. Run main_webcam.py, if you use camera to detect colors.
(It should be run on your terminal)

# Data Description
So, we have used multiple combination of plain colored images with 7 basic day to day used colors. These images are fed to color_histogram_extraction file where each image is converted into a specific RGB format along with its color class(0->Red, 1->Blue,..). These are then used to train our KNN classifier model. whenever we try to predict any color of an image, we need to pass the whole image, or we can test it out by converting that image into rgb format and passing it to KNN classifer to predict the color.

# Issues Faced.
1. we might face an issue while installing specific libraries.
2. make sure you have the latest version of python, since sometimes it might cause version mismatch.
3. Adding path to environment variables in order to run python files and anaconda environment in code editor, specifically in visual studio code.
4. make sure to change the path where your dataset is saved.

# Note:
**All the required data has been provided over here. Obviously, feel free to contact if you face any issues. mohd.mudassiruddin7@gmail.com**






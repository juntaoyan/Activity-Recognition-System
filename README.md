# Activity-Recognition-System

Description
-----------

This project reads raw Accelerometer, Gyroscope, Orientation, and EMG data recorded for daily activities like Writing, Cooking, Eating, Sleeping etc. from a Myo Armband. 
This data is then processed to distinguish and classify between different activities.


1. Program generate_features.py implements feature extraction for each of the activities using different feature extraction methods like Standard Deviation, Fast Fourier Transform, Min-Max, and Mean to generate an activity-feature matrix which is stored as a CSV file.
 
2. Program pca.py applies feature selection and dimensionality reduction to the output CSV file generated by enerate_features.py which helps us distinguish between different activities when projected on a 2-D plot.


Getting Started
---------------
The below instructions will help you set the project up and running on your local Windows machine for development and testing purposes.

Prerequisites
-------------
Before running and testing the programs included in this project, follow the below steps to set up the environment.

**Installing Python v3.7 for Windows**
1. Open a web browser and visit https://www.python.org/downloads/
2. Download the latest stable version(v3.7.0 at the time of development) .exe file.
3. Run the .exe file once downloaded and follow the steps in the wizard to install.

**Python Libraries required to run the Programs**
1. matplotlib
2. sklearn
3. numpy
4. pandas

Enter the below command in command prompt to install the libraries:
pip install <library_name>

Ex: pip install matplotlib

Note: Open command prompt as administrator if you have troubles installing the libraries.

**Development Dataset**

1. Development Dataset 'Data.zip' has been included in the Repository.
2. Unzip the dataset where you have save the Python code.


Running the Tests
-----------------

**Steps to Run the Programs**
1. Open Command Prompt
2. Enter Command python <dir>/<program_name>.py 

Example : python C:/Users/admin/Desktop/Activity-Recognition-System/generate_features.py


Release History
---------------
0.0.1 : Intial Development


Author
------
1. Darshan Dagly
2. Pranay Jagtap
3. Abhyudaya Srinet
4. Saurabh Abhale
5. Shreya Darak

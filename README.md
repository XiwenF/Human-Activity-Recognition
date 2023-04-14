# Human Activity Recognition using Wearable Sensor Technology
## Experiment design and data collection

A group of volunteers, aged between 19 and 48, are recruited to participate in the experiment. They performed a protocol consisting of six activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs, and walking upstairs). The experiment also recorded postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All participants wore a smart device on the waist during the experiment. It captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. In this context, the activities are considered outcomes, and the signals measured by the smart device are considered features.

## Data files

Two tab-delimited text files data/training_data.txt and data/test_data.txt are provided. The training data (labeled activity information included) should be used to construct and test your ML algorithms. Apply your algorithm to the test data (containing only feature information) and predict the activity corresponding to each time window.

## Object

### Build a binary classifier to classify the activity of each time window into static (0) and dynamic (1). For this task, consider postural transitions as static (0). 

### Build a refined multi-class classifier to classify walking (1), walking_upstairs (2), walking_downstairs (3), sitting (4), standing (5), lying (6), and static postural transition (7)

## Instructions to run
 
First, you need to import the module and data. The steps for binary classification and multi-class classification are almost the same. 

Step 1: Prepare the data. 

Step 2: Split the data into training data and test data. 

Step 3: Build the baseline model.

Step 4: Find the optimal parameters for each algorithms.

Step 5: Build the classifiers through different algorithms and evaluate the performance of each algorithm on training data.

Step 6: Select the algorithm that perform the best and obtain the result on test data. Then save the result in a file.

### Description about the file
The test data, features information and data dictionary are in the folder "Data" in the brach main. The training data is in the branch master. The file Code_Classifier is used to finish this project.

### Programming language

Python 3


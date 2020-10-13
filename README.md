# TransportModeDetection
The task of this repository is to develop models for transportation mode detection classification. Transportation Mode Detection involves finding out the specific mode of transport (i.e., bus/car/train/walking/running etc.) the user is involved. Smartphone sensors have become an important data source for this transportation mode detection. 
The schema of the dataset is as follows: user, timestamp, x, y, z, class
user: unique user id given to each participant
timestamp: timestamp of data recorded
x: Accelerometer reading X-axis obtained from sensor
y: Accelerometer reading Y-axis obtained from sensor
z: Accelerometer reading Z-axis obtained from sensor
class: labeled class i.e., transportation mode
There are 6 different transportation mode labels present in this dataset, namely bike, bus, car, e-bike, train, walk. The task of this assignment will be to build a classification model to label a sequence into one of these classes correctly

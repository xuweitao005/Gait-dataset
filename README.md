# Gait-dataset
This is the gait dataset collected from the kinetic energy harvester
This dataset contains gait data from 24 subjects. Each .CSV file represents the gait data from one subject. The sampling rate is 128Hz. There're four columns in the .CSV file. The first column represents the timestamp, the second column represent KEH data, and the 3-5 column represent the accelerometer data of X, Y and Z axis. 
The KEH data can be obtained by 
        KEH_data = 2nd-column-data / 4095 * 4.1, 
and the X/Y/Z accelerometer data can be obtained by 
        accX = 3rd-column-data / 100 * 9.8;
        accY = 4th-column-data / 100 * 9.8;
        accZ = 5th-column-data / 100 * 9.8;

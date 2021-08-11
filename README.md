### Mission
Continuing previous work on the bearing analysis, guessing faulty bearings, the team came back for further expertise. They want to know what type of failures occur! Or rather, if the failures exhibit similarities to other failures.

### Content
![](https://i.postimg.cc/gkgJGTnj/1.jpg)
 - For the experiments device shown on the picture was constructed. Two bearings were installed on the shaft. The rotation speed changed from 0 to 1500 rpm, was held for 10 seconds, and decreased to 250 rpm. 
 - The shaft was rotated using an DC motor connected to the shaft through a coupling. A radial load of 3.5 kg is applied to the shaft using a balanced weight.
The bearings were mounted on the shaft as shown in Figure 1. 
- GY-61 ADXL3353 accelerometers were mounted on the bearing housing 
- The sensor location is also shown in Figure. 
- The recording was saved along the x, y, z axes.
##### Datasets: 
   - bearing_signals.csv. Contains signals recordings.
   - bearing_classes.csv. Classes whole or defective for every bearing.

### Author:
* Minh Hien Vo (@minhhienvo368)

### Data preprocessing
 - Using the cleaned data from previous classification assigment. 
 - Data description: contain 96 columns representatives of different features of experiments data (min, max, median, std, entropy, impulse factor, margin factor, frequence center, mean_square_frequency, root_mean_square_frequency, root_variance_frequency, crest_factor)  from the orginal features (a1_x, a2_x, a1_y, a2_y, a1_z, a2_z, hz (Hertz) and watt)
 - Create sub-dataset to explore the correllation of features 


### With KMean clustering methods:





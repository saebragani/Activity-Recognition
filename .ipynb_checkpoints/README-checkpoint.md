# Activity-Recognition

In this repository you can find the code for classification of the common activities of electrical line workers. We recruited 37 subjects to perform the tasks and collected the acceleration signals from a signle wrist-worn Empatica E4 accelerometer. The following picture shows a sample subject and the experiment area.

![image](./images/wrist.png = 100x20)

We investigated the performance of *k*-Nearest Neighbors, Support Vector Machines, and Random Forest classifiers in combination with three feature sets (time, frequency, and time-frequency), and  two window lengths (4 and 10 seconds) for the classification. Also, we evaluated the classification performance in two scenarios of intra- and inter-subject. You can find the classification code in [Classification.ipynb](Classification.ipynb).
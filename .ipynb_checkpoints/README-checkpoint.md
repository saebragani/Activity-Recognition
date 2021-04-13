# Activity-Recognition

In this repository you can find the code for classification of the common activities of electrical line workers. We recruited 37 subjects to perform the tasks and collected the acceleration signals from a signle wrist-worn Empatica E4 accelerometer. The following picture shows a sample subject and the experiment area.

> sitting on a chair while keeping hands still on the chair arms for 3 minutes

> standing still for 3 minutes

> walking on a set path for 3 minutes

> hoisting a weighted bucket up and down to a height of 4 m for 10 repetitions

> lifting and lowering a weighted box for 20 repetitions

> pushing a cart on a set path for 10 repetitions

> typing on a computer for 3 minutes

> climbing up and down a ladder for 20 repetitions

> working on an electrical panel for 3 minutes

> and inserting screws using a screw driver at an overhead height for 3 minute

<img src="./images/wrist.png" alt="subject" width="400"/>

We investigated the performance of ```*k*-Nearest Neighbors```, ```Support Vector Machines```, and ```Random Forest``` classifiers in combination with three feature sets (```time```, ```frequency```, and ```time-frequency```), and  two window lengths (4 and 10 seconds) for the classification. Also, we evaluated the classification performance in two scenarios of intra- and inter-subject. You can find the classification code in [Classification.ipynb](Classification.ipynb) blah <a href="Classification.ipynb" target="_blank">Classification.ipynb</a>.
# Data mining using Weka

# Abstract

In this report, the purpose of this project is to perform data mining tasks for data analysis using a collection of machine learning algorithms from WEKA. Furthermore, using a real-world dataset from the 1984 United States congressional voting records database. As it pertains to the file; vote_arff.arff

# Tasks
- provide a context of use of the dataset by providing the classification task, and dataset characteristics. 
- Use exploratory data analysis to examine the categorical variables, and the target class variable.
- Then we compared evaluation protocols for classification running a 2-fold cross validation, and 10-fold cross validation, as well as reporting the performance.
- Show the list of attributes by order of importance.
- 3 runs using 10–fold cross validation algorithm and different number of attributes.
- Decision tree visualization, and classification of testing instances.

# Classification task 

The vote dataset represents the number of votes each one of the 16 bills received in favour (“yes”) and against (“no”) by the 435 members (267 Democrats and 168 Republicans) of the House of Representatives in the U.S.

![image](https://user-images.githubusercontent.com/78631693/236654570-40793960-4558-4e03-ab82-193f7d0a5927.png)

With 16 attributes (bills that were voted on), and 1 target variable (class)

![image](https://user-images.githubusercontent.com/78631693/236654582-8560151d-c2c5-4a8d-9c5b-2f63372aec4d.png)

# Classification using decision tree
In our conclusion, after 3 runs using 10-fold cross validation and different number of attributes. All three classifiers provided 95%+accuracy. However, it's better to select 3 attributes as the training tree is smaller, and prevents overfitting.

![image](https://user-images.githubusercontent.com/78631693/236654717-01075a73-13a6-4520-acb1-16fc30123b01.png)

# Decision tree visualization 
Size of tree: 11 (6 leaves, +5 nodes)
![image](https://user-images.githubusercontent.com/78631693/236654750-b8d65cda-98b7-4e97-ab5e-24381f39c48c.png)


Full analysis on the Data-mining report document.
The PowerPoint shows the presentation for the report.

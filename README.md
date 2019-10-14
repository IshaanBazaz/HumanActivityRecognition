The main aim of Human Activity Recognition is to identify the actions carried out by a human being given a set of observations of them and the surrounding environment. This can be accomplished by obtaining information using various sources such as sensors worn on body. But this approach is not a long-term solution for monitoring activity and also it is uncomfortable for the person wearing it. The alternative and better approach is using smartphones. The objective of this data collection was to understand the performance of using smartphones for obtaining inertial data using accelerometers and gyroscopes of smartphones.

The human activities in the dataset can be broadly classified under the following six categories:
- Standing
- Sitting
- Laying down
- Walking
- Walking downstairs
- Walking upstairs

30 volunteers between the age of 19 to 48 years performed the activities.


We used 4 models - KNN, SVM, Elastic Net, Random Forest. The best classification method achieved was Support Vector Machines (SVM) obtaining an accuracy of 96.2% on the testing data. The main reason is due to the usage of support vectors by the model.
The worst classification method was K Nearest Neighbour (KNN) obtaining an accuracy of 89.6% on the testing data.


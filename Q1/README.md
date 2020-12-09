# KNN

```ques
Lithionpower is the largest provider of electric vehicle (e-vehicle) batteries. It provides battery on a rental model to e-vehicle drivers. Drivers rent battery typically for a day and then replace it with a charged battery from the company. Lithionpower has a variable pricing model based on driver's driving history. As the life of a battery depends on factors such as over speeding, distance driven per day etc. You as a ML expert have to create a cluster model based upon KNN, where drivers can be grouped together based on the driving data. Drivers will be incentivized based on the cluster, so grouping has to be accurate.
* id: Unique Id of the driver
* mean_dist_day: Mean distance driven by driver per day
* mean_over_speed_perc: Mean percentage of time a driver was > 5 mph over the speed limit
* Increase in profits, up to 15-20% as drivers with poor history will be charged more.
```

- KNN => lazy learner => stores training data and uses it to predict only when asked

```doc
K nearest neighbours
- k => how many nearest points must be checked to give a label to the current point
- k can be selected using elbow method => trying every possible k and finding the best by plotting
- distance => 
  - euclidean distance is used in most of the cases (least possible)
    - ( (x1-x2)^2 + (y1-y2)^2 )^(1/2)
  - manhattan distance can also be used (along axis and right angle)
    - |x1-x2|+|y1-y2|
```

- usage
  - recommendation systems in shopping streaming
  - ads 
  - classifying documents/files 
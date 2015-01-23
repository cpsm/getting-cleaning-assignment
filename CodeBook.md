      Data Dictionary - Human Activity Recognition using Smart Phone

A group of 30 volunteers within the age group of 19 years to 48 years performed the activities wearing a Samsung Galaxy sII smartphone on their waist. The smartphone used for the experiment was having embedded accelerometer and gyroscope. The 3 axial linear acceleration and 3 axial angular velocity are captured at a constant rate of 50 HZ. The data set obtained from the experiments are partitioned into two sets such as training and test data. 

Each recorded observation contains the following fields.
* An identifier of the subject who carried out the experiment.
* Its activity label.
* Tri-axial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
* Tri-axial Angular velocity from the gyroscope. 
There are  561-feature vector with time and frequency domain variables. The mean and standard deviations derived from these 561 feature values are 68 which are  available in  tidy data.

1   Subject 
    Integer value between 1 to 30
2.  Label
    1 WALKING
    2 WALKING_UPSTAIRS
    3 WALKING_DOWNSTAIRS
    4 SITTING
    5 STANDING
    6 LAYING
3. The variables selected for the tidy data  come from the accelerometer and gyroscope. The time domain signal is prefix with [t] to represent time values. The accleration signals are converted into boday and gravity accleration. The jerk signal values are derived from linear accleration and angular velocity. The magnitude of the three dimensional signals are calculated using Euclidean norm. 
The frequency parameters are derived from applying EFT(Fast Fourier Transform) to some of the signals. The frequency parameters are pre-fixed with [f]
Using these observed values the mean and standard deviations for various parameters are derived 

 1. tBodyAcc-mean()-X  time domain body accleration for each direction         
 2. tBodyAcc-mean()-Y     - 
 3. tBodyAcc-mean()-Z
 4. tBodyAcc-std()-X   -time domain body accleration standard devaiation for each direction        
 5. tBodyAcc-std()-Y
 6. tBodyAcc-std()-Z
 7. tGravityAcc-mean()-X  time domain gravity accleration in each direction      
 8. tGravityAcc-mean()-Y
 9. tGravityAcc-mean()-Z
10. tGravityAcc-std()-X   time domain gravity accleration standard deviation       
11. tGravityAcc-std()-Y 
12. tGravityAcc-std()-Z 
13. tBodyAccJerk-mean()-X time domain accleration jerk mean for each direction
14. tBodyAccJerk-mean()-Y  
15. tBodyAccJerk-mean()-Z
16. tBodyAccJerk-std()-X   time domain accleration jerk  standard deviation    
17. tBodyAccJerk-std()-Y
18. tBodyAccJerk-std()-Z
19. tBodyGyro-mean()-X     time domain gyro mean for each direction      
20. tBodyGyro-mean()-Y
21. tBodyGyro-mean()-Z
22. tBodyGyro-std()-X     time domain gyro standard deviation      
23. tBodyGyro-std()-Y
24. tBodyGyro-std()-Z
25. tBodyGyroJerk-mean()-X   time domain gyro jerk mean  
26. tBodyGyroJerk-mean()-Y
27. tBodyGyroJerk-mean()-Z
28. tBodyGyroJerk-std()-X  time domain gyro jerk standard deviation     
29. tBodyGyroJerk-std()-Y 
30. tBodyGyroJerk-std()-Z
31. tBodyAccMag-mean()      time domain body accleration maginitude mean   
32. tBodyAccMag-std()       time domain body accleration maginitde standard deviation
33. tGravityAccMag-mean()   tiem domain gravity accleration maginitude mena
34. tGravityAccMag-std()    time domain gravity accleration maginitude standard deviation    
35. tBodyAccJerkMag-mean()  time domain body accleration jerk maginitude mean
36. tBodyAccJerkMag-std()   time domain body accleration jerk maginitude standard deviation 
37. tBodyGyroMag-mean()     time domain body gyro maginitude mean    
38. tBodyGyroMag-std()      time domain body gyro maginitude standard devaiation
40. tBodyGyroJerkMag-mean() time domain body gyro jerk maginitude mean 
41. tBodyGyroJerkMag-std()  time domain body gyro jerk maginitude standard deviation.

Rest of the values are defined for frequency domain.

42. fBodyAcc-mean()-X       
43. fBodyAcc-mean()-Y
44. fBodyAcc-mean()-Z          
45. fBodyAcc-std()-X
46. fBodyAcc-std()-Y
47. fBodyAcc-std()-Z           
48. fBodyAccJerk-mean()-X
49. fBodyAccJerk-mean()-Y
50. fBodyAccJerk-mean()-Z      
51. fBodyAccJerk-std()-X
53. fBodyAccJerk-std()-Y
54. fBodyAccJerk-std()-Z       
55. fBodyGyro-mean()-X
56. fBodyGyro-mean()-Y
57. fBodyGyro-mean()-Z         
58. fBodyGyro-std()-X
59. fBodyGyro-std()-Y
60. fBodyGyro-std()-Z          
61. fBodyAccMag-mean()
62. fBodyAccMag-std()
63. fBodyBodyAccJerkMag-mean() 
64. fBodyBodyAccJerkMag-std()
65. fBodyBodyGyroMag-mean()
66. fBodyBodyGyroMag-std()     
67. fBodyBodyGyroJerkMag-mean()
68. fBodyBodyGyroJerkMag-std() 


Readme file to explain the code flow

step 1
Keep the files in the current working directory under test and train

Read the test file  into tables 
test.subject with column names "subject"
test.label with column name "label"
test.data 

Read the training files into tables
train.subject with column name "subject"
train.label   with column name "label"
train.data

step2
Add the subject label and  data using columan bind for test and train
Merge the test and train data together

step 3 
read the features file and get the mean and std variable for various observations
read activity-label values and replace the activity number with correspondng activity label
Change the column names taking the features variable names for mean and standard deviation

step4
Get the mean for each subject and actvity from the data

wirte the data output to a file tidy.txt


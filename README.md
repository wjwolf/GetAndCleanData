GetAndCleanData
===============

run_analysis.R - Bill Wolf, Getting + Cleaning Data, Project 1

###Here is what we were assigned to do:

### Task: create one R script called run_analysis.R that does the following: 
#####   1. Merge the training and the test sets to create one data set.
#####   2. Extract the measurements on the mean and standard deviation for each measurement. 
#####   3. Uses descriptive activity names to name the activities in the data set
#####   4. Appropriately label the data set with descriptive variable names. 
#####   5. Creates a second, independent tidy data set with the average of each variable by activity and subject. 

###My program is structured to do each of those 5 steps in that order:


#### Step 1: create combined data set
	a. Download the raw data zip file if it isnt already in current working directory
	b. Extract the study's variable labels to use as initial column names
	c. Read the study's measurement data into data frame x.train and x.test
	d. Read the study's subject data into data frames x.train.subject and x.test.subject
	e. Read the study's activity data into data frames y.train and y.test
	f. combine the training data frames (x.train, x.subject.train, y.train) into a combined.train data frame
	g. combine the test data frames (x.test, x.subject.test, y.test) into a combined.test data frame
	h. combine the combined.train and combined.test into a single combined.all data frame 
#### Step 1: done - we have a combined data set!!

#### Step 2: Down select to mean, sd variables
	a. The study uses a variable naming convention that helps us here.
		The variable name include the strings "mean()" and "sd()" so we will use that pattern
		to select ones to keep.  There are other variable names in the data set that also contain 
		the string "Mean" in the name but my reading of the study documentation made me decide not 
		to include them.
	b. store the subset in a new data frame named combined.subset
#### Step 2: done - we have the subest!!

#### Step 3: apply descriptive labels to activities
	a. apply the labels "WALKING", "WALKING_UPSTAIRS", "WALKING_DOWNSTAIRS", "SITTING",
         "STANDING", "LAYING" to the activity values in the combined.subset data frame
#### Step 3: done - activity labels are applied!!

#### Step 4: Apply descriptive labels to variables
	a. Replace the studies variable names with more descriptive labels in combined.subset data frame
	   Make every name component lower case and dot separated; get rid of embedded punctuation
	   For example the original name "fBodyAccJerk-std()-z" becomes "freq.body.acc.jerk.std.z"
#### Step 4: done - variables have descriptive labels!!

#### Step 5: create tidy data set of mean for each activity and subject
	a. update combined.subset to make $subject a factor so it sorts the way we want
	b. use tapply to generate the mean of each set of measurements by activity and store in activity_mean vector; attach
	     the descriptive variable names from step 4
	c. use tapply to generate the mean of each set of measurements by subject and store in subject_mean vector; attach
	     the descriptive variable names from step 4
	d. combine activity_mean and subject_mean data into a new data frame named final.data
	e. write final.data to output file as requested
#### Step 5: all done - we have tidy data set of activity and subject mean values!!
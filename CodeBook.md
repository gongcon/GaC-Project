Original data is from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip. It has two data sets, training and test, in folder train and test, respectively. Each data set contains 561 features as in file features.txt.

Script run_analysis.R generates a tidy data set (tidy_data.txt) described as the following, see README.md for details.

"activity_label" - activity of subjects which can be one of these:
    WALKING
    WALKING_UPSTAIRS
    WALKING_DOWNSTAIRS
    SITTING
    STANDING
    LAYING

"subject" - the 30 volunteers, denotes from 1 to 30

Other columns are the average of each variable subset of the original data ("sum" and "std" only) for each activity and each subject, range from -1 to 1.
This file describes how run_analysis.R script works.

Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
Make suree the folder "data" and the run_analysis.R script are both in the current working directory.

Second, use source("run_analysis.R") command in RStudio. 

Third, you will find two output files are generated in the current working directory: 
-merged_data.txt: it contains a data frame called cleanedData 
-TidyData.txt it contains a data frame called result with 180*68 dimension.

Use data <- read.table("TidyData.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject

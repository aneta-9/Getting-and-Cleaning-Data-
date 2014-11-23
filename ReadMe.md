This file describes how run_analysis.R script works.
•	First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
•	Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
•	Second, use source("run_analysis.R") command in RStudio. 
•	Third, you will find two output files are generated in the current working directory: 
        o	merged_data.txt: it contains a data frame called cleanedData 
        o	TidyData.txt it contains a data frame called result with 180*68 dimension.
•	Finally, use data <- read.table("TidyData.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject

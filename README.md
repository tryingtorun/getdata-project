# getdata-project

# To Run This Project
In order to make this project reproductible on other systems, and since the Dataset for this project is not included in the repository, the instructions for running the 'run_analysis.R' script are as follows:

1) You will need to first set a variable named 'dataSetLocation' from within the R console. This variable will need to be set to the exact static location where the UCI HARD Dataset files reside. Since relative file paths and spaces in the folder name were causing errors in a Windows environment, the location of the folder has been left outside of the script to be set on a per user environment basis.
	Example: 
			dataSetLocation <- paste(getwd(),"/UCIHARDataset",sep="")
			//Sets 'dataSetLocation' to "C:/Users/username/Documents/UCIHARDataset"

2) You will need to run the 'run_analysis.R' script from the R console where the 'dataSetLocation' variable has been defined. 
	Example:
			sourcePath <- paste(getwd(),"/GitHub/getdata-project/run_analysis.R",sep="") 
			//Gets the static path to the script in the GitHub repository 'getdata-project'
			source(sourcePath) 
			//Runs the script

# How run_analysis.R Works

The Untidy Data Set consisted of the following (data) files:
	/features.txt
	/activity_labels.txt
	/train/X_train.txt
	/train/y_train.txt
	/train/subject_train.txt
	/test/X_test.txt
	/test/y_test.txt
	/test/subject_test.txt
	(as well as many raw data files in /train/Inertial Signals and /test/Intertial Signals folders)

To transform this mass of information into 'tidy' data, the data files above were combined and modified in the following manner:
	1.a) The single column of data from /train/subject_train.txt and other single column of data from /test/subject_text.txt were combined into a single column of data using the row bind function.
	1.b) features.txt was used as the 561 element vector of column names when reading in the 561 element per row /train/X_train.txt and /test/X_test.txt tables.
	1.c) The two X data frames were merged together, also using the row bind function.
	1.d) Just as in step 1, both /train/y_train.txt and /test/y_test.txt were loaded and merged together with row bind.
	2) The X data frame, produced in step 1.c, the columns in the data set were reduced to only those with 'mean' or 'std' in the label (the labels set in step 1.b).
	3) The y data frame, produced through step 1.d, was then merged with the /activity_labels.txt data by matching and replacing numeric values with their respective labels in the y data.
	4) Since the data was loaded in step 1.b with the feature list as the data column names, this extra step was not required.
	5.a) The data frames for Subject, x/Observation, and y/Activity data as they were created and modified in steps 1.a, 2, and 3, are all merged together into a single data frame using the column bind function.
	5.b) The data frame produced in 5.a is then aggregated to find the average of all fields (except the Subject and y/Activity), grouped by Subject and y/Activity.

When the script runs you will see output for each step the script takes. The script's console output is expected to look as follows:

	[1] "Step 0: Preload Labels."
	[1] "Loading Feature Labels..."
	[1] "Done."
	[1] "Loading Activity Labels..."
	[1] "Done."
	[1] "Step 0: Done."
	[1] "Step 1: Loading and Merging Data Sets."
	[1] "Loading Subject Training file..."
	[1] "Loading Subject Testing file..."
	[1] "Merging Subject files..."
	[1] "Done."
	[1] "Loading X Training file..."
	[1] "Loading X Testing file..."
	[1] "Merging X files..."
	[1] "Done."
	[1] "Loading Y Training file..."
	[1] "Loading Y Testing file..."
	[1] "Merging Y files..."
	[1] "Done."
	[1] "Step 1: Done."
	[1] "Step 2: Extracting Only Means and STD Measurements."
	[1] "Filtering Down Gathered Data to Only Means and STDs..."
	[1] "Done."
	[1] "Step 2: Done."
	[1] "Step 3: Use Descriptive Activity Names."
	[1] "Setting Activity Information to Human Readable Values..."
	[1] "Done."
	[1] "Step 3: Done."
	[1] "Step 4: Use Descriptive Data Names."
	[1] "Data was loaded with Feature Labels."
	[1] "Step 4: Done."
	[1] "Step 5: Create Tidy Data Set with Average of Each Variable for Each Activity for Each Subject."
	[1] "Step 5: Done."
	[1] "Writing Finished Product to: tidy_data.txt."
	[1] "Complete!"

 Output of the tidy data set created by the script will be saved in a file named 'tidy_data.txt' in your working directory.

# The UCI HARD Dataset was not altered for this project.
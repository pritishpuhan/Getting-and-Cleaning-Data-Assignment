# Getting-and-Cleaning-Data-Assignment
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set.
  The submitted data set is tidy.
  The Github repo contains the required scripts.
  GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information.
  The README that explains the analysis files is clear and understandable.
  The work submitted for this project is the work of the student who submitted it.
 
 Here is how my script implements:

  Cleans current workspace and sets up the working directory.
  Downloads the data set to the working directory from the target URL. 
  Unzips the file.
  Loads the activity labels and features.
  Selects the features including mean and standard deviation and assign the values to “features_need”.
  Loads the data for test and train including subject, activity and experiment result. Selects columns matching “features_need”.
  Combines the subject, activity and experiment result for test and train respectively and gets the data sets “train” and “test”.
  Merges “train” and “test” to get “mergeddata”.
  Cleans the special characters in “features_need”. Renames column names in “mergeddata” using “features_need”.
  Uses descriptive activity names to name the activity column in “mergeddata”
  Takes the average of each variable in “mergeddata” for each activity and each subject.
  Assigns the value to a new data set “summary_data”. Write the output.

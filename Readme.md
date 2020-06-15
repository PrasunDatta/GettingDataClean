---


---

<ul>
<li>This is the course project for the Getting and Cleaning Data Coursera course.</li>
<li>The included R script, <code>run_analysis.R</code>, conducts the following:<br>
1.Download the dataset from web if it does not already exist in the working directory.<br>
2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.<br>
3. Load the data(x’s) feature, activity info and extract columns named ‘mean’(<code>-mean</code>) and ‘standard’(<code>-std</code>). Also, modify<br>
4. Extract data by selected columns(from step 3), and merge x, y(activity) and subject data. Also, replace y(activity) column to it’s name by refering activity label (loaded step 3)<br>
5. Generate ‘Tidy Dataset’ that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file <code>tidy_dataset.txt</code>.</li>
</ul>


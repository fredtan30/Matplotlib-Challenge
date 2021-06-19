# Matplotlib-Challenge

The Power of Plots - Analysing the treatment using variant drugs for mouse tumor

1. Identify any duplicate time points of the mouse ID and remove any data associated with that mouse ID
    - Read the Data
    - Combined the data between mouse data and study results
    - Used the duplicated() function in finding duplicate ['Mouse ID', 'Timepoint']
    - Combined all the duplicated data with the Mouse ID
    - Used the drop() function to remove all the duplicated data
    - Display the clean Data
2. Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen
    - Calculating the mean, median, variance, std_deviation and sem value by Tumor Volume
    - Merge all values into a new dataframe and display the merge data
3. Preparing Bar Chart and Pie Chart using pandas and pyplot
4. The hardest challenge in this homework, try to understand the Quartiles, Outliers and Boxplots concepts
    - Start by getting the last (greatest) timepoint for each mouse
    - Merge this group df with the original dataframe to get the tumor volume at the last timepoint
    - Put treatments into a list for for loop (and later for plot labels)
    - Calculate the IQR and quantitatively determine if there are any potential outliers. 
    - Setting loop to locate the rows which contain mice on each drug and get the tumor volumes and append into the empty list as subset
    - Using the upperbound and lowerbound to determine the outliers
    - Generate a box plot of the final tumor volume of each mouse across four regimens of interest
5. Using line plot and scatter plot to display tumor volume vs. time point for a specific mouse id treated with Capomulin
6. Calculate the correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin regimen



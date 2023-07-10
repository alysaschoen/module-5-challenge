# Module 5 - Pymaceuticals
 Module 5 - Pymaceuticals


Goal:
Generate tables and figures using the provided case study csv files to compare the performance of the drug Capomulin against the other listed treatments.

Tasks
- Prepare data
    * Merge the two csv's into a single dataframe
    * Eliminate duplicate mice
    * Create a new database featuring the cleaned data
    * Show the correct total number of unique mouse subjects

- Generate Summary Statistics
    * Create a dataframe of summary statistics featuring 
            a. a row for each treatment regimen
            b. a column for the mean, median, variance, standard deviation, and Sem of the tumor volume

- Create Bar and Pie Charts
    | Comparing Mouse ID & Timepoint |
        * Create Bar Chart using pandas method
        * Create Bar Chart using matplotlib method

    | Comparing Male vs. Female Mice |  
        * Create Pie Chart using pandas method
        * Create Pie Chart using matplotlib method

- Calculate Quartiles, Find Outliers, Create Box Plot
    * Create grouped dataframe showing the greatest time point for each mouse, then merge this dataframe with the original
    * Create lists to hold the individual treatments and tumor volume data
    * Create a for loop to locate the rows that correspond to each treatment. Append the final timor volums for each drug in the tumor volume list created at the last step
    * Determine outliers by using upper and lowerbounds
    * Generate box plot 

- Create a Line Plot and Scatter Plot
    * Generate a line plot that shows tumor volume vs. time point
    * Generate a scatter plot that shows avg. tumor volume vs. weight

- Calculate Correlation and Regression
    * Calculate correlation coefficient and linear regression model


Please Note: I moved my github folder from documents to downloads due to my documents being connected to icloud. I believe this affected my original copy and created a copied version that affected the in and out numbers.




References Used -
1. To find and display a simple number of unique Mouse ID's -
    https://www.geeksforgeeks.org/how-to-count-distinct-values-of-a-pandas-dataframe-column/

2. To identify by Mouse ID & Timepoint using dataframe.loc duplicated  and subset
    https://towardsdatascience.com/finding-and-removing-duplicate-rows-in-pandas-dataframe-c6117668631f

3. To round the Tumor Volume while cleaning the data
    https://www.freecodecamp.org/news/how-to-round-a-float-in-pandas/#:~:text=Using%20the%20round()%20method,in%20a%20column%20called%20rounded_cost%20

4. To highlight the outlier on box plot
    https://stackoverflow.com/questions/25075023/matplotlib-boxplot-outlier-color-change-if-keyword-sym-is-used


I worked closely with my brother in law while we were on vacation as he is very familiar with pandas.
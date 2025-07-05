# DSA-Project
This project is aimed at analysing the data given to us by palmora group, to find out insights that the palmora management team would need to address and the second project is about Amazon product review Analysis.

## Project Topic: 
1. Palmora Group Hr Analysis
2. Amazon Peoduct Review Analysis
## Palmora Group HR Analysis

## Introduction 
based on the dat provided to us, we had to clean the data, the analyse before visualizing. it has beeen a great experience working on data as a data analyst, we used two tools to achieved our end results for this project'
# *Project Topic*: Palmora Group HR Analysis   

## Project overview
by Analysing the various parameters in the data received, we seek to gather enough insight to make reasonable decisions which can enable us to find compelling stories around our data from the insight gotten and to know the best performing from our data.

# Tools used
The following tools were used in achieving these project:
1. Ms Excel (For querying and Analyzing)
2. Power Bi ( For creating a report).

# Data Cleaning
In the initial phase of data cleaning, the following where carried out:
- Data Loading and inspection
- Data cleaning and formatting (We removed some null columns).

In the case of the recieved data, some Gender column were empty and also salary column, some were empty.
   In order for us not to allow null or empty column to slow dow our analysis, we replaced the Empty Gender with Undisclosed and then removed the null value.

## Exploratory Data Analysis (EDA)
In this Project, We explore the data to answer some questions about the data. we first of all used Excel to do little cleaning (filling the empty gender with Undisclosed) before taking the data into Power Bi environment. the following questions were the insight we needed to get and give answers to via this analysis
1. What is the GEnder Distribution in the Organization ( Based on Region and Department).
2. Show insight on rating based on gender.
3. Identify if there is Gender based gap; if there is, identify the department and regions that should be focuse of Management.
4. A recent Regulation was adopted which requires manufacturing companies to pay employee a minimum of $ 90,000

-  Does Palmora meet this requirement?
-  Show the pay distribution of emploee grouped by a band of $10,000- $20,000, $30, 000- $40,000 etc
-  Visualize by Region.
- An additional table of data (bonus table) was also received and the task was to calculate the Amount to be paid as a bonus to individual employees.
- We were also asked to calculate the Total amount to be paid to individual employees ( Salary inclusive of bonus)
-Total amount to be paid per Region and company wide.

During the Analysis, some calculated columns were formed, we created the Dept_ Rating Column with the formular [Dept]&"/"&[Attribute], we created that for the bonus file and the original file given to us in order to have relationship between the two data.
After that, the two files were merged using the merge button( merge as new). 

Some null values that were still present after data clean up was replaced with 0. 

We created A new column called Annual bonus, this is created based on the assigned bonus rate given from the bonus data we received . We use the formular Bonus Rate=[Salary]*[Bonus Rate] .



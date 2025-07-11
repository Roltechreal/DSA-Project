# DSA-Project
This project is aimed at analysing the data given to us by palmora group, to find out insights that the palmora management team would need to address.

## Project Topic: 
Palmora Group HR Analysis

## Introduction 
based on the dat provided to us, we had to clean the data, the analyse before visualizing. it has beeen a great experience working on data as a data analyst, we used two tools to achieved our end results for this project.  

## Project overview
by Analysing the various parameters in the data received, we seek to gather enough insight to make reasonable decisions which can enable us to find compelling stories around our data from the insight gotten and to know the best performing from our data.
## Data source
The data is gotten from the Palmora group, a manufacturingbcompany based in Nigeria, the company is embroiled in issues bordering on gender inequality in its three regions.

## Tools used
The following tools were used in achieving these project:
1. Power Bi ( For creating a report).

## Data Cleaning
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

During the Analysis, some calculated columns were formed, we created a custom culumn called the Dept_ Rating Column with the formular [Dept]&"/"&[Attribute], we created that for the bonus file and the original file given to us in order to have relationship between the two data.
After that, the two files were merged using the merge button( merge as new). 

Some null values that were still present after data clean up was replaced with 0. 

We created A new custom column called Annual bonus, this is created based on the assigned bonus rate given from the bonus data we received . We use the formular Annual Bonus =[Salary]*[Bonus Rate]. 

We Also created the conditional column, in order for us to know the range of Salary paid ($10,000-$20,000, $20,000-$30,000, $30,000-$40,000 etc).
We then renamed the merged data table which we later used for the analysis to answer some of the question raised by the company Pamor.

## Analysis of questions raised earlier.
# Gender distribution
 Answer : Based on region, Male are distributed more in Palmora employment. This is shown with the Analysis chart below.



![based on region](https://github.com/user-attachments/assets/bd8a4863-9ff1-4296-b53c-91f63a2266d0)

From the bar chart analysis shown above, Male employees are distributed more than the female. Male are 465 while female are 441.

### Rating Based on Department : male are distributed more than the female. Male are 465 while females are 441 as shown below.


![based on department](https://github.com/user-attachments/assets/d2e3f89a-cd66-460d-90a8-df7348b4f46e)


### Rating based on gender : the female are rated higher than then mmale, females are rated 15 while males are rated 14 as shown below



![based on gender main](https://github.com/user-attachments/assets/345177f1-cb2c-447f-aff4-38fac3edc67f)

### Gender Pay Gap, the male has the Total of $35M, While the female has $32M as shown below.
![Gender pay Gap](https://github.com/user-attachments/assets/b3915fb2-bc65-45a1-ad08-213d8cec55f9)

### Gender pay gap by region: From the piechart below We saw the pay distribtution based on the different regions:

![gender pay gap by region](https://github.com/user-attachments/assets/e4525410-0988-4052-871a-c3a12428a32e)

## Below are the distribtion of the pay (Salary) by Region:
### Kaduna: 
in this region, the male has $11,929,130 (17.11%)
 while the female has $13,622,690 (19.54%)
From our Analysis, we have seen that in this region, the females earn more than the males.

#### Abuja: 
in this region, the male has $11,131,420 (15.97%)
 while the female has $11,646,0640 (16.7%)
 In this region, females earn higher than the males.

#### Lagos: 
in this region, the male has $9508400 (13.64%)
 while the female has $8751290 (12.55%)
From our Analysis, we have seen that in this region, the males earn more than the females.
From our Analysis, it is seen that the Management needs to Foucus on the three Regions in terms of Slary payments to both genders.

### For the distribution of pay by Department:
There is no much difference in salary distribution between male and female, but in Legal Department, male has 5.13% and female has 3.34% distribution. in Accounting Department, male has 4.11% while female has 2.93%.
![gender pay gap by department](https://github.com/user-attachments/assets/5f5df721-a33d-4be6-8375-02a8e744ddbe)


# To Find out of the company Palmora meets the Requirement of $90,000 salary to its staff
They did not  reach the requirement $90,000 Minimum per employee, according to the analysis carried out, because, about 117 employee are paid $80,000, so this is below what the government ask them to pay the employees, this is shown below from the barchart gotten from this analysis

![pay distribution of employee](https://github.com/user-attachments/assets/8fad8e13-e3d1-4571-a699-8d81d2f7c589)

### To find the numbers of employees that fall into a band of $10,000-$20,000, $20,000- $30,000 etc 
From the barchart below:

- 28 employees falls into a band of $30,000-$40,000.
- 90 employees falls into the band of $100,000- $110,000.
- 96 employees falls into the band of $60,000- $70,000.
- 97 employees falls into the band of above $120,000.
- 99 employees falls into the band of $70,000- $80,000.
- 101 employees falls into the band of $40,000- $50,000.
- 105 employees falls into the band of $50,000- $60,000
- 105 employees falls into the band of $110,000- $120,000.
- 108 employees falls into the band of $90,000- $100,000.
- 117 employees falls into the band of $80,000- $90,000.

![pay distribution of employee](https://github.com/user-attachments/assets/82951a21-99d8-4911-8045-86691b0f692f)

### Number of employee paid by Region
![payment by region](https://github.com/user-attachments/assets/ff4994d2-682e-4623-8ceb-b4fdfc418088)

from the barchart above, it is seen that :
1. In kaduna about 361 employees are paid salary
2. In Abuja about 335 employees are paid salary
3. In Lagos about 250 employees are paid salary.

## Conclusion
From the analysis we carried out, it is seen that the salaries are not distributed evenly acros both Genders and the company does not meet up with the goverment $90,000 regulation payment of its staff.

## Reference
Palmora manufacturing company, Nigeria

# School-District-Analysis


## Overview of Project

Assist Maria, the Chief Data Scientest , in providing analysis on all schools within the district to identify patterns and trends by reviewing test scores and see if score performance can be linked to size of schools, type of schools, and the amount of money in the school budget and per capita basis.  This analysis will assist school board members in making decisions regarding funding and resource allocations.

### Purpose

During the analysis of the schools in the district and their performance on standardized testing in relationshipe to school type, budget, and size, it was communicated by the school board that there were signs of academic dishonesty; specifically reading and math grades for the ninth grade students at Thomas High School.  Due to the inability to discern the full extent of the academic dishonesty, the school board asked Maria to replace the reading and math scores for the entire 9th grade of Thomas High School with NaN and rerun the overally analysis and see what impact this would have on the analysis.

## Results

The district analysis was orginally completed without bias including all scores from all schools taken calculated in the analysis.  However, because of academic disnhonesty as it relates to the 9th grade scores at Thomas High School, the analysis was run two additional times.  Once, to return results based on score removal for Thomas High School ninth grade but, maintaining the Thomas High School population intact. Then once again focusing only on the 10th, 11th, and 12th grade population of Thomas High School.  The resulting summary can be found below.

### Analysis of District Summary

Upon running the District Analysis between data sets that include all students scores and scores that did not include math and reading scores for ninth graders at Thomas High School, the following can be observed:

* The Average Math Score dropped by .1% for the district when Thomas High School ninth graders scores were not calculated.
* The % Passing Math dropped by .2% for the district when Thomas High School ninth graders scores were not calculated.
* The % Passing Reading dropped by .1% for the district when Thomas High School ninth graders scores were not calculated.
* The % Overall Passing dropped by .3% for the district when Thomas High School ninth graders scores were not calculated.
* Special Note: To be consistent with formattng, the original full data output was re-formatted to include to the tenth decimal place.
* Please see images below for full District Analysi between full data set and data set where Thomas High School scores were not calculated.
 
![DistrictSumAllSchools](Resources/DistrictSumAllSchools.png)
![DistrictSumNaN9thTHS](Resources/DistrictSumNaN9thTHS.png)

Upon Analysis of the election analysis requirements, there are multiple opportunities for improvement that could automate the process of the election analysis and provide powerful data and reporting.  The Election Results report must output the following: 

*  Total Votes
*  County voting results displaying the county, quantity of votes for each county and percentage of votes for each county. 
*  The county with the largest voting turnout.
*  The candidate's names, quantity of votes received and percentage of votes received per candidate.
*  Declaration of the winner which provides winning candidates name, quantity of votes, and winning percentages.
*  Provide a report of above results in a command line format and .txt format.

### Analysis of School Spending

### Anaylsis of School Size

### Anaylsis of School Type

 
![ReadCSVfile](Resources/ReadCSVfile.png)



### Suumary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs

 

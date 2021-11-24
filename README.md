# School_District_Analysis

## Overview

In this project I have gone though school district data to remove altered grades using pandas function, then with the new dataset I continued to move forward with a school district analysis to fine correlation between students test scores and differnt factors between schools. 

## Process and Results

Before doing the analysis on the data we first had to remove the reading and math scores for all students at Thomas High School who are in the 9th grade because the staff thought there were faults in that data due to alteration. Because the data was removed we have slightly less conclusive results but if these false datapoints were kept in the data it would result in different passing rates, and different average scores for all students. 

After cleaning the data if faulty datapoints I started pulling out some basic numbers for the entire district (Shown Below)
![image](https://user-images.githubusercontent.com/81537476/143187866-c370c1b6-5249-4382-b1fd-2c86094168d5.png)

I have also created basic numbers for each school individually (Shown Below) so that you are able to take a deeper look into the data.
![image](https://user-images.githubusercontent.com/81537476/143187809-94dc3a65-7d31-4cfc-a37d-b1dd2c8ff137.png)

After creating the dataframes for the analysis I began looking into some important numbers such as the best and worst five schools out of the 15.
###### Best Five
Cabrera High School
Thomas High School
Griffin High School
Wilson High School
Pena High School

###### Worst Five
Rodriguez High School
Figueroa High School
Huang High School
Hernandez High School	
Johnson High School

Then to get some conclusive results I began looking into what factors might play into these schools being the top and bottom of the list. The three main factors that we tested for were school size, budget per student, and school type. 

According to the results for a school to have the best odds to product good testing scores you should be a small charter school with a high budget to student ratio. Though its not exact, there is a correlation between those factors and having higher test scores.


## Summary

When looking into school test scores, you will find that three factors that may work to your schools advantage are being a charter school, having a smaller student populatuion, and having a high budget compared to the number of students you have. 

Though some of these may simply be correlated and not directly cause the students to perform better it would require further testing to get more conclusive results. 




# Pewlett_Hackark_Analysis

## Overview of Project
This project is to investigate the relationship among the number of rides, trip durations, genders, usertype, day of the week, and the time of the day. 

This project focuses on following items:
 - **Checkout times** summarizes the number of rides by trip durations. 
 - **Checkout times by genders** presents the number of rides by trip durations and genders. 
 - **Trips by weekday and time** depicts the number of rides by the time of the day and the day of the week. 
 - **Trips by weekday, time, and genders** expresses the number of rides by time, weekday, and genders. 
 - **Trips by weekday, time, genders, and user types** presents the number of rides by time, weekday, genders, and user types. 

## Analysis

### The number of retirees by titles
Potential retirees are people who were born from 01/01/1952 to 12/31/1955. These people are about to reach retirement age (65) during the period from 2017 to 2020. According to the summary below, the company has retirees in all positions during the time from 2017 to 2020. In specific, the number of retirees as Managers are 2 (lowest), as Assistant Engineers are 1761, as Technique Leaders are 4502, as Staffs are 12242, as Engineer are 14222, as Senior Staff are 28255, and as Senior Engineers are 29414 (highest). 

**Checkout times**

![Checkout times](Images/01_Checkout_times.png)

### The number of retirees by titles and ages
According to the summary below, the number of retirees in each title are speading relatively evenly by age, which are 417 - 458 for Assistant Engineers, 3592 - 3682 for Engineers, 6943 - 7638 for Senior Engineers, 6655 - 7229 for Senior Staffs, 2849 - 3238 for Staffs, and 1069 - 1167 for Technique Leaders. At maanger level, one manager is about to retire each four year. Among groups, Senior Engineer and Serior Staff have the largest quantity of potential retirees. 

**The number of retirees by titles and ages**

![The number of retirees by titles and ages](Analysis/03_retirees_by_title_age.png)

### The number of internal eligible mentors
Eligible mentors are current employees that were born duing 1965. According to the summary below, the number of eligible mentors vary significantly between titles, in which Assistant Engineer and Technique Leader have only 29 and 77 eligible mentors respectively. The groups with highest number of mentors are Senior Engineer (529) and Senior Staff (569). For Staff and Engineer, there are respectively 155 and 190 mentors ready. No mentors exist for the manager level. 

**The number of internal eligible mentors**

![The number of internal eligible mentors](Analysis/02_mentor_by_title.png)

### The number of potential candidates per mentor
Potential candidates are assumed to be equal to the number of retirees. According to the summary below, the number of candidates broken down for each mentor change dramatically by titles. Even though the Senior Staff and Senior Engineer have the most empty positions, they also have the most eligible mentors which lower the number of candidates per mentor (49 and 55). The highest numbers belong to Staff and Engineer with 78 and 74 candidates per mentor. The numbers for Technique Leader and Assistant Engineer are 58 and 60 respectively. 

**The number of potential candidates per mentor**

![The number of potential candidates per mentor](Analysis/04_candidates_per_mentor.png)


### The number of potential candidates per mentor by year
According to the summary below, the number of candidates per mentor by year vary from 11 to 20. The groups with highest numbers are Staff and Engineer with 17 to 20 candidates per mentor due to the limit in the number of eligible mentors. The number for the Staff title is lowest with only 11 to 12 candidates per mentor. 

**The number of potential candidates per mentor by year**

![The number of potential candidates per mentor by year](Analysis/05_candidates_per_mentor_by_year.png)

## Conclusion
 - The company has 90,938 potential retirees in total during the period from 2017 to 2020, which equivalent to averagely 22,735 empty positions each year. The HR department would have to plan carefully and work hard to fulfill these positions either by external hiring or internal promotions. 
 - The potential retirees exist in all levels which might increase the difficulty of filling the empty positions.
 - The number of candidates per mentor vary significantly from 11 - 20 candidates per mentor per year. This could be a heavy task for mentors which might reduce their productivity. The HR department should consider asking retirees to help to reduce the number of candidates per mentor. 

## Limit
 - The report doesn't take into account the impact of internal promotions. For example, when staffs are promoted to be senior staffs, the number of staffs to be hired will increase. 
 - The report doesn't take into account the possibilty where potential retirees decide to retire earlier or later than the retirement age (before and after 65 years old). 
 - The report doesn't take into account the impact of technological advances that might affect the requirements of human labor. 

# Pewlett Hackard Postgres Analysis 

## Overview of Analysis

### Purpose 
Our purpose for the analysis was a continuation from our employee research into Pewlett Hackard's goal to plan for the future by determining the number of upcoming retirements. Previously Pewlett Hackard used Excel and VBA to review employee information, and by upgrading to Postgres SQL to perform this task will help build the database and query the combined results for further insight. Our analysis here is to provide further takeaways from the new database to help Pewlett Hackard efficiently plan for the future. The new tables helped determine the number of retiring employees per their title within the company, and also identify employees who are eligible to participate in a new mentorship program for building up the next wave of candidates.

## Pewlett Hackard Retiree Results

### Analysis Takeaways 
- As shown in the Retiring Titles chart below, there are only 2 current employees with the Manager title who are among the group of employees set to retire in the near future. 
- The significant majority of upcoming Retiring Titles will be from Senior positions, specifically Senior Engineer at 25,916 and Senior Staff at 24,926. 
- The mid-level positions do have a noticeable number of employees considered to be retiring soon but not as significant as the senior positions, for Engineers at 9,285 employees and Staff title at 7,636. 
- The Mentorship Eligibility program with the current criteria has a count of 1,549 employees eligible to participate in the program. 
![Retiring Title Chart](resources/retiring_titles.png)

## Pewlett Hackard Analysis Summary

### Retiree Analysis Outcome and Further Research
Pewlett Hackard will need to fill a total of 72,458 roles within the company when the "silver tsunami" begins to occur and this is determined from the sum of the above Retiring Titles Chart. This chart is compiled from all current employees who are entering the age range to be considering retirement soon. From the Mentorship Eligibility table, the total count of employees who are eligible to participate in the program is 1,549. There is a significant amount more retirement ready employees who can mentor the next group of eligible participants for the program, a recommendation would be to increase the criteria for employees who are eligible to be mentored through the program to take full advantage of the ample number of retiring employees who can mentor the next group. For additional insight into the current mentorship eligible employees, the below query provides the employee information along with their departments. A further breakdown is provided in the Mentorship Department table below that shows the employee count for mentorship eligibility across Pewlett Hackard's departments. 

```

```

![Mentorship Department Table](resources/mentorship_departments.png)






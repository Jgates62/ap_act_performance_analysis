## How does High School AP test performance relate to ACT test performance? And how well do students need to do on their ACT tests in order to get into their college of choice?


act_2019_ca.csv
Source: https://www.cde.ca.gov/ds/sp/ai/

ap18_19.csv
#Data Source: https://www.cde.ca.gov/ds/sp/ai/

sat_act_by_college.csv
Source: https://www.compassprep.com/college-profiles/

This project takes 3 datasets on high school AP test scores, ACT test scores, and college acceptance rates, and seeks to find the relationship between AP test performance and admittance to particular colleges.

|Feature|Type|Dataset|Description|
|:---|:---|:---|:---|
|college_name|object|df_college|School Name|
|test_optional|object|df_college|Whether or not the SAT or ACT was required for application|
|class_yrs|object|df_college|Applies to class year(s)|
|policy_details|object|df_college|Required test guidelines and exceptions|
|num_applicants|int|df_college|Number of people who applied to the current class year|
|accept_rate|object|df_college|Decimal percentage of applicants who were accepted|
|sat_iqr|object|df_college|Interquartile range of applicant's SAT scores|
|act_iqr|object|df_college|Interquartile range of applicant's ACT scores|
|act_iqr_lower|float|df_college|Lower limit of ACT score IQR|
|act_iqr_upper|float|df_college|Upper limit of ACT score IQR|
|scode|float|ap_act_df|School Code|
|ccode|float|ap_act_df|County Code|
|dcode|float|ap_act_df|District code|
|rtype|object|ap_act_df|Record Type: C=County, D=District, S=School, X=State|
|sname|object|ap_act_df|School Name|
|dname|object|ap_act_df|District Name|
|cname|object|ap_act_df|County Name|
|act_enroll12|float|ap_act_df|Enrollment of grade 12|
|act_numtsttakr|float|ap_act_df|Number of ACT Test Takers|
|act_avgscrread|float|ap_act_df|Average ACT Reading Score|
|act_avgscreng|float|ap_act_df|Average ACT English Score|
|act_avgscrmath|float|ap_act_df|Average ACT Math Score|
|act_avgscrsci|float|ap_act_df|Average ACT Science Score|
|act_numge21|float|ap_act_df|Number of Test Takers Whose ACT Composite Scores Are Greater or Equal to 21.|
|act_pctge21|float|ap_act_df|Percent of Test Takers Whose ACT Composite Scores Are Greater or Equal to 21.|
|ap_studentgroup|object|ap_act_df|AP Student Group|
|ap_enroll1012|float|ap_act_df|Number of AP students enrolled in grades ten, eleven, and/or twelve.|
|ap_enroll12|float|ap_act_df|Number of AP students enrolled in grade twelve.|
|ap_numtsttakr|float|ap_act_df|Number of students with AP exam scores as reported by the College Board.|
|ap_numscr1|float|ap_act_df|Number of students with an AP exam score of 1.|
|ap_numscr2|float|ap_act_df|Number of students with an AP exam score of 2.|
|ap_numscr3|float|ap_act_df|Number of students with an AP exam score of 3.|
|ap_numscr4|float|ap_act_df|Number of students with an AP exam score of 4.|
|ap_numscr5|float|ap_act_df|Number of students with an AP exam score of 5.|
|ap_score|float|ap_act_df|Number of students with an AP exam score of 5.|


When we looked at the data for college admissions, it became clear that colleges with lower acceptance rates tended to accept students with higher ACT test scores, but schools with higher acceptance rates were not nearly as selective when it came to ACT scores. Additionally, schools with a very high number of applicants were not necessarily any more selective of ACT scores. When we looked at high school AP test scores and ACT test scores, we found that they are positively correlated, and we recommend that high school students who are interested in attending a particular school pay attention to the average ACT scores of students who were accepted to that school. Once students know what ACT score to target, they can focus their current efforts on improving their AP test scores as necessary.
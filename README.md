# Mental health of International Islamic University Malaysia Students

## Introduction 
This data analysis project gives an insight to the mental health of students studying at International Islamic University Malaysia. By analysing this data set, we hope to identify insights, and make recommendations on how to reduce mental illness among students. 

## Problem Statement

The first step is to define the problem. The questions I am looking to answer are:

1.	How is CGPA distributed across the student population?
2.	What are the trends in the prevalence of mental illness among students across the four academic years? 
3.	Is there any significant correlation between marital status and the prevalence of mental illness? 
4.	What is the distribution of mental illness across different gender groups? 
5.	Is there a relationship between CGPA and the prevalence of mental illness?
6.	What is the age distribution of the student population?


## Data Sourcing 

For this project, the dataset used is gotten from kaggle.com. It has only one table that contains 102 rows and 11 columns 

## Tools 

Microsoft Power BI

## Data Importation 
The dataset was downloaded in Microsoft Excel CSV format and was imported, cleaned and analysed using Power BI.

## Analysis Approach

The data was cleaned in Microsoft power query by checking for duplicates, blank rows, wrong spellings, outliers. An extra column was added called "Mental illness" this is to check for any student who has 1 of the 3 already stated mental illness.

**How is CGPA distributed across the student population?**


![Students_CGPA](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/studentbyCGPA.png?raw=true)


This analysis examines the distribution of student CGPAs across five distinct groupings: 3.50-4.00, 3.00-3.49, 2.50-2.99, 2.00-2.49, and 0.00-1.99. The visualization (represented by purple bars) illustrates the number of students within each CGPA range.

Key observations from the data include:

•	The 3.50-4.00 CGPA group represents the largest segment of the student population, with a total of 48 students.

•	The 3.00-3.49 CGPA group also comprises a substantial portion of the student body, with 43 students.

•	The 2.50-2.99 CGPA group includes 4 students.

•	Both the 2.00-2.49 and 0.00-1.99 CGPA groups contain the fewest students, with 2 students each.

The visualization effectively demonstrates the distribution of student CGPAs, clearly indicating the concentration of students in the higher CGPA ranges.

**What are the trends in the prevalence of mental illness among students across the four academic years?**


![Academic_level](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/Screenshot%202024-12-25%20175832.png?raw=true)


This analysis examines the prevalence of mental illness across four academic levels. The visualisation presents the total number of students reporting mental health struggles at each level.

Key observations reveal a notable trend:

•	A significantly higher prevalence of mental illness is observed among Level 1 students, with a total of 25 students affected.

•	The prevalence exhibits a consistent downward trend across subsequent academic levels, culminating in only 2 students reporting mental health struggles at Level 4.

**Is there any significant correlation between marital status and the prevalence of mental illness?**


![Marital_status](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/Screenshot%202024-12-25%20175758.png?raw=true)


This analysis examines the distribution of mental illness among students based on their marital status. The data reveals a significant difference in the prevalence of mental illness between unmarried and married students:

•	Of the students reporting mental illness, 48 are unmarried.

•	16 married students are also experiencing mental health challenges.

**What is the distribution of mental illness across different gender groups?**


![Students_gender](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/Screenshot%202024-12-25%20175645.png?raw=true)


This analysis examines the distribution of mental illness across two gender groups. The visualization clearly illustrates a significant disparity in the prevalence of mental illness between female and male students.

Key findings:

•	Female students represent a significantly larger proportion of those reporting mental illness, with 48 students (75% of the total).

•	Male students account for a smaller proportion, with 16 students (25% of the total). 

**Is there a relationship between CGPA and the prevalence of mental illness?**


![Students_CGPA](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/Screenshot%202024-12-25%20175712.png?raw=true)


This analysis examines the relationship between CGPA and the prevalence of mental illness among students. The visualization illustrates the distribution of students experiencing mental health challenges across five CGPA groupings: 3.50-4.00, 3.00-3.49, 2.50-2.99, 2.00-2.49, and 0.00-1.99.

Key findings indicate a higher prevalence of mental illness among students with higher CGPAs:

•	The 3.50-4.00 CGPA group exhibits the highest number of students reporting mental health struggles, with a total of 31 students.

•	The 3.00-3.49 CGPA group also shows a substantial number of affected students, totaling 28.

•	The 2.50-2.99 CGPA group includes 3 students.

•	The 2.00-2.49 and 0.00-1.99 CGPA groups have the lowest number of students reporting mental illness, with 1 student each.

**What is the age distribution of the student population?**


![Students_age](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/Screenshot%202024-12-25%20175900.png?raw=true)


This analysis examines the age distribution of the student population, providing insights into the demographic makeup of the student body. The data encompasses students aged 18 to 24.

Key observations regarding the age distribution include:

•	Students aged 18 constitute the largest portion of the population, with 32 students.

•	Students aged 24 represent the second largest group, with 23 students.

•	The number of students aged 19 is 21.

•	There are 13 students aged 23.

•	Students aged 20 comprise a smaller group, with 6 students.

•	The smallest groups are students aged 21 and 22, with 3 and 2 students, respectively.

 
 ## Dashboard Snapshot (Power BI DESKTOP)

 ![Dashboard_snapshot](https://github.com/Lawahle/Mental-health-of-International-Islamic-University-Malaysia-Students/blob/main/dashboard.png?raw=true)


## Insights

A single page report was created on Power BI Desktop.

Following inferences can be drawn from the dashboard;

**Total students: 101**

This figure represents the total count of students analysed.

**Male students : 26**

This figure represents the total number of male students which is 24.8% of the total students.

**Female students: 75**

This figure represents the total number of female students which is 74.3% of the total students.

**Students with mental illness: 64**

This figure is the total count of students with at least one mental illness which makes up 63.4% of the total students.

**Students seeking treatment: 6**

This figure represents the number of students who has seek any specialist for treatment. This is 9.4% of the students with mental illness.

This analysis also reveals several key insights into student academic performance, mental health, and demographics.

**Academic Performance:** The CGPA distribution indicates a strong overall academic performance within the student population, with a higher concentration of students in the 3.00 and above CGPA range. This suggests that a significant portion of the student body is achieving strong academic results.

**Mental Health Prevalence and Contributing Factors:** Several factors appear to be associated with student mental health:

• **Academic Level:** A significantly higher prevalence of mental illness is observed among Level 1 students. This can likely be attributed to the challenges associated with transitioning to a new academic environment, increased academic workload, and the pressure to succeed, all of which can contribute to heightened stress and vulnerability to mental health challenges.

• **Marital Status:** Unmarried students report a considerably higher prevalence of mental illness compared to married students. This disparity may be related to the social support often provided within marriage, which can act as a buffer against stress and mental health difficulties.

• **Gender:** A significant difference exists in the reported prevalence of mental illness between male and female students. This difference is likely influenced by societal stigma surrounding men's mental health, which can discourage reporting and help-seeking behavior. Additionally, social and cultural expectations, along with experiences of gender inequality or discrimination, may contribute to the observed differences in mental well-being between genders.

• **CGPA:** Counterintuitively, a higher prevalence of reported mental illness is observed among students with higher CGPAs. This may be due to the increased academic pressure and perfectionistic tendencies often associated with high achievement, leading to elevated levels of stress and anxiety.

**Student Demographics:** The age distribution of the student population reveals a bimodal pattern, with peaks at ages 18 and 24. This suggests the presence of two distinct student groups: traditional freshmen entering directly from secondary education (age 18) and a significant population of non-traditional students (age 24), potentially including transfer students, returning students, or graduate students.

## Recommendations
Based on the analysis, the following recommendations are proposed to enhance student academic success and well-being:

**Academic Support:**
To address the performance of students in lower CGPA ranges, a targeted approach is recommended:

• **Targeted Academic Intervention:** Analyze student performance data in individual courses to pinpoint specific areas of academic difficulty. Based on this analysis, implement targeted interventions such as tutoring, mentoring, and academic advising programs designed to help these students improve their academic standing and achieve parity with their peers. This focused approach will contribute to overall student academic success.

**Mental Health Support:**

Several recommendations address the prevalence of mental health challenges observed within the student population:

• **Support for Level 1 Students:** Given the higher prevalence of mental illness among Level 1 students, it is crucial to investigate the specific stressors and challenges they face during their transition. This includes a timely review of course loads, assessment schedules, and the adequacy of available academic support resources at each level. Furthermore, the introduction of social integration programs, peer support initiatives, and improved access to counseling services for all levels, particularly Level 1, is strongly recommended.

• **Support Based on Marital Status:** To address the disparity in mental health prevalence between married and unmarried students, an investigation into the availability and utilization of social support resources is necessary. This includes on-campus support groups, counseling services, and social activities tailored to the needs of both groups.

• **Gender-Specific Support:** To address the observed differences in mental health prevalence between male and female students, a multi-faceted approach is needed. This includes conducting qualitative research (e.g., focus groups and interviews) to understand the perceived barriers to help-seeking among male students. Based on these findings, targeted awareness campaigns should be implemented to address stigma and promote help-seeking behavior. Furthermore, research should be conducted to investigate social and cultural factors contributing to gender-based differences in mental health, including surveys or focus groups to gather data on students' experiences with gender-related stressors.

• **Comprehensive Mental Health Services:** The finding of higher mental illness prevalence among higher-achieving students underscores the need for comprehensive mental health support services available to all students, regardless of their academic performance. This ensures that students facing mental health challenges have access to appropriate resources and support, irrespective of their CGPA.

**Student Demographics and Tailored Services:**

The bimodal age distribution highlights the need for tailored services and programs to enhance the student experience for all age groups. Further investigation into the characteristics and needs of both traditional (new) and non-traditional (returning/older) students is recommended to inform the development of these tailored support services.


## Conclusion

This analysis reveals generally strong academic performance, but highlights significant mental health challenges, particularly among Level 1, unmarried, and female students, as well as high-achieving students. A bimodal age distribution indicates distinct traditional (18-year-old) and non-traditional (24-year-old) student groups. Recommendations include targeted academic interventions for lower CGPA students, enhanced mental health support tailored to academic level, marital status, and gender, and further investigation into the needs of different age groups to inform tailored services. Comprehensive mental health services for all students, regardless of academic performance, are crucial.


# Team 7 MIST 4610 Group Project 2
[Sean Dixon]https://github.com/seanDixon04/expert-train.git 

[Manny Walia]https://github.com/msw05090/bookish-meme

[Daniella Raj]https://github.com/daniellaraj/didactic-computing-machine.git

[Jacob Gates]https://github.com/jgates01/fantastic-octo-umbrella

# Data Set Description 
This dataset was found on data.gov. It includes the attendance rate for public school students PK-12 by student group and by district during the 2021-2022 school year. The student groups include those experiencing homelessness, disabilities, those who qualify for free/reduced lunch, English learners, all high needs students (includes students who are English language learners, who receive special education or qualify for free and reduced lunch), and non-high needs students. It also lists students by their race/ethnicity (Hispanic/Latino of any race, Black or African American, White, and all other races). Attendance rates are provided for each student group by their district and for the state. The data columns consist of the categories of students, the locations, districts, attendance rates, student counts, and reporting periods. When no attendance data is displayed in a cell, the data has been suppressed to safeguard student confidentiality, or it ensures that statistics that are based on a very small sample size are not interpreted as equally representative as those based on a sufficiently larger sample size. 

# Questions 
Question 1 - Question 1 allowed us to take Connecticut's attendance mass data and separate it by race and school year. Not only was it able to clearly portray how the different school years were divided up, but it also helped us lead to a more precise graph in question 2. Actual attendance per race each year allowed readers to understand the racial disparity in school attendance within the state of Connecticut. Many make assumptions that less wealthy races typically have a lower attendance rate, and this graph proves that. However, many other variables affect attendance. For example, the graph states that whites were dominant in school attendance, but the state of Connecticut could also have a much higher percentage of white residents. Another question this graph could help interpret is the population of the minority student body within Connecticut. 

Question 2 - What was the variance in attendance rates between the different races of students in the years 2021 and 2022?
This question is very informative in many ways. First off, socially, it can be helpful to see the attendance disparities among different races. Could there be barriers faced by a certain race within the district that doesn't allow them fair access to education?, the graphic generates thought provoking questions as so. Policymakers within the education system could view the graphic and make changes for targeted groups to improve opportunities for students of all races. Secondly, as far as economic impact, school funding can be correlated to attendance. If students are consistently present, schools will be more likely to receive money for their needs. Having information about the attendance allows the policymakers to distribute money and resources to schools in need. Lastly, the cultural impact. Having a diverse body of students in each district is important because it creates a more inclusive and healthy environment. All students feeling comfortable and included is of utmost importance. 

# Data Manipulations

Graphic 1- Actual Attendance per Race by Year

Columns: Measure Names(Discrete)- Measure Names in the columns tab allows us to view the different years of students in each column. The field is blue, or discrete, because the measures/dimensions are finite, meaning there are a set number of students in each class.

Rows: Measure Values(Continuous)- The rows represent the number of students in attendance from each year. There are hundreds of thousands of students so the y-axis is shown in increments of 50k students.

Marks: 
Student Groups(Color)- The student group color filter visualizes the different races of students in the chart. You can now see the variation of races in the amount of students per class.

Student Groups(Text)- In addition to color, there is a text filter added as well. The text filter adds the name of the race over the color so that you can know the race of the color that you’re looking at. For example, the gray section of the bar graph shows the amount of white students and is labeled “White”.

Measure Values: SUM( Students from the different classes)- These filters are enabling us to add up the total number of students from each race, for each year. It lets us track the total number of students from each class.


Graphic 2- Percentage of Attendance by Race in Western Districts

Columns: 2020-21, 2021-22 Attendance(Continuous)- The columns visualize the attendance rates, in percentages, of the different groups. There are two columns, one for 2020-21, and one for 2021-22, respectively.

Rows: Student Group and District Name(Discrete)- The rows are split into two parts for each race. Each of the races has their own row, but there are subsections in each one that represent the different Western districts. There are 4 different race groups listed, and 5 districts per group, meaning that there is a total of 20 rows.

Marks:
Student Groups(Color)- The color filter visualizes the different races by making each one its own color. There is also a Student Group color key that goes along with each race.

Student Groups(Text)- The text filter is used to show the exact percentage next to the dots on the graph. This provides the viewer with more reliable knowledge rather than just having to approximate the percent by looking at the x-axis.

# Analysis/Results
Question 1 - Graph One portrays that the school year of 2019-2020 had the highest attendance rate among the three school years listed. The years 2020-2021 and 2021-2022 stayed consistent, but there was a significant drop-off after 2019-2020. The attendance rate by race stayed pretty consistent. The attendance of the white race was a dominant leader in all three school years. The white race attendance started at around 245,000 and declined to around 235,000. Hispanic/Latino attendance remained consistent at around 100,000-125,0000. Black was third, with around an attendance of 50,000-75,000. Lastly, we had All other Races at a consistent number of around 40,000.

Question 2 - 

# Tableau 
#### Question 1
![Q1](https://github.com/msw05090/refactored-octo-fiesta/assets/163200076/25175a65-d300-41f1-bf78-00c2ba060cac)
#### Question 2
![Q2](https://github.com/msw05090/refactored-octo-fiesta/assets/163200076/d4d97481-7b4f-4399-8106-681f47a54027)





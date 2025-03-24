# KY COUNTYWISE DEMOGRAPHIC DIVERSITY INFORMATION-2023 
# Table of Content
- [Introduction](#introuction)
- [Functionalities](#functionalities)
- [Data Model](#datamodel)
- [User Interface Development](#ui)
- [Challenges](#challenges)
- [Potential Improvements](#imporovements)
- [Conclusion](#conclusion)


# Introduction
This app visaulizes the population of differenet ethnic groups in various counties of Kentucky based on 2023 data. Demograhic data is taken from [data-link](http://ksdc.louisville.edu/data-downloads/estimates/).

# Functionalities
- For a selected county of Kentukcky, app shows the population count of the ethencities (White, Black, Hispanic, Asian and Other) in the bar/column chart
- App also shows the respective number of the population count a the top of the bar
- App also presents a map showing different counties of the Kentucky for reference

# Data Model
- After working with multiple sheets excel files Comma seperated Values (.csv ) file is created using Python and scientifc libarary: Pandas. 
- The csv file is uploaded and data table is created in the Power App Dashboard

# User Interface Development
- In the dashboard, user inputs the County name.
- The program selectes the data based on the selected county and creates a bar/column chart. 
![app ](pictures/powerapp.png)

# Challenges
- Data filtering took a considerable amount of time.
- It also took time to understand how different components of the container behaviour and its tweaking to get the desired result.

# Potential Improvements
- This app can be extened to use more demographic data across multiple years

# Conclusion
- This app creating skill and concepts easily transfers to Lab Scanerios. This approach with necessary modification can be implemented to multiple lab scanerios. For example we can track the use of different chemicals for different time period. We can track the growth of microbes in the lab with same concept. We can track the diversity of students in different labs. 


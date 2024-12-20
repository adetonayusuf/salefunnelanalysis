![image](https://github.com/user-attachments/assets/0ed72152-ab46-4e37-8287-cccdfb7f4ead)# salefunnelanalysis

## Overview

Following its official launch, LearnX rolled out an extensive marketing campaign, with different strategies including giving out free coupons to access paid courses & programs. This campaign strategy was successful in creating a buzz in various tech communities, and drew the attention of many users curious about LearnX courses. 

 
However, despite a significant number of users exploring courses, LearnX notices a disparity when it comes to the final enrollment numbers. In other words, while many people were seen exploring courses on LearnX, only few people enrolled on the platform.

 
This is a significant problem for LearnX, as it is preventing the company from reaching its full potential. It is also a costly problem, as LearnX is investing resources into marketing and acquiring new leads, only to lose them at the enrollment stage.

## Rationale For The Project
Sales funnel analysis provides a way to see how many people are taking each step on their way to buying from you. It helps you find where people are getting stuck and make changes to improve your sales process.

For example, you might find that a lot of people are visiting your website but not adding shoes to their cart. This could either mean that your website is not doing a good job of convincing people to buy your shoes, or it’s too complex to navigate. Once you know where people are getting stuck, you can make changes to improve your sales process. 

For LearnX, analyzing the sales funnel in the application process can help identify where users are dropping off, take actions to optimize its sales funnel, and  increase the number of students who enroll in its courses.

## Aim Of The Project
The main objective of this project is to analyze the course application funnel of LearnX, and finding out why users find it difficult to transition from course exploration to successful application.

 Identify the points where users typically drop out of the enrollment process. 
 Prepare a presentation slide documenting the insights. 
 Provide recommendations to optimize the sales funnel and increase conversion rates. 

 ## Data Description
 
LearnX has provided 8 files containing its website Page Visit information, and 1 file containing Users information. 

Users Table

 User_id: Unique identifier for all users that visited the website. 
 Date: Date the user visited the website 
 Device: Device used to visit the website  
 Gender: User Gender (Male or Female) 
Landing Page Table

 User Id: Unique Identifier of user that visited the Landing Page 
 Page: Page name the user visited 
Course Exploration Table

 User Id: Unique Identifier of user that visited the Course Exploration Page from the landing page 
Page: Page name the user visited

Signup Table

 User Id: Unique Identifier of user that visited the Sign-up Page from the course exploration page 
 Page: Page name the user visited 
Course Preview Table

 User Id: Unique Identifier of user that visited the Course preview Page after signing up or logging in 
 Page: Page name the user visited 
Enrollment Table

 User Id: Unique Identifier of user that visited the Course enrollment Page after previewing the course 
 Page: Page name the user visited 

 ## Tech Stack
 
The data would be analyzed in Power BI with Microsoft Excel used as the data source.

## Project Scope

Data Aggregation: Collect all necessary data and connect to power  BI

Data Wrangling: Wrangle the data and transform into a format needed for the analysis

Analysis & Visualization: Analyze data, define KPIs, and visualize it in Power BI

Report Presentation: Prepare a presentation slide to present analysis findings

## Dashboard & Findings
After importing the csv files into power query. I merged all the tables into a single and extract only the page columns for each tables. After then I converted the null values on all columns to zero and values of the pages columns to 1. I loaded only the merged table into power BI and carry out some analysis to understand the data better.


![Page Trend](https://github.com/adetonayusuf/salefunnelanalysis/blob/main/Page%20Trend.png)

The above dashboard shows the conversion rate for each page on the company's website and trend on a daily basis.

The funnel chart below shows the conversion rate by gender and device. It shows that majority of visitor on the company's site use thier desktop compare to phone. There's equal distribution between the gender.

![Funnel Chart](https://github.com/adetonayusuf/salefunnelanalysis/blob/main/Funnel%20Chart%20for%20Device%20%26%20Sex.png)

The dashboard shows the general overview of visitor activities on each page

![Funnel Chart](https://github.com/adetonayusuf/salefunnelanalysis/blob/main/Conversion%20Monitoring%20Dashboard.png)

Base on the above dashboards below are the insight and recommendations

## Insights

Given the analysis of LearnX's application funnel and the observed conversion rates, the focus should initially be on optimizing and improving the Signup Page. Here's why:
Significant Drop-off Point: The transition from the course exploration page to the signup page sees a notable reduction in conversion rate (from 71.8% to 43.4%). The decline from signup to preview (down to 13.1%) indicates that users are either losing interest or encountering obstacles that prevent them from moving forward, which makes it a key area for optimization to boost overall conversion rates. 

Potential for Immediate Impact: Addressing issues at the signup stage can have an immediate and cascading positive effect on the subsequent stages of the funnel. Improving the signup process can lead to more users entering the funnel's later stages, thereby increasing overall conversion rates.

## Recommendation

1. Simplify the Signup Process: Reduce steps/fields and offer social/email logins.
   
2. Ease of Navigation: Ensure that once users sign up, it's straightforward for them to navigate to the course preview. This could involve optimizing the user interface  
   and providing clear, compelling calls-to-action.
   
3. Engagement and Incentives: Motivate users with personalized recommendations, previews, or limited time access to exclusive content.
   
4. A/B Testing: Implement A/B testing on different versions of the signup page to understand what changes lead to higher conversion rates.
   
5. Monitor Conversion Trends: Regularly track conversion rates at each funnel stage to adapt and improve signup over time.








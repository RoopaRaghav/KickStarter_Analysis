# Kickstarting with Excel

## Overview of Project
 Performing Analysis on KickStarter Data to Uncover trends.
 Import dataset into Excel worksheets.
 Apply filters and create new columns as required to better understand the data.
 Creating pivot tables and charts to visualize the data.
 Understanding any outliers are affecting the data.

### Purpose
Louise’s (Customer/Client) play Fever came close to its fundraising goal in a short amount of time. Now, the client wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset the campaign its understood that outcomes are related based on their launch dates and their funding goals. So a written report is generated based on the analysis and the visualizations created using Excel.

## Analysis and Challenges
As part of UC Boot Camp weekly Challenge the Analysis is done based on the skills learnt in the Excel Module.The challenges are to study and analyze the kickstarter dataset and then create two analyses: outcomes based on goals and outcomes based on launch date that interests client. 

### Analysis of Outcomes Based on Launch Date
This analysis is done based on the Outcomes based on the launch date for the client interested parented category "Theater".The chart suggests that during the months of May and June the successful outcomes are high compared to failed and canceled. The Live outcomes are minimal and did not affect the analysis. 

![image](https://user-images.githubusercontent.com/111100908/185477744-65fbb2f2-4abe-499a-8580-9c200261845a.png)

### Analysis of Outcomes Based on Goals
This analysis is done based on the Outcomes based on Goals for the client intereted subcategory "Plays".The chart suggests that at lower goal values the percantage of successful outcomes of the project are more. As the goal value increased the success rate decreased. In this analysis also the Live outcomes are minimal and not considered.
![image](https://user-images.githubusercontent.com/111100908/185483709-dbbde492-dc9f-4210-8288-69eb0ad8c5c4.png)



### Challenges and Difficulties Encountered
The percentage of canceled projects are zero or very minimum in both the analysis shows that the analysis has ouliers.But the canceled projects were cross checked with actual dataset and found that the results visualised in charts are appropriate.

There were few difficulties while caluculating the outcomes based on the range of Goal amount. The outcomes were calculated based on $5000 increments in the analysis.
To make it easy the table is added with two extra columns Goal min range and max range and used them in the CountIFS operation.
![CountIFS](https://user-images.githubusercontent.com/111100908/185482015-9173bccb-5b53-496f-9de5-b6e8bf775336.png)


## Results

## What are two conclusions you can draw about the Outcomes based on Launch Date?
-   According to the Pivotchart and table of Theater Outcomes by LaunchDate
-   The Successful outcomes are more in the month of May and June.
-   After the June month the Successful outcomes has steadily dropped and by the end of the year in December month 
    there were only 2 successful outcomes compared to failed.

## What can you conclude about the Outcomes based on Goals?
-   According to the Outcomes based on Goals Pivot chart and table
-    The percentage of goals successful and failed complemented each other as the goal value increased for the subcategory Plays.
-    At the lower goal value the successful percentage is more and vice versa.
-    The number of total successful projects are double compared to failed with lesser goal value.

## What are some limitations of this dataset?
-  The Dataset doesnot have canceled projects in the client interested Theater/Plays. 

## What are some other possible tables and/or graphs that we could create?
  -We could generate how many staff picked goals outcomes within the deadline are successful, failed or canceled applying a country filter.
    


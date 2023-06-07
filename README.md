# Crowdfunding Data Analysis

## Background
In this project, I analyzed a database of 1,000 sample crowdfunding projects to uncover hidden trends and gain insights into the crowdfunding market. The data was generated by edX Boot Camps LLC and is intended for educational purposes only.

## Data Analysis
To analyze the sample-project data, I performed the following tasks:

* Conditional Formatting: I used conditional formatting to color code the cells in the "Outcome" column based on the campaign's status (successful, failed, canceled, or live).

* Percent Funded: I created a new column called "Percent Funded" that calculated the percentage of funding a campaign received relative to its initial funding goal. The cells in this column were formatted using a three-color scale, ranging from dark red (0%) to green (100%) and blue (200%).

* Average Donation: I calculated the average amount contributed by each project backer and recorded the values in the "Average Donation" column.

* Parent Category and Sub-Category: I split the "Category" and "Sub-Category" column into two separate columns called "Parent Category" and "Sub-Category" using formulas.

## Category Stats
To analyze the data at the category level, I created a new sheet with a pivot table that counted the number of successful, failed, canceled, and live campaigns per category. I also created a stacked-column pivot chart that could be filtered by country.

## Subcategory Stats
At the subcategory level, I created another sheet with a pivot table that counted the number of successful, failed, canceled, and live campaigns per sub-category. Similar to the category analysis, I created a stacked-column pivot chart that could be filtered by country and parent category.

## Date Conversion
The dates in the "deadline" and "launched_at" columns were provided as Unix timestamps. To convert them into a readable format, I created two new columns: "Date Created Conversion" and "Date Ended Conversion." These columns used specific formulas to convert the Unix timestamps into Excel's date format.

## Outcomes Based on Launch Date
To analyze the outcomes based on the launch date, I created a new sheet with a pivot table. The pivot table had columns for outcomes, rows for the converted launch dates, values based on the count of outcomes, and filters based on parent category and years. I also visualized this data by creating a pivot-chart line graph.

## Report in Microsoft Word
I created a report in Microsoft Word to answer the following questions:

* Conclusions about Crowdfunding Campaigns: I drew three conclusions based on the provided data, highlighting trends and patterns in crowdfunding campaigns.

* Limitations of the Dataset: I discussed the limitations of the dataset, acknowledging any potential shortcomings or biases.

* Additional Tables and Graphs: I suggested other possible tables and graphs that could be created to provide additional value and insights beyond the initial analysis.

## Crowdfunding Goal Analysis
To analyze the relationship between crowdfunding goals and project outcomes, I created a new sheet with eight columns. The "Goal" column had 12 rows representing different goal ranges. I populated the "Number Successful," "Number Failed," and "Number Canceled" columns using the COUNTIFS() formula. Based on these data points, I calculated the total number of projects and the percentages of successful, failed, and canceled projects per goal range. Finally, I created a line chart to visualize the relationship between goal amounts and project outcomes.

## Statistical Analysis
To gain a deeper understanding of campaign backers, I created a new worksheet with columns for the number of backers of successful and unsuccessful campaigns. Using Excel, I evaluated summary statistics for both successful and unsuccessful campaigns, including the mean, median, minimum, maximum, variance, and standard deviation of the number of backers. I also determined whether the mean or the median better summarized the data and analyzed the variability between successful and unsuccessful campaigns.

Please refer to the project files and report for more detailed information and insights gained from the analysis.

Note: This README file provides an overview of the project and the actions taken. For more specific details, please refer to the project files and report included in the shared link.

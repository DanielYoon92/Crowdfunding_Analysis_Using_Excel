**Background**

Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success. To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. I will organize and analyze a database of 1,000 sample projects to uncover any hidden trends.

**My Tasks**

I had a task to analyze a table containing a database of 1,000 sample crowdfunding projects in order to uncover market trends.

The dataset for this project was generated by edX Boot Camps LLC, and it was intended for educational purposes only.

My first task was to use conditional formatting to fill each cell in the "Outcome" column with a different color, depending on whether the associated campaign was successful, failed, canceled, or was currently live.

Next, I needed to create a new column called "Percent Funded" that used a formula to calculate how much money each campaign made relative to its initial funding goal. I then applied conditional formatting to fill each cell in the "Percent Funded" column according to a three-color scale, starting with a dark shade of red at 0, transitioning to green at 100, and blue at 200.

To analyze the average donation for each project, I created a new column called "Average Donation" using a formula to calculate the average amount paid by each project backer.

I also created two new columns, "Parent Category" and "Sub-Category," by using formulas to split the existing "Category" and "Sub-Category" column into separate columns.

For category statistics, I created a new sheet with a pivot table that analyzed the initial worksheet to count the number of successful, failed, canceled, and live campaigns per category. Additionally, I created a stacked-column pivot chart that could be filtered by country based on the created table.

Similarly, for subcategory statistics, I created another new sheet with a pivot table that analyzed the initial sheet to count the number of successful, failed, canceled, and live campaigns per sub-category. I also created a stacked-column pivot chart that could be filtered by country and parent category based on the table.

The "deadline" and "launched_at" columns in the dataset used Unix timestamps. Fortunately, there was a formula available that could be used to convert these timestamps to a normal date. I created two new columns, "Date Created Conversion" and "Date Ended Conversion," which used this formula to convert the data in the "launched_at" and "deadline" columns into Excel's date format.

Next, I created a new sheet with a pivot table that included columns for outcome, rows for "Date Created Conversion," values based on the count of outcomes, and filters based on parent category and years. This pivot table provided insights into outcomes based on launch date. I also created a pivot-chart line graph to visualize the data.

After completing the above tasks, I created a report in Microsoft Word to answer the following questions:
1. Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
2. What are some limitations of this dataset?
3. What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

Moving on to crowdfunding goal analysis, I created a new sheet with eight columns: "Goal," "Number Successful," "Number Failed," "Number Canceled," "Total Projects," "Percentage Successful," "Percentage Failed," and "Percentage Canceled." In the "Goal" column, I added 12 rows with specific ranges. This table showed the percentage of projects that were successful, failed, and canceled based on their crowdfunding goal. I used the COUNTIFS() formula to count the number of successful, failed, and canceled projects within each goal range and populated the corresponding columns.

To analyze the relationship between a goal amount and its chances of success, failure, or cancellation, I created a line chart based on the data from the goal analysis table.

Moving on to statistical analysis, I created a new worksheet and added two columns: one for the number of backers of successful campaigns and another for unsuccessful campaigns. This table allowed me to evaluate the summary statistics of the number of backers for both successful and unsuccessful campaigns.

Using Excel, I calculated the mean, median, minimum, maximum, variance, and standard deviation of the number of backers for successful campaigns. I then repeated the process for unsuccessful campaigns.

Finally, I used the gathered data to determine whether the mean or median better summarized the number of backers and analyzed the variability between successful and unsuccessful campaigns. I considered if the observed differences made sense and provided reasoning for my conclusions.




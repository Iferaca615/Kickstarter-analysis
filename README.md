# Kickstarter-analysis
performing analysis on kickstarter data to find trends
# Kickstarting with Excel

## Overview of Project:

  The goal of this analysis was to draw conclusions and further visualize the data on the dataset, \"Kickstarter.xlsx"\.

In this challenge, I was trying to help Louise better visualize and understand how other campaigns did based on their launch dates and fundraising goals.  The purpose of this challenge was to collect and organize data in various ways in order to make unreadable data, readable, to our client Louise.  From the data, we were able to draw various conclusions. 

## Analysis and Challenges

  * I was able to preform my analysis by creating two sheets in \"Kickstarter_Challenge"\, named \"Outcomes Based on Launch Date"\, and \"Outcomes Based on Goals"\.  
      - The first analysis was made using a pivot table to help visualize the number of successful, failed and canceled theater campaigns in regard to their launch month and could be filtered by year as well as by parent category in order to see different types of campaigns and not just theater.
      - The second analysis visualized the Outcomes based on a range of Goals of various campaigns and data points from the dataset \"kickstarter"\, as well as graphing the data based on the percentage of success, failure and cancelation.
      ### Data Visualizations
      1) ![Theater_Outcomes_Vs_Launch](Theater_Outcomes_Vs_Launch.png)
      2) ![Outcomes_vs_Goals](Outcomes_vs_Goals.png)
      3) ![outcomes_launchdate_table](outcomes_launchdate_table.png)
      4) ![outcomes_vs_goals table](outcomes_vs_goals_table.png) 
---

### Analysis of Outcomes Based on Launch Date

* After creating a pivot table to better display the data regarding outcomes of theater campaigns versus their launch dates, some things were made very clear.
	- Overall, most theater campaigns are successful and less than 3% off all kickstarter campaigns are canceled.
* To better see trends within the data of the pivot table, I created a pivot chart.  From the chart we can see that;
	1) The most successful time to launch is May through June
		- ~65% succeed during these months
	2) The least successful time to launch is December
		- ~50% fail in December


### Analysis of Outcomes Based on Goals

* The data is being displayed as fundraising goal range versus percentage of campaigns succeeded/failed.  Looking at \"outcomes_vs_goals_table.png" we were able to see that as the range of the goals increased the number of fundraising campaigns in that category fell  in the single digits range. Because of the lack of data points in these ranges, the data from around a goal of 20,000 is less meaningful than the data in the ranges <1,000 to 15,000.
	- You can also see that far fewer campaigns are launched with higher funding goals, and that instead, most campaigns are launched with goals under 5,000.
* You can see from \"Outcomes_vs_Goals.png" that the relationship between fundraising goal and percent success rate is an inverse relationship.  This shows that as the fundraising goals increase in amount, the percent rate of those campaigns succeeding decreases.  
* From this data it is also visible that most campaigns go until they either fail or succeed, they don't cancel.  Cancellations don't play a major role in impacting the data.

---
### Challenges
1) bash error:  file or directory does not exist:
	* this was the main error that I ran into when I was trying to use git commit to commit my files to my project repository.  The folder that I created on my desktop named, "Analytics_projects' was not reachable using my "cd" command.  I tried using "pwd" to see which directory I was in and then used "ls" while in the desktop directory to see if the folder would show up.  The file was shown under Desktop, but for some reason was still unreachable to be used with "git commit". 	
		- **Solution:** I created a new directory using "mkdir" and then transferred my files from \"Analytics_projects" into the new directory.  Once I did this, I was able to access the correct directory and was able to copy my repository into it.  From there I used my text editor to edit my README file and make changes to my files and then add, commit, and push my changes to my GitHub repository.
2) ssh key:
	* When I went to copy my repository to Kickstarter-analytics directory I realized I didn't make an SSH key.  After I went through all of the steps to create the key, when I went to clone my repository I had an error come up regarding an invalid ssh key.  I was confused because the key uploaded into GitHub just fine so I didn't understand what the issue was.
		- **Solution:**  Instead of using the SSH key, I ended up using the HTTPS key to clone my repository into my Kickstarter-analysis directory and from there I was able to get all of my files and updates to register to GitHub.
3) Readme File:
	* While writing my README file I was having some difficulties with the formatting of my paragraphs as well as getting my links to the PNG pictures to work. My PNG files ended up working under the header, "Data Visualizations", however when I tried inserting the same file down into another header, the link wouldn't work.
		- **Solution:**  I didn't end up getting the link to work under a new header, so I just included all of my images under the header data visualizations. I believe the issue was due to the spacing of my tab key.  When I had first started writing my README file I had done so within GitHub using the edit button.  I would then just commit my changes to GitHub from there.  However, after I got my git clone to work and I was able to get my files in my repository, I started writing my README file in Text editor and using git commit to commit to my repository.  I think the spacing is a little different in text editor than it is on Github.

## Results

- Conclusions: "Outcomes versus Launch date"
	1) **Most** successful campaigns launch May-June
	2) **Least** successful campaigns launch December

- Conclusions: "Outcomes versus Goals"
	1) As the fundraising goal increases, more campaigns begin to fail
	2) Most successful fundraising range is less than 5,000
	3) There is not enough data available in the higher goal ranges for the data to be as meaningful as the data with more data points.

- Limitations of this dataset:
	1) The dataset was very large and was spread over many different categories.  Having included different currencies, different countries, and different times, there were many other outside factors that could have impacted our data that we were not aware of.  The data that we collected for Louise was very filtered and often left out some data that otherwise could have been very useful to draw more conclusions.

- Other possible tables and/or graphs:
	1) A box and whisker graph would be helpful to show the averages of the data as well as to identify outliers in the data set.


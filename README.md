## Console Video game Markert analysis 
by Max Johnson 
### Data 
[Video Game Sales with Ratings
](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings/data)
### Abstract
This is a portfolio project and my main goal was to combine my knowledge of both SQL and Tableau. I started off by finding a dataset on Kaggle. After importing the dataset into BigQuery and structuring the data according to my requirements, I proceeded to transfer it to Tableau for the purpose of creating visualizations.

### Background 
It is 2018 and I am an entry level data analyst and I am assigned to the company "ABC Developers" a new and up and coming developers. After some questioning I realized what they were asking for. "A dashboard to better help them understand the console market and the impact of their decisions both globally and regionally" ,the most important decisions being outlined as : console exclusivity and the genre of their games.


### Cleaning Data 
In shaping the dataset, I converted the Year_of_Release to an integer and filtered records for the years 2010 through 2016. I grouped up the data to get an understanding of the various platforms, and a subsequent categorization by major companies (Nintendo, Sony, Microsoft) was done. To streamline the dataset, unnecessary columns were removed, focusing on key variables. Addressing duplicate game names resulting from multi-platform releases, I kept duplicates, using Concat to combine the Names with the platforms they were released on, distinguishing each value. A specific duplicate issue was manually resolved in Google Sheets. These steps were crucial for aligning the dataset with the project's goals, preparing it for Tableau visualizations.

###  Visualization
Link to [dashboard](https://public.tableau.com/app/profile/maximillian.johnson/viz/VideoGameDashBoard_17032090372230/Dashboard1) I decided to make both the pie chart showcasing a given companies market share and a bubble chart of the most popular genres as filters. My reasoning is that considering these some of the most important decisions ABC developers can make, they should be able to use the dashboard to elaborate on these decisions.


### So What? 
ABC Developers should be able to use the dashboard to have a general understanding of the markets of various genres and companies. An example could be if they wanted to make a puzzle game, they could filter for it to see that Nintendo holds almost 98% market share with Nintendo themselves being the largest publisher for the genre. Overall this dashboard should fit the stakeholders needs.





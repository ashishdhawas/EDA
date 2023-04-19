# EDA
Abstract:

The hotel industry has a very peculiar set of booking arrangements with different distribution Channels. The Space team has worked on the hotel industry dataset to get a comprehensive image of the hospitality industry. From basic data visualizations to complex multivariate analysis, we have performed data analysis at every level of the dataset to draw out key insights about the industry.

Problem Statement:

We have been put into the shoes of a marketing team for a new hotel startup that wants to know about the hotel industry. We have been provided a dataset of the hotel industry of the region in which our startup aims to begin its initial operations. Our primary goal is to understand the market of this particular region and try to use our data analysis techniques to draw out key features of the market. Our secondary goal is to draw out actionable insights from our analysis and give conclusions about key aspects of the market such as cancellation rate, distribution channels, and alike.

Data Summary:

Based upon the initial assessment we found that the data was pretty much clean except for some missing values in a few columns. Upon using the info() method, we draw out the following key insights about the data:-

The dataset has a shape of (119390, 32) which means that it contains approximately 1.2 lakh rows and 32 columns.

Our Dataset has 4 columns with float64 dtype, 16 columns with int64 dtype, and 12 columns with object dtype.

In our Dataset, we observed null values in the following columns:

●4 null values in the children column

●488 null values in the country column

●16,340 null values in the agent column

●112,593null values in the company column

We have the following column names provided to us in the dataset,

● hotel

● is_canceled

● lead_time

● arrival_date_year

● arrival_date_month

● arrival_date_week_number

● arrival_date_day_of_month

● stays_in_weekend_nights

● stays_in_week_nights

● adults

● children

● babies

● meal

● country

● market_segment

● distribution_channel

● is_repeated_guest

● previous_cancellations

● previous_bookings_not_canceled

● reserved_room_type

● assigned_room_type

● booking_changes

● deposit_type

● agent

● company

● days_in_waiting_list

● Customer_type

● adr

● required_car_parking_spaces

● total_of_special_requests

● reservation_status

● reservation_status_date

Steps involved in the Data Analysis: -

Framing the questions: Before any form of analysis, it is important to frame the questions that we want to know from the data. For this, the space team collectively performed many creative thinking techniques such as brainstorming, team discussions, and debates to take out all the questions that could be asked related to the dataset.

Filtering out the ideas: After getting a long list of questions and assumptions that we want to solve from the dataset. As per the guidance of our mentor, we started filtering out our question list. One approach that we used to filter questions was to think from a customer and business perspective and look for answers to only those questions that mattered to any one of them.

Cleaning the Data: As mentioned before, the dataset provided to us by the Alma Better faculty was pretty much clean from the start. By clean we mean that it didn’t have any nested lists or dictionaries as row elements or wrong dtypes in dataframe columns. However, it had four variables with null values, so we had to take them into account before proceeding further with our analysis.

EDA analysis: By EDA we mean exploratory data analysis. In this, we looked at the dataframe and decided our target variables (Important Columns) based upon which we were going to conduct further analysis. We started comparing our target variable with other independent variables (leftover columns) to get insights into the relationship between them. This also gave us a better picture of how the different variables affect the target variable.

Visualization of Insights: After we completed the analysis of our data, we used matplotlib and seaborn libraries of python to present our analysis graphically. We used Pie charts, bar charts, scatterplots, displots, and much more to give complex insights in an eye-catching manner. We learned a lot about the different visualization tools that are available for data analysis.

Drawing Conclusions and Finding Answers: Finally we warped up each analysis by drawing out conclusions from them. While compiling the conclusion, we also realized the answers to the questions that we had asked at the start of our project. This helped us to get actionable insights into the hotel industry.

Actionable Insights:

Suggestions based upon insights to build a sound marketing strategy.

● ‘Direct’, ‘GDS’ and ‘TA/TO’ channels deliver the highest AM-ADR across all the months. More monthly marketing budget could be allocated to these channels to maximize AM-ADR.

● ‘Corporate’ channel delivers the most repeated guests. New Letters, updates, and other promotional material should be sent to corporate clients, monthly to keep in touch with them and to further increase the number of repeated guests.

● Cancellation percentages are consistently high for the ‘TA/TO’ channel across all months. A deposit should be taken from guests delivered by the ‘TA/TO’ distribution channel to cut down losses and operational inefficiencies.

● ‘TA/TO’ channel delivers guests who make the most special requests across all months, followed by guests delivered by the ‘Direct’ channel. Special requests add to the revenue of the hotel and so, customers from the ‘TA/TO’ and ‘Direct’ channels should be offered to avail of special requests by the staff as frequently as possible to increase the special requests that are made.

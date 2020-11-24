# Ford Go Bike Analysis
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

# Dataset overview
Before running straight into the exploration, let's just take a moment to get a high-level overview of the dataset. We can refer back to these points if we need to get our bearings on what we should expect to see from each variable
  - We have 183,412 rows and 16 columns. After being cleaned now we have 174,952 rows and 16 colums
  - We will have 2 numerical variables to be explored which are member_birth_year and duration_sec
  - We will also have 3 categorical variables to be explored which are member_gender, user_type, bike_share_for_all_trip

# Summary of Exploratory Findings
Here are some main topics that we can explore through this project 
  - How is the difference of trip length between user type?
  - How is the proportion of bike sharing during trip between user type?
  - How is the difference behavior of trip length duration between user type and gender?
  
### Univariate Exploration
  - The distribution of duration after we change the scale is normal
  - The distribution is negatively skewed
  - Majority of gender from our data is male (74.6%)
  - Majority of users never share bike for all trip (90.1%)
  - Majority of our users are subscribers (90.5%)
  
### Bivariate Exploration
  - Scatterplot shows that the correlation between birth year and duration is very weak and almost has no correlation
  - There is no major difference of duration between gender if we see from the chart
  - In bike share variable, there is no significant difference as well. but we can we users share the bike, the duration of trip a little bit longer (in general)
  - Meanwhile in user type we can see that customers tend to have longer duration of trip compared to subscribers
  - There is no significant difference of birth year vs other variables
  - In gender, overall the distribution seems similar
  - In bike share variable, those who share the bike are grouped in moreorless 2000s
  - The same thing happens in user type, the distribution is a bit fatter around 1990s
  - We can't see the difference of behavior between gender and user type
  - The proportion of female in customer type is bit higher than subscribers. there is a subtle difference between user type and gender
  - No customer has shared the bike
  
### Multivariate Exploration
  - From previous sections we can gather the attributes that probably have correlation with each other, such as duration, user type, gender, and bike sharing
  - So we only have one numeric varibables and three categorical variables
  - There is a different behavior between duration, gender, and user type

# Key Insights included in the presentation
Based on the questions that we asked before and post exploration, we can get several key takeaway which are
<ul>
<li>Customers spend longer duration of trip. On average, customers spend 1311 seconds or around <b>22 minutes</b> meanwhile, subscribers spend 640 seconds or <b>11 minutes</b></li>
<li>There is no customer who shares the bike during the trip. <b>Customers probably are not allowed to share the bike</b></li>
<li>Female customers significantly have a <b>longer duration</b> of trip compared to Male customers</li>
</ul>

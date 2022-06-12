# Bikesharing
Implementing Tableau
This is project will be performed as one of the stakeholder like to see the Analysis of the bike sharing. For this analysis, we’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
 - Show the length of time that bikes are checked out for all riders and genders
 - Show the number of bike trips for all riders and genders for each hour of each day of the week
 - Show the number of bike trips for each type of user and gender for each day of the week.
 - Finally, we’ll add these new visualizations to the two you created in this module for the final presentation and analysis to pitch to investors.

## Deliverable 1: Change Trip Duration to a Datetime Format 

### Convertion of the csv file into the data frame:
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/D1.png)

### Listing out the data types from the data frame objects:
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/D11.png)

## Exporting the dataframe without the index column
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/D12.png)

## Deliverable 2: Create Visualizations for the Trip Analysis :

### line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour :

![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/D2.png)

###  Line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender :

![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/D21.png)

### Heatmap is created showing the number of bike trips for each hour of each day of the week

![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/Heat_Map.png)


![]()

### Heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender:

![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/Heat_Map_byGender.png)

### Heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/customer_Subcriber_gender.png)

## Deliverable 3: Create a Story and Report for the Final Presentation:

### The Overview of the Customers by Gender and Break down by the customer types:

![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/pie_charts.png)
The Pie-Chart indicates that the proportion of the male is way more compare to the other Genders. Also, when it comes to the subcribers and customers the subcribers holding is way more compare to the customers.


The Left side indicates the Trips by weekdays by hours.
The Right side indicates the Trips by Gender and sorted - weekday by hour. 
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/Story.png)
From the above analysis we can conclude that around 6am to 9 am and 4pm to 7 pm the users are using the services more then other time slots. When it comes to Gender differenciation Male uses the services more. 


### Differenciating the categories by customers and subcribers in respect to Gender:

![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/customer_Subcriber_gender.png)
According to the above data Male and Female prefer more of the subcription services than to be a customer.

### The following chart shows the Trips by the top use and the comparision is done by filtering the by the Gender and the Users:
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/Trip_By_use.png)


### The following graph indicates the most used sharing bikes in the area:
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/top_stations.png)


## Summary

From the above analysis folowing conclusions are made:
 - The majority are the men on the gender data and also the usage of the services
 - The team have to work on the Women and other Gender categories.
 - Also if we change the filter we can find the list of the unuse services 
 
![](https://github.com/urvish7/bikesharing/blob/main/Screenshots/overall.png)

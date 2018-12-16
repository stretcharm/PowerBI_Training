# PowerBI_Training
Introduction to Data Visualisation and Analysis with PowerBI


Video Playlist
https://www.youtube.com/watch?v=WM_sS72xGXg&list=PLUIkYG_TQD7wkDrK7L8P7XnLPIl_G7Ugv

Presentation to accompany the training videos
https://github.com/stretcharm/PowerBI_Training/blob/master/DataViz%20And%20Analysis%20PowerBI%20Session.pptx

## Video 1 - Start PowerBI Desktop

### We are going to Open PowerBI and look around some of the toolbars and panes

- Start PowerBI Desktop
- Visualisation & Fields Panes
- Toolbar
- Help and Support Links
- Preview Features

https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%201-4.pbix

## Video 2 - Download some sample Data

### Here we get sample data for the rest of the training

- Links to webpages to get the sample data
- https://www.visitbritain.org/inbound-tourism-trends
- https://www.ons.gov.uk/peoplepopulationandcommunity/leisureandtourism/datasets/monthlyoverseastravelandtourismreferencetables
- https://www.ofx.com/en-gb/forex-news/historical-exchange-rates/monthly-average-rates/

https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%201-4.pbix

## Video 3 - Get Data from csv File

### We now open a csv file and load the data into PowerBI

- Get Data
- From Start of Home Toolbar
	- Lots of data source types supported.
- Open Csv/text
	- Sample Data provided change delimiter
	- Load or Edit
- Query Editor allows you to change the data after it's loaded
	- Close and Apply
- Drag and drop fields to background to add a couple of quick visuals
- Visuals try to guess what the best type is for the data e.g map for countries
	- Cross highlighting

https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%201-4.pbix

## Video 4 - Improve the Query

### Editing the data data we loaded to clean it or make it better for visualisation

- Save the Document
- We can search for fields 
	- Fields have indicators for different types e.g. Date, Summary, Measure, Calculated Column, Geolocation
- Change visuals
	- Click and then select a different visualisation
- Edit Query 
	- Opens Query Editor Window
- Name our Query( or File we loaded)
- CSV type uses headers from the file
- Rename Columns 
	- F2 or Right mouse rename
- Bar under name gives simple profile data
- Column Dropdown to see list and filter
- Lots of toolbar or menu option to help you manipulate you data

End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%201-4.pbix

## Video 5 - Improve the Query2

### Make some more chages to the Query. Add a Date from the Month and Year data we have

- Extract Month into a new Column
- Formular bar
- Column from example
	- Select columns
	- Enter the Answer in the new Column
	- PowerBI tries to create the code to get you this for all other rows
	- Change name
	
- Change types
	- Try to keep types correct as it can give you problems
	- if a field is not a date or number and you want to to behave like one
- Apply
	- Powerbi loads the data and then applys all the changes we make
	- If we change the source then it will reapply the steps we added
- Date field shows with data icon and automatically adds a hierarchy
- Add date based line/bar
- visuals understand the hierarchy 
	- Icons/Right Mouse for drill in/out, expand or go up/down a level
	- Data cross filters
	- We can edit the levels on the visual e.g. remove Quarter

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%201-4.pbix	
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%205.pbix
	
## Video 6 - Add More visuals

### Lets add more visuals from our data

- Move/resize the current visuals
- Copy (Ctrl C) and Paste (Ctrl V)
- Edit the fields used by the visual
- Drag fields onto the visual or the visualisation field lists
- Dragging to background creates a new visual
	- We can also have tables 
	- Hover over shows tool tips
- Manually create a hierarchy on some visuals by draggin a column to the axies
- Format pane of the visial has lots of options
	- Visuals also have ... which can control items like sort order
- We can add slices to filter that data
- Treeview help show the size
- Ribbon shows the change by types over time

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%205.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%206.pbix

## Video 7 - Add More visuals2

### Work on our visuals some more

- We can resize them using the general to get the same size and use the align options to make the tidy
- Change values to use % calcs and show the data labels
- Add tooltips to visuals
- You can add visuals from the toolbar as well and can overlay one on top of another e.g. Card with a KPI behind a Donut
- Everything still cross highlights

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%206.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%207.pbix

## Video 8 - Themes and Adding Dax Measure Calculations

### This video shows how to create a Dax Measures, grouping/binning and adding Quick Measures

- We can quickly change the colour scheme using themes either built in or we can create our own
- DAX is the name of the language used to create calculations in PowerBI
- Measures are calculations on our data and can be added from the right menu over the fields or toolbar
- The calcuklate is show in the forumlar bar.
- We can add a calcuation similar to exce like Sum
- Then use in our visuals
- Note: Measures work over the data set unless filtered, but are the same calculation for 1 or a million rows
- Lots of functions just like Excel
- Functions with X at the end calculate on a row by row basis
- They appear in our field list with a different icon
- We can show data behind the visuals if we want to check (or use a table visual)
- There is also an option to make the visuals full screen in the corner if you hover
- DAX can be simple or complex and have multiple lines
= In order to get a rank we need to Provide a list of things to rank e.g. Country and a value to rank. We have to use a calculate function get the sum
- Calculate can do very advanced things but here it just provides the total for each country
- We can add multiple pages to our document
- Adding data to a table lets use check the calculation is working correctly
- The Measure works on the data given so if want to see it by year it will calculate the rank on each year
- Visuals can have too much data so we can filter to the Top values
- We can also bin or group data to make it easier to work with on our visuals
- Right Mouse on field and select new group
	- A new field and icon is created for the group/bin
	- We can then use this on an axis
	- We can edit the options to make it suit our needs.
	- PowerBI does this by creating a Dax in the background for us.
- We can also make use of Dax Quick Measures which are prebuilt calculatutions
	- Pick the fields you want and it will create the DAX
	- You can then edit it or just learn how to write more advanced DAX
- Here we can create a calculation that shows the spending different from a yearly visit purpose from thtat spend by those
visiting friends or Relatives

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%207.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%208.pbix

## Video 9 - Add Some Excel Data, parameters and more Query Editing

### This video shows adding more data this time from an Excel spreadsheet and using parameters

- PowerBI provides parameters which are very useful for configuration such as the location of your files
	- We can then use a parameter in our queries
- Excel or file data can provide us with challenges if it has headers of different structures on different rows.
	- Use Get Data or New Source
	- We can pick a Sheet from the excel
	- Rename the Query
	- Make use of our parameter
- Clean up the data removing unwanted rows and getting headers from the top row
	- Rename columns
- The Years are missing on some rows so we can use the Fill Down transformation to fix this
	- We also have blank rows so filter them out using the Month columns
	- Select and remove unwanted columns
	- There are some extra characters in the Month that will cause problems so we can use replace to get rid of them
- Use add column by example to create a date field
- Set types manually or use detect data types, but be careful if there is text and numbers of a column as it doesn't look at all the rows.
- You can reorder columns to make it easier to work with
- Close and Apply
	- We now have a new Query/Table in our field list
- The grid (Data) view shows the rows
- The third view is relationships and can show how our data is linked
- Again we can use the dates and fields to create a visual
- However the data has a column for each value type this can harder to work with. 
E.g if we had months columns on or spreadsheet we cannot filter them as they are seperate fields

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%208.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%209.pbix

## Video 10 - UnPivot the Data

### Here we show how to pivot the columns into rows so the data is easier to work with

- We start by duplicating our query. 
	- This is also useful if you want to try something as there is no undo in the query editor
- If we want to use the results of the first query we could also use reference
- To turn the columns into rows we select the columns we dont want to pivot and then use Unpivot other Rows
	- We now have a row for each type of value
- We can then create the same graph with an Area Legend and filter different areas as required
- This will also cross hightlight/filter 

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%209.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%2010.pbix


## Video 11 - Add Exchange Rate from Web

### We can also add data from the internet such as the exchange rates by monthly

- Use Get Data and paste the web site
	- We have 2 options use tables if the web site has provided them or using web by example.
Web by example tries to fid the data you want from a web site given columns and values you provide
	- If possbile use tables as the data is often more reliable
- Again clean up the data by remoiving unwanted rows renaming fields and setting data types
- Apply and we have a 3rd query/table
- However the dates dont match the other data. How can we fix this?

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%2010.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%2011.pbix


## Video 12 - Add Date Table & Connect Data

### In the final video we create a date table and join our different data sets together so they can be filtered

- First filter the excange rates as we don't have an data as our other data is not as old
- Ensure you filter your data as much as possible before loading into PowerBI whilst it can handle very large data sets it will be slower
- If we use a date slicer it only works on a single data set
- As each data set has different grains(the level of detail) we cannot just join the dates. They have more than 1 row per date
So to let use connect them we can create special table that just has a list of dates
- I'm going to use DAX for this, but it can be done in many ways
Add new Table in Modelling and use the Calendar function
- This creates a row for each date between the ranges I provided
- I can then join the Date to the other tables on the relationship view
- Change the slicer to use this date table and we can now filter the different date together
- We can use similar techniques to join data and build models
- Dax can also be used to calculate measure accross data that is joined like this

Start File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%2011.pbix
End File
https://github.com/stretcharm/PowerBI_Training/blob/master/Uk%20Tourism_Exercise%20Video%2012.pbix


## Final File

### I've added some more data including UK weather with some more examples of visuals and a more complex models

https://github.com/stretcharm/PowerBI_Training/blob/master/UK_Tourism_final.pbix

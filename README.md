# UFOs
## Overview of Project
For this challenge I was tasked with building a table with Javascript that would take in user input on search filters then build the table with the data that meets their intended filter search and put it into an html file for easy viewing. The purpose of the table is for people to be able to search up and see different UFO sighting data based on certain dates, cities, states and etc.
## Results 
The way this table was created allows for users to really narrow down their search criteria for UFO sightings. The way the code works is when a user changes the input in one of the search bars the page automatically filters through the base data and puts out all data that matches that specific value set by the user. This allows users to slowly narrow their search down. An example would be they first want to see the data for a certain date, so they enter in a date and the table shows them all the data that corresponds with that date. 
![alt text](https://github.com/Cdonovan87/UFOs/blob/main//Static/images/datefilter.png)

They can then look through that data and decide well i also want to see it for a certain state as well as date so when they enter in a state the code filters through the data that was saved, the data corresponding to the entered date, and then shows the ones that match both the date and state. This allows users to slowly add new search criteria for the data  as it saves what they put in and filters the table accordingly.

![alt text](https://github.com/Cdonovan87/UFOs/blob/main/Static/images/statefilter.png)
## Summary
Overall this design is very usefull however it does come with some drawbacks. One drawback is that it does not allow a user to filter the data based on two of the same criteria, i.e someone wanted to look at both california and arkansas data. In order to do that they would have to enter California first look through that data and then enter Arkansas and go through that data instead of seeing both in the table at the same time. Harping on this I would reccomend that code be added that allows for the user to do this. This could be done by creating a way for the user to save past search criteria so the code can run through and add all the data that has either of the search terms. I also believe another development that should be added would be a way for the user to enter key words to filter through the comments part of the table so they could see the different data that had similar comments to eachother.

# DailyPlanner
The purpose of this assignment was to create a Daily Planner that is time sensitive and also keeps stored actvities on the page. I had alot of trouble with this assignment because I used data trributes so i could add classes to each Div. After a long struggle i figured I needed to go through the DOM differently to target the elements individually.
0. Current time to be added under header using moment js.
1. create rows inside of the div container.
2.add 3 columns to each row appromixmately using 2-8-2 ratio 
2a first column will be used for the different times.
3.add input element to biggest containers of each row this is where user input dailt info
4.add button to last column,this will be the save button class .savebtn as specified in css
5.  functions will need to be made for saving inputs in daily planner
6.add event listener will need to be added for the click of the save button
7. inside event listener , input of the daily planner must be stored in local storage so that they remain on screen
8. Next we will have to use our current time to manipulate the different css features
9. We will have to create a variable for the current time .
10. in a function addClass() , we will create a condition that adds the class of .past .present or .future to our middle column  (col-md-8)
10a. to execute this each row will have to have a data attribute with a value of their time
10b. based on the time value the condition will add a past future or present class.;

# Workday Scheduler 

## Purpose
The purpose of this application was to create a work day planner with time blocks from 9am to 5PM(the work day). Each hour block has a text area where the user can type in the plans of the specific hour, save that information on the page and in local stoarge. The hour blocks are color coded depending on where the current hour falls in the work day schedule. The current hour has a background color ofred, future hours are green and past hours are grey.

## My Experience
I was able to pseudocode this assignment out thoroughly which helped me significantly. I started off by creating an on click even for users to have their text be saved to local storage. Then I needed to create a way to compare the current hour to the hours in my work day scheduler and color code them accordingly. I created an array using military time and used moment.js to create a variable for the current hour. With those two pieces I was able to iterate through the array and use if else statements to add a class to the textarea. I was able to specify the text area by adding unique ID's to each one and dynamically iterating through them while comparing them to the array. I then created a function to get items from my local storage. The difficult portion was figuring out how to uniquely identify the text area to the the specific class added, I realized this after noticing that every class(past, present, future) was being added to the textarea element on the html page.I added a unique ID to the parent div and was able to index through them and compare them to the military time index. 

## Technologies Used
- jQuery
- JavaScript
- Local Storage was used
- Moment.js

## Link to the Working App
 The app is deployed on github pages, [here](https://janetiqal.github.io/Workday-Scheduler/).

## ScreenShots of Working App
<img width="1432" alt="Screen Shot 2021-07-10 at 11 06 41 AM" src="https://user-images.githubusercontent.com/84414488/125170989-ffd91100-e16e-11eb-90be-4ec9c6790902.png">

## Created By Janet Iqal 

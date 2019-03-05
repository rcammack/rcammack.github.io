---
layout: project
type: project
image: images/calendar.png
title: "iCalendar Event File Generator"
date: 2018-08-10
labels:
  - HTML/CSS
  - JavaScript
  - GitHub
summary: My team designed a web application for users to download custom calendar event files for sharing and importing into calendar systems. 
---
For my final project for ICS 414 (Software Engineering II), our task was to build a system to create .ics  files that can be emailed or shared, and read into the recipient’s calendars. My team and I created a web application where users can create their own calendar event files. A user can fill out the fields to generate custom calendar event files following the [RFC 5545 format](https://tools.ietf.org/html/rfc5545). The user can then download the files to import event reminders into various calendar systems. 

We implemented the following functionality within our
calendar event file system as described in RFC 5545: Version, Summary, Location, DTSTART, DTEND, Recurrence Rule (Frequency, Count), Priority, Classification, and Time Zone Identifier. In addition, we incorporated a link to a Google Maps search of the location string using the URL field. Our application also automatically generates a DTSTAMP and Unique Identification (UID) required for .ics and .vcs files. We wrote scripts to verify the inputs, control the UI, set default values, and, in general, deal with translating the user input into the format needed to make an event file readable. 

One way that we verified the correctness of our system was with the frequent use of the console.assert function. We initialized some test data and passed it into our smaller functions, (such as our date/time converter function), to verify that the results returned from the functions were accurate. If an invalid input was detected, our system would reveal it in the console. Most of our verification checks were managed by a function which was created to further control the calling of the createFile() function such that it would inhibit the file from being generated. In addition to including tests while writing the code, we also performed usability tests. This manual form of testing was constructed by having individuals complete two tasks:
1. Create a file for the following: Bob’s birthday party in China tomorrow from 11AM to 1PM
2. Create a file for the following: A reminder to update the CEO’s schedule at 8AM on the first of every month for the next 12 months

The general idea was to have the user fill in (1) summary, location, start/end date/time and (2) summary, start/end date/time, recurrence and count, priority, and classification fields. We observed the users perform the 2 tasks and took note of the aspects of each task that took them the longest/shortest amount of time to complete and if they triggered an invalid input alert. 
Most users didn’t trigger an alert but the most confusing aspect of our application was the end date field. In future versions of our application, we could change the visibility of different fields based on other fields (such as hiding the end date field when a user wants a repeating event, which was the most common request for our application).

Another main aspect of this class was project management. My team and I adopted the Agile idea of "sprints" by scheduling team check-ins to verify that each person in our team was on track.  With each check-in, we discussed what we accomplished during the sprint, demoed our progress, listed any problems we encountered, and coordinated on what we would work on next. 

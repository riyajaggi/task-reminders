# Task Reminders

Google Apps Script that sends daily email with To-Do List from Google Tasks

## Table of Contents

* [Introduction](#introduction)
* [Version 1](#version1)
* [Version 2](#version2)
* [Designs](#designs)


<a name="introduction"></a>
## Introduction
The desktop version of Google Calendar allows you to add Google Tasks and visualize them on the calendar.

 
**Google Calendar with Events and Tasks**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/screenshots/calendar%20with%20events%20and%20tasks.png" width="700" title="Google Calendar with Events and Tasks">


While there's an in-build user preference that if set sends you a daily email with your schedule for the day, it does not include your Google Tasks.

  
**Google Calendar Daily Agenda Email**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/screenshots/daily%20agenda%20google%20calendar.png" width="700" title="Google Calendar Daily Agenda Email">

In order to keep my day more organized and motivated, I decided to create a script using Google Apps Scripts and Tasks API that will extract these tasks and email me every morning.

  
<a name="version1"></a>
## Version 1
I created the first version in March 2020 and it was very basic. My focus was to get the data from my Google Tasks List and send myself an email with the items due for that day. The email was plain text and extremely raw, in fact, it just used the data values from the API object without even changing them to proper format or readable value.

  
**Data Extracted using Google API**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/screenshots/data%20extracted%20from%20Google%20Tasks%20API.png" width="700" title="Data Extracted using Google API">

  
**My Tasks Email Version 1**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/screenshots/tasks%20email%20v1.png" width="700" title="My Tasks Email Version 1">

  
<a name="version2"></a>
## Version 2
In August 2020, I decided to improve this script to prepare for the upcoming semester as I am studying remotely from abroad and it is more important than ever to keep track of my due dates! 

I worked on making the code design better and resolved any previous bugs. An upgrade from the previous version was to divide my tasks into *Today* and *Tomorrow*, marking each as *Incomplete* or *Complete*. I even included a section for *Pending/Overdue* items. With a little free time, I tried making some designs to (they are not the best, it's my first time using Figma!! 🙈)

  
**Testing Version 2 Features**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/screenshots/tasks_testing.gif" width="700" title="Testing Version 2 Features">

 
**My Tasks Email Version 2**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/screenshots/tasks%20email%20v2.png" width="700" title="My Tasks Email Version 2">

  
<a name="designs"></a>
## Designs

**Header**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/designs/title.png">

**Completed**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/designs/complete.png">

**Incompleted**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/designs/incomplete.png">

**Overdue**

<img src="https://github.com/riyajaggi/task-reminders/blob/master/designs/overdue.png">


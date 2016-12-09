[Project Concept](#project-concept) | [User Stories](#user-stories) | [Personas](#personas) | [Platform Analysis and Selection](#platform-analysis-and-selection) | [Finalized Documentation](#finalized-documentation)

# Project Concept

[Project Concept](\assets\ProjectConcept.pdf)

# User Stories

### #1 Administrator 

As an administrator trying to schedule students for the writing center, I want to be able to automatically generate a schedule which will fill all of the required timeslots and schedules all returning tutors before filling the rest of the schedule with prospective hires so that I know which students to interview. After generating the schedule, I want to be able to modify the schedule as needed so that I can make individual adjustments as requested. Last, I want to be able to view each employee’s information, hours worked to date, and availability in a separate tab. 

### #2 Work-Study student

As a returning or potential work-study student, I want an easily accessible website and I want to be able to easily enter and modify my availability. The website should have a calendar where I can easily modify my availability for each day and half-hour. I want to be able to view the master schedule after the master schedule has been set.  As a student I want the scheduler to schedule continuous blocks of tutoring blocks for me to minimize the time wasted traveling to and from the tutoring buildings and travel time. For example, working a two hour block is better than two one hour blocks in a day as this cuts the number of trips to and from the tutoring center in a day. 

# Personas

### #1 Janice the admin

Janice is non-technical, but must interact with this system a great deal at the beginning of the semester, and then make adjustments as the semester progresses.  Janice wants to produce an optimal work study schedule with as little user input as possible.  She can invite new users to the system, require them to fill out availability, and then easily generate a schedule when she's satisfied.  She also wants an intuitive interface for changing schedules later on.  It's very important that she not have to fight with the system to get her job done.  Janice is busy, and scheduling is not her main priority. Janice wants precise control and the ability to modify the schedule freely if she chooses to. 

### #2 Phil the work-study student

Phil is non-technical, and doesn't interact with this system very much.  Janice sent him an email with a link once at the beginning of the semester, and he followed it to log into a strange scheduling portal he vaguely remembers seeing last semester.  It's been a long time, and Phil can't remember his password.  Phil is busy and doesn't have time to sit and remember where all of the features are.  He wants a simple interface to give janice his work availability so he can get back to his homework.  If it takes longer than drafting an email to Janice, Phil might get frustrated.

### #3 Chenda the potential new hire

Chenda is non-technical, but pretty good with web interfaces like facebook and google calendar.  She's applying for a job at the Writing Center, and Janice sent her an email to fill out some personal info.  When she gets some free time, she clicks the link and logs into a scheduling portal.  She's unsure exactly what Janice wanted, so she begins filling out any forms and fields the portal gives her.  She's excited about the prospects of a new job, and spends time clicking around to see what's behind all the buttons and navigation links.  After spending a while exploring, she submits her schedule and sends Janice an email saying the task is complete - just to make sure.

# Platform Analysis and Selection

After evaluating a few python solutions (Django, Flask) our team has decided to use Flask.

Flask is lightweight, optimal for small applications, highly configurable, and more pythonic in design.  

FullCalender will be the interface that we will be using to simplify the process of diplaying the front end representation of the schedule.

# Finalized Documentation

Functional Spec | Test Plan | Design Document | User Manual | Code
---             | ---       | ---             | ---         | ---
[Functional Spec](\assets\FunctionalSpec523.pdf) | [Test Plan](\assets\TestPlan.pdf) | [Design Document](\assets\DesignDocument.pdf) | Our website will include a help tab, one for the administrator and one for the students which will contain the information needed in order to properly use the website.  | [Code](https://github.com/WritingCenterScheduler)



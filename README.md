# Software Design Documentation
###### Project Name: Student Scheduler
###### Date: 9th February , 2023
###### Written By: Modupeoluwa Daniel, Mitchell Hansbauer, Corin Manning, Tara Poudyel 
## Introduction
This project is a student scheduler. Students will use this website to schedule meetings, remember deadlines and plan their time effectively. 
System Overview
This system would have a calendar where students can click on specific dates and schedule meetings, reminders and deadlines on it. It will have a login/Sign up feature because students need to have specific accounts to work.
## StoryBoard
Screen Mockups

![Picture1](https://user-images.githubusercontent.com/109301573/218340294-651a1364-8544-431b-b490-38152d68f342.png)

## Functional Requirements
###### As, I want, so that I can
 - As a User, I want to be able to Login to my account , so that I can see my schedule
 - As a User, I want to be able to schedule a meeting , so that I can reminded about it
 - As a User, I want to be able to edit my reminders, so that i can make changes if i make a mistake filling out the form. 

###### Given, When, Then
 - Given a user fills the login form, when login details are wrong, then return an error message
 - Given a user schedules a meeting, when it's time for that meeting, then send a notification reminding them about the meeting. 
## Class Diagram
Describe components and subcomponents.

![Picture2](https://user-images.githubusercontent.com/109301573/218340305-04143a3e-93e3-4935-bc2e-362a59dec5e9.png)

## Class Diagram Description
Firstly, we have the main class, which would be the user class. The user class contains basic information about the user that is necessary such as userId, name and their email. The class also contains methods to schedule and join events along with getting their calendar information. We then have a UserEvent class which acts as a bridge between the user and event classes. This is to keep the user and event independent of one another so we use the user event class as a middle man. The event class’s only purpose is to store information regarding the event. Last but not least we have the calendar class, which is responsible for all things event. This is the class which is responsible for creating, deleting and changing events.
## Github Link
https://github.com/studentscheduler
## Scrumy Link
I emailed the teacher and He let me use Jira instead of Scrumy, but the link cannot be shared publicly so I attached an image.
![Picture3](https://user-images.githubusercontent.com/109301573/218340307-e63f2c54-185f-49ac-86f6-b4ec3f372c46.png)

## Team Roles
Product Owner:, Hansbauer Mitchell 

Business Logic and Persistence: Poudyel Tara

UI: Manning Corin, Modupeoluwa Daniel


# IRSR-Front-End-Architecture

Front-end architecture for this build week project.

https://trello.com/b/85OrQdbz/internation-rural-school-report

MVP Features Breakdown:

MVP: School Admin can login and create, read, update and delete information on the condition of the school including general issues and the condition of equipment devices in the school (TVs, tablets, chromebooks, servers, routers, HDMI cables). A board member can log in and mark the action as done, scheduled, or ignored, and comment with more information. 

General issue request:
User(School Admin)
Date
Location (if applicable)
Request Info
Status: default to open

Equipment request:
User (School Admin)
Date
Location
Request Info
Status: default to open

Update General Issue Request:
User(School Board)
Date
Location (if applicable)
Request Info
Status: updated
Status Info:

Update Equipment Request:
User(School Board)
Date
Location (if applicable)
Request Info
Status: (done, scheduled, or ignored)
Board Status Comment:

Login Page/Modal - After a user logs in, they'll be directed to a home page.

Navigation - Navigation is present on all pages, Users should know what page is active by clicking on a nav link and activating their tab.

Home Page - Contains a general school button to list issues by date entered, and a list of issue types (security, electrical, furniture, textbooks, general school supplies, tech equipment, and resolved) laid out in a grid format.

Single Issue View Page - Loads information about the issue, who logged the issue, category of issue, optional photo, date issue was logged, how many days since issue was logged.

Resolved issues page- Loads information about past issues, who resolved it, date issue was resolved, and how it was resolved.

Delete issue- modal confirming action, user routed back to homepage and item is gone from list of issues.

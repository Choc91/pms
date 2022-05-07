# pms
Project Management System using .NET/Angular to plan, organize, and manage resource tools and develop resource estimates.
Mandatory Modules:
 USERS:
 There are 2 types of users in the system:
 • Manager/Hr (Admin)
 • Employee (He can only view his profile)

Module 1: (Admin)
As a Manager/Hr I can login to my application and If I don’t have credentials then I can sign up and create an account to login.
Once Login is done,As a manager I should see dashboard page which should display the team summary , project briefing , team members detail 
As a Manager , I should be able to add new project details
As a Manager, I should be add to add new employees to the project
As a Manager, I should be add to removes employees from the project
As a Manager , I should be add clients ,update project costs

Module 2: (User)
As a Employee I can login to my application and If I don’t have credentials then I can sign up and create an account to login.
Once Login is done, I should see all the list of mapped projects to the employee
As a employee I can see my project details and will not have any role to edit it



Front-End : (Need to consume all the above API’s)
As a F.E I will be creating the login page, signup page UI and will consume the above created API in .NET
I can also reset my password if I forget.
I should have all the necessary buttons for add update and delete API in front end.
Add the authorization in the UI as well. The buttons should not be visible for the users.
The page should be responsive. (Use bootstrap)

The data model consists of three main subject areas:
•	Users and roles
•	Projects
•	Tasks 

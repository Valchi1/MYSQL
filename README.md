# MYSQL

Scenario
You work as a systems developer in a small IT team for a secondary school. The school requires a system to be developed that will help track technology related faults and issues within the school. Previously, issues were reported via phone, and jotted down for technicians to work through. This system is obviously flawed, as issues reported would sometimes be lost or forgotten, and there was also no way to inform or update anyone on the progress of the issue. 

You have been tasked with developing a web based system that will solve this problem. 

System requirements
The system will allow for two types of user, an admin (a technician) and a regular user (school teacher, admin or support staff). 

A regular user will have the ability to:
Register for a regular user account
Login into the system with their account details
Report a fault
View all faults
View all faults they have reported
Logout

An admin user will have the ability to:
Login using an assigned admin account
Report a fault
View all faults
Search for a fault
Edit / update a fault
Delete a fault
Logout

A fault must have the following associated fields. All fields are mandatory.
ID (automatically assigned)
Title
Description
Location
Date and Time (automatic timestamp)
Fault status (This field will always start as empty and only an admin has the ability to update this field)
Job Complete (This field will be a yes / no choice)
User ID (automatically populated by using the information of the user currently logged in user and used to assign the fault to the user)

Technical requirements
The system you develop should abide by the following rules:
Be hosted on your university webserver
Be contained in a folder of your username, for example subdomain.uoswebspace.co.uk/bh55ab
Be all your own work and not use any frameworks
Make use of PHP and MariaDB (MySQL) technologies
Be as robust as possible
Make use of PDO style database connections only
Contain good programming practices, such as sensible variable names, indentation and useful comments. 


#prototype system.

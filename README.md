# InstallingPostgreSQL
 
 Hello to you all! Kindly find below some details of my experience in installing PostgreSQL for MacOS users. 
 ---------------------------------------------------------------------------------------------------------
 The simplest and most time efficient way of installing PostgreSQL is to simply download the Postgress App.
 This method ensures you do not run into minor installation issues that can prevent you from moving on further. 
 
 To begin with download the app at the following link:
 https://postgresapp.com/downloads.html
 
 Once downloaded and placed in the application folder, you must log on to a host and onto a port on the first page of the app.
 
 Potential Issues/Errors: 
 - *ERROR: PORT 5432 is already in use*
 This means that when you are attempting to open a server on the app through port 5432, you have already gave some functionality to this port at an earlier stage. Although this may appear intimidating, the solution is fairly simple. 
 Enter the following sudo code on the command line of your Mac terminal:
 sudo pkill -u postgres
 For more help please open the following:
 https://stackoverflow.com/questions/42416527/postgres-app-port-in-use?rq=1
 
 When moving forward, I suggest you install a UI (User interface) that allows you to build queries, view structure and understand content. 
 
 The two most well known UI's are: 
 
 1) PGAdmin (available at: https://www.pgadmin.org/download/pgadmin-4-macos/)
 2) PSequel (available at: http://www.psequel.com/)    ** preferred among Mac users.


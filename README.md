CSE591_AW_Social_Viz_With_Behavior_Logging


Instruction to Run the Application
1.	Download the zip file Assign1-SukanyaPanda, which contains the .war file (source code), Instructions in Readme.doc and a video recording(Screen_recording) of the application.
2.	Extract the content from the zip file.
3.	Download and install server apache-tomcat-8.5.33 for running the application (WAR file)
4.	Now, place the .WAR file in the webapps folder of the apache-tomcat-8.5.33.
5.	Then, go to the bin folder of the apache-tomcat-8.5.33 where there is a startup.bat (batch) file and double click on the same. 
If the app is being tested on a mac machine, please make sure the user has permission to run all shell script (.sh) files. If not run the command sudo chmod 777 *.sh and then run the command ./catalina.sh start from terminal
6.	After the server is started, give the following link in Google Chrome to view the application:
LINK:  http://localhost:8080/CSE591_Assignment1/
 
7.	Once the webpage opens, the login page has options for user registration (for creating new users) and login options (for Existing users). I have already prepared data files where the existing users are aaa, bbb, ccc with password 123 for all of them. 

The data folder is named as Sukanya. Please unzip the main folder(Assign1-SukanyaPanda.zip), and once you unzip go into Assign1-SukanyaPanda folder, copy the Sukanya folder present inside the Assign1-SukanyaPanda folder, place it on your desktop. It already has existing users aaa,bbb,ccc with password 123 for testing, user audit data and user event data. Click on login as admin hyperlink on the start page of the application to view existing data visualization of the users given. 

Once logged in as either aaa, bbb, ccc, there is a link to stack overflow page on the right-hand side of the user profile page. You can log out from the user profile page through the logout link in the extreme right side of the page. 

The stack overflow link on the right side of the user profile page redirects to the stack overflow page to track user actions. Please click on the vote up, vote down, Favorites (star mark), share and post comments to log these actions. While clicking on share, please click on either the Facebook, Twitter, or google icon to log the ‘share’ action and then click on close on the bottom right of the box. 

I have even logged user actions (vote up, vote down, favorites, shares, comments on posts) of the following users (aaa, bbb, ccc) along with their data visualizations. Please click on the link Login as admin (user id: admin and password: admin) on the application start page to view interactive data visualizations for the existing users aaa, bbb and ccc.

The data visualization is depicted through an Interactive pie chart which again shows metadata information on hovering the cursor over its individual sectors. By default, the sub pie chart shows the Vote up count and percentage of the three users. It eventually changes on hovering the mouse over different sectors of the main pie chart. There is a Heatmap which represents the overall comparison of the three users. The pie chart as well as the Heatmap gets updated as and when the number of users or the number of activities with logs changes.
These features best work on Google Chrome.

You can open a new tab and login as any user, perform actions by going to stack overflow page and refresh admin page which is present in another tab or new window after you log out from the stack overflow page in other window or tab to visualize changed data.

If you do not want to use the data folder Sukanya.zip, once you start the application you can register as any new user and log in as the same. The folder Sukanya gets created on the desktop in which the application is running and data files (.txt) also gets created once user registration, user log in and actions on stack overflow page are performed.


8.	Below the data visualization, there is dropdown which shows the number users and changes as and when new users are added. Choosing the user from the drop down would give the type of user based on analysis as mentioned in the same page.

I have already prepared a readymade data file (userEventdetails.txt) inside Sukanya folder which contains user activities justifying different user nature in which User ‘aaa’ behaves like an Engaged User, ‘bbb’ behaves like Moderate User and ‘ccc’ behaves like a Casual user.




# RPA_SertificateAutomation
This is a certificate delivery automation software project
Can be used to automatically entry data from excel file to certificate template and submit webinar certificate to email participate. 
Project build with UIPath Studio

Requirements :
You must use Microsoft Outlook and power point with a minimum version of 2019
and you have default account in outlook dekstop application

Setup requirements :

Before start the automation "using photoshop":
1. You have photoshop certificate template files
2. Then open photoshop application
3. Open photoshop certificate template files
4. Then you swipe text layer "Participant Name" to top
5. Be sure photoshop application stay open, until the automation process stop running

Before start the automation "using power point" :
1. You have power point certificate template files
2. Then open power point application
3. Open Power point certificate template files
4. You have remember default text from field "name participant",
   which will be used as a reference by the robot to find the text to be replaced
5. You have close power point application


How To Use This Projects :
1. Download the zip file in the repository, then extract it on your desktop or computer
2. Extract the file, then open the UIPath software
3. Click Open, then select the "project.json" file in the extracted folder
4. Then click "Debug File", make sure you have opened Photoshop and have a certificate softcopy file that complies with the requirements


Project Application Steps:
1. Enter an excel data file that has at least 2 columns of "Name" and "Email" when running the software
2. Enter the name sheet in the first column
3. On the next occasion, enter the name of the column that is used as a reference in writing the name. This is useful as a reference for robots to change names in files later
4. Next, enter the name of the column that is used as a reference in writing and sending emails. this is useful so that later the robot can send certificates automatically through a third party (Microsoft Outlook). Notes: Make sure you are logged in and have a Microsoft Outlook account
5. Select Software application options, there are 2 options
    - Photoshop
    - Power point
6. In the next column, enter a Subject which will be the subject of your email message. you can write your company name like "RPA Company"
7. In the next field, fill in the message that will be conveyed to the recipient.
8. Press "Submit".
9. Then you will look message box information,you can press enter or click "ok" button
10. Then you have to choose a folder that will be used as a place to store all certificates

/////////////-ENJOY-//////////////

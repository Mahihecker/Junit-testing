# Junit-testing:

#Step1: 


You need to Download IntelliJ from the following link:
https://www.jetbrains.com/idea/download/?section=windows

Create student account using University email to get the free license from following
link: https://www.jetbrains.com/community/education/#students/

After downloading install the IntelliJ. And connect your student account with it.
After installation create the project select your desired folder for it. You will need to
download JDK to run java (this option is available in IntelliJ by default you can download
from there).


#Step2: 


Then Install MYSQL (or any other if you are already using some) download link:
https://dev.mysql.com/downloads/installer/ (download 300MB one)
Install the full version 
After installation is complete Go back to your project (IntelliJ) on top right corner you will
find the Database Icon click on it. From the list select your SQL server (if download MYSQL
select that or you can select any other).
In the modal enter your username (most of the time it is root (if you didn’t change)) and
your password.
Your will find option to download the drivers download it. Test connection and Click on Ok
Run the provided SQL script
After that change the variables (user name and password) in Java file with your username
and password. And run the java code. You will see the simple login in Screen.


#Step3:


downlaod the jar files provided in the repository 


#Step4:


open the project structure by going to file in intellij

open the Libraries -> click the "+" and add as "java" seach through ur files and add teh jar files provided above

do it seperately for each one

apply the changes


#Step5:


open the module option in the project structure and go to dependencies

click tick the dependencies of libararies you added 

do compile option for sql-connector and test option for the other two jar files

aplly the changes

go to the source in the modules and see if scr/main is mark directory as source (blue in color)
and  the scr/test directory marked as teh test (green in color)

apply the changes

click ok


#Step6:

go to file click on clear invalid cache and click tick to every option click ok

Rebuild the project 

connect the databse by clicking on it and run the test cases 

ur all set ;3

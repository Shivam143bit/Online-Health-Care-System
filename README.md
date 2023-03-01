# HealthCare
 
#Prerequisites

Install XAMPP web server Any Editor (Preferably VS Code or Sublime Text) Any web browser with latest version

# Languages and Technologies used

javaScript (to create dynamically updating content) HTML CSS XAMPP (A web server by Apache Friends) Php MySQL

# Steps to run the project in your machine

Download and install XAMPP in your machine
1.Clone or download the repository
2.Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
3.Start the Apache and Mysql in your XAMPP control panel.
4.Open your web browser and type 'localhost/phpmyadmin'
5.In phpmyadmin page, create a new database from the left panel and name it as 'sourcecodester_healthcaredb'
6.import the file 'sourcecodester_healthcaredb' inside your newly created database and click ok.
7.Open a new tab and type 'localhost/foldername' in the url of your browser

#Starting Apache And MySQL in XAMPP:

The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.

![Screenshot (7)](https://user-images.githubusercontent.com/85752605/222200378-9c9bc567-c0d8-48f2-9678-f8a8cbad6aa2.png)


#GETTING INTO THE PROJECT:

Online Health care System in php and mysql. This system has a ‘Home’ page from where the user, doctor & administrator can login into their accounts by toggling the tabs accordingly. Fig shows the ‘Home’ page of our project.

![Screenshot (8)](https://user-images.githubusercontent.com/85752605/222200636-a2bf6e3c-3ae8-4374-82fc-5bb8106d1017.png)


The ‘Home’ page consists of 3 modules:
1.User Module
2.Doctor Module
3.Admin Module

# Patient Module:
This module allows patients to create their account, book an appointment to see a doctor and see their appointment history. The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.

![Screenshot (8)](https://user-images.githubusercontent.com/85752605/222209896-ef58f6ce-c9ca-44a1-9368-0a0094d87739.png)


Once the patient has logged out of his account, if he wants to go into his account again, he can login his account, instead of register his account again. Fig 1.9 shows the login page. Clicking on ‘Login’ button will redirect the patient to his dashboard page which we have seen earlier

# Doctor Module:

The doctors can login into their account which can be done by toggling the tab from ‘User’ to ‘Doctor’. Fig 1.1 shows the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.

# Admin Module:
This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too.       Login into admin account can be done by toggling into admin tab of the Home page. Fig 1.2 shows the login page for admin.   username: admin@gmail.com, password: admin


![Screenshot (10)](https://user-images.githubusercontent.com/85752605/222200724-ba51dccf-2f50-45eb-aa18-57d3e26202dc.png)

![Screenshot (9)](https://user-images.githubusercontent.com/85752605/222200812-2ac6bdf7-e6d7-4ec5-8153-84431d40081f.png)


![Screenshot (13)](https://user-images.githubusercontent.com/85752605/222200965-9c291fe9-dea9-4e16-b11c-c9448f5e9238.png)


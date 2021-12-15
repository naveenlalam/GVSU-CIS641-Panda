# Overview
----------

* University Messaging System shall be a web based application which can be leveraged as communication platform between the university faculty and students.The application shall have of four modules Registration, Administration, Login and Application.Users shall register/apply access to system and administrator shall be approving the requests. Once a request is approved the users shall be recieving an email and then he or she shall be able to login to the application and send, receive and view messages.


# Functional Requirements
------------------------

## 1. Registration
  * 1.1 Registration form shall be loaded when the user clicks on the registration link.
  * 1.2 Register link shall be displayed on the right portion of the web page under the label First Time User.
  * 1.3 The Registration page shall have the user input values like user id, password, first name, last name, G number, and email id. Users shall be able to input all the values and save         the details.
  * 1.4 All the input values like GNumber, email, and phone number shall be validated on the registration page.
  * 1.5 User shall receive a mail once the registration is successfully completed.

## 2. Administration        
  * 2.1 Administration page shall be only accessible to the Application Administrator.
  * 2.2	Administration page displays all the requests in ascending order by date.
  * 2.3	Administrator shall have an option to approve or reject the request.
  * 2.4	Users shall receive an email once the administrator approves the request.
  * 2.5 Administrator shall respond to all the user queries on an email.

## 3. Login
  * 3.1 User shall login to the application with the registered credentials.
  * 3.2 User profile shall be locked after 3 failed attempts of login.
  * 3.3 User shall be able to reset the password using the forgot password link provided on the page.
  * 3.4 User shall be able to unlock his id by raising a request with the Administrator.
  * 3.5 User authentication is done by validating the credentials with the database.

## 4. Application 
  * 4.1 Users shall view all the existing messages as a list on the home page.
  * 4.2 Users shall be able to send messages to any registered user in the system.
  * 4.3 Users shall be able to receive messages from any registered user in the system.
  * 4.4 Users shall be able to send group messages depending on the rights granted to the profile.
  * 4.5 Users shall be able to raise a request to disable access with the system.

## 5. Logout
  * 5.1 User shall be able to log out of the application at any point of time from the home page.
  * 5.2 User session shall be created once the user logs into the system.
  * 5.3 User session shall be destroyed immediately on click of logout.
  * 5.4 User shall be logged automout if the system is kept idle for 180 secs.
  * 5.5 User shall see a pop-up message warning before the system automatically logs the user out.

# Non-Functional Requirements
------------------------------

## 1. Compatibility
  * 1.1 The application website shall be Cross-browser compatible.
  * 1.2 The application shall be accessible on Chrome, Internet Explorer, Edge and Safari browsers without any issues.
  * 1.3 The application shall be compatable on Windows, Linus and MAC operating system.
  * 1.4 Mobile version of the application shall be developed.
  * 1.5 Android and Apple Operating systems compatable versions shall be available.

## 2. Scalability
  * 2.1 The application shall be ported onto more than one web server and load balanced. 
  * 2.2 The application shall have to be ported to the cloud down the line in the future.
  * 2.3 The application shall be horizontally scaled on the cloud environment depending on the user demand.
  * 2.4 Depending on the server memory usage and disk space the server shall be horontally scaled(addition RAM will be added to the server).
  * 2.5 Once ported to cloud application shall be available 24/7 irrespective of server activities.

## 3. Maintenance 
  * 3.1 Regular code maintenance activity shall be performed on the application.
  * 3.2 Server shall be scanned periodically to find if on the rce or weak ciphers and protocols.
  * 3.3 Latest patches shall be installed on the server periodically.
  * 3.4 Server shall be configured to reboot automatically during the weekend to free up application memory.
  * 3.5 As part of the regular maintenance activity the server shall be scanned periodically to find if there are any missing patches.

## 4. Security
  * 4.1 Password encryption shall be implemented in the application code.
  * 4.2 Password shall be stored as an encrypted value in the database.
  * 4.3 Application shall leverage HTTPS protocol and a secure certificate shall be installed on the server. 
  * 4.4 Server shall have all the latest security patches installed on it. 
  * 4.5 Week ciphers and protocols shall be disabled on the server. 

## 5. Performance
  * 5.1 Application shall have a decent response time.
  * 5.2 Application shall be tested with a load of concurrent users to check if there are any server spikes in RAM and io.
  * 5.3 Application shall be tweaked to avoid any out-of-memory issues.
  * 5.4 Application performance shall be same on all the browsers.
  * 5.5 Application performance shall be more faster on mobile as lighter version shall be deployed for mobile.
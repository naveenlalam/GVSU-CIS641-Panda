# Overview
----------

* University Messaging System shall be a web based application which can be leveraged as communication platform between the university faculty and students.The application shall have of four modules Registration, Administration, Login and Application.Users shall register/apply access to system and administrator shall be approving the requests. Once a request is approved the users shall be recieving an email and then he or she shall be able to login to the application and send, receive and view messages.


# Functional Requirements
### Registration 

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |Registration form shall be loaded when the user clicks on the registration link.|
| FR2 |Register link shall be displayed on the right portion of the web page under the label First Time User.|
| FR3 |The Registration page shall have the user input values like user id, password, first name, last name, G number, and email id. Users shall be able to input all the values and save         the details|
| FR4 |All the input values like GNumber, email, and phone number shall be validated on the registration page.|
| FR5 |User shall receive a mail once the registration is successfully completed.|


### Administration

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |Administration page shall be only accessible to the Application Administrator.|
| FR2 |Administration page displays all the requests in ascending order by date.|
| FR3 |Administrator shall have an option to approve or reject the request.|
| FR4 |Users shall receive an email once the administrator approves the request.|
| FR5 |Administrator shall respond to all the user queries on an email.|

### Login

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |User shall login to the application with the registered credentials.|
| FR2 |User profile shall be locked after 3 failed attempts of login.|
| FR3 |User shall be able to reset the password using the forgot password link provided on the page.|
| FR4 |User shall be able to unlock his id by raising a request with the Administrator.|
| FR5 |User authentication is done by validating the credentials with the database.|


### Home

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |Users shall view all the existing messages as a list on the home page.|
| FR2 |Users shall be able to send messages to any registered user in the system.|
| FR3 |Users shall be able to receive messages from any registered user in the system.|
| FR4 |Users shall be able to send group messages depending on the rights granted to the profile.|
| FR5 |Users shall be able to raise a request to disable access with the system.|

### Logout

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |User shall be able to log out of the application at any point of time from the home page.|
| FR2 |User session shall be created once the user logs into the system.|
| FR3 |User session shall be destroyed immediately on click of logout.|
| FR4 |User shall be logged automout if the system is kept idle for 180 secs.|
| FR5 |UUser shall see a pop-up message warning before the system automatically logs the user out.|

# Non-Functional Requirements

### Compatibility

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |The application website shall be Cross-browser compatible.|
| FR2 |The application shall be accessible on Chrome, Internet Explorer, Edge and Safari browsers without any issues.|
| FR3 |The application shall be compatable on Windows, Linus and MAC operating system.|
| FR4 |Mobile version of the application shall be developed.|
| FR5 |Android and Apple Operating systems compatable versions shall be available.|

### Scalability

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |The application shall be ported onto more than one web server and load balanced. |
| FR2 |The application shall have to be ported to the cloud down the line in the future.|
| FR3 |The application shall be horizontally scaled on the cloud environment depending on the user demand.|
| FR4 |Depending on the server memory usage and disk space the server shall be horontally scaled(addition RAM will be added to the server).|
| FR5 |Once ported to cloud application shall be available 24/7 irrespective of server activities.|

### Maintenance

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |Regular code maintenance activity shall be performed on the application.|
| FR2 |Server shall be scanned periodically to find if on the rce or weak ciphers and protocols.|
| FR3 |Latest patches shall be installed on the server periodically.|
| FR4 |Server shall be configured to reboot automatically during the weekend to free up application memory.|
| FR5 |As part of the regular maintenance activity the server shall be scanned periodically to find if there are any missing patches.|

### Security

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |Password encryption shall be implemented in the application code.|
| FR2 |Password shall be stored as an encrypted value in the database.|
| FR3 |Application shall leverage HTTPS protocol and a secure certificate shall be installed on the server. |
| FR4 |Server shall have all the latest security patches installed on it.|
| FR5 |Week ciphers and protocols shall be disabled on the server.|

### Performance

| ID  | Requirement |
| :-------------: | :----------: |
| FR1 |Application shall have a decent response time.|
| FR2 |Application shall be tested with a load of concurrent users to check if there are any server spikes in RAM and io.|
| FR3 |Application shall be tweaked to avoid any out-of-memory issues. |
| FR4 |Application performance shall be same on all the browsers.|
| FR5 |Application performance shall be more faster on mobile as lighter version shall be deployed for mobile.|

# Traceability links

<Description of this section>

## Use Case description and diagrams

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| [Administration document](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/Administration%20Use%20Case%20Description.docx) | Administration Use Case description | FR1,FR2,FR3,FR4,FR5 |
|[Administration](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/UseCaseDiagramAdministration.drawio.png)| Administration Use Case | FR1,FR2,FR3,FR4,FR5 |
|[Login](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/UseCaseDiagramLogin.drawio.png)| Login Use Case | FR1,FR2,FR3,FR4,FR5 |
|[Registration](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/UseCaseDiagramRegistration.drawio.png)| Registration Use Case | FR1,FR2,FR3,FR4,FR5 |
|[User](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/UserUseCaseDiagram.drawio.png)| User Use Case | FR1,FR2,FR3,FR4,FR5 |

## Activity Diagrams

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| [Administration](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/ActivityDiagramAdministration.drawio.png) | Administration Activity Diagram | FR1,FR2,FR3,FR4,FR5 |
|[Home](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/ActivityDiagramHome.drawio.png)| Home Activity Diagram | FR1,FR2,FR3,FR4,FR5 |
|[Registration](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/ActivityDiagramRegistration.drawio.png)| Registration Activity Diagram | FR1,FR2,FR3,FR4,FR5 |

## Class Diagram & CRC Diagram

| Artifact ID  | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| [Application](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/ClassDiagram.png) | Application Class Diagram | FR1,FR2,FR3,FR4,FR5 |
|[Application CRC](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/CRC%20diagram.xlsx)| Application CRC Diagram | FR1,FR2,FR3,FR4,FR5 |
  

# Change Management Plan
This is a web based application and do not require any installation steps users shall be accessing it on the browsers. All the details about the website shall be provided to the users during the training.
  
## How will you train people to use it?
This is a browser-based application and people can be trained over skype or zoom meeting.
Users can access the application during the training and register for access. 
The respective requests will be approved and they shall be able to login to the application.
Also, documentation with help screenshots shall be available for them for reference.
               
## How will you ensure it integrates within their ecosystem / software?
The application code which is developed as part of this project is an open-ended and it flexible and open for modifications. 
As most of the technologies used in the project are open source and can be integrated with any other applications or software without any issues.
As a next step webservices shall be developed and exposed so that other applications in the ecosystem can consume them.
                  
## How will you ensure that it any discovered issues are resolved?
Any issues discovered will be logged into JIRA and each issue would be assigned with a priority level like ‘critical’, ‘major’ and ‘minor’.
As next step feedback from Users shall be taken and depending on their requirement the
Issues with highest priority shall be fixed followed by low priority ones.
  
# Software Artifacts
[Class and Object Diagram](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/Class%20Description%20and%20Object%20diagram.docx)
[Application Class Diagram](https://github.com/naveenlalam/GVSU-CIS641-Panda/blob/master/artifacts/functional-models/ClassDiagram.png)
[Project Details](https://naveenlalam.github.io/GVSU-CIS641-Panda/)

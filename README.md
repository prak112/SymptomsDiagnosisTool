# Overview
<p> 
    Everytime a person feels off from their daily mood or energy levels, they would like to understand what is going on with their body (I would like to!). This project is an attempt to help people, like me, to understand what could be the probable cause for their off-the-routine health condition. This way a person can recover their control over their own body and if needed could reach out for immediate medical attention.
</p>
<p>
    The application provides a simple and distraction free UI for the user. The user enters the symptoms of their current health state and recieves immediate diagnosis with a probability percentage assigned to every diagnosis. The user can verify these diagnosis further by clicking on the hyperlink to read more about it on the WHO Internation Classification of Diseases webpage and understand what exactly could be the issue they are dealing with.
</p>
<p>
    The user can choose to be diagnosed in one of the two ways - general search or specific search. The diagnosis from general search is processed and categorised into three categories - top, suggested and excluded, based on the score of relevancy to the symptom.
</p>
<p>
    The diagnosis from specific search yields top result picked by the API based on score, matching text. The data is processed but since there is only 1 result there will be no categorisation. The score is defined by the ICD API.
</p>
<p>
    The application provides possibility to use the application as guest or registered user. The user can register, login and logout from the application. The authentication process is validated on Frontend and Backend.
</p>
<p>
    The user information and symptoms are stored in MongoDB. This provides the possibility to provide entire search history to registered users and session history for guest users. In the near future, the patient data will be encrypted. The actual state of the application is clearly declared on the UI.    
</p>

<hr>

# Implementation
- The application architecture follows the MERN stack model, integrating MongoDB, Express, React, and Node.
- The application is built for two different platforms (visit the below repositories for further details):
    - [Web Client using React, Material UI](https://github.com/prak112/Symptom-Checker-frontend)
    - [Mobile Client using React Native with Expo](https://github.com/prak112/SymptomChecker-frontend-mobile)
    - [Shared Backend using NodeJS, Express](https://github.com/prak112/Symptom-Checker-backend)
    - Database used is a Document Database, MongoDB Atlas.
	    - ORM used is Mongoose to handle database schemas and backend-database communication.
        - Check MongoDB page for [setup](https://www.mongodb.com/atlas)
- See [Project plan](/docs/PLAN.md) for details about implementation and features.
- See [Process Flows](/docs/PROCESS_FLOWS.md) for understanding User interaction, Application workflows and Database schema
- This repository will host the deployed version of the final build from the Frontend and Backend repositories.
    - *...coming soon...*
<!--  
- [Shared Admin Client using .NET Blazor Server](https://github.com/prak112/SymptomChecker_Admin) 
- Prototype to understand ICD 11 API  
    - [Prototype](/app.js)
-->
    
<hr>

## Progress
- Feel free to check and contribute to the current state of application. 
    - [Feature Tracker](https://github.com/users/prak112/projects/2)
- Any complaints or wishes could be made through a pull request.
- If you wish to contact me directly - prakirthgovardhanam@gmail.com 

<hr>

<hr>
<br>

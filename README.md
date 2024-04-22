# Cure-Connect: Revolutionizing Healthcare Accessibility and Convenience

CureConnect is a groundbreaking web application designed to revolutionize healthcare accessibility and convenience. By eliminating geographical barriers and optimizing time utilization for patients and healthcare professionals, CureConnect facilitates seamless communication through virtual appointments, personalized treatment plans, and secure online access to prescriptions. With integrated medicine purchase features, it streamlines the healthcare process, emphasizing medication adherence and compliance. Through its holistic approach, CureConnect aims to enhance the overall healthcare experience, improve patient outcomes, and foster a more patient-centric approach to healthcare delivery, ultimately contributing to the efficiency and effectiveness of the entire healthcare ecosystem.

### Deployed Link: <https://cure-connect.netlify.app/>
### Backend URL: [<https://cureconnect-zgvj.onrender.com>]

## Group Information

* Members:
    * [Aniket Mhatre](mailto:an370985@dal.ca) [B00969798]
    * [Bhavya Mevawala](mailto:bh84221@dal.ca) [B00953053]
    * [Heramb Kulkarni](mailto:hr835429@dal.ca) [B00962182]
    * [Manan Mistry](mailto:manan.mistry@dal.ca) [B00948831]
    * [Parth Karkhanis](mailto:pr401159@dal.ca) [B00959176]
    * [Shubham Pawar](mailto:sh764760@dal.ca) [B00969363]


### Built With

* [React](https://legacy.reactjs.org/docs/getting-started.html/) - The web framework used.
* [npm](https://docs.npmjs.com//) - Dependency Management.
* [TailwindCSS](https://tailwindcss.com/docs) - CSS Framework.
* [FlowBite](https://flowbite-react.com/) - CSS Components
* [Firebase](https://firebase.google.com/docs) - Backend as a Service (BaaS) platform.
* [Spring Boot](https://spring.io/projects/spring-boot) - Java-based framework for building web applications.
* [MongoDB](https://docs.mongodb.com/) - NoSQL database.
* [Render](https://render.com/) - Cloud application hosting for backend.
* [Netlify](https://app.netlify.com/) - Cloud application hosting for frontend.
* [ZegoCloud](https://www.zegocloud.com/) - Online Video Call API.
* [Stripe](https://stripe.com/en-ca) - Payment Infrastructure for the application.
* [Apache POI](https://poi.apache.org/) - For handling Excel documents.
* [OpenCSV](https://opencsv.sourceforge.net/) - For handling CSV documents.
* [Model Mapper](https://modelmapper.org/) - Library for Object Mapping

### Features and their Tasks (12/12 Features completed  = 100% of project completed)

- Features:
  1. User Management - Bhavya Mevawala
     * Sign Up
     * Log In
     * Forget Password
     * Logout
     * Profile Management
  2. Patient Dashboard - Bhavya Mevawala
  3. Doctor’s Appointment management - Heramb Kulkarni
     * Doctor posting available appointment slots
     * Delete appointment slots
  4. Doctor Patient Online Meeting - Heramb Kulkarni
     * Doctor joining online appointment
     * Doctors can view medical history and prescribe medicines during meetings
  5. Patient Appointment management - Aniket Mhatre
      * View available slots of Doctor
      * Patient Appointment booking
  6. Medicine inventory management - Aniket Mhatre
      * Admin is uploading stock details of medicines using the built-in form
      * Admin updating stock details of medicines by uploading an Excel/CSV file
      * Admin can view, edit, and delete stock of each medicine
  7. Medication Purchase for Patient - Shubham Pawar
      * Select the appointment 
      * Edit the list of medicines to buy
      * Get order details
  8. Past Appointment - Shubham Pawar
      * View and filter the list of patient's past appointments
      * View and download prescription
  9. Doctor Approval feature for Admin - Manan Mistry
      * Doctor’s approval
  10. Patient’s prescription management and medical history - Manan Mistry
      * Doctor views medical history and past prescriptions
      * Doctor updates an old prescription
  11. Doctor Search and Filter for Patients - Parth Karkhanis
      * User wants to search doctors in find doctors page
      * Users want to read details about doctors
  12. Doctor Profile Management - Parth Karkhanis
      * Doctor Registration:Doctor can register themselves on cureconnect platform
      * Doctor Profile Updation:Doctor can edit his profile such as the password of the account

## Getting Started

### Prerequisites

To clone the Group project repository to your local machine, follow these steps:

1. Open your command line interface.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command:

```bash
git clone https://git.cs.dal.ca/bmevawala/csci-5709-group-12
```

To have a local copy of this project up and running on your machine, you will need to install the following software/libraries/plugins:

### Frontend Dependencies:

```
npm (Comes with node.js installation)

"dependencies":{

    "@react-icons/all-files": "^4.1.0",
    "@zegocloud/zego-uikit-prebuilt": "^2.0.1",
    "axios": "^1.6.8",
    "dotenv": "^16.4.5",
    "flowbite-datepicker": "^1.2.6",
    "flowbite-react": "^0.7.6",
    "firebase": "^10.10.0",
    "react": "^18.2.0",
    "react-big-calendar": "^1.11.2",
    "react-countup": "^6.5.0",
    "react-dom": "^18.2.0",
    "react-icons": "^5.0.1",
    "react-responsive": "^10.0.0",
    "react-router-dom": "^6.22.1",
    "react-slick": "^0.30.2",
    "react-toastify": "^10.0.4",
    "react-typed": "^2.0.12",
    "slick-carousel": "^1.8.1",
    "uuid": "^9.0.1"
} 
```

### Backend Dependencies:

```
"dependencies": {
    "implementation": {
        "org.springframework.boot:spring-boot-starter-data-mongodb": "latest_version",
        "com.opencsv:opencsv": "5.9",
        "org.apache.poi:poi": "5.2.5",
        "org.apache.poi:poi-ooxml": "5.2.5",
        "org.springframework.boot:spring-boot-starter-security": "latest_version",
        "org.springframework.boot:spring-boot-starter-web": "latest_version",
        "org.projectlombok:lombok": "latest_version"
    },
    "compileOnly": {
        "org.projectlombok:lombok": "latest_version"
    },
    "annotationProcessor": {
        "org.projectlombok:lombok": "latest_version"
    },
    "testImplementation": {
        "org.springframework.boot:spring-boot-starter-test": "latest_version",
        "org.springframework.security:spring-security-test": "latest_version"
    },

    "implementation": {
        "com.google.firebase:firebase-admin": {
            "version": "9.2.0",
            "exclude": {
                "group": "com.google.guava",
                "module": "guava"
            }
        },
        "com.google.guava:guava": "33.0.0-jre",
        "org.springframework.boot:spring-boot-starter-oauth2-resource-server": "latest_version"
    }
}

```
To install these dependencies, run the following command:

```bash
npm install @react-icons/all-files @zegocloud/zego-uikit-prebuilt axios dotenv flowbite-datepicker flowbite-react firebase react react-big-calendar react-countup react-dom react-icons react-responsive react-router-dom react-slick react-toastify react-typed slick-carousel uuid
```
### **Running the Application:**

#### Starting Frontend and Backend

To run the application, navigate to the top-level folder of the project ("/") in your terminal. Then, execute the following command to start both the frontend and backend servers:

```bash
npm start
```

## Deployment

### Frontend:

Link the GitHub/GitLab repository with [Netlify](https://app.netlify.com/).

#### Site Configurations:
- **Base directory:** `/frontend/`
- **Build command:** `npm run build`
- **Publish directory:** `/frontend/build`

### Backend:

Link the GitHub/GitLab repository with [OnRender](https://app.netlify.com/).

#### Site Configurations:
- **Base directory:** `/backend/`
- **Build command:** 
  - Before deploying, make sure to build your Spring Boot application locally using Gradle.
  - run: `gradle clean build`
- **MongoDB URI:**
  - Update the MongoDB URI in `backend/CureConnect/src/main/resources/application.properties` Replace with your MongoDB Atlas URI.
  - Example: `spring.data.mongodb.uri= <your URL>`

### **Environment Variables:**

This project requires the following environment variables to be set:

```
- VITE_MEETING_APP_ID = <PASTE API ID>
- VITE_MEETING_SERVER_SECRET = <PASTE Meeting Server Secret>
- VITE_API_PATH = <PASTE Backend API Path>
```

### Folder Structure and Justification 

#### Frontend folder Structure:

Frontend was implemented using the Create-react-app which gives a basic folder structure and then we developed over that folder structure

* Assets - The Assets folder contains all essential frontend files, including images utilized on the website. Centralizing these resources in one directory streamlines asset classification and facilitates accessibility.

* Components - The Components folder houses React components developed for reuse by other group members. Centralizing reusable components in a common directory facilitates seamless sharing among team members.

* Service - The Services folder encompasses service files containing Axios code responsible for communication with the backend. Centralizing these service files in one directory streamlines backend communication and ensures consistency in API interactions.

* Indiviudal Feature Folders - This structure was decided by the team so that each member can easily keep their things in the folder of the feature they are developing, this helps in faster debugging and keeps logically related things together. 

* Pages: The Pages folder houses all the pages developed for this application by group members. Centralizing these pages in one directory enhances organization and simplifies navigation within the project.

#### Backend Folder Structure: 
```
/backend
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── CureConnect
│   │   │           └── CureConnect
│   │   │               ├── admin       # Contains admin-specific files
│   │   │               │   ├── controller   # Contains controllers for admin-related HTTP requests
│   │   │               │   ├── model        # Contains entity classes representing admin-related database tables
│   │   │               │   ├── repository   # Contains repository interfaces for admin-related database CRUD operations
│   │   │               │   └── service      # Contains service classes for admin-related business logic
│   │   │               ├── appointment  # Contains appointment-specific files
│   │   │               │   ├── controller   # Contains controllers for appointment-related HTTP requests
│   │   │               │   ├── model        # Contains entity classes representing appointment-related database tables
│   │   │               │   ├── repository   # Contains repository interfaces for appointment-related database CRUD operations
│   │   │               │   └── service      # Contains service classes for appointment-related business logic
│   │   │               ├── user        # Contains user-specific files
│   │   │               │   ├── controller   # Contains controllers for user-related HTTP requests
│   │   │               │   ├── model        # Contains entity classes representing user-related database tables
│   │   │               │   ├── repository   # Contains repository interfaces for user-related database CRUD operations
│   │   │               │   └── service      # Contains service classes for user-related business logic
│   │   │               ├── doctor      # Contains doctor-specific files
│   │   │               │   ├── controller   # Contains controllers for doctor-related HTTP requests
│   │   │               │   ├── model        # Contains entity classes representing doctor-related database tables
│   │   │               │   ├── repository   # Contains repository interfaces for doctor-related database CRUD operations
│   │   │               │   └── service      # Contains service classes for doctor-related business logic
│   │   │               ├── config      # Contains configuration files
│   │   │               ├── inventory   # Contains inventory-specific files
│   │   │               │   ├── controller   # Contains controllers for inventory-related HTTP requests
│   │   │               │   ├── model        # Contains entity classes representing inventory-related database tables
│   │   │               │   ├── repository   # Contains repository interfaces for inventory-related database CRUD operations
│   │   │               │   └── service      # Contains service classes for inventory-related business logic
│   │   │               └── CureConnectApplication.java   # Main class to run the Spring Boot application
│   │   └── resources
│   │       └── application.properties   # Configuration file for Spring Boot application
│   └── test
│       └── java   # Contains test classes
└── build.gradle  
   
```

# References

- [Netlify app, Netlify.com](https://app.netlify.com/)
- [Getting started, Create-react-app.dev](https://create-react-app.dev/docs/getting-started)
- [Npm: React-router-dom, npm](https://www.npmjs.com/package/react-router-dom)
- [React-toastify](https://fkhadra.github.io/react-toastify/introduction/)
- [How to save react form data into database using Spring Boot](https://dev.to/realnamehidden1_61/how-to-save-react-form-data-into-database-using-spring-boot-39li)
- [Get Started with Firebase Authentication on Websites](https://firebase.google.com/docs/auth/web/start)
- [React Authentication with Firebase](https://medium.com/@shishir7850/react-authentication-with-firebase-30fcc07dd80c)
- [Image uploading to Firebase in React.js](https://medium.com/@mahir.uslu/image-uploading-to-firebase-in-react-js-e045b31d8ca8)
- [Import Wizard — Reading CSVs and Excel Sheets in Spring Boot](https://naveenrk22.medium.com/import-wizard-reading-csvs-and-excel-sheets-in-spring-boot-d509b3d5cc1e)
- [Read CSV File to Java Bean (using Open CSV)](https://sunitc.dev/2020/05/31/read-csv-file-to-java-bean-using-open-csv/)
- [React Modal - Flowbite](https://flowbite-react.com/docs/components/modal)
- [How to use Array.map to render a list of items in React](https://scrimba.com/articles/react-list-array-with-map-function/)
- [React.js and Spring Data REST](https://spring.io/guides/tutorials/react-and-spring-data-rest)
- [Mapping Lists with ModelMaper](https://www.baeldung.com/java-modelmapper-lists)
- [Introduction to Spring Method Security](https://www.baeldung.com/spring-security-method-security)

## Acknowledgments

Image Credits
- [Animated Doctor Image](https://www.freepik.com/free-vector/doctor-examining-patient-clinic-illustrated_12557507.htm)
- [Contant Us](https://storyset.com/illustration/call-center/cuate#utm_source=freepik&utm_medium=referall&utm_campaign=storiesdetail&utm_content=edit-button&utm_term=edit)
- [Old Lady](https://www.freepik.com/free-photo/close-up-portrait-senior-woman_21081258.htm#query=old%20lady&position=15&from_view=keyword&track=ais&uuid=90c40c3f-5c46-43d4-a92c-19050d58fc2f)
- [Doctor](https://www.freepik.com/free-photo/woman-doctor-wearing-lab-coat-with-stethoscope-isolated_20999942.htm#fromView=search&page=1&position=12&uuid=a60833c6-a570-47c4-96d0-a84172036d5b)
- [Teacher](https://unsplash.com/photos/shallow-focus-photography-of-woman-outdoor-during-day-rDEOVtE7vOs)
- [Software Engineer](https://www.freepik.com/free-photo/closeup-portrait-caucasian-happy-teacher-glasses_10586129.htm#fromView=search&page=1&position=1&uuid=e43d26de-76e6-4a52-95ff-fc2e23ead0ea)
- [Patient Welcome Image](https://iconscout.com/illustration/welcome-page-8693993)
- [User Profile Default Image](https://www.freepik.com/free-vector/illustration-businessman_2606517.htm#query=user%20profile&position=18&from_view=keyword&track=ais&uuid=0ff722d3-37c9-47d8-be30-b303b6f741a5)
- [face-pack-person](https://www.svgrepo.com/svg/492697/face-pack-person)
- [sick-sweat-temperature](https://www.svgrepo.com/svg/302763/sick-sweat-temperature)
- [chill-cold-corona](https://www.svgrepo.com/svg/302750/chill-cold-corona)
- [pregnant-woman](https://www.svgrepo.com/svg/312897/pregnant-woman)
- [baby](https://www.svgrepo.com/svg/493390/baby)
- [Performance](https://www.svgrepo.com/svg/304808/sex)
- [Medical background Image](https://www.freepik.com/free-vector/medical-background-design_978306.htm#query=doctor&position=21&from_view=search&track=sph&uuid=e3049155-d620-43d0-bdee-732beaa88d03)
- [Smiling Doctor](https://www.istockphoto.com/photo/headshot-portrait-of-smiling-female-doctor-in-hospital-gm1330046035-413589594)
- [Portrait of Health Worker](https://www.freepik.com/free-photo/portrait-health-worker-with-copy-space_14602871.htm#query=doctor%20profile&position=25&from_view=keyword&track=ais&uuid=e2ee7bb9-07e4-4bbf-b119-92a264f3a998)
- [Smiling Male Doctor](https://www.istockphoto.com/photo/headshot-portrait-of-smiling-male-doctor-with-tablet-gm1311511363-400594458?searchscope=image%2Cfilm)

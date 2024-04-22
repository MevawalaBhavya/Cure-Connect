# Cure-Connect: Revolutionizing Healthcare Accessibility and Convenience

CureConnect is a groundbreaking web application designed to revolutionize healthcare accessibility and convenience. By eliminating geographical barriers and optimizing time utilization for patients and healthcare professionals, CureConnect facilitates seamless communication through virtual appointments, personalized treatment plans, and secure online access to prescriptions. With integrated medicine purchase features, it streamlines the healthcare process, emphasizing medication adherence and compliance. Through its holistic approach, CureConnect aims to enhance the overall healthcare experience, improve patient outcomes, and foster a more patient-centric approach to healthcare delivery, ultimately contributing to the efficiency and effectiveness of the entire healthcare ecosystem.

### Deployed Link: <https://cure-connect.netlify.app/>
### Repo Link: <https://git.cs.dal.ca/bmevawala/csci-5709-group-12>
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

## Sources Used
 
### Calendar.jsx
 
*Lines 114 - 122*
 
```
<Datepicker
      theme={customTheme}
      minDate={formatDate(new Date())}
      value={selectedDate}
      inline={isMediumScreen}
      className="w-full  lg:w-80" 
      format="{mm/dd/yyyy}"
      onSelectedDateChanged={handleDateChange}
    />

```

*Lines 8 - 94*

```
  const customTheme = {
    root: {
      base: "relative",
    },
    popup: {
      root: {
        base: "absolute top-10 z-50 block pt-1",
        inline: "relative top-0 z-auto",
        inner:
          "inline-block rounded-lg bg-whiteColor p-4 shadow-lg",
      },
      header: {
        base: "",
        title:
          "px-2 py-3 text-center font-semibold text-secondaryColor",
        selectors: {
          base: "mb-2 flex justify-between",
          button: {
            base: "rounded-lg  bg-whiteColor px-5 py-2.5 text-sm font-semibold text-secondaryColor hover:bg-gray-200 focus:outline-none focus:ring-2 focus:ring-secondaryColor",
            prev: "",
            next: "",
            view: "",
          },
        },
      },
      view: {
        base: "p-1",
      },
      footer: {
        base: "mt-2 flex space-x-2",
        button: {
          base: "w-full rounded-lg px-5 py-2 text-center text-sm font-medium",
          today:
            "bg-secondaryColor text-white hover:bg-primaryColor transition duration-200 ease-in-out",
          clear:
            "border border-secondaryColor border-2 bg-whiteColor text-secondaryColor hover:bg-gray-200 transition duration-200 ease-in-out",
        },
      },
    },
    views: {
      days: {
        header: {
          base: "mb-1 grid grid-cols-7",
          title:
            "h-6 text-center text-sm font-medium leading-6 text-gray-500 dark:text-gray-400",
        },
        items: {
          base: "grid w-64 grid-cols-7",
          item: {
            base: "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-secondaryColor hover:bg-gray-200",
            selected: "bg-primaryColor text-whiteColor hover:bg-darkPrimary",
            disabled: "text-gray-500",
          },
        },
      },
      months: {
        items: {
          base: "grid w-64 grid-cols-4",
          item: {
            base: "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-secondaryColor hover:bg-gray-200",
            selected: "bg-primaryColor text-whiteColor hover:bg-darkPrimary",
            disabled: "text-gray-500",
          },
        },
      },
      years: {
        items: {
          base: "grid w-64 grid-cols-4",
          item: {
            base: "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-secondaryColor hover:bg-gray-200",
            selected: "bg-primaryColor text-whiteColor hover:bg-darkPrimary",
            disabled: "text-gray-500",
          },
        },
      },
      decades: {
        items: {
          base: "grid w-64 grid-cols-4",
          item: {
            base: "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-secondaryColor hover:bg-gray-200",
            selected: "bg-primaryColor text-whiteColor hover:bg-darkPrimary",
            disabled: "text-gray-500",
          },
        },
      },
    },
  };

```

The code above was created by adapting the code in [React Datepicker - Flowbite](https://flowbite-react.com/docs/components/datepicker) as shown below: 

```
function Component() {
  return <Datepicker minDate={new Date(2023, 0, 1)} maxDate={new Date(2023, 3, 30)} />;
}
```

```
{
  "root": {
    "base": "relative"
  },
  "popup": {
    "root": {
      "base": "absolute top-10 z-50 block pt-2",
      "inline": "relative top-0 z-auto",
      "inner": "inline-block rounded-lg bg-white p-4 shadow-lg dark:bg-gray-700"
    },
    "header": {
      "base": "",
      "title": "px-2 py-3 text-center font-semibold text-gray-900 dark:text-white",
      "selectors": {
        "base": "mb-2 flex justify-between",
        "button": {
          "base": "rounded-lg bg-white px-5 py-2.5 text-sm font-semibold text-gray-900 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:bg-gray-700 dark:text-white dark:hover:bg-gray-600",
          "prev": "",
          "next": "",
          "view": ""
        }
      }
    },
    "view": {
      "base": "p-1"
    },
    "footer": {
      "base": "mt-2 flex space-x-2",
      "button": {
        "base": "w-full rounded-lg px-5 py-2 text-center text-sm font-medium focus:ring-4 focus:ring-cyan-300",
        "today": "bg-cyan-700 text-white hover:bg-cyan-800 dark:bg-cyan-600 dark:hover:bg-cyan-700",
        "clear": "border border-gray-300 bg-white text-gray-900 hover:bg-gray-100 dark:border-gray-600 dark:bg-gray-700 dark:text-white dark:hover:bg-gray-600"
      }
    }
  },
  "views": {
    "days": {
      "header": {
        "base": "mb-1 grid grid-cols-7",
        "title": "h-6 text-center text-sm font-medium leading-6 text-gray-500 dark:text-gray-400"
      },
      "items": {
        "base": "grid w-64 grid-cols-7",
        "item": {
          "base": "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-gray-900 hover:bg-gray-100 dark:text-white dark:hover:bg-gray-600 ",
          "selected": "bg-cyan-700 text-white hover:bg-cyan-600",
          "disabled": "text-gray-500"
        }
      }
    },
    "months": {
        }
      }
    },
    "years": {
      "items": {
        "base": "grid w-64 grid-cols-4",
        "item": {
          "base": "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-gray-900 hover:bg-gray-100 dark:text-white dark:hover:bg-gray-
      "items": {
        "base": "grid w-64 grid-cols-4",
        "item": {
          "base": "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9 text-gray-900 hover:bg-gray-100 dark:text-white dark:hover:bg-gray-600",
          "selected": "bg-cyan-700 text-white hover:bg-cyan-600",
          "disabled": "text-gray-500"600",
          "selected": "bg-cyan-700 text-white hover:bg-cyan-600",
          "disabled": "text-gray-500"
        }
      }
    },
    "decades": {
      "items": {
        "base": "grid w-64 grid-cols-4",
        "item": {
          "base": "block flex-1 cursor-pointer rounded-lg border-0 text-center text-sm font-semibold leading-9  text-gray-900 hover:bg-gray-100 dark:text-white dark:hover:bg-gray-600",
          "selected": "bg-cyan-700 text-white hover:bg-cyan-600",
          "disabled": "text-gray-500"
        }
      }
    }
  }
}
```

- Implementing the Flowbite React Datepicker required a thorough exploration of its source code. This ensured we captured its full capabilities and delivered an accurate integration.
- [React Datepicker - Flowbite](https://flowbite-react.com/docs/components/datepicker) provides customizable date-picker which helped to create date-picker matching with the theme of our project
- [React Datepicker - Flowbite](https://flowbite-react.com/docs/components/datepicker)'s code was modified with theme properties to fit our color scheme.

### AppointmentManagement.jsx

*Lines 290 - 298*

```
     <BigCalendar
                localizer={localizer}
                events={events}
                startAccessor="start"
                endAccessor="end"
                eventPropGetter={eventStyleGetter}
                className="border-2 rounded-lg border-secondaryColor p-2 overflow-y-auto "
                onSelectEvent={handleEventClick}
              />
```
The code above was created by adapting the code in [Implement calendar with events using react-big-calendar](https://www.npmjs.com/package/react-big-calendar) as shown below:

```
import { Calendar, momentLocalizer } from 'react-big-calendar'
import moment from 'moment'

const localizer = momentLocalizer(moment)

const MyCalendar = (props) => (
  <div>
    <Calendar
      localizer={localizer}
      events={myEventsList}
      startAccessor="start"
      endAccessor="end"
      style={{ height: 500 }}
    />
  </div>
)
```
* Above code explains how to use the *Calendar* Component with its properties from react-big-calendar package
* The react-big-calendar is used to show doctors their appointments in a calendar view.


### MedicineModal.jsx

*Lines 120 - 264*

```
 <Modal.Header className="p-4 px-6 truncate">
        Edit Medicine
      </Modal.Header>
      <Modal.Body className="p-0 pb-5">
        <form
          className="bg-whiteColor text-secondaryColor"
          onSubmit={handleSubmit}
        >
          <div className="px-5 pb-5 m-4">
            <label htmlFor="subject" className="block text-sm px-1 font-bold ">
              Medicine
            </label>
            <input
              placeholder="Medicine"
              name="name"
              className=" text-secondaryColor placeholder-gray-600 w-full px-4 py-1.5 mb-5 mt-1 text-base transition duration-200 ease-in-out border-transparent rounded-lg bg-gray-200 focus:outline-none focus:ring-4 focus:ring-primaryColor focus:bg-whiteColor"
              onChange={handleChange}
              defaultValue={editItem.name}
            />
            {errors.name && (
              <p className="text-errorText mb-4 text-start uppercase text-[0.60em] font-bold tracking-[0.15em]">
                ❌ Medicine name cannot be empty
              </p>
            )}
            <label htmlFor="subject" className="block text-sm px-1 font-bold ">
              Manufactured By
            </label>
            <input
              placeholder="Brand"
              name="brand"
              className=" text-secondaryColor placeholder-gray-600 w-full px-4 py-1.5 mb-5 mt-1 text-base transition duration-200 ease-in-out border-transparent rounded-lg bg-gray-200 focus:outline-none focus:ring-4 focus:ring-primaryColor focus:bg-whiteColor"
              onChange={handleChange}
              defaultValue= {editItem.brand}
            />
            {errors.brand && (
              <p className="text-errorText mb-4 text-start uppercase text-[0.60em] font-bold tracking-[0.15em]">
                ❌ Brand name cannot be empty
              </p>
            )}
            <label htmlFor="subject" className="block text-sm px-1 font-bold ">
              Expiry Date
            </label>
            <input
              type="date"
              name="expiryDate"
              min={new Date().toISOString().split("T")[0]}
              className=" text-secondaryColor placeholder-gray-600 w-full px-4 py-1.5 mb-5 mt-1 text-base transition duration-200 ease-in-out border-transparent rounded-lg bg-gray-200 focus:outline-none focus:ring-4 focus:ring-primaryColor focus:bg-whiteColor"
              onChange={handleChange}
              defaultValue={new Date(editItem.expiryDate).toISOString().split("T")[0]}
            />
            {errors.expiryDate && (
              <p className="text-errorText mb-4 text-start uppercase text-[0.60em] font-bold tracking-[0.15em]">
                ❌ Expiry date cannot be empty
              </p>
            )}
            <div className="flex flex-row items-start">
              <label
                htmlFor="subject"
                className="block text-sm px-1 font-bold  basis-1/2"
              >
                Quantity
              </label>
              <label
                htmlFor="subject"
                className="block text-sm px-1 ml-1 font-bold  basis-1/2"
              >
                Price
              </label>
            </div>
            <div className="flex flex-row">
              <input
                placeholder="Quantity"
                name="quantity"
                className=" text-secondaryColor placeholder-gray-600 w-full px-4 py-1.5 mb-5 mt-1 mr-1 text-base transition duration-200 ease-in-out border-transparent rounded-lg bg-gray-200 focus:outline-none focus:ring-4 focus:ring-primaryColor focus:bg-whiteColor"
                type="number"
                step="1"
                onChange={handleQuantityChange}
                defaultValue={editItem.quantity}
              />
              <input
                placeholder="Price"
                name="price"
                className=" text-secondaryColor placeholder-gray-600 w-full px-4 py-1.5 mb-5 mt-1 ml-1 text-base transition duration-200 ease-in-out border-transparent rounded-lg bg-gray-200 focus:outline-none focus:ring-4 focus:ring-primaryColor focus:bg-whiteColor"
                type="number"
                step=".01"
                onChange={handlePriceChange}
                defaultValue={editItem.price}
              />
            </div>
            {errors.quantity && (
              <p className="text-errorText mb-4 text-start uppercase text-[0.60em] font-bold tracking-[0.15em]">
                ❌ Enter correct quantity.
              </p>
            )}
            {errors.price && (
              <p className="text-errorText mb-4 text-start uppercase text-[0.60em] font-bold tracking-[0.15em]">
                ❌ Enter correct price.
              </p>
            )}
            <label
              htmlFor="description"
              className="block text-sm px-1 font-bold"
            >
              Description
            </label>
            <textarea
              className="min-h-[100px] max-h-[300px] mt-1 h-28 placeholder-gray-600 appearance-none block w-full bg-grey-lighter text-grey-darker border border-grey-lighter rounded-lg py-4 px-4 text-secondaryColor bg-gray-200 focus:outline-none focus:ring-4 focus:ring-primaryColor focus:bg-whiteColor transition duration-200 ease-in-out"
              placeholder="Description"
              name="description"
              onChange={handleChange}
              defaultValue={editItem.description}
            ></textarea>
            {errors.description && (
              <p className="text-errorText mb-4 text-start uppercase text-[0.60em] font-bold tracking-[0.15em]">
                ❌ Description cannot be empty
              </p>
            )}
          </div>
          <hr className="my-4 border-secondaryColor border-1"></hr>
          <div className="flex flex-row-reverse px-9">
            <div className="flex-initial pl-3">
              <button
                type="submit"
                className="flex items-center px-5 py-2.5 font-medium tracking-wide text-whiteColor capitalize bg-primaryColor rounded-md hover:bg-darkPrimary focus:outline-none focus:bg-gray-900  transition duration-300 transform active:scale-95 ease-in-out"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  height="24px"
                  viewBox="0 0 24 24"
                  width="24px"
                  fill="#FFFFFF"
                >
                  <path d="M0 0h24v24H0V0z" fill="none"></path>
                  <path
                    d="M5 5v14h14V7.83L16.17 5H5zm7 13c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3zm3-8H6V6h9v4z"
                    opacity=".3"
                  ></path>
                  <path d="M17 3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V7l-4-4zm2 16H5V5h11.17L19 7.83V19zm-7-7c-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3-1.34-3-3-3zM6 6h9v4H6z"></path>
                </svg>
                <span className="pl-2 mx-1">Save</span>
              </button>
            </div>
          </div>
        </form>
      </Modal.Body>
```

The code above was created by adapting the code
in [React Modal - Flowbite](https://flowbite-react.com/docs/components/modal) as
shown below:

```
<Modal show={openModal} size="md" onClose={onCloseModal} popup>
<Modal.Header />
<Modal.Body>
  <div className="space-y-6">
    <h3 className="text-xl font-medium text-gray-900 dark:text-white">Sign in to our platform</h3>
    <div>
      <div className="mb-2 block">
        <Label htmlFor="email" value="Your email" />
      </div>
      <TextInput
        id="email"
        placeholder="name@company.com"
        value={email}
        onChange={(event) => setEmail(event.target.value)}
        required
      />
    </div>
    <div>
      <div className="mb-2 block">
        <Label htmlFor="password" value="Your password" />
      </div>
      <TextInput id="password" type="password" required />
    </div>
    <div className="flex justify-between">
      <div className="flex items-center gap-2">
        <Checkbox id="remember" />
        <Label htmlFor="remember">Remember me</Label>
      </div>
      <a href="#" className="text-sm text-cyan-700 hover:underline dark:text-cyan-500">
        Lost Password?
      </a>
    </div>
    <div className="w-full">
      <Button>Log in to your account</Button>
    </div>
    <div className="flex justify-between text-sm font-medium text-gray-500 dark:text-gray-300">
      Not registered?&nbsp;
      <a href="#" className="text-cyan-700 hover:underline dark:text-cyan-500">
        Create account
      </a>
    </div>
  </div>
</Modal.Body>
</Modal>
```

### InventoryTable.jsx

*Lines 181 - 210*

```
<Modal
show={openDeleteModal}
size="md"
onClose={() => setDeleteOpenModal(false)}
popup
>
<Modal.Header />
<Modal.Body>
  <div className="text-center">
    <HiOutlineExclamationCircle className="mx-auto mb-4 h-14 w-14 text-secondaryColor " />
    <h3 className="mb-5 text-md font-normal text-secondaryColor ">
      Are you sure you want to delete this Medicine?
    </h3>
    <div className="flex justify-center gap-4">
      <button
        className="bg-red-600 hover:bg-red-700 text-whiteColor font-bold py-2 px-4 rounded hover:scale-105 transition duration-200 ease-in-out"
        onClick={handleDelete}
      >
        {"Yes, I'm sure"}
      </button>
      <button
        className="bg-gray-600 hover:bg-secondaryColor text-whiteColor font-bold py-2 px-4 rounded hover:scale-105 transition duration-200 ease-in-out"
        onClick={() => setDeleteOpenModal(false)}
      >
        No, cancel
      </button>
    </div>
  </div>
</Modal.Body>
</Modal>
```

The code above was created by adapting the code
in [React Modal - Flowbite](https://flowbite-react.com/docs/components/modal) as
shown below:

```
<Modal show={openModal} size="md" onClose={() => setOpenModal(false)} popup>
    <Modal.Header />
    <Modal.Body>
      <div className="text-center">
        <HiOutlineExclamationCircle className="mx-auto mb-4 h-14 w-14 text-gray-400 dark:text-gray-200" />
        <h3 className="mb-5 text-lg font-normal text-gray-500 dark:text-gray-400">
          Are you sure you want to delete this product?
        </h3>
        <div className="flex justify-center gap-4">
          <Button color="failure" onClick={() => setOpenModal(false)}>
            {"Yes, I'm sure"}
          </Button>
          <Button color="gray" onClick={() => setOpenModal(false)}>
            No, cancel
          </Button>
        </div>
      </div>
    </Modal.Body>
</Modal>
```

### FileUpload.jsx

*Lines 77 - 81*

```
if (status) {
    toast.success(`${fileName} uploaded successfully`);
}else{
    toast.error(`${fileName} failed to upload`);
}
```

### MedicineForm.jsx

*Lines 61 - 74*

```
if (!isValid) {
  toast.warning("Please fill all the required fields.");
  return;
}
try {
  addOrUpdateMedicine(formData).then((res) => {
    event.target.reset();
    toast.success("Medicine added successfully!");
    setTimeout(() => handleRefresh(true), 1000);
  });
  
} catch (error) {
  toast.error("Error while adding medicine. Please try again");
}
```

Both the code above was created by adapting the code
in [React-Toastify](https://fkhadra.github.io/react-toastify/icons) as
shown below:

```
toast.info("Lorem ipsum dolor"); // same as toast(message, {type: "info"});
toast.error("Lorem ipsum dolor")
toast.success("Lorem ipsum dolor")
toast.success("Lorem ipsum dolor", {
  theme: "colored"
})
toast.warn("Lorem ipsum dolor")
toast.warn("Lorem ipsum dolor", {
  theme: "dark"
})
```

### MedicineService.java

*Lines 169 - 178*

```
private static <T> List<T> convertToModel(MultipartFile file) throws IOException {
    Reader reader = new BufferedReader(new InputStreamReader(file.getInputStream()));
    CsvToBean<Medicine> csvReader = new CsvToBeanBuilder(reader)
            .withType(Medicine.class)
            .withSeparator(',')
            .withIgnoreLeadingWhiteSpace(true)
            .withIgnoreEmptyLine(true)
            .build();
    return (List<T>) csvReader.parse();
}
```

The code above was created by adapting the code
in [Read CSV File to Java Bean (using Open CSV)](https://sunitc.dev/2020/05/31/read-csv-file-to-java-bean-using-open-csv/)
as
shown below:

```
CsvToBean<Product> csvReader = new CsvToBeanBuilder(reader)
                .withType(Product.class)
                .withSeparator(',')
                .withIgnoreLeadingWhiteSpace(true)
                .withIgnoreEmptyLine(true)
                .build();
```

### MedicineService.java

*Lines 61 - 89*

```
Workbook workbook = new XSSFWorkbook(file.getInputStream());
for (Sheet sheet : workbook) {
    Map<String, Integer> columnMapping = new HashMap<>();
    Row headerRow = sheet.getRow(0);
    for (String column : columnNames) {
        boolean flag = false;
        for (int i = 0; i < headerRow.getLastCellNum(); i++) {
            if (column.equalsIgnoreCase(headerRow.getCell(i).toString())) {
                columnMapping.put(column, i);
                flag = true;
                break;
            }
        }
        if (!flag) {
            return false;
        }
    }

    for (int i = 1; i <= sheet.getLastRowNum(); i++) {
        Row row = sheet.getRow(i);
        Medicine.MedicineBuilder medicine = Medicine.builder().name(row.getCell(columnMapping.get("medicine")).toString())
                .brand(row.getCell(columnMapping.get("brand")).toString())
                .expiryDate(row.getCell(columnMapping.get("expiry date")).toString())
                .quantity((int) Double.parseDouble(row.getCell(columnMapping.get("quantity")).toString()))
                .price(Double.parseDouble(row.getCell(columnMapping.get("price")).toString()));
        medicine.description(columnMapping.containsKey("description") ? row.getCell(columnMapping.get("description")).toString() : "No Description Available");
        addMedicine(medicine.build());
    }
}
```

The code above was created by adapting the code
in [Import Wizard — Reading CSVs and Excel Sheets in Spring Boot)](https://naveenrk22.medium.com/import-wizard-reading-csvs-and-excel-sheets-in-spring-boot-d509b3d5cc1e)
as
shown below:

```
@PostMapping("/excel")
public String parseExcel(@RequestParam MultipartFile file) throws IOException {

  XSSFWorkbook workbook = new XSSFWorkbook(file.getInputStream());

  // Loop through sheets
  for(Sheet sheet : workbook) {
    System.out.println(sheet.getSheetName());
  
    // Loop through rows
    for(Row row : sheet) {
      // Process cell data
    }
  }

  return "Processed Excel with " + workbook.getNumberOfSheets() + " sheets!";
}
```


### PatientDashboard.js

*Lines 107 - 139*

```
const specialties = [
        {
            icon:
                <img src="/src/assets/patientDashboardIcons/pregnant.png" alt="Period doubts or Pregnancy" className="w-8 h-8" />,
            title: 'Period doubts or Pregnancy',
            consultText: 'CONSULT NOW',
            path: '/pregnancy',
        },
        {
            icon: <img src="/src/assets/patientDashboardIcons/skin-issues.png" alt="Period doubts or Pregnancy" className="w-8 h-8" />,
            title: 'Acne, pimple or skin issues',
            consultText: 'CONSULT NOW',
            path: '/pregnancy',
        },
        {
            icon: <img src="/src/assets/patientDashboardIcons/performance-issue.png" alt="Period doubts or Pregnancy" className="w-8 h-8" />,
            title: 'Performance issues in bed',
            consultText: 'CONSULT NOW',
            path: '/pregnancy',
        },
        {
            icon: <img src="/src/assets/patientDashboardIcons/cold.png" alt="Period doubts or Pregnancy" className="w-8 h-8" />,
            title: 'Cold, cough or fever',
            consultText: 'CONSULT NOW',
            path: '/pregnancy',
        },
        {
            icon: <img src="/src/assets/patientDashboardIcons/child.png" alt="Period doubts or Pregnancy" className="w-8 h-8" />,
            title: 'Children not feeling well',
            consultText: 'CONSULT NOW',
            path: '/pregnancy',
        },
    ];
```
*Lines 107 - 139*
```
<div className="flex justify-center md:justify-around flex-wrap p-4 md:p-10 md:-mt-8">
    {specialties.map((specialty, index) => (
        <div className="flex flex-col items-center w-full md:w-1/6 m-2 md:m-4" key={index} onClick={() => handleSpecialtyClick(specialty.path)}>
            <div className="bg-gray-200 rounded-full p-4">{specialty.icon}</div>
            <div className="flex flex-col justify-between items-center h-full">
                <p className="mt-2 font-bold text-center">{specialty.title}</p>
                <button className="text-xs sm:text-sm md:text-md h-fit w-fit bg-secondaryColor rounded-lg text-whiteColor p-3 hover:bg-primaryColor mt-4">
                    {specialty.consultText}
                </button>
            </div>
        </div>
    ))}
</div>
 
```
The code above was created by adapting the code in [How to Render Lists in React using array.map()](https://www.freecodecamp.org/news/how-to-render-lists-in-react/) as shown below:

```
 const applicants = [ {
    name: 'Joe', work: 'freelance-developer',
    blogs: '54', websites: '32',
    hackathons: '6', location: 'morocco', id: '0',
  },
  {
    name: 'janet', work: 'fullstack-developer', 
    blogs: '34', websites: '12', 
    hackathons: '8', location: 'Mozambique', id: '1',
  },

];

function App() {
  return (
    <>
    {applicants.map(function(data) {
      return (
        <div>
          Applicant name:  {data.name}
        </div>
      )
    })}
    </>

  )
}
```


### Search.jsx
 
*Lines 146 - 177*
 
```
              {doctorDetails.map((item, index) => {
                return (
                  <div
                    key={index}
                    className="flex flex-col items-center md:items-stretch gap-2 md:flex-row w-full mb-5 rounded-lg bg-whiteColor border border-secondaryColor p-4 hover:scale-105 transition duration-200"
                  >
                    <div className="border-2 w-40 h-40 border-primaryColor rounded-md overflow-hidden md:basis-2/10">
                      <img
                        src={item.profileUrl}
                        className=" w-40 h-40 rounded-md object-cover"
                      />
                      </div>
                    <div className="w-full mx-4 flex flex-col md:flex-row justify-between md:basis-4/10">
                      <div className="flex flex-col items-center md:items-stretch">
                        <div className="text-2xl font-semibold text-secondaryColor mb-5">{"Dr."+item.userName}</div>
                        <div className="text-base ">
                          {item.specialization}
                        </div>
                        <div className="text-base mb-5">{"Experience: "+item.experience+" Years"    }</div>
                        <div className="text-md ">{item.educationDetails}</div>
                      </div>
                      <div className="flex h-full justify-center items-center md:basis-4/10 mx-2">
                      <button 
                      onClick={() => handleBookAppointment(item)}
                      className="text-sm sm:text-base h-fit bg-secondaryColor text-white my-2 px-4 py-2 rounded-md">
                        Book Appointment
                      </button>
                      </div>
                    </div>
                  </div>
                );
              })}
```

The code above was created by adapting the code in [How to use Array.map to render a list of items in React](https://scrimba.com/articles/react-list-array-with-map-function/) as shown below:
 
```
const Headings = () => { 
    const headings = heroes.map((hero,index) => <h1 key={index}>{hero}</h1>)   
    return <header>{headings}</header> 
}
```
* Reference has been taken from this and then according to our understanding and knowledge, we have used it in project.

### AttendedPatients.java

* Lines 7 - 9

```
@Data
@AllArgsConstructor
@NoArgsConstructor
```

Mentioned code above was created by using the code in [A complete Guide to Lombok](https://auth0.com/blog/a-complete-guide-to-lombok/) as shown below:

```
@Data
public class Author {
    int id;
    String name;
    String surname;
}
```
 ```
@NoArgsConstructor
@AllArgsConstructor
@RequiredArgsConstructor
public class Author {
    private int id;
    private String name;
    private String surname;
    private final String birthPlace;
}
```

- Lombok helped us to generate boilerplate code such as Getter, Setter and Constructors for below-mentioned files :
    - [AttendedPatients.java](https://git.cs.dal.ca/bmevawala/csci-5709-group-12/-/blob/Mann_Mistry/backend/CureConnect/src/main/java/com/cureconnect/CureConnect/doctors/DTO/AttendedPatients.java?ref_type=heads)
    - [GetPatientAppointments.java](https://git.cs.dal.ca/bmevawala/csci-5709-group-12/-/blob/Mann_Mistry/backend/CureConnect/src/main/java/com/cureconnect/CureConnect/doctors/DTO/GetPatientAppointments.java?ref_type=heads)
    - [PatientAppointment.java](https://git.cs.dal.ca/bmevawala/csci-5709-group-12/-/blob/Mann_Mistry/backend/CureConnect/src/main/java/com/cureconnect/CureConnect/doctors/DTO/PatientAppointment.java?ref_type=heads)

### DoctorService.java

* Lines 66 - 69

```
List<PatientAppointment> futureAppointments = appointmentService.getFutureAppointmentsByDoctorIdAndPatientId(doctorId,patientId)
                .stream().map(appointment -> modelMapper.map(appointment, PatientAppointment.class)).toList();
        List<PatientAppointment> pastAppointments = appointmentService.getPastAppointmentsByDoctorIdAndPatientId(doctorId,patientId)
                .stream().map(appointment -> modelMapper.map(appointment, PatientAppointment.class)).toList();
```

Mentioned code above was created by using the code in [Mapping Lists with ModelMapper](https://www.baeldung.com/java-modelmapper-lists) as shown below:

```
List<UserDTO> dtos = users
  .stream()
  .map(user -> modelMapper.map(user, UserDTO.class))
  .collect(Collectors.toList());
```

- The Model Mapper helps to create one object from another one without using multiple lines of code to create and set data in new object (in context of above code User object will be used to create UserDTO's object)

### DoctorController.java
* Lines 47 - 58

```
@GetMapping("/patients")
    @PreAuthorize("hasAuthority('ROLE:DOCTOR')")
    public ResponseEntity getPatients(@AuthenticationPrincipal Jwt jwt) {
        return doctorService.getPatients(jwt.getSubject());
    }

    @GetMapping("/patients/{patientId}/appointments")
    @PreAuthorize("hasAuthority('ROLE:DOCTOR')")
    public ResponseEntity getPatientsAppointments(@AuthenticationPrincipal Jwt jwt, @PathVariable String patientId) {
        return doctorService.getPatientsAppointments(jwt.getSubject(), patientId);
    }
```

Mentioned code above was created by using the code in [Introduction to Spring Method Security](https://www.baeldung.com/spring-security-method-security) as shown below:

```
@PreAuthorize("hasAuthority('SYS_ADMIN')")
public String getUsernameLC(){
    return getUsername().toLowerCase();
}
```

- The Spring Security helped over here to check the claims from JWT (to verify authorization of user) which is being passed to the end point from where the DoctorController.java accesses the DoctorService.java to fetch data.
- The @PreAuthorize annotation was used here to secure the endpoint for particular user


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

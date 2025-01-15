# Microservice_Project_Spring_boot
# Flight Management System 

The Flight Management System enables administrators to manage airports, airplanes, and flights, while allowing customers to search for and book flights, with automatic seat confirmation or waiting queue placement, and provides booking history for both customers and admins.


**NOTE: The video is attached and is called Video_of_project.mp4. you have to download it to see the video**

## Requirements

Before running the project, ensure you have the following installed on your machine:

- **Java JDK 8 or higher**
- **Apache Maven** (for building and managing the project)
- **Oracle Database** (or any other relational database with corresponding configurations)
- **IDE** (e.g., IntelliJ IDEA or Eclipse)

## Setup

### Clone the repository

Clone the project to your local machine using the following command:

```
git clone https://github.com/your-username/FMS-SpringBoot-Backend.git
```

- **Install Angular CLI if not already installed in your system.**
- **Run ```npm install``` in the cmd line in the Frontend directory of the project.**
- **Then, run ```ng serve``` command.**

- **Then in backend directory**
- **run ```mvn clean install```**
- **```mvn spring-boot:run```**

### API Endpoints
-Here are some API endpoints :

- **POST /flights - Create a new flight**
- **GET /flights - Retrieve a list of all available flights**
- **GET /flights/{id} - Retrieve details of a flight by its ID**
- **POST /bookings - Create a new booking for a flight**
- **GET /bookings - Retrieve a list of all bookings**
- **GET /bookings/{id} - Retrieve booking details by its ID**


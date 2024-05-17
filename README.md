# Banking Application

## Introduction

The Banking Application offers a highly secure and efficient platform to manage personal banking services. This solution facilitates operations such as account creation, deposits, withdrawals, transfers, and account closures. It also features real-time notifications for account-related activities, enhancing user engagement and security.

The project showcases the implementation of the Gang of Four (GoF) Design Patterns in Java, demonstrating advanced software architecture techniques.

## Features

- **Account Management**: Provides functionality to create, manage, and close banking accounts seamlessly.
- **Transaction Handling**: Supports all key transactions including deposits, withdrawals, and inter-account transfers.
- **Alerts and Notifications**: Implements real-time email notifications to keep users updated on significant account movements and changes.

## Technologies Used

- **Backend**: Utilizes Spring Boot for the backend framework, Hibernate for ORM, and Spring Data JPA for data management.
- **Frontend**: Built with React and Axios for efficient frontend development and API interaction.
- **Database**: Uses MySQL for production and H2 for development testing to ensure data integrity.
- **Build Tool**: Maven is employed to manage project builds and dependencies effectively.

## Getting Started

### Prerequisites

- Java JDK 11 or higher
- Node.js 12.x or higher
- Maven 3.6.x or above
- MySQL Server 8.x or a Docker container for MySQL

## Front End Setup

Frontend Setup Navigate to

```bash
cd frontend

cd banking-app
```

Run following commands to install dependencies and Run

```bash
npm install

npm start
```

## Back End Setup

In your Java IDE import project from existing sources as Maven project.

Then run maven clean, maven install and run the application

OR

Run following commands to install dependencies and Run

```bash
mvn clean install

mvn spring-boot:run

```

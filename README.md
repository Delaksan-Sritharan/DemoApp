# Delaksan Demo App

This is a simple Spring Boot application that displays a "Hello World" message.

## Overview

The `Delaksan Demo App` is a basic web application built with Spring Boot. It exposes a single endpoint that returns a greeting message.

---

## Features

* **RESTful Endpoint:** Provides a `/` endpoint that serves a "Hello World" string.
* **Spring Boot:** Leverages Spring Boot for rapid application development and easy deployment.

---

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

* **Java Development Kit (JDK) 17 or higher:** You can download it from the [Oracle website](https://www.oracle.com/java/technologies/downloads/) or use a package manager like SDKMAN!
* **Maven:** You can download it from the [Apache Maven project website](https://maven.apache.org/download.cgi) or use a package manager.

### Installation and Running Locally

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository_url>
    cd DelaksanDemoApp
    ```
    *(Note: Replace `<repository_url>` with the actual URL if this project is hosted on a version control system like GitHub.)*

2.  **Build the application using Maven:**
    ```bash
    mvn clean install
    ```

3.  **Run the application:**
    ```bash
    mvn spring-boot:run
    ```

    Alternatively, you can run the JAR file directly after building:
    ```bash
    java -jar target/DemoAppApplication.jar
    ```

### Accessing the Application

Once the application is running, open your web browser and navigate to:


<img width="922" alt="Screenshot 2025-05-29 at 12 18 31 PM" src="https://github.com/user-attachments/assets/79df5d92-5a9e-4466-b3dd-f6f84ce875f3" />


You should see the message: "Hello World, Welcome to Delaksan Demo App"

---

## Project Structure

* `src/main/java/com/delaksan/DemoApp/`: Contains the main application source code.
    * `DemoAppApplication.java`: The main entry point for the Spring Boot application.
    * `Hello.java`: Defines the REST controller with the `/` endpoint.

---

## Technologies Used

* **Spring Boot:** Framework for building the application.
* **Java:** Programming language.
* **Maven:** Dependency management and build automation tool.

---

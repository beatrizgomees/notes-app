# CRUD Notes App

This is a simple notes app that allows you to create, read, update, and delete (CRUD) notes. It uses an API built with Quarkus and utilizes Provider for state management.
Project Structure

The project directory structure is organized as follows:

    Model: Contains the classes representing the app's data (e.g., Note).
    
    View: Defines the user interface and how information is displayed.
    
    Controller View: Manages the interaction between the View and Model, handling the UI logic.
    
    Constants: Stores constant values used throughout the app.
    
    Repository: Implements the data access logic and communicates with the Quarkus API.
    
    Service: Contains business logic and data processing.
    
    Themes: Defines style themes (colors, fonts, etc.) for the application.
    
    Components: Holds reusable components for the user interface.


## Features

- Create a note: Add a new note with a title and description.
- Read notes: View the list of all saved notes.
- Update a note: Edit the content of an existing note.
- Delete a note: Remove a note from the list.

## Technologies Used

### Frontend: Flutter
### Backend: Quarkus (RESTful API)
### State Management: Provider
### Design Patterns: Clean Architecture

#### Prerequisites

- Flutter SDK installed
- Quarkus set up and running the API

### How to Run Frontend

Clone the project repository.
Navigate to the project folder.
Run the following command to install dependencies:

    bash

    flutter pub get

Start the application:

    bash

    flutter run

### Backend (Quarkus API)

Make sure Quarkus is installed and configured.
Clone the Quarkus API repository.
Navigate to the API folder and run the following command:

    bash

    ./mvnw compile quarkus:dev

#### Contribution

Feel free to contribute to improvements! Fork the project, create a branch, and submit a pull request.

Let me know if you'd like any other modifications!


![image](https://github.com/user-attachments/assets/8f0333ec-73cc-4883-9ed7-aaeac6879a40)
![image](https://github.com/user-attachments/assets/17fdd786-b797-4bd4-a575-bf61a8d045f5)


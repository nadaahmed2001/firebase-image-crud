# firebase-image-crud

A simple HTML application with Firebase integration for CRUD operations (Create, Read, Update, Delete) with images.

## Introduction

This project demonstrates how to integrate Firebase Realtime Database and Firebase Storage into a web application to perform CRUD operations with images. It allows users to upload images, which are stored in Firebase Storage, and their corresponding URLs are saved in the Firebase Realtime Database.

## Features

- **Upload Images**: Users can upload images along with their ID.
- **Retrieve Images**: Users can retrieve and view uploaded images based on their ID.
- **Delete Images**: Users can delete images associated with their ID.

## Technologies Used

- **HTML**: For creating the user interface.
- **Firebase**: For real-time database and storage services.
- **JavaScript (ES6)**: For scripting the functionality.
- **CSS**: For basic styling.

## Usage
1. Install Nodejs and Firebase.
2. Clone the repository:

    ```bash
    git clone https://github.com/nadaahmed2001/firebase-image-crud
    ```

3. Open `index.html` in a web browser.

4. Enter your ID and select images to upload.

5. Click on the "Upload Images" button to upload the selected images.

6. Click on the "Retrieve Images" button to view the uploaded images associated with your ID.

7. Click on the "Delete User" button to delete all images and data associated with the entered ID.

## Configuration

Before running the application, ensure you have set up Firebase in your project:

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Obtain your Firebase project's configuration object (`firebaseConfig`).
3. Replace the placeholder values in the `firebaseConfig` object in the HTML file with your Firebase project's configuration.

## Hosting

The application is hosted using Firebase Hosting. You can access the hosted application at:

- [Firebase Image CRUD App](https://hostingtask-cec93.web.app/)

# Advance Pizza

## Overview
Advance Pizza is an Android application designed for a pizza restaurant, enabling users to order pizzas online or from a local database. The app offers a user-friendly interface and a variety of features to enhance the user experience.

## Features

### Introduction Layout
- **Get Started Button**: Connects to a server to load pizza types.
  - **Success**: Proceeds to login and registration.
  - **Failure**: Displays an error message.

### Login and Registration
- **Login**: Allows users to log in with email and password.
  - Includes a "Remember Me" feature to save the email.
- **Sign-Up**: Enables new users to register with email, phone number, name, gender, and password.
  - Validates user inputs before registration.

### Home Layout (Customer)
- **Navigation Drawer Activity**:
  - **Home**: Displays restaurant history.
  - **Pizza Menu**: Shows pizza types with details, search filters, and options to add to favorites or order.
  - **Your Orders**: Lists previous orders with details.
  - **Your Favorites**: Shows favorite pizzas with ordering options.
  - **Special Offers**: Displays special offers with ordering functionality.
  - **Profile**: Allows users to view and update personal information.
  - **Call Us or Find Us**: Provides options to call the restaurant, find it on Google Maps, or send an email.
  - **Logout**: Logs out the user.

### Home Layout (Admin)
- **Navigation Drawer Activity**:
  - **Admin Profile**: Allows admins to view and update personal information.
  - **Add Admin**: Enables adding new admins.
  - **View All Orders**: Displays all orders with details.
  - **Add Special Offers**: Allows creating new special offers.
  - **Logout**: Logs out the admin.

### Extra Features
- **Profile Picture**: Users can add and change their profile pictures.
- **Order/Income Calculation**: Admins can calculate the number of orders and total income for each pizza type.

## Technical Details
- **Layouts**: Utilizes both dynamic and static Android layouts.
- **Intents & Notifications**: Implements toast messages.
- **Database**: Uses SQLite for local data storage.
- **Animation**: Includes frame and tween animations.
- **Fragments**: Manages UI components.
- **Shared Preferences**: Stores user preferences.
- **REST**: Communicates with the server.

## Setup and Installation
1. Clone the repository.
2. Open the project in Android Studio.
3. Build and run the project on an emulator or physical device.
4. Ensure the device/emulator has internet access to connect to the REST API.

## Usage
1. Launch the app.
2. On the introduction screen, click "Get Started."
3. If connected successfully, proceed to the login or sign-up page.
4. Use the Navigation Drawer to explore the app's functionalities.


## Authors
- [Amani Rabee]
- [Noor Hamayel]



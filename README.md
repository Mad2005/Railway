# Railway Reservation System

## Overview
The Railway Reservation System is a Java-based desktop application designed to manage train reservations. This application provides functionalities for users to sign up, log in, book tickets, and cancel reservations. The application is built using Java Swing for the graphical user interface and MySQL for database management.

## Project Structure
The project is organized into several JFrame classes, each serving a specific purpose in the application:

### 1. `login.jframe`
- **Description**: The login screen where users can enter their credentials to access the system.
- **Features**:
  - User authentication.
  - Redirects to the main menu or sign-up screen if the login fails.

### 2. `sign_up.jframe`
- **Description**: The registration screen where new users can create an account.
- **Features**:
  - User registration with validation.
  - Redirects to the login screen upon successful registration.

### 3. `addtrain.jframe`
- **Description**: The interface for adding new ticket details to the system.
- **Features**:
  - Form for entering train information (e.g., train number, name, class type).
  - Validation and submission of train details to the database.

### 4. `cancellation.jframe`
- **Description**: The screen where users can request ticket cancellations.
- **Features**:
  - Form for entering reservation details to be canceled.
  - Displays the list of reservations eligible for cancellation.

### 5. `cancel_confirm.jframe`
- **Description**: The confirmation screen for ticket cancellations.
- **Features**:
  - Displays the details of the reservation being canceled.
  - Provides options to confirm or cancel the cancellation request.

### 6. `display.jframe`
- **Description**: The display screen for viewing train details and reservations.
- **Features**:
  - Shows details of a selected train.
  - Provides options to view reservation details and perform other related actions.

## Setup and Installation

1. **Clone the Repository**:
   ```sh
   git clone <repository-url>
   ```

2. **Open Project in NetBeans**:
   - Launch NetBeans IDE.
   - Go to `File` -> `Open Project`.
   - Select the cloned project folder and open it.

3. **Set Up the Database**:
   - Ensure you have XAMPP installed and running.
   - Use phpMyAdmin to import the provided SQL schema to create the necessary database tables.

4. **Configure Database Connection**:
   - Update the database connection settings in the `connect` method of the `display` class and other classes that require database access.
   - Ensure the database URL, username, and password are correctly set.

5. **Build and Run**:
   - Right-click on the project in NetBeans.
   - Select `Clean and Build`.
   - Once built successfully, run the project by clicking `Run` or pressing `F6`.

## Usage

- **Login**: Enter your credentials on the login screen to access the system.
- **Sign Up**: Register a new account if you don't have one.
- **Add Train**: Use the add train interface to input new train details.
- **Cancel Reservation**: Request a reservation cancellation using the cancellation form.
- **Confirm Cancellation**: Confirm or cancel a cancellation request.

## Troubleshooting

- **Access Denied Error**:
  Ensure that the database credentials are correct and the user has the necessary permissions.

- **Database Connection Issues**:
  Check if the MySQL server is running and the connection settings are accurate.

## Contributing

Feel free to contribute to the project by submitting pull requests or reporting issues. Your feedback and contributions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

By:Madhumitha K

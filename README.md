# User-Management-Screen-UI-Specification-Document

## Introduction

This document provides the specifications for the user interface of the application. The interface includes various components such as buttons, checkboxes, input fields, and a result screen. The purpose of this document is to guide the software developers in implementing the user interface as described below.

### Requirements

The user interface should meet the following requirements:

1.  Display a user-friendly layout that is easy to navigate.
2.  Provide functionality to create new users.
3.  Allow users to filter and sort the list of users on the result screen.
4.  Default behavior should be to show enabled users only.
5.  All buttons should have a blue background with white text colors.

## User Interface Components

### 1. "+ New User" Button

-   Position: Top left of the page.
-   Description: This button allows the user to create a new user.
-   Action: When clicked, it should open the "New User" input form on the right side of the page.

### 2. "Hide Disabled User" Checkbox

-   Position: Next to the "+ New User" button.
-   Description: This checkbox is used to toggle the visibility of disabled users in the result screen.
-   Default State: Checked (by default, only enabled users are shown).
-   Action: When checked, the result screen should hide disabled users. When unchecked, it should display all users.

### 3. "Save User" Button

-   Position: Top right of the page.
-   Description: This button is used to save changes made to a new or existing user.
-   Action: When clicked, it should save the user details entered in the "New User" input form.

### 4. Result Screen

-   Position: Left side of the page.
-   Description: This area displays the list of users with their corresponding details.
-   Fields:
    -   "ID": The user ID. Clicking on this field should sort the list in ascending or descending order based on user ID.
    -   "Username": The username of the user. Clicking on this field should sort the list in ascending or descending order based on usernames.
    -   "Email": The email address of the user. Clicking on this field should sort the list in ascending or descending order based on email addresses.
    -   "Enabled": This column shows "True" if the user is enabled and "False" if the user is disabled. Clicking on this field should sort the list to group enabled and disabled users separately.
-   Filtering: Users should have the option to apply filters on any of the fields mentioned above, such as filtering by username or email.
-   Default View: The result screen should display a list of users sorted in ascending order based on user IDs, with only enabled users visible (as "Hide Disabled User" is checked by default).

### 5. "New User" Input Form

-   Position: Right side of the page.
-   Title: "New User"
-   Description: This form is used to create a new user by entering their details.
-   Input Fields:
    -   "Username": Text field to enter the desired username.
    -   "Display Name": Text field to enter the display name of the user.
    -   "Phone": Text field to enter the phone number of the user.
    -   "Email": Text field to enter the email address of the user.
    -   "User Roles" Drop Down: A dropdown with options "Guest", "Admin", and "SuperAdmin" to select the role of the user.
    -   "Enabled" Checkbox: A checkbox to indicate if the user should be enabled or disabled.
-   Saving: When the "+ New User" button is clicked, and the required details are entered, clicking the "Save User" button should save the new user's information.

## Styling

-   All buttons should have a blue background with white text colors.

## Conclusion

This user interface specification document outlines the requirements and details for the application's user interface. It provides guidance to the software developers responsible for implementing the interface, ensuring a consistent and user-friendly experience for the end-users.


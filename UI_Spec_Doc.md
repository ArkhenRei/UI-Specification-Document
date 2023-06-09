# User Interface Specification Document for User Management Screen

# Header

-   Header has New User Button, Hide Disabled User Checkbox and Save User Button.
-   It has a grey background.
-   New User Button and Hide Disabled User Checkbox is on the left end.
-   Save User Button is on the right end.

## New User Button

-   The Text is "+ New User"
-   Blue background, white font, rectangle
-   When clicked, adds the last saved user from user database
-   If there is no user in the user database or the last saved user is the same user on the table:
    -   A message pops out and says "You can't add New User"

## Hide Disabled User

-   There is a Checkbox button on the left side of Text
-   The Text is "Hide Disabled User"
-   When checkbox is filled, on the User Information Table, hide the user that writes False under the Enabled column.

## Save User Button

-   The Text is "Save User"
-   A button with blue background, white font and rectangle
-   Button is not clickable until all information is filled in the "New User Form"
    -   Button looks less saturated in this status
-   When clicked, saves all entered user information to the user database

------------------------------------------------------------------------

# Dashboard

-   Dashboard will include User Information Table and New User Form.
-   User Information Table will be on the right and New User Form will be on the left

## User Information Table

-   This table displays information of added users from database
-   Table rows have blue background and white text
-   Table columns have user information (ID, User Name, Email, Enabled)
-   Last added user column's background is less saturated blue

### ID

-   The Text is "ID"
-   There are sort up and sort down arrows on the right side of the text.
    -   They sort users by ID
-   There is filter button on the right side of the sort arrows
    -   When clicked, user can hide some of the data.

### User Name

-   The Text is "User Name"
-   There are sort up and sort down arrows on the right side of the text.
    -   They sort usernames by alphabetical order
-   There is a filter button on the right side of the sort arrows
    -   When clicked, user can hide some of the data.

### Email

-   The text is "Email"
-   There are sort up and sort down arrows on the right side of the text.
    -   They sort emails by alphabetical order
-   There is a filter button on the right side of the sort arrows
    -   When clicked, user can hide some of the data.

### Enabled

-   The text is "Enabled"
-   There are sort up and sort down arrows on the right side of the text.
    -   They sort users by their enabled status (true or false)
-   There is a filter button on the right side of the sort arrows
    -   When clicked, user can hide some of the data.

## New User Form

-   New User Heading is rectangle and has grey background.
-   The form is located below under the heading.
-   The form is saved when the "Save User" button is clicked.

### Username

-   The Text is "Username:"
-   There is a textbox on the right side of the text.
    -   When clicked, users can enter the information.

### Display

-   The Text is "Display Name:"
-   There is a textbox on the right side of the text.
    -   When clicked, users can enter the information.

### Phone

-   The Text is "Phone:"
-   There is a textbox on the right side of the text.
    -   When clicked, users can enter the information.

### Email

-   The Text is "Email:"
-   There is a textbox on the right side of the text.
    -   When clicked, users can enter the information.

### User Roles

-   The Text is "User Roles:"
-   There is a dropdown box on the right side of the text.
    -   When clicked, user can choose one of the three roles of a user can have (Guest, Admin, Super Admin)
    -   Before clicked, "Select user roles..." writes on the box

### Enabled

-   The Text is "Enabled:"
-   There is a checkbox on the right side of the text
    -   If user fills the check box added user will be enabled.
    -   If not then added user will be disabled



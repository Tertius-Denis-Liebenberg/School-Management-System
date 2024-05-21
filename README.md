# School Management System

## Overview

This project entails the creation of a School Management System using Java Swing. The system comprises two main frames: the Login frame and the Main frame. The Main frame incorporates a CardLayout to manage different sections of the interface, allowing users to navigate between various panels seamlessly. The system caters to tasks such as user authentication, viewing employee profiles, managing teachers and children, and more.

## Features

- **Login Frame**: 
  - Utilizes an undecorated form centered on the screen.
  - Provides authentication via username and password fields.
  - Displays a welcoming message upon successful login using JOptionPane.

- **Main Frame**:
  - Consists of three main sections: Header, Side Panel, and Center Panel.
  - Header Panel:
    - Features a close button and a white background.
  - Side Panel:
    - Displays user information and navigation buttons.
    - Buttons are highlighted when selected.
    - Provides navigation to different sections such as Profile, Dashboard, View Teachers, View Children, and Logout.
  - Center Panel:
    - Implements CardLayout for seamless navigation between panels.
    - Contains panels for Profile, Dashboard, Teachers, and Children sections.

## Implementation Details

### Login Frame (10 Marks)
- Username and password fields for user authentication.
- Close button on a panel.
- Undecorated form centered on the screen.
- Welcome message displayed using JOptionPane upon successful login.
- Navigation to the Main frame after successful login.

### Main Frame (20 Marks)
#### Header Panel (5 Marks)
- White background.
- Close button implemented using a panel.

#### Side Panel (15 Marks)
- Displays employee name.
- Navigation buttons for various sections.
- Highlighted button on selection.
- Logout button navigates back to the Login form.

#### Center Panel (95 Marks)
- Implements CardLayout for navigation between panels.
- Profile Button: Navigates to the Profile panel displaying user information.
- Dashboard Button: Navigates to the Dashboard panel showing basic information about the system.
- View Teachers Panel:
  - Navigates to the Kids Klub Teachers panel.
  - Uses JTable to display teacher information.
- View Children Panel:
  - Navigates to the Kids Klub Children panel.
  - Utilizes JTable to display children information.
- Remove Child Panel:
  - Populates fields with relevant child information.
  - Provides functionality to remove a child from the database.

### Submission Requirements
- Zipped folder containing program code.
- PDF document with screenshots of the program output.
- 5-minute PowerPoint recording demonstrating the program functionality.

## Author

**Tertius Denis Liebenberg**  

For any questions or feedback, please contact [tertiusliebenberg7@gmail.com].
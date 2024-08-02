Task Management Application Documentation
Overview
The Task Management Application is a web-based tool designed to help users manage their tasks efficiently. It includes several pages for task management, user registration, and authentication, all built using HTML, CSS, and Bootstrap.

Project Structure
The project is organized into several HTML files, each representing different functionalities:

Home Page (index.html)
Task Dashboard (task-dashboard.html)
Task Details (task-details.html)
Task Creation (task-create.html)
Task Editing (task-edit.html)
Register Page (register.html)
Authentication Page (login.html)
Requirements
HTML for structure
CSS for custom styles (optional)
Bootstrap for responsive design and pre-built components
Pages Overview
1. Home Page (index.html)
Purpose: Introduce users to the application and provide navigation links.
Features: Navbar, Jumbotron for welcome message, Cards to display key features.
2. Task Dashboard (task-dashboard.html)
Purpose: Provide an interactive dashboard to view and manage tasks.
Features: Cards for individual tasks, buttons to view details and create new tasks.
3. Task Details (task-details.html)
Purpose: Display detailed information about a specific task.
Features: Card layout showing task details, button to edit the task.
4. Task Creation (task-create.html)
Purpose: Allow users to create new tasks.
Features: Form layout for entering task title and description, validation feedback.
5. Task Editing (task-edit.html)
Purpose: Enable users to edit existing tasks.
Features: Pre-filled form with current task information, validation feedback.
6. Register Page (register.html)
Purpose: Allow new users to register for the application.
Features: Form layout for entering email and password, validation feedback.
7. Authentication Page (login.html)
Purpose: Allow existing users to log in.
Features: Form layout for entering username and password, validation feedback.
Bootstrap Integration
Grid System: Used to create responsive layouts.
Components: Navbar, Cards, Forms, Buttons.
Utilities: Spacing, alignment, visibility.
Responsive Design
Breakpoints: Utilizes Bootstrap’s built-in classes to ensure the application is responsive across various devices.
Testing: Use Chrome DevTools or similar tools to test responsiveness.
User Experience Enhancements
Navigation: Intuitive navigation using Bootstrap Navbar and Dropdown menus.
Feedback: Visual feedback for form validation to enhance user experience.
Setup Instructions
Download Bootstrap:

Include Bootstrap via CDN in the <head> of each HTML file.
Example: <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
Create HTML Files:

Create separate HTML files for each page as listed above.
Custom Styles:

Optionally, add custom CSS for additional styling in a separate CSS file linked in the <head> of each HTML file.
Test Responsiveness:

Ensure the application works well on various devices by resizing the browser window or using device emulation tools.
Future Enhancements
JavaScript Integration: Add interactivity and advanced validation.
Backend Integration: Connect to a server for task persistence and user management.
User Interface Improvements: Refine the design based on user feedback.
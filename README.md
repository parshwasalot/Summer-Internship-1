# Project Development Timeline

## Week 1

### Day 1

- Briefing and initialization of the project
- Created initial pages of the project 
- Continued creating initial pages of the project
- Started with backend development
- Established connection between database and frontend

### Day 2

- Solved a few errors in the program
- Added further functionality related to the project
- Simplified the code for better readability and reusing
- Implemented functionality for user bifurcation

### Day 3

- Completed faculty dashboard and student dashboard
- Added basic read functionality
- Added other CRUD functionalities
- Added CSS for better UI

### Day 4

- Added window popstate to disable users from going back to login after being on the dashboard
- Used UserAuth for login authentication
- Updated functionality to ensure only the registered user can edit or delete an entry
- Solved a bug preventing the delete entry function from working

### Day 5

- Updated UserAuth with tokens
- Added the waitlist function
- Created pages for the waitlist function
- Added a registration success page

## Week 2

### Day 1

- Added an Available button in waitlist as a popup
- Set up the backend API for the same
- Removed window popstate for login navigation
- Added navigation so that a user can only go back to the login page if they are logged out and the token is deleted

### Day 2

- Created a new user (Admin)
- Made Admin Dashboard
- Solved a CSS bug
- Continued solving CSS issue

### Day 3

- Added User Register Page in Admin Dashboard
- Set up backend API for User Register
- Added User Display Page in Admin Dashboard
- Set up backend API for User Display

### Day 4

- In User Display, added change password functionality for admin
- Created a backend API for changing passwords
- On the faculty dashboard, added a password change functionality for faculty
- Created API for the same

### Day 5

- Implemented edit forms pre-filled data recovery
- Formatted and sorted data in display
- Divided single API file into multiple routes

## Week 3

### Day 1

- Researched hashing algorithms for password encryption
- Applied BcryptJs for password encryption
- Tried SHA256 for username encryption
- Solved errors due to username hashing

### Day 2

- Created log in database for login and logout
- Set up the backend route for the same
- Added search bars in the Event Display component
- Added search bars in the User Display component

### Day 3

- Researched the 10 attacks of cyber security
- Researched AWS KMS to apply next week
- Added validations to all inputs and sanitization through mongoose
- Solved errors generated due to validation

### Day 4

- Uploaded final backend files to the repository
- Solved errors related to root directory, etc.
- Solved build errors and deployment errors
- Deployed backend on Render

### Day 5

- Uploaded final frontend files to the repository
- Solved errors related to root directory, etc.
- Solved build errors and deployment errors
- Deployed frontend on Vercel

## Week 4

### Day 1

- Created a new component to check empty halls without registering the whole event
- Made backend route for the same
- Added system interaction logs

### Day 2

- Added sanitization of inputs to backend routes and models
- Used SCA tools like OWASP Dependency Check to check dependencies
- Used npm dependency-check

### Day 3

- Started on a new project of a Chrome extension for tab-logging
- Researched and learned about how to make a Chrome extension using ReactJS
- Created a manifest.json for configuration
- Created background.js for running the extension in the background

### Day 4

- Created server.js file
- Created a schema for storing logs according to IP
- Connected backend routes and tested the app, solving a few errors
- Changed the log schema to object-based

### Day 5

- Added input validations in the search bar for the allotment-system project
- Created a workflow in GitHub Actions for automated integrity checks in the CI/CD pipeline

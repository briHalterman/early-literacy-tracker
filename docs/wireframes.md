# Wireframes

## Landing Page

### Purpose
Public page for marketing app and directing user to register or log in.

### States
- Default state

## Registration Page

### Purpose
Public page displaying registration form.

### States
- Default state
- Validation error state
  - Email format validation error
  - Duplicate email validation error
  - Unacceptable password validation error
  - Passwords do not match validation error
- Registration prompt state
  - Redirected from book search

## Login Page

### Purpose
Public page displaying login form.

### States
- Default state
- Authentication error state
  - Incorrect credentials error

## Reading Log Page

### Purpose
Main authenticated screen where users view titles of books that have been logged.

### States
- Default state
- Empty state
- Success state
  - Successful registration message
  - Welcome back login message
  - Successful new log entry creation message
  - Successful log entry deletion message
- Validation error state
  - Empty search error
- Operation error state
  - Search failed error
- Milestone message state

## Create Log Entry Page

### Purpose
Screen displaying form for new log entry creation.

### States
- Default state
- Book selected/pre-filled form
- Validation error state
  - Missing title validation error
- Operation error state
  - New log entry creation failed error

## Log Entry Details Page

### Purpose
Authenticated screen where users can view the details of a reading log entry.

### States
- Default state
- Success state
  - Successful log entry update message

## Edit Log Entry Page

### Purpose
Authenticated screen displaying form to update an existing log entry with new details and option to delete the entry.

### States
- Default state
- Validation error state
  - Missing title validation error
- Operation error state
  - Log entry update failed error
  - Log entry deletion failed error

## Book Search Results Page

### Purpose
Screen that displays the results of third-party API book search.

### States
- Default state
- Empty results state
- Operation error state
  - Unable to select book

## Unauthorized Access Page

### Purpose
Screen indicating a user does not have access to a particular route.

### States
- Default state

## 404 Not Found Page

### Purpose
Screen indicating that a page is not found.

### States
- Default state
# User Stories

### User Story: Template

**As a ___, I want ___ so that ___.**

#### Acceptance Criteria
- Given ___, when ___, then ___.
- Given ___, when ___, then ___.

## Authentication

### User Story: Registration

**As a new user, I want to create an account so that I can save my reading log.**

#### Acceptance Criteria
- Given that I am on the registration page, when I enter a valid email and password, then my account is created.
- Given I enter an email that is in a wrong format, when I submit the form, then I see an error message.
- Given I enter an email that is already in use, when I submit the form, then I see an error message.
- Given that I enter an unacceptable password, when I submit the form, then I see an error message.
- Given that I enter passwords that do not match, when I submit the form, then I see an error message.
- Given that signup is successful, when I submit the form, then I am logged in automatically.
- Given that signup is successful, when I submit the form, then I am redirected to my empty reading log page.

### User Story: Login

**As a registered user, I want to log in so that I can access my reading log.**

#### Acceptance Criteria
- Given that I am on the login page, when I enter correct credentials and submit the form, then I am redirected to my reading log.
- Given that I enter incorrect credentials, when I submit the form, then I see an error message.
- Given that I am logged in, when I refresh the page, then my session persists.

### User Story: Logout

**As a logged-in user, I want to log out so that the application is no longer open to my account.**

#### Acceptance Criteria
- Given that I am logged in, when I click the Logout button, then my current session is ended.
- Given that I am logged in, when I click the Logout button, then I am redirected to the landing page.
- Given that I am not logged in, when I click the Logout button, then I am redirected to the landing page.
- Given that logout fails, when I click the Logout button, then I see an error message.

## Reading Log Management

### User Story: View Reading Log

**As a logged-in user, I want to view a list of my saved books' titles so that I can review my progress.**

#### Acceptance Criteria
- Given that I am logged in, when I am on my reading log page, then I see a list of the titles of the books I have logged in descending order of date added.
- Given that I have no books logged, when I am on my reading log page, then I see an (encouraging) empty state message.
- Given that I am not logged in, when I navigate to my reading log page, then I am redirected to the login page.
- Given that I attempt to view another user's reading log, when I request the page, then access is denied.
- Given that my reading log contains milestones, when I view my reading log, then milestone markers are displayed.

### User Story: Create Log Entry

**As a logged-in user, I want to add a book to my reading log so that I can track reading.**

#### Acceptance Criteria
- Given that I am on the create log entry page, when I enter a valid title, then a new log entry is created.
- Given that I leave the title blank, when I submit the form, then I see an error message.
- Given that I enter an author, illustrator, or publication date, when I submit the form, then those details are included on the log entry.
- Given that log entry creation is successful, when I submit the form, then I am redirected to my reading log page which includes the new log entry.
- Given that log entry creation is successful, when I submit the form, then I see a success message.
- Given that log entry creation fails, when I submit the form, then I see an error message.
- Given that I am not logged in, when I navigate to the create log entry page, then I am redirected to the login page.
- Given that I am not logged in, when I submit the form, then I am redirected to the login page.

### User Story: View Log Entry

**As a logged-in user, I want to view the data I save in an individual reading log entry so that I can review information about the books I have logged.**

#### Acceptance Criteria
- Given that I am logged in, when I am on an individual log entry's view page, then I can view the book's title, date logged, and, if included on the entry, author, illustrator, and/or publication date.
- Given that I am not logged in, when I navigate to a log entry's page, then I am redirected to the login page.
- Given that I attempt to view another user's log entry, when I request the page, then access is denied.

### User Story: Update Log Entry

**As a logged-in user, I want to be able to change the details of a log entry.**

#### Acceptance Criteria
- Given that I am on a log entry's edit page, when I enter valid updates to my log entry, including a title, then the log entry is changed to include the updated details.
- Given that I leave the title blank, when I submit the form, then I see an error message.
- Given that log entry update is successful, when I submit the form, then I am redirected to the log entry's view page.
- Given that log entry update is successful, when I submit the form, then I see a success message.
- Given that log entry update fails, when I submit the form, then I see an error message.
- Given that I am not logged in, when I navigate to a log entry's edit page, then I am redirected to the login page.
- Given that I am not logged in, when I submit the form, then I am redirected to the login page.
- Given that I attempt to view another user's log entry edit page, when I request the page, then access is denied.
- Given that I attempt to edit another user's reading log, then I receive an error message (and the update is rejected).

### User Story: Destroy Log Entry

**As a logged-in user, I want to be able to delete a log entry so that I can remove it from my reading log.**

#### Acceptance Criteria
- Given that I am on a log entry's edit page, when I click the Delete button, then the log entry is deleted.
- Given that log entry deletion is successful, when I click the Delete button, then I am redirected to my reading log page which no longer contains the removed log entry.
- Given that log entry deletion is successful, when I click the Delete button, then I see a success message.
- Given that log entry deletion fails, when I click the Delete button, then I see an error message.
- Given that I am not logged in, when I click the Delete button, then I am redirected to the login page.
- Given that I attempt to delete another user's reading log, then I receive an error message (and the deletion is rejected).

## Third Party API Book Search

### User Story: Book Search

**As a logged-in user, I want to search for books so that I can prefill the details of a new reading log entry.**

#### Acceptance Criteria
- Given that I enter a search term, when I click the Search button, then I see a list of matching books.
- Given that I leave the search field blank, when I click the Search button, then I see an error message.
- Given that I enter a search that yields no matches, when I click the Search button, then I see a message.
- Given that I am logged in, when I select a search result, then I am redirected to the create log entry page.
- Given that I am not logged in, when I select a search result, then I am redirected to the login page.
- Given that I am redirected to the log entry creation page after selecting a book, then the selected book's details are pre-filled into the form.
- Given that I select a search result, when I am redirected to the create log entry page, then I can still edit any prefilled fields.
- Given that a search fails, when I click the Search button, then I see an error message.
- Given that a book selection fails, when I click the book, then I see an error message.

### User Story: Public Book Search Demo

**As a non-logged-in user, I want to search for books so that I can demo the book search feature of the app.**

#### Acceptance Criteria
- Given that I enter a search term, when I click the Search button, then I see a list of matching books.
- Given that I leave the search field blank, when I click the Search button, then I see an error message.
- Given that I enter a search that yields no matches, when I click the Search button, then I see a message.
- Given that I am not logged in, when I select a search result, then I am redirected to the registration page.
- Given that I am not logged in, when I select a search result, then I see a message encouraging me to register in order to use the app.
- Given that a search fails, when I click the Search button, then I see an error message.

## Milestone Tracking

### User Story: Milestone Tracking

**As a logged-in user, I want to have a visual representation at some milestones in my reading journey so that I enjoy tracking my progress.**

#### Acceptance Criteria
- Given that I log a milestone book, when I submit the form, then I see a celebration message.
- Given that I log a milestone book, when I submit the form, then I see a visual marker of the milestone at that point in the list of book titles.
- Given that I remove a book from the reading log, when the log order changes, then the milestone markers are displayed on the correct books.
- Given that I complete the milestone of reading 1000 books, when I add another book, then I can still continue to add books to my reading log.

Note: Milestones are marked at the following reading counts:
- 1
- 5
- 10
- 20
- 50
- 99 (almost to 100)
- 100
- 150
- 200
- 250
- 300
- 400
- 475 (almost half way)
- 500
- 600
- 700
- 800
- 900 (almost done)
- 995 (so close)
- 999 (one more book)
- 1000
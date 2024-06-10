# SieNoteTaker
note taking app week 11
# Note Taker

## Description

The Note Taker is a simple web application that allows users to create, view, and delete notes. It uses an Express.js backend and saves and retrieves note data from a JSON file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Acceptance Criteria](#acceptance-criteria)
- [License](#license)
-[Credits](#credits)
## Installation

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/note-taker.git
# Note Taker

## Description

The Note Taker is a simple web application that allows users to create, view, and delete notes. It uses an Express.js backend and saves and retrieves note data from a JSON file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Acceptance Criteria](#acceptance-criteria)
- [License](#license)
-[Credits](#credits)

## Installation

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/note-taker.git
Navigate to the project directory.

cd note-taker
Install the necessary dependencies.

npm install
##Usage
Start the server.

npm start
Open your web browser and navigate to http://localhost:3001.
Navigating the Application
Landing Page: The landing page provides a link to navigate to the notes page.
Notes Page: This page displays a list of existing notes on the left and provides fields to enter a new note's title and text on the right.
Creating and Managing Notes
Add a Note:

Enter a note title and text.
Click the "Save" button that appears in the navigation.
The new note will be saved and displayed in the list on the left.
View a Note:

Click on an existing note in the list to view its content.
Delete a Note:

Click the delete button next to the note in the list to remove it.
##API Routes
GET /api/notes
Retrieves all saved notes as JSON.
POST /api/notes
Receives a new note to save on the request body, adds it to the db.json file, and returns the new note to the client.
Each note is given a unique ID using the uuid package.
DELETE /api/notes/
Receives a query parameter that contains the ID of a note to delete.
Reads all notes from the db.json file, removes the note with the given ID, and rewrites the notes to the db.json file.
##Acceptance Criteria
Landing Page: Contains a link to the notes page.
Notes Page: Displays existing notes and provides fields to enter a new note title and text.
Save Note: Allows saving a new note, which appears in the list of existing notes.
View Note: Displays a clicked note's content.
Delete Note: Allows deletion of a note from the list.
##License
This project is licensed under the MIT License.

##Credits
This Project was done by me studying and the help of AI

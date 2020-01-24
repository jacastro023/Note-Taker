# Note-Taker
* For this assignment we are to create an application that can be used to write, save, and delete notes. This application will use an express backend and save and retrieve note data from a JSON file.

* It has to be deployed using heroku.

## Usage
* This application is dependent on two packages, express and mysql. However, heroku takes care of installing those when deploying the application.

* The user can create a new note by typing in the title of the note and then the text for the note.

* Upon providing both inputs, the save button appears on the right top side of the page.

* Once clicked, the save button saves and appends the note on the left side of the page.

* The user can also click on notes already saved, which will bring them back on to the right side and show what is inside the text of the note.

## User Story

AS A user, I want to be able to write and save notes

I WANT to be able to delete notes I've written before

SO THAT I can organize my thoughts and keep track of tasks I need to complete


## Problems
* The main problem was that I could not get the notes to delete upon clicking the delete button.

* Since there are a lot of files and folders, creating the right paths when linking the files was also confusing.

* The terminal would help solve most of these problems since it would let me know when the files did not exist.

* This was my first time working with heroku, updating my files or incomplete files would result in errors, and I would spend time trying to figure it out.

## Future improvements
* I have to make sure to get the notes to delete when the user clicks on the delete icon.
# 🔮 crystal

## Introduction
* Boilerplate from https://github.com/HosseinKarami/fastshell

## Get started
* Check out codebase
* Follow installation instructions https://github.com/HosseinKarami/fastshell/blob/master/DOCS.md
* Run using `gulp`

## Development methodology
* Number of phases (3 phases)
* All tasks with be broken up in Trello board
* Each task is sized
* Unit testing is not required


## Design
* Every button, on tap, should change in opacity to 0.9 as a clear indication that their button was tapped
* All text (except for the loading screen) is i18n configurable, a language file, and should be able to support all languages, should be used in the project, and American-English language phrases are implemented instead of hardcoding the language
* On app load, it detects the user's phone language, and then sets that as the language of the app
* On pages where the user should only select 1, when the user selects another emoji, it should deselect any other options
* On pages where the user should only select 1, when the user clicks on 'next' it should display an error message, 'Please select 1 emoji!'
* On pages where the user must select 3, allow the user to select as many as they like, when they click the 'next' button, if the user has selected less than, or more than 3, display an error message 'Please select 3 emojis!'.

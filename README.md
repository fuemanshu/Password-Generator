# Password Generator
Password Generator App (DESKTOP Only)


This app generates a random password using a combination of characters from numbers, letters, and special characters.

## Technologies Used
* **Frontend:** HTML, JavaScript

- DESKTOP Directions
    - go to https://github.com/fuemanshu/Password-Generator
    - click on the zip file - "PasswordGeneratorWebApp1-2" 
        - on the next screen next to the search field -  "go to file", click on the three dots then click on "Download"
        - download to desired location on your computer
    - extract files from zip file
    - Open "PasswordGeneratorApp.html" file (it will open in your default web browser)
        - provide your password requirements
        - click "Generate Password" button
        - write down your password
        - click "Reset" button the clear the app

- MOBILE Directions (Android)
    - go to https://github.com/fuemanshu/Password-Generator
    - click on the "PasswordGeneratorApp.html" file link
    - Download "PasswordGeneratorApp.html" file
        - on the next screen on the right where it says "Raw" there is a download icon (arrow pointing down)
            - click on it
        - this downloads it to your mobile device
            - download folder location may vary for each mobile device so check your download folder location
    - open "PasswordGeneratorApp.html" file (it will open in your default web browser)
    - provide your password requirements
    - click "Generate Password" button
    - write down your password
    - click "Reset" button the clear the app


Developer Ending Statement - Any questions or comments please let me know. Use at your own Peril....


------------------------------------------------------------------------------------------------------------------
Development and Version Notes

090225
Currently in Brainstorm Phase

090325
App is at MVP 1.0
- Accepts User Input, creates an array, generates random password and displays on the application and console.

- Characters for random password are in the "availableCharacters" variable in the script in the PasswordGeneratorApp.html file. Make a change to these characters if you want to use different characters. I plan to add options to include/exlude certain characters based on user need.

090525
- Password Generator Web App Zip file added for non develops to use/test

090825
- brainstormed some ideas and wrote the algorithm for MVP 1.1

090925
- added the following features
    - checkboxes for lower and upper case letters, numbers, and special characters
    - add form field for any characters that need to be removed from available characters
        - this allows for users to tailor the available characters to their needs
    - added a reset button that refreshes the app
    - also cleaned up the code and comments
    - added some minor instructions to help users know what to fill out
        - Asked one of my roommate, to test the app and provide some feedback
            - feedback - add instructions, encryption, and add ability to save passwords

091025
- refactor code
	- decided switch cases were not necessary
	- removed array for characters to be removed (realized i could just use the string length and values to remove characters)
	- revised user input data validation


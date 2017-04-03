# reddit-placebot-raocow
Guide to install and run https://github.com/zequez/reddit-placebot
------
1. Download and install V7.8.0 https://nodejs.org/en/
 
2. Download and extract https://github.com/Zequez/reddit-placebot/archive/e8abb8aa8d82600f9fa7273c250de49028513e45.zip

3. In the new folder, rename the "users.example.json" to "users.json". (If it doesn't have a ".json" at the end, just change the name from "users.example" to the "users")
 
4. Open the "users.json 'with your favorite editor and add all your Reddit accounts like so:

   {"Username: Password", "Username2": "password2"}
 
5. Open up https://github.com/DekuLink/reddit-placebot-raocow/blob/master/config.js
   Right click on "Raw" button and click "Save link as". Save it where you can find it. Drag the new config.js into the folder of the original so that it replaces the old config.js.

6. WINDOWS: Open a terminal in the folder (shift + rightclick folder, Open Command Prompt / PowerShell here) and enter "NPM install" into the terminal and hit enter.
   OSX: Open a terminal and "cd" to the folder you downloaded earlier.
        Tex "cd / Users / -" your user name "- / Downloads / reddit-the placebo-master /"
        write "npm install" in the terminal.
 
7. To run, type "npm run start" into the terminal and leave it open. To finish the press Ctrl + C twice.

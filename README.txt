BANKIST Project:

BANKIST Web Page with multiple effects created using JavaScript behind the scenes.


____________________________________________________________________________________________________________________________

Start:

1. Download the files to a local folder and open it in VSC.

2. For security reasons change the PORT number that is set to '1234' and save the file.
   For that go to 'package.json' --> 'scripts' --> "devserver": "live-server --port=XXXX" (choose any number with 4 digits).

3. In VSC, open a terminal window and type 'npm i' (this will install the necessary dependencies for the site to work properly. See 'package.json').

4. In a terminal window type 'npm start'.
   This command will run the following script: 
   "start": "npm-run-all --parallel devserver"

   This script will automatically run 1 other scripts:
       . "devserver" : script that is going to open a page in your pre defined browser and reload the page when changes are made in the code.
                        

____________________________________________________________________________________________________________________________

Notes:

. Copyright © by Jonas Schmedtmann. Original design is credit to the original author, Jonas Schmedtmann.
. My special thanks to Jonas Schmedtmann for is online course 'Complete JavaScript Course'.
. Responsibility for downloads, assembly files and launch this project in the browser, are your sole responsibility. 
. Enjoy it!!
  

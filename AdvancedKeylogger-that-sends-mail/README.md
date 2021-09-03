# HACKING-NOTES-AND-SCRIPTS-
## Installation
- To make sure this program runs as designed Python 3.8 should be installed. This project has many modules incorporated, some of which are not included by default. Any missing modules have to be installed with PIP before the program can run.So, i would recommend you all to google it
- Make sure the associated modules are installed.
- At line 81 enter your full email( username@gmail.com ).
- At line 82 enter the password for that email account.
- Make sure in the gmail account settings that the allow less secure apps is on.
- Open up a command prompt and run the program.
- Change to the directory the program is placed and execute it.
- Open the graphical file manager and go to the C://Users/Public/Logs directory to watch the program in action.
- After files are encrypted and sent to email, download them place them in the directory specified in
  decryptFile.py and run the program in command prompt.


## How it works
- Creates a directory to temporarily store information to exfitrate
- Gets all the essential network information -> stores to log file			(takes about a minute in a half)
- Gets the wireless network ssid's and passwords in XML data file
- Retrieves system hardware and running process/service info
- If the clipboard is activated and contains anything -> stores to log file
- Browsing history is retrieved as a JSON data file then dumped into a log file
- Then using multiprocessing 4 features work together simultaniously:			(set to 5 minutes for demo but timeouts and ranges can be adjusted)
1. Logs pressed keys
2. Takes screenshots every 5 seconds
3. Records microphone in one minute segments
4. Takes webcam picture every 5 seconds
- After all the .txt and .xml files are grouped together and encrypted to protect sensitive data
- Then by individual directory, the files are grouped and sent through email by file type with regex magic
- Finally the Log directory is deleted and the program loops back to the beginning to repeat the same process

## Purpose
> As a Cybersecurtiy enthusiast the purpose of this project was originally to learn to make a keylogger just for educational purpose.
> This is a project for learning and experimentation; unethical use is strictly prohibited.
> Only use on this program on personally owned systems or anyone that allows permission of use
> as a demonstration for raising awareness.

###Note
Soon i will be updating it and making a completely self made code for the same but till then this code is just what i learned...


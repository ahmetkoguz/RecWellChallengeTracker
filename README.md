# RecWellChallengeTracker
Instructions:
* To use code please download latest version of Python (https://www.python.org/downloads/) and pygsheets.
  * To download pygsheets, open command prompt by searching up cmd or pressing "Windows"+"R" keys and typing cmd. If on Mac open terminal.
  * If on Windows, paste "py -m ensurepip --upgrade" into command prompt, then paste "pip install pygsheets" as well. If on Mac "curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py" and, then "python3 get-pip.py". Do not include quation marks.
  * Will require you to download Google API's private key for Google Sheets. Make sure you are using the purdueheadguard@gmail.com for the following. Please follow the instructions bellow. 
  * If creating a new Google Sheet, please add lifeguard-challenges@challenge-tracking-python.iam.gserviceaccount.com as an editor to the Google Sheet planning to use.
  * Go to https://console.cloud.google.com  
  * Click on the project "Challenge-Tracking-Python".
  * Go to the project settings, within the "Dashboard" tab, under "Project Info".
  * From there, go to "Service accounts" on the left dropdown menu.
  * Click the email that starts with lifeguard-challenges.
  * Click the "Keys" tab.
  * Then, click on "Add Key", and "Create new key".
  * Select JSON format and create. The private key will be added to your computer.
  * Add the key into the folder containing all of the .py files. Make sure all the files and the key are in the same folder. 
  * Please paste the key file name into the autherization part in the main.py code, on line 5, after keyName = . So, you would copy the name of the file and paste it inside quotation marks. So it would look: keyName = "YOURPRIVATEKEY.json"
  * Similarly, on the next line (line 6), write the name of the master sheet using. So it would look like masterSheetName = "YOURSHEETNAME". If the name has blank spaces, include them.
* Finally run main.py by pressing (F5) or using the run tab on IDLE. Running it the first time will create the sheets needed to operate the code. Add the names of lifeguards to LifeguardList. The number of teams can be changed accordingly without changing anything in the code. 
* Please refer to the original master sheet, as an example when needed. 

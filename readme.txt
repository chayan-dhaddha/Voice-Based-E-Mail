This is a Python Application which allows its users to send, receive E-Mails through voice.

Complete the steps described in the rest of this page, and in about five minutes you'll have a simple Python command-line application that makes requests to the Gmail API.

Prerequisites:-

1. Python 2.6 or greater.
2. The pip package management tool.
3. Access to the internet and a web browser.
4. A Google account with Gmail enabled.
Use the link given to create client_secret.json https://developers.google.com/gmail/api/quickstart/python

Step 1: Turn on the Gmail API

a) Use this link 'https://accounts.google.com/signin/v2/identifier?service=cloudconsole&osid=1&passive=true&continue=https%3A%2F%2Fconsole.developers.google.com%2Fstart%2Fapi%3Fid%3Dgmail&flowName=GlifWebSignIn&flowEntry=ServiceLogin' to create or select a project in the Google Developers Console and automatically turn on the API. Click Continue, then Go to   credentials.
b) On the Add credentials to your project page, click the Cancel button.
c) At the top of the page, select the OAuth consent screen tab. Select an Email address, enter a Product name if not already set, and click the Save button.
d) Select the Credentials tab, click the Create credentials button and select OAuth client ID.
e) Select the application type Other, enter the name "Gmail API Quickstart", and click the Create button.
f) Click OK to dismiss the resulting dialog.
g) Click the file_download (Download JSON) button to the right of the client ID.
h) Move this file to your working directory and rename it client_secret.json.

Step 2: Run installation.sh file through terminal with command 'sh installation.sh'
        if this command run successfully jump to Step 3  
                   OR
       Run the following commands on terminal in sequence-
    1) $ sudo apt-get update
    2) $ sudo apt-get upgrade
    3) $ sudo apt-get install python-pip.
    4) Check the version by running $ pip -V , must be version 9.0.1 or above. if not run this command $ sudo -H pip2 install --upgrade pip
    5) $ sudo python -m pip install html2text
    6) $ sudo apt-get install git
    7) $ sudo apt-get install libasound-dev
    8) $ git clone http://people.csail.mit.edu/hubert/git/pyaudio.git
    9) $ cd pyaudio
    10) $ sudo python setup.py install
    11) $ sudo apt-get install libportaudio-dev
    12) $ sudo apt-get install python-dev
    13) $ sudo apt-get install libportaudio0 libportaudio2 libportaudiocpp0 portaudio19-dev
    14) $ sudo pip install SpeechRecognition        
    15) $ sudo pip install pyttsx
    16) $ sudo pip install --upgrade google-api-python-client ( Google Client Library )

        
Step 3: Save the files voice_project.py, send.py, text_speech.py, listmessages.py, authenticate.py, getmessage.py, client_secret.json in a folder named 'voice_email'.

Step 4: Open Terminal and use the command 'cd voice_email' to change the directory.

Step 5: Run 'python voice_project.py' to start the application

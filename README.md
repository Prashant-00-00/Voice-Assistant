**Chitti the Robot Voice Assistant**
This repository contains a Python script that implements a voice assistant called Chitti the Robot. Chitti can perform various tasks such as searching Wikipedia, opening websites, playing music, telling the time, and sending emails.

Prerequisites
Before running the code, make sure you have the following installed:

Python 3.x
pyttsx3 library
speech_recognition library
wikipedia library
smtplib library (for sending emails)

You can install these libraries using pip by running the following command:

pip install pyttsx3 speechrecognition wikipedia


**Usage**
Clone this repository or download the script chitti.py to your local machine.

Open a terminal or command prompt and navigate to the directory where the script is located.

Run the following command to execute the script:

python chitti.py
Chitti will greet you and start listening for your commands. You can interact with Chitti by speaking out your commands.

**Features**
Wikipedia Search: Chitti can search for information on Wikipedia. Just say "Wikipedia" followed by your query.

Website Opening: Chitti can open popular websites like YouTube and Google. Simply say "Open YouTube" or "Open Google" to open the respective websites.

Custom Website Opening: Chitti can also open a specific website if you provide the URL. Say "Open <website-name>" to open the desired website.

Music Playing: Chitti can play music from a specified directory. Ensure that you have a directory containing music files and update the music_dir variable in the code with the correct path. Then say "Play music" to enjoy some tunes.

Time Telling: If you want to know the current time, ask Chitti by saying "Time".

Code Editor Opening: Chitti can open a code editor for you. Update the codePath variable in the code with the correct path to your code editor executable. Then say "Open code" to launch the editor.

Email Sending: Chitti can send emails using Gmail. Update the email credentials in the sendEmail() function with your Gmail username and password. To send an email, say "Mail" and provide the content of the email when prompted by Chitti.

**Note**
This code is set to use the default voice "voices[1]". You can change the voice by modifying the setProperty() method in the code.
Ensure that your system has a working microphone for voice input.
Feel free to customize the code according to your needs and have fun with Chitti the Robot!

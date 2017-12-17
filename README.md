# SpeechToTextConverter

Sample program to convert Speech to text, developed using Django

This app is for running this speech to text converter locally.

The api used for conversion is - WebKit SpeechRecognition

Supported browser - Google Chrome

How to start:

1.    Install python3 using sudo apt-get install python3
2.    Clone or download this repository locally.
3.    Now go to SpeechToTextConverter/SpeechConverter directory.
4.    To start the app type python manage.py runserver
5.    Copy the local url with port number which will be mentioned in the console. eg http://127.0.0.1:8000/
6.    Paste the Url in the web browser.

How to use:

1.    On the homepage of this app a microphone button is present.
2.    Click on the button. 
3.    Web browser will prompt to Allow access to use the microphone.
4.    Start speaking and you will be able to find the text appearing in the text area.

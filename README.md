# Flask_translator_webapp

### The application is deployed on AWS EC2 machine
### To try the LIVE translation activity: visit http://3.22.98.205:5000/

This project is based on learning gained from Micrsoft Learn platform.
In this module, we have built a website using Flask and Azure Cognitive Services to translate text in multiple languages listed in the drop down menu.

We Learnt:
1. How to set up a Flask development environment
2. How to use Flask to build a form and
3. How to use the Translator service to translate text

Tools Used: Python(3.6 or above) and Visual Studio Code.

For translator service, we have used Azure Cloud Computing platform for accessing the keys for Cognitive Services.

Creating the app:
I have created the core application in file named app.py
The routes have been added for GET and POST methods for the user to fetch the HTML page (GET) and to provide the text, choose the translator language code and recieve the translated text along with the language code the user chose earlier (POST).
The HTML code is present in 'templates' folder where we have two files index.html to take the input (to show the form to user, accept the text and language code as response for translation service) and result.html to show the output (original text, translated text and language code selected by the user).


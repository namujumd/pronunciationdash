*To run on local (in terminal):
1. open the application.py file and enter your subscription_key and region values
2. cd pronunciationdash
3. activate your virtualenv
4. pip install -r requirements.txt
5. Download and extract the [Speech SDK for JavaScript](https://aka.ms/csspeech/jsbrowserpackage)  microsoft.cognitiveservices.speech.sdk.bundle.js file, and place it in a folder accessible to your HTML file - static folder
6. set FLASK_APP=application.py
7. set FLASK_ENV=development
8. flask run

*To run on local (in terminal):
1. cd pronunciationdash
2. activate your virtualenv
3. run: "pip install -r requirements.txt" in your shell
4. Download and extract the [Speech SDK for JavaScript](https://aka.ms/csspeech/jsbrowserpackage)  microsoft.cognitiveservices.speech.sdk.bundle.js file, and place it in a folder accessible to your HTML file - static folder
2. set FLASK_APP=application.py
3. set FLASK_ENV=development
4. flask run

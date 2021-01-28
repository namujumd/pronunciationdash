To run on local (in terminal):
 
git clone the code
open the application.py file and enter your subscription_key and region values
Download and extract the [Speech SDK for JavaScript](https://aka.ms/csspeech/jsbrowserpackage)  microsoft.cognitiveservices.speech.sdk.bundle.js file, and place it in a folder accessible to your HTML file - static folder 

In cmd line, type the following commands:

cd pronunciationdash
\\activate your virtualenv\\
pip install -r requirements.txt
set FLASK_APP=application.py
set FLASK_ENV=development
flask run

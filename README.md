# TextToSpeech
PROBLEM STAEMENT
In this project our goal is to acheive the problem of converting textual data into speech data.
DESCRIPTION OVERVIEW
As we know, some people have difficulty reading large amounts of text due to dyslexia and other learning disabilities. Some people have basic literary levels. They often get frustrated trying to browse the internet because so much of it is in text form or on other hand some people prefer to listen or watch a news article (or something like this) instead of reading. So to solve all these problems a concept comes into mind that is ”text to speech”.
Text-to-speech (TTS) technology reads aloud digital text. It can take words on computers, smartphones, tablets and convert them into audio.
We will be using Google Text to Speech commonly known as the gTTS API. It is very easy to use the library which converts the text entered, into an audio file which can be saved as a mp3 file. It supports several languages and the speech can be delivered in any one of the two available audio speeds, fast or slow.
TECHNOLOGY USE
Here we will be using  Anaconda Python 3.6 and GTTS.

INSTALLATION
Installation of this project is pretty easy. Please do follow the following steps to create a virtual environment and then install the necessary packages in the following environment.

In Pycharm it’s easy 

1. Create a new project.
2. Navigate to the directory of the project
3. Select the option to create a new new virtual environment using conda with python3.6
4. Finally create the project using used resources.
5. After the project has been created, install the necessary packages from requirements.txt file using the command pip install -r requirements.txt


In Conda also it’s easy

1. Create a new virtual environment using the command
    conda create -n your_env_name python=3.6
2. Navigate to the project directory.
3. Install the necessary packages from requirements.txt file using the command         
pip install -r requirements.txt

WORKFLOW DIAGRAM





















IMPLEMENTATION
1. Project Directory







This is the folder stucture of this project.
2. requirements.txt



This file contains the necessary package called gtts i.e Google Text to Speech, Flask and others.


3. textToSpeech.py


4. clientApp.py










This file contains the script to convert the digital text to speech using gtts.
TESTING IN LOCAL/API
To run this project in your local system just run the file clientApp.py and webserver will start and landing page will open at  http://0.0.0.0:5000/


Next Enter the Text in the left hand box and click on Predict button.


Next you can listen the speech in the Results box.
CONCLUSION
Hence we have successfully converted digital text data data in audio data or speech.
COMPARISION
Here we can improve the results by testing with other APIs which are available from diffrent third party sources or try out deep learning approaches.

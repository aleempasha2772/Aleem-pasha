# google-text-to-speech-

in this repository i want to share how to convert "text to speech using gTTS" in python.

NOTE: you need to have python3.7 or upgraded version of python

Step-1: install gTTS library.
Step-2: command to insatll gTTS
        pip install gtts

*Sample program to run gTTS*

from gtts import gTTS 
tts = gTTS('hello')
tts.save('hello.mp3')


# Software and Internet of Things Track | Task4_5_6  

## Converting STT-and-TTS using IBM Watson Assistant and Python 

- Description:

This project is a program written in Python that converts speech into text using a microphone and saves it as a text file, as well as sends the speech to IBM Watson Assistant to analyze the speech and save it according to the dialect that has been prepared in advance, then the program receives the text from IBM Watson Assistant and converts it back to a file audio and save it as an MP3 file.
---------------------------------------------------------

## Project requirements:

In order for the program to work properly, you must install the extensions written in the (requirements.txt) This is done by typing the following command:

```
pip install pipwin
```

```
pipwin install pyaudio
```

Must download Google Text-to-Speech (gTTS) library
By typing the command


```
pip install gTTS==2.2.2
```

## Run the program:
To test the program, open the transcribe.py file using Visual Studio or any editor that supports the Python language and run the terminal or through the cmd command prompt
Then specify the folder path by typing the command

```
cd :c \Users \.........
```
  
After making sure that you are inside the project folder, type the following command to run the program

```
python transcribe.py -t 20
```

Where 20 stands for the number of seconds your voice will be recognized and you can change it as you like.

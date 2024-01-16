Overview

This is a simple text-to-speech converter program written in Python using the gTTS library for text-to-speech conversion and Tkinter for the graphical user interface.
Prerequisites

Python 3.x
gtts library (install using pip install gtts)

Getting Started
1. Clone the repository:

        git clone https://github.com/michals0snowski/TextToSpeech-python.git
        cd text-to-speech-converter

2. Install the required dependencies:

        pip install gtts

3. Run the program:

        python txtToSpeech.py

Usage

Enter the text you want to convert into the provided entry field.
Click the "Start" button to initiate the text-to-speech conversion.
The program will generate an audio file named output.mp3 and play it.

Dependencies

gTTS: Google Text-to-Speech, a Python library and CLI tool to interface with Google Translate's text-to-speech API.

Notes

The program currently supports the English language for text-to-speech conversion.
The generated audio file is saved as output.mp3 in the same directory as the script.
The program uses the os.system command for playing the generated audio. For macOS, it uses the afplay command.

Contributing

Feel free to contribute by submitting issues or pull requests.
License

This project is licensed under the MIT License.

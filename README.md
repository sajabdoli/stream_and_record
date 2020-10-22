# stream and record

This Jupyter notebook is a simple audio recorder. This recorder uses pyaudio to listen to the input signal from the microphone. 

This program can be used to measure the intensity values from the microphone. The desired threshold in dB may be specified. The program records and saves the audio when the intensity value of the input surpasses the desired threshold. 

Instead of recording the audio by the use of soundfile, you may send the audio to the server for appropriate processing like speech to text processing


## Python Package Prerequisites
- Python >= 3
- pyaudio
- os
- struct
- matplotlib-
- time
- soundfile
- numpy
- collections

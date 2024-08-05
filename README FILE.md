

# Automated Transcript Generator

This project is a code which would automatically return the respective transcript of the video which is input by the user.
The video must be input with its respective drive link or the file address.

To create a transcript using Python libraries such as whisper for speech recognition and moviepy for video processing, you can follow these steps:

## Libraries Used and Their Usages:-
###  moviepy
Usage: Extracts audio from video files.

Purpose: Converts video files to audio files, which are then transcribed to text.

###  whisper
Usage: A module for Automatic Speech Recognition (ASR) developed by OpenAI.

Purpose: Transcribes audio files into text using pre-trained models

### gdown
Usage: A module to download files from Google Drive using their shareable links.

Purpose: Downloads video files from the provided Google Drive links for processing

## Code Explained:-
### 1. Mount the drive
Please make sure to mount drive first

``` from google.colab import drive```


### 2. Install Required Libraries
 Install ffmpeg, moviepy, whisper, and gdown for handling video, audio, and transcription tasks.

````!apt-get install ffmpeg````

### 3. Setup directory
Create a directory named "Video_to_text" in Google Drive to store the outputs

### 4. Convert Video to Audio
Convert the downloaded videos to audio files using moviepy.

### 5. Transcribe Audio to Text
Uses the Whisper ASR model to transcribe the audio files into text.

### 6. Save Transcriptions
Save the transcribed text files in the specified directory on Google Drive











##  Suhani Tatiya
Hi, I'm Suhani Tatiya, a Data Scientist based out of Bangalore! Do Visit my LinkedIn profile to know more about me.


### 🔗 LinkedIn profile

[![linkedin ](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suhani-tatiya/)



## 🛠 Skills
Artificial Intelligence, Machine Learning, Data Science, Data Analysis, and so on



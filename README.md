# Audio-to-Text Transcription App

This simple web application allows users to transcribe audio to text using speech recognition technology. It's built with Python, utilizing the Gradio library for the user interface and the Hugging Face Transformers library for speech recognition.

## Features

- Record audio directly from your microphone
- Upload audio files for transcription
- Real-time transcription of audio to text
- Simple and intuitive user interface

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. Clone this repository:
   
   ```
   git clone https://github.com/Amiche02/Audio2text.git
   cd Audio2text
   ```

2. Install the required packages:
   
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   
   ```
   python app.py
   ```

2. Open your web browser and go to the URL displayed in the terminal (usually `http://localhost:7860`).

3. Use the interface to either record audio or upload an audio file.

4. Click the "Transcribe Audio" button to get the transcription.

## Downloading Audio/Video from YouTube

If you need audio files to test with this application, you can download audio or video from YouTube for free using the following website:

[YouTube Audio/Video Downloader](https://ddownr.com/enXB/)

Please ensure you have the right to use any content you download and respect copyright laws.

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.





Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
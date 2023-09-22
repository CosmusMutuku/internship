# Meeting Video Summarization

## Table of Contents
- Introduction
- Project Overview
- Technologies Used
- Installation
- Usage
- Video to Text Transcription
- Speaker Diarization
- Transcription and Summarization
- Results
- Acknowledgments
- Contact Information

## Introduction
Welcome to the Meeting Video Summarization project. This project is designed to automatically summarize recorded meeting videos by converting video content into text and then generating a concise summary.

### Project Overview
The project can be summarized in the following steps:

1. Video to Text Transcription: The recorded meeting video is first converted into audio, and then an AI model transcribes the audio into text.

2. Speaker Diarization: The text is analyzed to identify different speakers in the meeting, allowing us to attribute dialogue to specific participants.

3. Transcription and Summarization: The transcribed text is processed and summarized to extract key insights, important discussions, and action items from the meeting.

### Technologies Used
- Python
- PyTube
- FFmpeg
- Transformers
- OpenAI Whisper ASR
- AWS S3 (for data storage)

### Installation
To run this project locally, follow these installation steps:

1. Clone the repository
2. Install dependencies: pip install torch pytube huggingsound transformers ffmpeg-python spectralcluster Resemblyzer whisper
3. Set up AWS credentials for S3 access if needed.
4. Run the project by executing specific scripts or commands as explained in the Usage section.

## Usage
To use this project for summarizing your own meeting videos, follow these steps:

### Video to Text Transcription
1. Obtain the video you want to summarize.
2. Convert the video to audio using FFmpeg: ffmpeg -i input_video.mp4 -acodec pcm_s16le -ar 16000 output_audio.wav
3. Diarize the audio to identify speakers

### Transcription and Summarization
1. Transcribe the audio segments using OpenAI Whisper ASR
2. Summarize the transcribed text to extract key points

## Results
The summarized text can be found as the output, and you can use or analyze it as needed.

## Acknowledgments
Many thanks to my colleagues from the Academy and the internship Supervisor.
Hugging-face models and the open-source codes helped a lot in this project. To the Openai fraternity, Kudos!

## Contact Information
For inquiries or collaborations, please contact Cosmus Mutuku via cosmuskavithi@gmail.com.

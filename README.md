# YouTube MP3 Downloader

![Python](https://img.shields.io/badge/python-3.6+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

A simple Python script to download audio from YouTube videos and convert them to MP3 format.

## Features

- Download audio from any YouTube video
- Automatic conversion to MP3 format
- High-quality audio (192 kbps)
- Simple command-line interface
- Clean and minimal code

## Requirements

- Python 3.6 or higher
- FFmpeg

## Installation

### 1. Install FFmpeg

**macOS:**
```bash
brew install ffmpeg
```

**Linux (Ubuntu/Debian):**
```bash
sudo apt update
sudo apt install ffmpeg
```

**Windows:**
Download from [ffmpeg.org](https://ffmpeg.org/download.html) or use chocolatey:
```bash
choco install ffmpeg
```

### 2. Clone the repository

```bash
git clone https://github.com/vladyslav-averin/youtube-mp3-downloader.git
cd youtube-mp3-downloader
```

### 3. Create virtual environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the script:

```bash
python yt_mp3_downloader.py
```

Enter the YouTube video URL when prompted:

```
Enter YouTube URL: https://www.youtube.com/watch?v=pFS4zYWxzNA
```

The MP3 file will be saved in the `downloads/` folder.

## Project Structure
```
youtube-mp3-downloader/
├── yt_mp3_downloader.py   # Main script
├── requirements.txt        # Python dependencies
├── .gitignore             # Git ignore file
├── LICENSE                # MIT License
└── README.md              # This file
```

## Disclaimer

This tool is for personal use only. Please respect copyright laws and YouTube's Terms of Service.
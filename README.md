# MKV to MP4 Video Converter

A simple web application that allows users to upload MKV video files and convert them to MP4 format.

## Features

- Upload MKV files through a user-friendly web interface
- Convert MKV to MP4 using FFmpeg
- Automatic download of converted files
- Progress indication during conversion

## Requirements

- Python 3.6+
- Flask
- ffmpeg-python
- FFmpeg binaries

## Installation

1. Clone this repository
2. Create a virtual environment (optional but recommended):
   ```
   python -m venv .venv
   .venv\Scripts\activate
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
4. Make sure the FFmpeg binaries are in your system PATH or in the project directory

## Usage

1. Start the application:
   ```
   python app.py
   ```
2. Open a web browser and go to http://127.0.0.1:5000
3. Upload an MKV file using the file input
4. Click "Convert to MP4" to start the conversion
5. The converted file will be available for download upon completion

## Project Structure

- `app.py`: Main Flask application
- `templates/`: Contains HTML templates
- `static/`: Contains CSS and JavaScript files
- `downloads/`: Temporary storage for uploaded and converted files
- `ffmpeg-7.1.1/`: FFmpeg binaries

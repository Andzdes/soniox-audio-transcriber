# Soniox Async Transcriber

Web UI for asynchronous transcription of audio files using the [Soniox API](https://soniox.com).

## Features
- Upload local MP3 files (primary method).
- Alternative option: transcribe from an audio URL.
- Model: `stt-async-preview`.
- **Language Identification (LID)** – auto-detect spoken language.
- **Speaker Diarization** – segment by speaker.
- **Context Field** – add custom words/phrases (comma-separated) to improve recognition.
- Progress indicators for **file upload** and **transcription status**.
- Responsive layout for desktop and mobile.
- Export results as **Text** or **JSON**.

## Quick Start
1. Clone this repository:
   ```bash
   git clone https://github.com/Andzdes/soniox-audio-transcriber.git

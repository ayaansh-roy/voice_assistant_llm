# Voice Assistant with AI Interaction

This repository contains code for a voice assistant that interacts with an AI model for natural language understanding (NLU). The assistant is designed to record audio input from users, transcribe it, and then interact with the AI model to provide relevant responses.

## Features

- Record audio input from users in chunks.
- Transcribe the recorded audio using a pre-trained AI model.
- Interact with the AI model to generate responses based on user input.
- Utilizes a knowledge base for context-aware responses.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- `pyaudio`
- `numpy`
- `scipy`
- `wave`
- `faster_whisper` (Installable via pip)
- `qdrant_client` (Installable via pip)
- Other dependencies specified in `requirements.txt`

## Usage

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/voice-assistant.git

2.  Install the dependencies using pip.

```pip install -r requirements.txt

3. Run the main script voice_assistant.py.

```python voice_assistant.py

4. Follow the prompts to interact with the voice assistant. Speak into the microphone when prompted.

## Configuration
- You can adjust the default model size and chunk length in the script as per your requirements.
- Modify the paths and settings related to the knowledge base and AI model if needed.

### Notes
- Ensure that your system's microphone is correctly configured and accessible by the script.
- Make sure to handle exceptions and errors gracefully, especially during audio recording and transcription processes.

### License
- This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments
- The AI model used in this project is based on faster_whisper.
- Special thanks to the developers of pyaudio, numpy, and scipy for their contributions.
# Jarvis - Voice Controlled Virtual Assistant

Jarvis is a simple voice-controlled virtual assistant that can process various commands such as opening websites, playing music, fetching the latest news, and answering queries using OpenAI's GPT-3. It uses speech recognition to capture commands and text-to-speech for responses.

## Features

- **Speech Recognition**: Listens for commands using the microphone.
- **Web Navigation**: Open websites like Google, Facebook, YouTube, and LinkedIn.
- **Music Player**: Play songs from a custom music library.
- **News Fetcher**: Fetches top headlines using the News API.
- **AI Integration**: Uses OpenAI's GPT-3 to respond to complex queries.
- **Text-to-Speech**: Responds using `pyttsx3` and `gTTS`.

## Requirements

To run this project, you will need the following Python libraries:

- `speech_recognition`
- `pyttsx3`
- `requests`
- `gTTS`
- `pygame`
- `openai`
- `musicLibrary` (custom module for music links)

### Install Dependencies

You can install the required dependencies by running:

```bash
pip install speechrecognition pyttsx3 requests gTTS pygame openai
```

Additionally, you might need to install **pocketsphinx** for speech recognition:

```bash
pip install pocketsphinx
```

## Setup

1. Clone the repository:

```bash
git clone https://github.com/SmshardaTmu/Desktop.git
cd Desktop
```

2. Replace the placeholders for API keys:
   - Replace `<Your Key Here>` with your **OpenAI API key** and **News API key** in the script.

## How to Use

1. **Run the script**:

```bash
python jarvis.py
```

2. **Activate Jarvis**:
   - Once the program starts, it will wait for the wake word **"Jarvis"**.
   - After recognizing the wake word, it will be ready to listen for commands such as:
     - "Open Google"
     - "Play [song name]"
     - "News"
     - "Tell me [query]"

3. **Jarvis will respond**:
   - It will perform the action (open website, play music, etc.) and speak the response back to you.

## Commands

- **Open Websites**:
  - "Open Google"
  - "Open Facebook"
  - "Open YouTube"
  - "Open LinkedIn"

- **Play Music**:
  - "Play [song name]"

- **Get News**:
  - "News"

- **Ask Jarvis**:
  - "Tell me about [topic]"
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README covers the basics of setting up and running your project. You can modify it according to your needs!
 

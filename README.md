# Jarvis - AI Personal Assistant

Jarvis is a Python-based personal assistant that helps users perform everyday computer tasks using voice commands. It combines speech recognition, text-to-speech, web automation, and Google Gemini AI to provide a simple and interactive assistant experience.

## Features

- Voice command recognition
- Voice-based responses
- Play specific songs on YouTube
- Open Google and websites
- Answer questions using Google Gemini AI
- Execute supported system commands
- Environment variable support for API key management

## Technologies Used

- Python
- Google Gemini API
- SpeechRecognition
- PyWhatKit
- pyttsx3
- python-dotenv

## Requirements

- Python installed on your computer
- Microphone for voice commands
- Internet connection for online features
- Google Gemini API key

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the Project Folder

```bash
cd YOUR-REPOSITORY
```

### 3. Install Dependencies

```bash
pip install SpeechRecognition pywhatkit pyttsx3 python-dotenv google-genai
```

### 4. Configure the API Key

Create a `.env` file in the project folder and add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual API key.

**Important:** Never upload your API key or `.env` file to a public GitHub repository.

### 5. Run the Project

```bash
python jarvis.py
```

Replace `jarvis.py` with the actual name of your Python file if necessary.

## Project Structure

```text
Jarvis-Personal-Assistant/
├── jarvis.py
├── .env
├── .gitignore
└── README.md
```

This is an example structure. Your actual project files may be different.

## Security

- Keep API keys and credentials private.
- Add `.env` to `.gitignore`.
- Review system commands before executing them.
- Use system-level operations carefully.

## Future Improvements

- Add more voice commands.
- Improve speech recognition accuracy.
- Add reminders and task management.
- Support additional languages.
- Improve error handling and performance.

## Author

**Kajal Kumari**

Python and AI Enthusiast

## License

This project is available for learning and educational purposes. Add a suitable open-source license if you want others to reuse and distribute your code.

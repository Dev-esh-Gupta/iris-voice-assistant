### Iris Voice Assistant

The Iris Voice Assistant is a voice-activated application designed to perform specific tasks based on user commands. This assistant uses speech recognition to understand your voice and can execute tasks such as opening websites, reading news, and playing songs on YouTube.

#### Features

- **Open Websites**: Quickly open popular websites like YouTube, Facebook, and GitHub through voice commands.
- **Read News**: Stay updated with the latest news using the News API.
- **Play Songs on YouTube**: Enjoy your favorite songs by giving voice commands from a predefined list of song names.

#### Technologies and Libraries

This project utilizes the following Python libraries:

- **speech_recognition**: For capturing and interpreting voice commands.
- **webbrowser**: To open web pages.
- **pyttsx3**: For text-to-speech conversion.
- **musicLibrary**: Custom library for handling music-related commands.
- **requests**: To fetch data from the News API.
- **gtts**: Google Text-to-Speech for converting text to speech.
- **pygame**: For handling audio playback.
- **os**: For interacting with the operating system.

#### Installation and Setup

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Dev-esh-Gupta/iris-voice-assistant.git
   cd iris-voice-assistant
   ```

2. **Activate the virtual environment**:
   ```sh
   .\venv\Scripts\activate
   ```

3. **Install the required dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the voice assistant**:
   ```sh
   python main.py
   ```

#### Usage

Simply run the voice assistant and start speaking commands like:
- "Open YouTube"
- "Open Facebook"
- "Open GitHub"
- "Read news"
- "Play [song name] on YouTube"

The assistant will respond to your commands and perform the requested actions.

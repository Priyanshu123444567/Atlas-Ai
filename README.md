# Atlas AI

Atlas AI is a voice-controlled virtual assistant that can recognize speech, respond to queries using OpenAI, open websites, and perform various system-related tasks.

## Features
- **Voice Recognition**: Uses `speech_recognition` to process user voice commands.
- **AI Chatbot**: Integrates with OpenAI's GPT model to respond to queries.
- **Web Navigation**: Opens popular websites like YouTube, Google, and Wikipedia.
- **Music Playback**: Plays local music files.
- **Time Telling**: Tells the current time.
- **Application Control**: Opens applications like FaceTime and Passky.
- **Chat Reset**: Resets the chat history.
- **Exit Command**: Closes the assistant.

## Requirements
- Python 3.x
- Required Python Libraries:
  - `speech_recognition`
  - `openai`
  - `numpy`

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Priyanshu123444567/Atlas-Ai.git
   ```
2. Navigate to the project folder:
   ```sh
   cd Atlas-Ai
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up your OpenAI API key in a `config.py` file:
   ```python
   apikey = "your_openai_api_key"
   ```

## Usage
Run the script:
```sh
python main.py
```
Once started, Atlas AI will listen for voice commands and respond accordingly.

## Commands
- **"Open YouTube"** → Opens YouTube in the browser.
- **"Open Google"** → Opens Google in the browser.
- **"The time"** → Tells the current time.
- **"Open music"** → Plays a predefined music file.
- **"Using artificial intelligence"** → Calls the AI function to process the query.
- **"Atlas Quit"** → Exits the assistant.
- **"Reset chat"** → Clears the chat history.

## Contributing
Feel free to fork this repository, improve the project, and submit pull requests.

## License
This project is licensed under the MIT License.
